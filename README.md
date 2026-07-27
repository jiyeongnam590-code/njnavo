[naengil-home-full-design-v1.html](https://github.com/user-attachments/files/30396782/naengil-home-full-design-v1.html)
<!DOCTYPE html>
<html lang="ko"><head><meta charset="utf-8"/><meta content="width=device-width,initial-scale=1.0" name="viewport"/><title>냉일 홈 전체 디자인</title><style>
:root{
  --brand:#2FAE77;--brand-dark:#1D7C57;--brand-soft:#EAF8F1;
  --accent:#FF8E5D;--accent-soft:#FFF1EA;
  --blue:#4C6FFF;--blue-soft:#EEF1FF;
  --danger:#E95C4B;--danger-soft:#FFF0ED;
  --warning:#D97A24;--warning-soft:#FFF6E8;
  --gray-0:#FFFFFF;--gray-50:#FAFAFA;--gray-100:#F5F5F5;--gray-200:#EEEEEE;
  --gray-300:#E0E0E0;--gray-400:#BDBDBD;--gray-500:#9E9E9E;--gray-600:#757575;
  --gray-700:#616161;--gray-800:#424242;--gray-900:#212121;--page:#ECEFF1;
  --fs-12:12px;--fs-14:14px;--fs-16:16px;--fs-18:18px;
  --fw-400:400;--fw-500:500;--r8:8px;--r12:12px;--r16:16px;--r20:20px;
  --mono:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;
}
*{box-sizing:border-box}
html,body{margin:0}
body{font-family:Pretendard,"Noto Sans KR","Apple SD Gothic Neo",sans-serif;background:var(--page);color:var(--gray-900);padding:32px 20px 64px;font-size:var(--fs-12);line-height:1.55}
button,input{font:inherit}
button{cursor:pointer}
.doc{max-width:1560px;margin:auto;background:#fff;border-radius:24px;padding:40px 38px 54px;box-shadow:0 8px 38px rgba(30,45,60,.08)}
.mono{font-family:var(--mono)}
.dh{border-bottom:2px solid var(--gray-900);padding-bottom:24px;margin-bottom:26px}
.dh-eye{font-size:var(--fs-12);color:var(--brand-dark);letter-spacing:.16em;font-weight:var(--fw-500);margin-bottom:8px}
.dh-main{display:flex;align-items:flex-end;gap:14px;flex-wrap:wrap}
.dh-id{font:var(--fw-500) 32px/1 var(--mono);color:var(--blue)}
.dh-name{font-size:28px;font-weight:var(--fw-500)}
.tag{padding:5px 9px;border-radius:6px;background:var(--gray-900);color:#fff}
.tag.green{background:var(--brand-soft);color:var(--brand-dark);border:1px solid #CBEBDD}
.meta{display:grid;grid-template-columns:repeat(6,1fr);border:1px solid var(--gray-300);border-radius:10px;overflow:hidden;margin-top:18px}
.meta-c{padding:11px 13px;border-right:1px solid var(--gray-300)}.meta-c:last-child{border-right:0}
.meta-k{color:var(--gray-600);margin-bottom:4px}.meta-v{font-weight:var(--fw-500);font-size:var(--fs-14)}
.hist{margin-top:14px;border:1px solid var(--gray-300);border-radius:10px;overflow:hidden}
.hist-h{background:var(--gray-100);padding:8px 12px;font-weight:var(--fw-500)}
table{width:100%;border-collapse:collapse}
th{background:var(--gray-100);color:var(--gray-700);text-align:left;padding:9px;border-top:1.5px solid var(--gray-900);border-bottom:1px solid var(--gray-300)}
td{padding:9px;border-bottom:1px solid var(--gray-200);vertical-align:top}
.cur{background:var(--brand-soft)}
.ov{display:grid;grid-template-columns:1.25fr 1fr 1fr;gap:14px;margin:26px 0}
.ov-c{padding:15px;border-radius:12px;background:var(--gray-50);border:1px solid var(--gray-200)}
.ov-c.accent{background:var(--brand-soft);border-color:#CBEBDD}
.ov-k{color:var(--blue);font-weight:var(--fw-500);margin-bottom:7px}.ov-v{font-size:var(--fs-14);color:var(--gray-700)}
.kpi{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;margin-bottom:34px}.kpi-c{border:1px solid var(--gray-300);border-radius:12px;padding:13px}.kpi-k{color:var(--gray-600)}.kpi-n{font:var(--fw-500) 22px/1.2 var(--mono);color:var(--brand-dark);margin:6px 0}
.sh{display:flex;align-items:center;gap:9px;margin:0 0 14px}.sh-no{width:24px;height:24px;border-radius:5px;background:var(--gray-900);color:#fff;display:grid;place-items:center;font:var(--fw-500) var(--fs-12) var(--mono)}.sh-t{font-size:var(--fs-18);font-weight:var(--fw-500)}.sh-sub{color:var(--gray-600)}
.main{display:grid;grid-template-columns:430px 1fr;gap:34px;align-items:start;margin-bottom:38px}.phone-col{position:sticky;top:14px}
.phone{width:390px;max-width:100%;height:820px;margin-left:18px;border:9px solid #1D2730;border-radius:38px;overflow:hidden;background:#F8FAF8;position:relative;box-shadow:0 20px 50px rgba(20,30,40,.22)}
.status{height:30px;background:#fff;padding:7px 17px 0;display:flex;justify-content:space-between}
.app{height:calc(100% - 30px);overflow:auto;padding-bottom:82px;background:#F8FAF8;scroll-behavior:smooth}
.app-head{position:sticky;top:0;z-index:12;background:#fff;border-bottom:1px solid var(--gray-200);padding:12px 15px;display:flex;align-items:center;justify-content:space-between}
.brand{display:flex;align-items:center;gap:9px}.brand-mark{width:34px;height:34px;border-radius:12px;background:var(--brand);display:grid;place-items:center;color:#fff;font-size:18px}.brand-copy b{display:block;font-size:var(--fs-18)}.brand-copy span{color:var(--gray-600)}
.head-actions{display:flex;gap:8px}.icon{width:44px;height:44px;border:0;border-radius:12px;background:var(--gray-100);font-size:var(--fs-18)}
.section{padding:0 14px 14px}.section-head{display:flex;justify-content:space-between;align-items:end;margin:14px 0 10px}.section-head h4{font-size:var(--fs-16);margin:0}.section-head button{border:0;background:transparent;color:var(--brand-dark)}
.today{margin:14px;padding:16px;border-radius:18px;background:linear-gradient(135deg,var(--brand-soft),#fff);border:1px solid #CBEBDD}
.today-top{display:flex;justify-content:space-between;gap:12px}.today h3{font-size:var(--fs-18);margin:4px 0}.today p{margin:0;color:var(--gray-700);font-size:var(--fs-14)}
.score{width:70px;height:70px;border-radius:50%;display:grid;place-items:center;background:#fff;border:7px solid #BCE9D5}.score b{font-size:var(--fs-18)}
.metrics{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:12px}.metric{background:#fff;border:1px solid var(--gray-200);border-radius:12px;padding:10px}.metric small{color:var(--gray-600);display:block}.metric b{font-size:var(--fs-16)}
.ai-card{background:var(--gray-900);color:#fff;border-radius:18px;padding:16px;position:relative;overflow:hidden}.ai-card:after{content:"✦";position:absolute;right:14px;top:10px;font-size:56px;opacity:.12}.ai-card .eyebrow{color:#BDEBD8}.ai-card h3{font-size:var(--fs-18);margin:6px 0}.ai-card p{color:#D9E3DE;margin:0 0 12px}.reason{display:flex;gap:6px;flex-wrap:wrap}.chip{display:inline-flex;align-items:center;padding:6px 9px;border-radius:999px;background:var(--gray-100);border:1px solid var(--gray-300)}.ai-card .chip{background:rgba(255,255,255,.1);border-color:rgba(255,255,255,.15);color:#fff}
.ai-actions{display:flex;gap:8px;margin-top:14px}.btn{border:0;border-radius:12px;padding:11px 13px;font-size:var(--fs-14);font-weight:var(--fw-500)}.btn.primary{background:var(--brand);color:#fff}.btn.light{background:#fff;color:var(--gray-900)}.btn.ghost{background:var(--gray-100);color:var(--gray-900);border:1px solid var(--gray-300)}
.expiring-list{display:grid;gap:8px}.ing{display:grid;grid-template-columns:48px 1fr auto;gap:10px;align-items:center;background:#fff;border:1px solid var(--gray-200);border-radius:14px;padding:10px}.food{width:48px;height:48px;border-radius:12px;background:var(--brand-soft);display:grid;place-items:center;font-size:28px}.ing b{font-size:var(--fs-14)}.ing small{display:block;color:var(--gray-600)}.dday{font-weight:var(--fw-500);color:var(--danger)}
.fridge-summary{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}.fridge-card{background:#fff;border:1px solid var(--gray-200);border-radius:14px;padding:12px}.fridge-card span{font-size:24px}.fridge-card b{display:block;font-size:var(--fs-16);margin-top:3px}.fridge-card small{color:var(--gray-600)}
.recipe-scroll,.chef-scroll,.quick-scroll{display:flex;gap:10px;overflow:auto;padding-bottom:3px}.recipe{flex:0 0 210px;background:#fff;border:1px solid var(--gray-200);border-radius:16px;overflow:hidden}.recipe-img{height:120px;background:linear-gradient(135deg,#FFE2D3,#FFF);display:grid;place-items:center;font-size:56px}.recipe-body{padding:11px}.recipe-body b{font-size:var(--fs-14)}.recipe-body small{display:block;color:var(--gray-600);margin-top:3px}
.chef{flex:0 0 88px;text-align:center}.chef .avatar{width:58px;height:58px;border-radius:50%;margin:auto;background:var(--blue-soft);display:grid;place-items:center;font-size:28px;border:2px solid transparent}.chef.active .avatar{border-color:var(--brand)}.chef b{display:block;margin-top:6px}.chef small{color:var(--gray-600)}
.quick{flex:0 0 92px;background:#fff;border:1px solid var(--gray-200);border-radius:14px;padding:12px;text-align:center}.quick span{font-size:28px}.quick b{display:block;margin-top:5px}
.shopping{background:#fff;border:1px solid var(--gray-200);border-radius:16px;padding:12px}.shop-row{display:flex;align-items:center;justify-content:space-between;padding:9px 0;border-bottom:1px solid var(--gray-100)}.shop-row:last-child{border-bottom:0}.shop-row label{display:flex;gap:8px;align-items:center}
.bottom{position:absolute;left:0;right:0;bottom:0;height:70px;background:#fff;border-top:1px solid var(--gray-200);display:grid;grid-template-columns:repeat(5,1fr);padding:6px 4px}.nav{border:0;background:none;display:grid;place-items:center;gap:2px;color:var(--gray-500);min-height:44px}.nav span{font-size:var(--fs-18)}.nav.active{color:var(--brand-dark)}.nav.ai{width:50px;height:50px;border-radius:50%;background:var(--brand);color:#fff;margin:-18px auto 0}
.cols2{display:grid;grid-template-columns:1fr 1fr;gap:28px;margin-bottom:34px}.rules{display:grid;grid-template-columns:repeat(2,1fr);gap:10px}.rule{border:1px solid var(--gray-300);border-radius:12px;padding:12px}.rule h4{font-size:var(--fs-14);margin:5px 0}.rule p{margin:0;color:var(--gray-700)}
pre{white-space:pre-wrap;background:#14202A;color:#D8E7DF;padding:14px;border-radius:12px;font-size:var(--fs-12);overflow:auto}
.toast{position:fixed;left:50%;bottom:24px;transform:translateX(-50%) translateY(80px);background:var(--gray-900);color:#fff;border-radius:999px;padding:10px 14px;opacity:0;transition:.25s;z-index:120}.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
@media(max-width:1100px){.main{grid-template-columns:1fr}.phone-col{position:static}.meta{grid-template-columns:repeat(2,1fr)}.ov,.cols2{grid-template-columns:1fr}.kpi{grid-template-columns:repeat(2,1fr)}}
@media(max-width:700px){body{padding:12px}.doc{padding:24px 16px}.meta,.rules{grid-template-columns:1fr}.phone{margin-left:0;height:760px}.kpi{grid-template-columns:1fr}}
@media (prefers-reduced-motion:reduce){*{scroll-behavior:auto!important;animation:none!important;transition:none!important}}

/* ===== v2 UX refinement ===== */
.signature-hero{
  margin:14px;padding:18px;border-radius:20px;
  background:linear-gradient(135deg,var(--brand-soft),#fff 72%);
  border:1px solid #CBEBDD;position:relative;overflow:hidden
}
.signature-hero:after{content:"🥬";position:absolute;right:12px;top:10px;font-size:76px;opacity:.12}
.signature-hero .hello{color:var(--brand-dark);font-weight:var(--fw-500)}
.signature-hero h2{font-size:var(--fs-18);margin:6px 0 4px}.signature-hero p{font-size:var(--fs-14);color:var(--gray-700);margin:0}
.hero-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin:14px 0}
.hero-stat{background:#fff;border:1px solid var(--gray-200);border-radius:12px;padding:10px}
.hero-stat small{display:block;color:var(--gray-600)}.hero-stat b{font-size:var(--fs-16)}
.hero-primary{width:100%}
.ai-carousel{display:flex;gap:10px;overflow:auto;scroll-snap-type:x mandatory;padding-bottom:4px}
.ai-option{flex:0 0 88%;scroll-snap-align:start;background:var(--gray-900);color:#fff;border-radius:18px;padding:16px;position:relative}
.ai-option h3{font-size:var(--fs-18);margin:6px 0}.ai-option p{color:#D9E3DE;margin:0 0 10px}
.ai-rank{display:inline-flex;width:24px;height:24px;border-radius:50%;align-items:center;justify-content:center;background:var(--brand);font-weight:var(--fw-500)}
.ai-meta{display:flex;gap:6px;flex-wrap:wrap;margin:10px 0}.ai-meta .chip{background:rgba(255,255,255,.1);border-color:rgba(255,255,255,.15);color:#fff}
.explain{margin-top:10px;background:rgba(255,255,255,.08);border-radius:12px;padding:10px}
.explain b{display:block;margin-bottom:5px}.explain span{display:block;color:#DDE8E3}
.fridge-visual{background:#fff;border:1px solid var(--gray-200);border-radius:18px;padding:14px}
.fridge-box{height:220px;border:2px solid var(--gray-300);border-radius:18px;display:grid;grid-template-columns:1fr 1fr;overflow:hidden;position:relative;background:linear-gradient(#fff,#F7F9F8)}
.fridge-zone{position:relative;border-right:1px solid var(--gray-300);display:flex;align-items:center;justify-content:center}
.fridge-zone:last-child{border-right:0}.fridge-zone .badge{position:absolute;top:10px;left:10px;background:var(--brand);color:#fff;border-radius:999px;padding:5px 8px}
.fridge-zone .emoji{font-size:58px}.fridge-lower{position:absolute;left:0;right:0;bottom:0;height:64px;border-top:1px solid var(--gray-300);display:grid;grid-template-columns:1fr 1fr;background:#FAFBFA}
.fridge-lower div{display:flex;align-items:center;justify-content:center;gap:6px}.fridge-lower div:first-child{border-right:1px solid var(--gray-300)}
.ing-actions{margin-top:7px}.ing-actions button{border:0;background:var(--brand-soft);color:var(--brand-dark);border-radius:9px;padding:7px 9px}
.recipe-body .recipe-meta{display:flex;gap:5px;flex-wrap:wrap;margin-top:7px}.recipe-body .recipe-meta span{background:var(--gray-100);border-radius:999px;padding:4px 7px}
.recipe-foot{display:flex;align-items:center;justify-content:space-between;margin-top:9px}.recipe-foot button{border:0;background:none}
.emotion-card{background:var(--blue-soft);border:1px solid #D8DEFF;border-radius:16px;padding:14px}.emotion-card h4{font-size:var(--fs-16);margin:0 0 4px}.emotion-card p{margin:0;color:#4059AD}
.fab-menu{position:absolute;left:50%;bottom:78px;transform:translateX(-50%) scale(.92);width:260px;background:#fff;border:1px solid var(--gray-300);border-radius:18px;padding:10px;box-shadow:0 14px 36px rgba(20,30,40,.18);opacity:0;pointer-events:none;transition:.18s;z-index:30}
.fab-menu.open{opacity:1;pointer-events:auto;transform:translateX(-50%) scale(1)}
.fab-menu-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}.fab-option{border:1px solid var(--gray-200);background:var(--gray-50);border-radius:12px;padding:12px;text-align:left}.fab-option span{font-size:24px}.fab-option b{display:block;margin-top:4px}
.flow-strip{display:grid;grid-template-columns:repeat(6,1fr);gap:8px;margin:0 0 34px}.flow-step{border:1px solid var(--gray-300);border-radius:12px;padding:12px;text-align:center}.flow-step b{display:block;margin-top:5px}.flow-arrow{display:none}
@media(max-width:1100px){.flow-strip{grid-template-columns:repeat(3,1fr)}}
@media(max-width:700px){.flow-strip{grid-template-columns:1fr 1fr}}


/* ===== FINAL DATA-CONNECTED IMPLEMENTATION ADDITIONS ===== */
.impl-final{margin-top:40px;border-top:2px solid var(--gray-900,#16191D);padding-top:24px}
.impl-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.impl-card{border:1px solid var(--gray-300,#E1E4E8);border-radius:12px;padding:14px;background:var(--gray-0,#fff)}
.impl-card h3{font-size:14px;font-weight:500;margin:0 0 8px}
.impl-card p,.impl-card li{font-size:12px;line-height:1.7;color:var(--gray-700,#565D66)}
.impl-card ul{padding-left:18px;margin:0}
.route-table{width:100%;border-collapse:collapse}
.route-table th{background:var(--gray-200,#EDEFF2);text-align:left;padding:9px;font-size:12px}
.route-table td{padding:9px;border-bottom:1px solid var(--gray-200,#EDEFF2);font-size:12px;vertical-align:top}
.state-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:8px}
.state-chip{border:1px solid var(--gray-300,#E1E4E8);border-radius:10px;padding:10px;text-align:center;background:var(--gray-0,#fff)}
.state-chip b{display:block;margin-bottom:4px}
.pill{display:inline-block;padding:3px 7px;border-radius:999px;font-size:11px;border:1px solid var(--gray-400,#CDD2D8)}
.pill.p1{background:var(--gray-900,#16191D);color:#fff;border-color:var(--gray-900,#16191D)}
.pill.ok{background:#EEF8F2;color:#1E7A4F;border-color:#CDEAD9}
.pill.warn{background:#FFF6E8;color:#9A5B00;border-color:#F3D6A4}
@media(max-width:900px){.impl-grid{grid-template-columns:1fr}.state-grid{grid-template-columns:1fr 1fr}}


/* ===== HOM-001 B/C/D/E visual states ===== */
.state-showcase{display:grid;grid-template-columns:repeat(2,minmax(340px,1fr));gap:22px;margin:0 0 36px}
.state-panel{border:1px solid var(--gray-300);border-radius:18px;padding:14px;background:var(--gray-50)}
.state-label{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:10px}
.state-label h3{font-size:var(--fs-16);margin:0}.state-label p{margin:3px 0 0;color:var(--gray-600)}
.state-screen{width:375px;max-width:100%;height:760px;margin:auto;background:#F8FAF8;border:7px solid #1E2932;border-radius:34px;overflow:hidden;position:relative}
.state-app{height:100%;overflow:auto;padding-bottom:72px}
.state-head{height:58px;background:#fff;border-bottom:1px solid var(--gray-200);display:flex;align-items:center;justify-content:space-between;padding:0 16px}
.state-content{padding:14px}.state-card{background:#fff;border:1px solid var(--gray-200);border-radius:16px;padding:16px;margin-bottom:12px}
.state-hero{background:var(--brand-soft);border-color:#CBEBDD}.state-hero h4{font-size:var(--fs-18);margin:5px 0}.state-hero p{margin:0;color:var(--gray-700)}
.state-icon{width:72px;height:72px;border-radius:50%;display:grid;place-items:center;background:var(--gray-100);font-size:34px;margin:18px auto 12px}
.state-center{text-align:center;padding:24px 16px}.state-center h4{font-size:var(--fs-18);margin:0 0 6px}.state-center p{color:var(--gray-600);margin:0 0 16px}
.state-actions{display:grid;gap:8px}.state-actions.two{grid-template-columns:1fr 1fr}
.state-btn{min-height:44px;border:0;border-radius:12px;padding:11px;font-weight:var(--fw-500)}.state-btn.primary{background:var(--brand);color:#fff}.state-btn.secondary{background:#fff;border:1px solid var(--gray-300)}
.skeleton{background:linear-gradient(90deg,var(--gray-100) 25%,var(--gray-200) 37%,var(--gray-100) 63%);background-size:400% 100%;animation:sk 1.4s ease infinite;border-radius:9px}
.sk-line{height:13px;margin-bottom:8px}.sk-line.short{width:55%}.sk-hero{height:150px}.sk-card{height:105px}
@keyframes sk{0%{background-position:100% 0}100%{background-position:0 0}}
.offline-banner{background:var(--warning-soft);border:1px solid #F1D3AE;border-radius:12px;padding:11px;margin-bottom:12px}.offline-banner b{display:block;color:#8B5A1E}.offline-banner span{color:#8B6B48}
.partial-error{background:var(--danger-soft);border:1px solid #F4C3BC;border-radius:14px;padding:14px}.partial-error b{display:block;color:#A53B30;margin-bottom:4px}.partial-error p{margin:0 0 10px;color:#8F554F}
.fallback-list{display:grid;gap:8px}.fallback-item{border:1px solid var(--gray-200);background:#fff;border-radius:12px;padding:12px}
.state-bottom{position:absolute;left:0;right:0;bottom:0;height:66px;background:#fff;border-top:1px solid var(--gray-200);display:grid;grid-template-columns:repeat(5,1fr);padding:6px}
.state-nav{text-align:center;color:var(--gray-500)}.state-nav b{display:block;font-size:18px}.state-nav.active{color:var(--brand-dark)}
.state-rule{margin-top:12px;padding:11px;border-left:3px solid var(--brand);background:#fff;border-radius:8px;color:var(--gray-700)}
@media(max-width:980px){.state-showcase{grid-template-columns:1fr}}
@media(prefers-reduced-motion:reduce){.skeleton{animation:none}}


/* ===== v5 full-page scroll fix =====
   휴대폰 프리뷰 내부의 이중 스크롤을 제거하고,
   브라우저의 일반 세로 스크롤로 모든 콘텐츠를 확인한다. */
.phone{
  height:auto !important;
  min-height:820px;
  overflow:hidden !important;
}
.app{
  height:auto !important;
  max-height:none !important;
  overflow:visible !important;
  padding-bottom:0 !important;
}
.bottom{
  position:sticky !important;
  left:auto !important;
  right:auto !important;
  bottom:0 !important;
  z-index:40;
}
.phone-col{
  position:static !important;
}
.state-screen{
  height:auto !important;
  min-height:760px;
  overflow:hidden !important;
}
.state-app{
  height:auto !important;
  max-height:none !important;
  overflow:visible !important;
  padding-bottom:0 !important;
}
.state-bottom{
  position:sticky !important;
  left:auto !important;
  right:auto !important;
  bottom:0 !important;
  z-index:20;
}
.full-scroll-guide{
  margin:0 0 16px 18px;
  width:390px;
  max-width:100%;
  padding:10px 12px;
  border:1px solid var(--gray-300);
  border-radius:10px;
  background:#fff;
  color:var(--gray-700);
}
.full-scroll-guide b{color:var(--brand-dark)}
@media(max-width:700px){
  .phone{height:auto !important;min-height:760px}
}


.low-badge{display:inline-flex;align-items:center;gap:4px;padding:5px 8px;border-radius:999px;background:var(--warning-soft);color:#8B5A1E;border:1px solid #F1D3AE;font-weight:var(--fw-500)}
.low-ing{border-color:#F1D3AE;background:#FFFDFC}
.low-ing .food{background:var(--warning-soft)}
.low-dot{display:inline-block;width:7px;height:7px;border-radius:50%;background:var(--warning);margin-right:5px}
.low-summary{display:flex;align-items:center;justify-content:space-between;margin-top:10px;padding:10px 12px;border-radius:12px;background:var(--warning-soft);border:1px solid #F1D3AE}
.low-summary b{color:#8B5A1E}
.low-reason{color:#F6D6A8!important}
.low-count{background:var(--warning-soft)!important;color:#8B5A1E!important;border-color:#F1D3AE!important}
.detail-guide{margin-top:40px;border-top:2px solid var(--gray-900);padding-top:24px}
.guide-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.guide-card{border:1px solid var(--gray-300);border-radius:14px;padding:15px;background:#fff}
.guide-card h3{font-size:var(--fs-16);margin:0 0 8px}
@media(max-width:900px){.guide-grid{grid-template-columns:1fr}}


html,body{margin:0!important;padding:0!important;background:#E9EEF0!important}
body{font-size:12px!important}
.doc,.dh,.ov,.kpi,.main>div:not(.phone-col),.sh,.full-scroll-guide,.cols2,.rules,.detail-guide,.impl-final,.state-showcase{display:none!important}
.phone-col{display:block!important;position:static!important}
.phone{width:min(100%,430px)!important;max-width:none!important;margin:0 auto!important;border:0!important;border-radius:0!important;box-shadow:0 0 28px rgba(21,35,45,.16)!important;min-height:100vh!important;background:#F8FAF8!important;overflow:visible!important}
.status{height:34px!important;padding:7px 22px 0!important}
.app{height:auto!important;overflow:visible!important;padding-bottom:84px!important}
.app-head{top:0!important;padding:14px 18px!important}
.bottom{position:fixed!important;left:50%!important;right:auto!important;bottom:0!important;transform:translateX(-50%)!important;width:min(100%,430px)!important;z-index:50!important}
.fab-menu{position:fixed!important;left:50%!important;bottom:84px!important;z-index:60!important}
.toast{z-index:100!important}
.signature-hero{margin-top:20px!important}
@media(max-width:700px){body{padding:0!important}.phone{width:100%!important}}

.icon-wrap{position:relative;display:inline-flex}.unread-badge{position:absolute;right:-3px;top:-4px;min-width:18px;height:18px;padding:0 5px;border-radius:999px;background:var(--danger);color:#fff;border:2px solid #fff;display:grid;place-items:center;font:500 10px/1 var(--mono)}
</style></head><body><div class="phone">
<div class="status"><span>9:41</span><span>▮▮▮ Wi‑Fi 🔋</span></div>
<div class="app" id="homeApp">
<header class="app-head">
<div class="brand"><div class="brand-mark">냉</div><div class="brand-copy"><b>냉일</b><span>냉장고에서 시작하는 오늘의 식사</span></div></div>
<div class="head-actions"><button aria-label="검색" class="icon" data-action="search">⌕</button><span class="icon-wrap"><button aria-label="읽지 않은 알림 3건" class="icon" data-action="alarm">🔔</button><span class="unread-badge">3</span></span></div>
</header>
<section class="signature-hero">
<div class="hello">안녕하세요, 양양님</div>
<h2>오늘 뭐 드실까요?</h2>
<p>오늘 소비하면 좋은 재료를 기준으로 AI가 식단 3가지를 준비했어요.</p>
<div class="hero-stats">
<div class="hero-stat"><small>오늘 소비 추천</small><b>3개</b></div>
<div class="hero-stat"><small>예상 절약</small><b>4,500원</b></div>
<div class="hero-stat low-count"><small>조금 남은 재료</small><b>2개</b></div>
</div>
<button class="btn primary hero-primary" data-action="ai">오늘의 냉일 추천 시작</button>
</section>
<section class="today">
<div class="today-top">
<div><span class="chip">7월 24일 · 금요일</span><h3>오늘 식단 준비도 72%</h3><p>아침은 기록했고, 점심과 저녁 추천이 준비됐어요.</p></div>
<div class="score"><b>72</b></div>
</div>
<div class="metrics">
<div class="metric"><small>섭취 칼로리</small><b>580</b><span> / 1,650 kcal</span></div>
<div class="metric"><small>물</small><b>3</b><span> / 8잔</span></div>
<div class="metric"><small>단백질</small><b>28g</b><span> / 75g</span></div>
</div>
</section>
<section class="section">
<div class="section-head"><h4>AI 오늘의 추천 3가지</h4><button data-action="reroll">다시 추천</button></div>
<div class="ai-carousel">
<article class="ai-option">
<span class="ai-rank">1</span><h3>파프리카 닭가슴살 볶음</h3>
<p>소비기한이 오늘인 파프리카를 가장 먼저 사용할 수 있어요.</p>
<div class="ai-meta"><span class="chip">25분</span><span class="chip">320kcal</span><span class="chip">고단백</span></div>
<div class="explain"><b>왜 추천했나요?</b><span>✓ 파프리카 D-0</span><span class="low-reason">✓ 새우 조금 남음</span><span>✓ 오늘 단백질 47g 부족</span><span>✓ 30분 이내 조리 가능</span><span>✓ 최근 7일 메뉴와 중복 없음</span></div>
<div class="ai-actions"><button class="btn light" data-action="recipe">레시피 보기</button><button class="btn primary" data-action="mealAdd">식단에 담기</button></div>
</article>
<article class="ai-option">
<span class="ai-rank">2</span><h3>상추 불고기 덮밥</h3>
<p>D-1 상추와 남은 불고기를 한 번에 사용할 수 있어요.</p>
<div class="ai-meta"><span class="chip">20분</span><span class="chip">480kcal</span><span class="chip">한 그릇</span></div>
<div class="explain"><b>추천 이유</b><span>✓ 상추 D-1</span><span class="low-reason">✓ 치즈 조금 남음</span><span>✓ 남은 반찬 활용</span><span>✓ 점심 선호 메뉴</span></div>
<div class="ai-actions"><button class="btn light" data-action="recipe">레시피 보기</button><button class="btn primary" data-action="mealAdd">식단에 담기</button></div>
</article>
<article class="ai-option">
<span class="ai-rank">3</span><h3>토마토 계란볶음</h3>
<p>10분이면 완성되는 가벼운 저녁 메뉴예요.</p>
<div class="ai-meta"><span class="chip">10분</span><span class="chip">260kcal</span><span class="chip">쉬움</span></div>
<div class="explain"><b>추천 이유</b><span>✓ 방울토마토 D-2</span><span>✓ 부족한 단백질 보완</span><span>✓ 짧은 조리시간</span></div>
<div class="ai-actions"><button class="btn light" data-action="recipe">레시피 보기</button><button class="btn primary" data-action="mealAdd">식단에 담기</button></div>
</article>
</div>
</section>
<section class="section">
<div class="section-head"><h4>오늘 먼저 먹어야 해요</h4><button data-action="expiry">전체보기</button></div>
<div class="expiring-list">
<div class="ing"><div class="food">🫑</div><div><b>파프리카</b><small>냉장실 중간칸 · 1개</small><div class="ing-actions"><button data-action="ingredientRecipe">이 재료 요리 보기</button></div></div><div class="dday">오늘</div></div>
<div class="ing low-ing"><div class="food">🍤</div><div><b>새우</b><small>냉동실 위칸 · 상태로 관리 중</small><div class="ing-actions"><button data-action="ingredientRecipe">이 재료 요리 보기</button></div></div><div class="low-badge"><span class="low-dot"></span>조금 남음</div></div>
<div class="ing"><div class="food">🥬</div><div><b>상추</b><small>야채칸 · 1봉</small><div class="ing-actions"><button data-action="ingredientRecipe">이 재료 요리 보기</button></div></div><div class="dday">D-1</div></div>
</div>
</section>
<section class="section">
<div class="section-head"><h4>내 냉장고</h4><button data-action="fridge">냉장고 열기</button></div>
<div class="fridge-visual">
<div class="fridge-box">
<div class="fridge-zone"><span class="badge">냉동 7</span><span class="emoji">❄️</span></div>
<div class="fridge-zone"><span class="badge">냉장 18</span><span class="emoji">🧊</span></div>
<div class="fridge-lower">
<div><span>🥬</span><b>야채 5</b></div>
<div><span>🥫</span><b>기타 4</b></div>
</div>
</div>
<p style="margin:10px 0 0;color:var(--gray-600)">임박 3개 · 오래된 냉동재료 1개 · 총 34개</p><div class="low-summary"><span><span class="low-dot"></span>조금 남은 재료</span><b>2개 ›</b></div>
</div>
</section>
<section class="section">
<div class="section-head"><h4>AI 추천 레시피</h4><button data-action="allRecipe">더보기</button></div>
<div class="recipe-scroll">
<article class="recipe"><div class="recipe-img">🍳</div><div class="recipe-body"><b>채소 계란말이</b><small>백선생 레시피</small><div class="recipe-meta"><span>20분</span><span>쉬움</span><span>320kcal</span></div><div class="recipe-foot"><small>저장 128</small><button data-action="recipe">보기</button></div></div></article>
<article class="recipe"><div class="recipe-img">🥘</div><div class="recipe-body"><b>닭가슴살 토마토 스튜</b><small>최셰프 레시피</small><div class="recipe-meta"><span>35분</span><span>보통</span><span>410kcal</span></div><div class="recipe-foot"><small>저장 96</small><button data-action="recipe">보기</button></div></div></article>
<article class="recipe"><div class="recipe-img">🥗</div><div class="recipe-body"><b>상추 두부 샐러드</b><small>리나 레시피</small><div class="recipe-meta"><span>10분</span><span>쉬움</span><span>260kcal</span></div><div class="recipe-foot"><small>저장 211</small><button data-action="recipe">보기</button></div></div></article>
</div>
</section>
<section class="section">
<div class="section-head"><h4>좋아하는 요리사</h4><button data-action="chef">편집</button></div>
<div class="chef-scroll">
<button class="chef active"><div class="avatar">👩‍🍳</div><b>백선생</b><small>집밥</small></button>
<button class="chef"><div class="avatar">👨‍🍳</div><b>최셰프</b><small>한식</small></button>
<button class="chef"><div class="avatar">🧑‍🍳</div><b>리나</b><small>다이어트</small></button>
<button class="chef"><div class="avatar">👩‍🍳</div><b>하루</b><small>간단요리</small></button>
</div>
</section>
<section class="section">
<div class="section-head"><h4>쇼핑리스트</h4><button data-action="shopping">전체보기</button></div>
<div class="shopping">
<div class="shop-row"><label><input type="checkbox"/> 두부 1모</label><span>저녁 식단</span></div>
<div class="shop-row"><label><input type="checkbox"/> 바나나</label><span>아침 간식</span></div>
<div class="shop-row"><label><input type="checkbox"/> 현미밥</label><span>재고 없음</span></div>
</div>
</section>
<section class="section">
<div class="section-head"><h4>빠른 실행</h4></div>
<div class="quick-scroll">
<button class="quick" data-action="photo"><span>📷</span><b>사진 AI</b></button>
<button class="quick" data-action="manual"><span>✍️</span><b>직접 입력</b></button>
<button class="quick" data-action="receipt"><span>🧾</span><b>영수증</b></button>
<button class="quick" data-action="voice"><span>🎙️</span><b>음성 입력</b></button>
</div>
</section>
<section class="section">
<div class="emotion-card">
<h4>이번 주 냉일 기록</h4>
<p>조금 남은 재료 2개를 다음 메뉴에 활용했어요. 기록이 더 쌓이면 주간 변화를 비교해드릴게요.</p>
</div>
</section>
<div class="fab-menu" id="fabMenu"><div class="fab-menu-grid"><button class="fab-option" data-action="photo"><span>📷</span><b>사진 AI</b></button><button class="fab-option" data-action="manual"><span>✍️</span><b>직접 입력</b></button><button class="fab-option" data-action="receipt"><span>🧾</span><b>영수증 OCR</b></button><button class="fab-option" data-action="voice"><span>🎙️</span><b>음성 입력</b></button></div></div><nav class="bottom">
<button class="nav active" data-action="home"><span>⌂</span>홈</button>
<button class="nav" data-action="fridge"><span>▣</span>냉장고</button>
<button aria-controls="fabMenu" aria-expanded="false" class="nav ai" id="fabButton"><span>＋</span></button>
<button class="nav" data-action="meal"><span>▤</span>식단</button>
<button class="nav" data-action="my"><span>●</span>마이</button>
</nav>
</div>
</div><div aria-live="polite" class="toast" id="toast"></div><script>
const toast=document.getElementById('toast');
function showToast(message){toast.textContent=message;toast.classList.add('show');clearTimeout(window.__t);window.__t=setTimeout(()=>toast.classList.remove('show'),1700)}
const map={search:'GLB-002 검색 홈으로 이동합니다',alarm:'GLB-005 알림센터를 엽니다',recipe:'REC-001 레시피 상세로 이동합니다',reroll:'냉장고 재료를 다시 분석해 추천을 바꿉니다',expiry:'소비기한 임박 재료를 모아봅니다',fridge:'FRD-001 내 냉장고로 이동합니다',allRecipe:'추천 레시피 목록을 엽니다',chef:'좋아하는 요리사를 편집합니다',photo:'사진 AI 재료 등록으로 이동합니다',manual:'직접 입력으로 이동합니다',receipt:'영수증 OCR로 이동합니다',voice:'음성 입력으로 이동합니다',shopping:'쇼핑리스트로 이동합니다',ai:'AI 추천 영역으로 이동합니다',meal:'MEAL-001 식단으로 이동합니다',mealAdd:'추천 메뉴를 오늘 식단에 담았어요',ingredientRecipe:'이 재료를 활용하는 레시피를 보여드려요',my:'MYP-001 마이로 이동합니다',home:'홈 최상단으로 이동합니다'};
document.querySelectorAll('[data-action]').forEach(el=>el.addEventListener('click',()=>{const a=el.dataset.action;if(a==='home')window.scrollTo({top:0,behavior:'smooth'});if(a==='ai')document.querySelector('.ai-carousel')?.scrollIntoView({behavior:'smooth'});showToast(map[a]||'선택했습니다')}));
document.querySelectorAll('.chef').forEach(btn=>btn.addEventListener('click',()=>{document.querySelectorAll('.chef').forEach(x=>x.classList.remove('active'));btn.classList.add('active');showToast(btn.querySelector('b').textContent+' 요리사를 선택했어요')}));
const fabButton=document.getElementById('fabButton'),fabMenu=document.getElementById('fabMenu');
fabButton?.addEventListener('click',e=>{e.stopPropagation();const open=fabMenu.classList.toggle('open');fabButton.setAttribute('aria-expanded',String(open))});
document.addEventListener('click',e=>{if(!fabMenu?.contains(e.target)&&e.target!==fabButton&&!fabButton?.contains(e.target)){fabMenu?.classList.remove('open');fabButton?.setAttribute('aria-expanded','false')}});
</script></body></html>
