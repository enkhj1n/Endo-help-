<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Iodine Status Assessment</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Georgia,serif;background:#f5f3ef;min-height:100vh;color:#334}
/* Header */
.hdr{background:#1e4d5c;color:#fff;padding:24px 32px 16px}
.hdr .sub{font-size:10px;letter-spacing:3px;color:#7fbfcc;text-transform:uppercase;margin-b
.hdr h1{font-size:22px;font-weight:700}
.hdr .mn{font-size:12px;color:#8ecfdc;margin-top:4px}
/* Tabs */
.tabs{background:#174050;display:flex;border-bottom:2px solid #1e4d5c}
.tab{padding:12px 22px;background:transparent;color:#8ecfdc;border:none;cursor:pointer;
font-size:13px;font-family:Georgia,serif;border-top:3px solid transparent}
.tab.active{background:#f5f3ef;color:#1e4d5c;font-weight:700;border-top:3px solid #f59e0b}
/* Container */
.wrap{max-width:900px;margin:0 auto;padding:24px 18px}
/* Cards */
.card{background:#fff;border:1.5px solid #e0ddd8;border-radius:8px;margin-bottom:14px;overf
.card-head{background:#1e4d5c;color:#fff;padding:11px 18px;font-size:12px;font-weight:700;
letter-spacing:1px;text-transform:uppercase}
/* Risk bars */
.risk{border-radius:8px;margin-bottom:14px;overflow:hidden;display:grid;
grid-template-columns:110px 160px 1fr}
.risk .score-box{padding:18px 14px;text-align:center;border-right:1px solid var(--bdr)}
.risk .score-box .slbl{font-size:10px;color:#888;text-transform:uppercase;letter-spacing:1p
.risk .score-box .sval{font-size:20px;font-weight:800}
.risk .label-box{padding:18px 14px;border-right:1px solid var(--bdr)}
.risk .label-box .badge{display:inline-block;color:#fff;font-size:10px;font-weight:700;
padding:3px 8px;border-radius:3px;letter-spacing:.8px;margin-bottom
.risk .label-box .mn{font-size:12px;color:#555}
.risk .advice-box{padding:16px 18px}
.risk .advice-box .albl{font-size:11px;color:#888;text-transform:uppercase;letter-spacing:1
.risk .advice-box .item{font-size:13px;margin-bottom:5px;display:flex;gap:7px}
.risk .advice-box .mn-block{margin-top:10px;padding-top:8px;border-top:1px dashed var(--bdr
.risk .advice-box .mn-lbl{font-size:10px;color:#999;margin-bottom:4px;letter-spacing:.8px}
.risk .advice-box .mn-item{font-size:11px;color:#667;margin-bottom:3px}
/* Scoring grid */
.sg{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:10px}
.sg-row{display:flex;justify-content:space-between;font-size:12px;padding:5px 10px;
background:#f8f7f4;border-radius:4px}
/* Assessment layout */
.assess-grid{display:grid;grid-template-columns:1fr 290px;gap:20px;align-items:start}
/* Question card */
.qcard{background:#fff;border:1.5px solid #e0ddd8;border-left:4px solid #e0ddd8;
border-radius:8px;padding:16px 18px;margin-bottom:12px}
.qcard.answered{border-left-color:#1e4d5c}
.qcard .qlbl{font-size:13px;font-weight:600;color:#1e4d5c;margin-bottom:4px}
.qcard .qmn{font-size:11px;color:#888;margin-bottom:12px}
.qcard .opts{display:flex;flex-wrap:wrap;gap:8px}
.opt-btn{padding:7px 14px;border-radius:5px;cursor:pointer;font-size:12px;
font-family:Georgia,serif;background:#f5f3ef;color:#445;
border:2px solid #e0ddd8;font-weight:400}
.opt-btn.sel{background:#1e4d5c;color:#fff;border-color:#1e4d5c;font-weight:700}
.opt-btn .pts{font-size:10px;font-weight:700;margin-left:6px}
/* Result panel */
.result-panel{position:sticky;top:20px;border-radius:8px;padding:20px 18px;margin-bottom:14
.result-panel .score-big{font-size:48px;font-weight:800;line-height:1;margin-bottom:10px}
.result-panel .badge{display:inline-block;color:#fff;font-size:10px;font-weight:700;
padding:3px 10px;border-radius:4px;letter-spacing:.8px;margin-bottom:1
.result-panel .rec{font-size:12px;margin-bottom:5px;display:flex;gap:6px}
/* Pregnancy box */
.preg-q{background:#faf5ff;border:1.5px solid #e9d5ff;border-left:4px solid #7c3aed;
border-radius:8px;padding:16px 18px;margin-bottom:18px}
.preg-q .plbl{font-size:12px;font-weight:700;color:#7c3aed;margin-bottom:10px}
.preg-q .popts{display:flex;gap:10px}
.preg-btn{padding:7px 16px;border-radius:5px;cursor:pointer;font-size:12px;
font-family:Georgia,serif;background:#fff;color:#555;border:2px solid #ddd}
.preg-btn.sel{background:#7c3aed;color:#fff;border-color:#7c3aed;font-weight:700}
/* Preg advice */
.preg-advice{border-radius:8px;padding:16px;margin-top:0}
.preg-advice .plbl{font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.
.preg-advice .item{font-size:11px;margin-bottom:5px;display:flex;gap:6px}
/* Table rows */
.trow{display:flex;justify-content:space-between;align-items:center;padding:11px 18px;
border-bottom:1px solid #f0ece6}
.trow:last-child{border-bottom:none}
.trow:nth-child(even){background:#fafaf8}
/* Food table */
.frow{display:grid;grid-template-columns:1fr 160px 80px;padding:10px 18px;
border-bottom:1px solid #f0ece6}
.frow:last-child{border-bottom:none}
.frow:nth-child(even){background:#fafaf8}
/* Green tips */
.green-box{background:#f0fdf4;border:1.5px solid #bbf7d0;border-left:5px solid #16a34a;
border-radius:8px;padding:16px 20px}
.green-box .glbl{font-size:12px;font-weight:700;color:#16a34a;text-transform:uppercase;
letter-spacing:1px;margin-bottom:10px}
.green-box .gitem{font-size:13px;margin-bottom:6px;display:flex;gap:8px}
/* Preg 2-col */
.preg-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px}
/* Note */
.note{margin-top:24px;padding:12px 16px;background:#ece9e3;border:1px solid #ddd8d0;
border-radius:6px;font-size:11px;color:#888}
/* Reset btn */
.reset-btn{padding:10px 20px;background:#1e4d5c;color:#fff;border:none;border-radius:6px;
cursor:pointer;font-size:13px;font-family:Georgia,serif;margin-top:4px}
/* Scoring note */
.score-note{font-size:12px;color:#888;margin-top:10px}
@media(max-width:650px){
.assess-grid{grid-template-columns:1fr}
.risk{grid-template-columns:1fr}
.preg-grid{grid-template-columns:1fr}
.result-panel{position:static}
}
</style>
</head>
<body>
<div class="hdr">
<div style="display:flex;align-items:center;gap:16px;margin-bottom:8px">
<img src="https://i.ibb.co/m5TXJ97R/att-F8m-B6-TIsp-NCqw-Fk-i-SEa-Gem-J8-ETJm-Rnj7-UOo0-X
alt="Эндокрин Оюутны Клуб" style="height:64px;width:64px;border-radius:8px;object-fi
<div>
</div>
</div>
</div>
<div class="sub">Endocrinology · Nutrition Assessment</div>
<h1>Iodine Status Assessment</h1>
<div class="mn">Йодын хэрэглээ ба мэдлэгийн үнэлгээ</div>
<div class="tabs">
<button class="tab active" onclick="showTab('table',this)">Risk Reference Table</button>
<button class="tab" onclick="showTab('assess',this)">Patient Assessment</button>
<button class="tab" onclick="showTab('edu',this)">IDD Education</button>
</div>
<div class="wrap">
<!-- ══ TAB: REFERENCE TABLE ══ -->
<div id="tab-table">
<p style="font-size:13px;color:#666;margin-bottom:20px">
Cross-reference the patient's response pattern to determine iodine status category and cl
</p>
<!-- Scoring guide -->
<div class="card" style="padding:18px 20px;margin-bottom:20px">
<div style="font-size:11px;font-weight:700;color:#1e4d5c;letter-spacing:1px;text-transfor
<div class="sg">
<div class="sg-row"><span>Non-iodized salt</span><span style="font-weight:700;color:#dc
<div class="sg-row"><span>Don't know salt type</span><span style="font-weight:700;color
<div class="sg-row"><span>Adds salt while boiling</span><span style="font-weight:700;co
<div class="sg-row"><span>Doesn't know storage rule</span><span style="font-weight:700;
<div class="sg-row"><span>Dairy: 1–2×/wk</span><span style="font-weight:700;color:#dc26
<div class="sg-row"><span>Dairy: never</span><span style="font-weight:700;color:#dc2626
<div class="sg-row"><span>Eggs: 1–2×/wk</span><span style="font-weight:700;color:#dc262
<div class="sg-row"><span>Eggs: never</span><span style="font-weight:700;color:#dc2626"
<div class="sg-row"><span>Seafood: 1–2×/wk</span><span style="font-weight:700;color:#dc
<div class="sg-row"><span>Seafood: never</span><span style="font-weight:700;color:#dc26
<div class="sg-row"><span>Knows 1 consequence</span><span style="font-weight:700;color:
<div class="sg-row"><span>Knows none</span><span style="font-weight:700;color:#dc2626">
<div class="sg-row"><span>No supplement</span><span style="font-weight:700;color:#dc262
</div>
<div class="score-note">Optimal answers score 0 on all items. Higher total = greater defi
</div>
<!-- ADEQUATE -->
<div class="risk" style="background:#f0fdf4;border:1.5px solid #bbf7d0;border-left:5px soli
<div class="score-box" style="border-right-color:#bbf7d0">
<div class="slbl">Score</div>
<div class="sval" style="color:#16a34a">0–3</div>
</div>
<div class="label-box" style="border-right-color:#bbf7d0">
<div class="badge" style="background:#16a34a">ADEQUATE</div>
<div class="mn">Хангалттай</div>
</div>
<div class="advice-box">
<div class="albl">Recommendations</div>
<div class="item"><span style="color:#16a34a;font-weight:700">›</span>Iodine intake app
<div class="item"><span style="color:#16a34a;font-weight:700">›</span>Continue using io
<div class="item"><span style="color:#16a34a;font-weight:700">›</span>Maintain regular
<div class="item"><span style="color:#16a34a;font-weight:700">›</span>No supplementatio
<div class="mn-block" style="border-top-color:#bbf7d0">
<div class="mn-lbl">МН ЗӨВЛӨМЖ</div>
<div class="mn-item">• Йодын хэрэглээ хангалттай байна</div>
<div class="mn-item">• Йоджуулсан давсаа зөв хадгалж хэрэглэсээр байх</div>
</div>
</div>
</div>
<!-- AT RISK -->
<div class="risk" style="background:#fffbeb;border:1.5px solid #fde68a;border-left:5px soli
<div class="score-box" style="border-right-color:#fde68a">
<div class="slbl">Score</div>
<div class="sval" style="color:#d97706">4–7</div>
</div>
<div class="label-box" style="border-right-color:#fde68a">
<div class="badge" style="background:#d97706">AT RISK</div>
<div class="mn">Эрсдэлтэй</div>
</div>
<div class="advice-box">
<div class="albl">Recommendations</div>
<div class="item"><span style="color:#d97706;font-weight:700">›</span>Dietary review re
<div class="item"><span style="color:#d97706;font-weight:700">›</span>Switch to iodized
<div class="item"><span style="color:#d97706;font-weight:700">›</span>Increase seafood
<div class="item"><span style="color:#d97706;font-weight:700">›</span>Add salt after co
<div class="item"><span style="color:#d97706;font-weight:700">›</span>Consider suppleme
<div class="mn-block" style="border-top-color:#fde68a">
<div class="mn-lbl">МН ЗӨВЛӨМЖ</div>
<div class="mn-item">• Йодын хэрэглээ дутмаг байж болзошгүй</div>
<div class="mn-item">• Йоджуулсан давс хэрэглэж эхлэх</div>
<div class="mn-item">• Давсаа хоол бэлэн болсны дараа хийх</div>
</div>
</div>
</div>
<!-- HIGH RISK -->
<div class="risk" style="background:#fef2f2;border:1.5px solid #fecaca;border-left:5px soli
<div class="score-box" style="border-right-color:#fecaca">
<div class="slbl">Score</div>
<div class="sval" style="color:#dc2626">≥ 8</div>
</div>
<div class="label-box" style="border-right-color:#fecaca">
<div class="badge" style="background:#dc2626">HIGH RISK</div>
<div class="mn">Дутагдлын өндөр эрсдэл</div>
</div>
<div class="advice-box">
<div class="albl">Recommendations</div>
<div class="item"><span style="color:#dc2626;font-weight:700">›</span>Clinical assessme
<div class="item"><span style="color:#dc2626;font-weight:700">›</span>Switch to iodized
<div class="item"><span style="color:#dc2626;font-weight:700">›</span>Supplementation s
<div class="item"><span style="color:#dc2626;font-weight:700">›</span>Test thyroid func
<div class="item"><span style="color:#dc2626;font-weight:700">›</span>Follow-up in 3 mo
<div class="mn-block" style="border-top-color:#fecaca">
<div class="mn-lbl">МН ЗӨВЛӨМЖ</div>
<div class="mn-item">• Йод дутагдлын эрсдэл өндөр — эмнэлзүйн үнэлгээ хийх</div>
<div class="mn-item">• Йодын нэмэлт бэлдмэл уух (150 мкг/өдөр)</div>
<div class="mn-item">• Бамбай булчирхайн үйл ажиллагааг шинжлүүлэх</div>
</div>
</div>
</div>
<!-- Pregnancy -->
<div style="background:#faf5ff;border:1.5px solid #e9d5ff;border-left:5px solid #7c3aed;bor
<div style="font-size:12px;font-weight:700;color:#7c3aed;text-transform:uppercase;letter-
<div class="preg-grid">
<div style="background:#faf5ff;border:1px solid #e9d5ff;border-radius:6px;padding:14px
<div style="font-size:11px;font-weight:700;color:#7c3aed;margin-bottom:10px">Adequate
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
</div>
<div style="background:#fff1f2;border:1px solid #fecdd3;border-radius:6px;padding:14px
<div style="font-size:11px;font-weight:700;color:#be123c;margin-bottom:10px">At-risk
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
<div class="item" style="font-size:12px;margin-bottom:5px;display:flex;gap:6px"><span
</div>
</div>
</div>
<div class="note"><strong>Note:</strong> This tool uses response-pattern scoring for dietar
</div>
<!-- ══ TAB: ASSESSMENT ══ -->
<div id="tab-assess" style="display:none">
<div class="assess-grid">
<div>
<!-- Pregnancy question -->
<div class="preg-q">
<div class="plbl">Is the patient pregnant or breastfeeding? (Female patients only)</d
<div class="popts">
<button class="preg-btn" id="preg-yes" onclick="setPreg('yes')">Yes</button>
<button class="preg-btn" id="preg-no" onclick="setPreg('no')">No</button>
<button class="preg-btn" id="preg-na" onclick="setPreg('na')">N/A (male)</button>
</div>
</div>
<!-- Questions injected by JS -->
<div id="questions-container"></div>
<button class="reset-btn" onclick="resetAll()">Reset All</button>
</div>
<!-- Sticky result -->
<div>
<div id="result-panel" class="result-panel" style="background:#fff;border:1.5px solid #
<div style="font-size:11px;color:#888;text-transform:uppercase;letter-spacing:1px;mar
<div class="score-big" id="res-score" style="color:#ccc">–</div>
<div id="res-content" style="font-size:13px;color:#999">Answer all 8 questions </div>
<div id="preg-advice-panel" style="display:none"></div>
</div>
</div>
</div>
to see
<!-- ══ TAB: EDUCATION ══ -->
<div id="tab-edu" style="display:none">
<p style="font-size:13px;color:#666;margin-bottom:20px">Key patient education points on iod
<!-- Consequences -->
<div class="card" style="margin-bottom:18px">
<div class="card-head">Consequences of Iodine Deficiency</div>
<div class="trow"><div><div style="font-size:13px;font-weight:600;color:#1e4d5c">Goiter (
<div class="trow"><div><div style="font-size:13px;font-weight:600;color:#1e4d5c">Cognitiv
<div class="trow"><div><div style="font-size:13px;font-weight:600;color:#1e4d5c">Hair los
<div class="trow"><div><div style="font-size:13px;font-weight:600;color:#1e4d5c">Increase
</div>
<!-- Daily requirements -->
<div class="card" style="margin-bottom:18px">
<div class="card-head">Daily Iodine Requirements</div>
<div class="trow"><span style="font-size:13px">Adults (general)</span><span style="font-s
<div class="trow"><span style="font-size:13px">Pregnant women</span><span style="font-siz
<div class="trow"><span style="font-size:13px">Breastfeeding women</span><span style="fon
<div class="trow"><span style="font-size:13px">Children 1–8 yrs</span><span style="font-s
<div class="trow"><span style="font-size:13px">Children 9–13 yrs</span><span style="font-
<div class="trow"><span style="font-size:13px">Upper safe limit (adults)</span><span styl
</div>
<!-- Food sources -->
<div class="card" style="margin-bottom:18px">
<div class="card-head">Dietary Iodine Sources</div>
<div class="frow"><span style="font-size:13px">Seaweed / Kelp</span><span style="font-siz
<div class="frow"><span style="font-size:13px">Cod / white fish</span><span style="font-s
<div class="frow"><span style="font-size:13px">Iodized salt</span><span style="font-size:
<div class="frow"><span style="font-size:13px">Dairy milk</span><span style="font-size:12
<div class="frow"><span style="font-size:13px">Yogurt</span><span style="font-size:12px;c
<div class="frow"><span style="font-size:13px">Egg (1 large)</span><span style="font-size
<div class="frow"><span style="font-size:13px">Shrimp</span><span style="font-size:12px;c
<div class="frow"><span style="font-size:13px">Beef liver</span><span style="font-size:12
</div>
<!-- Salt practices -->
<div class="green-box">
<div class="glbl">✓ Correct Iodized Salt Practices</div>
<div class="gitem"><span style="color:#16a34a;font-weight:700">›</span>Use iodized salt —
<div class="gitem"><span style="color:#16a34a;font-weight:700">›</span>Store in a sealed,
<div class="gitem"><span style="color:#16a34a;font-weight:700">›</span>Add salt AFTER coo
<div class="gitem"><span style="color:#16a34a;font-weight:700">›</span>Do not store near
<div class="gitem"><span style="color:#16a34a;font-weight:700">›</span>Replace salt every
</div>
<div class="note" style="margin-top:18px"><strong>Note:</strong> UIC (urinary iodine concen
</div>
</div><!-- end .wrap -->
хэрэгл
<script>
const questions=[
{id:"salt",label:"Type of salt used",mn:"Хэрэглэдэг давсны төрөл",
opts:[{l:"Iodized salt",v:"iodized",s:0},{l:"Non-iodized / Rock / Lake salt",v:"non",s:2},
{id:"cooking",label:"When is salt added during cooking?",mn:"Давсаа хэзээ хийдэг вэ?",
opts:[{l:"While boiling (high heat)",v:"boil",s:2},{l:"After cooking / when serving",v:"af
{id:"storage",label:"Knows iodized salt should be stored in sealed, light-protected contain
opts:[{l:"Yes",v:"yes",s:0},{l:"No",v:"no",s:1}]},
{id:"dairy",label:"Dairy consumption (milk, yogurt, cheese)",mn:"Сүү, цагаан идээний opts:[{l:"Daily",v:"daily",s:0},{l:"3–5×/week",v:"often",s:0},{l:"1–2×/week",v:"sometimes"
{id:"eggs",label:"Egg consumption",mn:"Өндөгний хэрэглээ",
opts:[{l:"Daily",v:"daily",s:0},{l:"3–5×/week",v:"often",s:0},{l:"1–2×/week",v:"sometimes"
{id:"seafood",label:"Seafood / seaweed consumption",mn:"Далайн гаралтай хүнсний хэрэглээ",
opts:[{l:"Daily",v:"daily",s:0},{l:"3–5×/week",v:"often",s:0},{l:"1–2×/week",v:"sometimes"
{id:"knowledge",label:"Knows consequences of iodine deficiency",mn:"Йод дутагдсанаар үүсэх
opts:[{l:"Knows ≥2 consequences",v:"good",s:0},{l:"Knows 1 consequence",v:"partial",s:1},{
{id:"supplement",label:"Takes iodine supplement",mn:"Йодын нэмэлт бэлдмэл уудаг уу?",
opts:[{l:"Yes",v:"yes",s:0},{l:"No",v:"no",s:1}]},
];
const risks=[
{range:[0,3],label:"ADEQUATE",mn:"Хангалттай",color:"#16a34a",bg:"#f0fdf4",bdr:"#bbf7d0",
advice:["Iodine intake appears sufficient","Continue iodized salt stored correctly","Maint
{range:[4,7],label:"AT RISK",mn:"Эрсдэлтэй",color:"#d97706",bg:"#fffbeb",bdr:"#fde68a",
advice:["Dietary review recommended","Switch to iodized salt if not already","Seafood ≥2×/
{range:[8,99],label:"HIGH RISK OF DEFICIENCY",mn:"Дутагдлын өндөр эрсдэл",color:"#dc2626",b
advice:["Clinical assessment advised urgently","Switch to iodized salt immediately","Suppl
];
const pregAdvice={
ok:{color:"#7c3aed",bg:"#faf5ff",bdr:"#e9d5ff",
items:["Requirements: 220 µg/day (pregnancy), 290 µg/day (breastfeeding)","Prenatal iodin
risk:{color:"#be123c",bg:"#fff1f2",bdr:"#fecdd3",
items:["URGENT — irreversible fetal neurodevelopmental harm risk","Prescribe iodine 150–2
};
let answers={};
let pregStatus=null;
function buildQuestions(){
const c=document.getElementById('questions-container');
c.innerHTML='';
questions.forEach(q=>{
const d=document.createElement('div');
d.className='qcard'+(answers[q.id]!==undefined?' answered':'');
d.id='qcard-'+q.id;
let optsHtml=q.opts.map(o=>`
<button class="opt-btn${answers[q.id]===o.v?' sel':''}" onclick="selectOpt('${q.id}','$
${o.l}${o.s>0?`<span class="pts" style="color:${answers[q.id]===o.v?'#fde68a':'#dc262
</button>`).join('');
d.innerHTML=`<div class="qlbl">${q.label}</div><div class="qmn">${q.mn}</div><div class="
c.appendChild(d);
});
}
function selectOpt(qid,val,score){
answers[qid]=val;
buildQuestions();
updateResult();
}
function setPreg(v){
pregStatus=v;
['yes','no','na'].forEach(x=>{
document.getElementById('preg-'+x).classList.toggle('sel',x===v);
});
updateResult();
}
function getRisk(score){
return risks.find(r=>score>=r.range[0]&&score<=r.range[1]);
}
function updateResult(){
const answered=Object.keys(answers).length;
const total=Object.entries(answers).reduce((acc,[id,val])=>{
const q=questions.find(q=>q.id===id);
const opt=q?.opts.find(o=>o.v===val);
return acc+(opt?.s||0);
},0);
const panel=document.getElementById('result-panel');
const scoreEl=document.getElementById('res-score');
const countEl=document.getElementById('res-count');
const contentEl=document.getElementById('res-content');
const pregPanel=document.getElementById('preg-advice-panel');
countEl.textContent=`Risk Score (${answered}/${questions.length} answered)`;
if(answered<questions.length){
scoreEl.style.color='#ccc';
scoreEl.textContent=answered>0?total:'–';
panel.style.background='#fff';
panel.style.borderColor='#e0ddd8';
panel.style.borderLeftColor='#ccc';
contentEl.innerHTML=`<span style="color:#999">Answer all ${questions.length} questions</s
pregPanel.style.display='none';
return;
}
const r=getRisk(total);
scoreEl.textContent=total;
scoreEl.style.color=r.color;
panel.style.background=r.bg;
panel.style.borderColor=r.bdr;
panel.style.borderLeftColor=r.color;
const badgeHtml=`<div style="display:inline-block;background:${r.color};color:#fff;font-siz
const advHtml=r.advice.map(a=>`<div style="font-size:12px;margin-bottom:5px;display:flex;ga
contentEl.innerHTML=badgeHtml+advHtml;
// Pregnancy overlay
if(pregStatus==='yes'){
const isRisk=r.label!=='ADEQUATE';
const pa=isRisk?pregAdvice.risk:pregAdvice.ok;
const itemsHtml=pa.items.map(i=>`<div class="item" style="font-size:11px;margin-bottom:5p
pregPanel.style.display='block';
pregPanel.innerHTML=`<div class="preg-advice" style="background:${pa.bg};border:1.5px sol
<div class="plbl" style="color:${pa.color}">⚠ Pregnant / Breastfeeding</div>${itemsHtml
} else {
pregPanel.style.display='none';
}
}
function resetAll(){
answers={};
pregStatus=null;
['yes','no','na'].forEach(x=>document.getElementById('preg-'+x).classList.remove('sel'));
buildQuestions();
updateResult();
}
function showTab(id,btn){
['table','assess','edu'].forEach(t=>{
document.getElementById('tab-'+t).style.display=t===id?'block':'none';
});
document.querySelectorAll('.tab').forEach(b=>b.classList.remove('active'));
btn.classList.add('active');
}
// Init
buildQuestions();
updateResult();
</script>
</body>
</html>
