<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Pangmie Analytics</title>
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@600;800&family=Nunito:wght@400;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#FFF3D6;--surf:#FFFFFF;--ink:#3A0F0C;--mut:#7a4a3f;--red:#B3201A;--gold:#E59A00;--line:#ecd6a6;--ok:#1f8a3b;--bad:#B3201A;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#2a0b09;--surf:#3d1511;--ink:#FFF3D6;--mut:#e0b98f;--red:#e5483d;--gold:#F5B31B;--line:#5a2a22;--ok:#4cc46f;--bad:#ff7a6e}}
:root[data-theme="dark"]{--bg:#2a0b09;--surf:#3d1511;--ink:#FFF3D6;--mut:#e0b98f;--red:#e5483d;--gold:#F5B31B;--line:#5a2a22;--ok:#4cc46f;--bad:#ff7a6e}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 16px/1.5 Nunito,system-ui,sans-serif}
main{max-width:1040px;margin:0 auto;padding:20px 16px 48px}
h1,h2{font-family:"Baloo 2",system-ui,sans-serif;line-height:1.1;margin:0}
h1{font-size:clamp(28px,5vw,42px);font-weight:800}
h2{font-size:20px;font-weight:800;margin-bottom:10px}
.sub{color:var(--mut);margin:6px 0 16px;max-width:70ch}
.tag{display:inline-block;background:var(--gold);color:#3A0F0C;border-radius:999px;padding:2px 12px;font-weight:700;font-size:13px;margin-left:8px;vertical-align:middle}
.card{background:var(--surf);border:2px solid var(--line);border-radius:18px;padding:18px}
.g2{display:grid;grid-template-columns:1.6fr 1fr;gap:16px;margin-top:16px}
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:12px}
@media (max-width:820px){.g2{grid-template-columns:1fr}.g4{grid-template-columns:repeat(2,1fr)}}
.kpi b{display:block;font:800 30px "Baloo 2",system-ui,sans-serif;line-height:1.1}
.kpi span{color:var(--mut);font-size:13px}
.kpi i{font-style:normal;font-weight:700;font-size:13px}
.ok{color:var(--ok)}.bad{color:var(--bad)}
label{display:flex;justify-content:space-between;align-items:center;gap:10px;margin:7px 0;font-size:14px}
input[type=number]{width:90px;padding:6px 8px;border-radius:8px;border:2px solid var(--line);background:var(--bg);color:var(--ink);font:inherit}
button{font:800 15px "Baloo 2",system-ui,sans-serif;border:0;border-radius:999px;padding:9px 20px;cursor:pointer;background:var(--red);color:#FFF3D6;margin-top:8px}
button:focus-visible,input:focus-visible{outline:3px solid var(--gold);outline-offset:2px}
table{width:100%;border-collapse:collapse;font-size:14px}
td,th{padding:6px 4px;border-bottom:1px solid var(--line);text-align:left}
th{color:var(--mut);font-weight:700}
td:not(:first-child),th:not(:first-child){text-align:right}
.scroll{overflow-x:auto}
svg text{fill:var(--mut);font:12px Nunito,system-ui,sans-serif}
.bar{height:16px;border-radius:999px;background:var(--line);overflow:hidden;position:relative;margin:8px 0 4px}
.bar div{height:100%;border-radius:999px}
.verdict{border-left:6px solid var(--gold);padding:10px 14px;border-radius:10px;background:var(--bg);margin-top:12px}
.leg{display:flex;gap:16px;font-size:13px;color:var(--mut);margin-top:4px}
.leg span:before{content:"";display:inline-block;width:18px;height:4px;border-radius:2px;margin-right:6px;vertical-align:middle;background:var(--c)}
</style>
</head>
<body>
<main>
<h1>Pangmie Analytics<span class="tag">Data simulasi</span></h1>
<p class="sub">Mengukur apakah Spin Pangsit menambah repeat order dalam 30 hari tanpa melewati batas biaya hadiah 6% omzet. Angka di bawah dihitung dari asumsi di panel kanan; ganti dengan data asli Anda saat uji berjalan.</p>

<section class="g4" aria-label="Ringkasan">
  <div class="card kpi"><b id="a1"></b><span>Repeat order 14 hari (spin)</span><br><i id="a1d"></i></div>
  <div class="card kpi"><b id="a2"></b><span>Repeat order 30 hari (spin)</span><br><i id="a2d"></i></div>
  <div class="card kpi"><b id="a3"></b><span>Order per pelanggan / bulan</span><br><i id="a3d"></i></div>
  <div class="card kpi"><b id="a4"></b><span>Biaya hadiah / omzet</span><br><i id="a4d"></i></div>
</section>

<div class="g2">
  <section class="card" aria-labelledby="h1">
    <h2 id="h1">Repeat order kumulatif, 30 hari</h2>
    <div class="scroll"><svg id="chart" viewBox="0 0 620 300" role="img" aria-label="Grafik repeat order kumulatif kontrol dibanding spin" style="min-width:420px;width:100%"></svg></div>
    <div class="leg"><span style="--c:var(--mut)">Kontrol (tanpa spin)</span><span style="--c:var(--red)">Kelompok spin</span></div>
    <div class="verdict" id="verdict"></div>
  </section>

  <section class="card" aria-labelledby="h2">
    <h2 id="h2">Asumsi uji</h2>
    <label>Pelanggan per kelompok<input type="number" id="n" value="1000" min="50" step="50"></label>
    <label>Repeat 30 hari, kontrol (%)<input type="number" id="p0" value="30" min="1" max="95"></label>
    <label>Kenaikan relatif dari spin (%)<input type="number" id="up" value="25" min="-50" max="200"></label>
    <label>Membuka spin per hari (%)<input type="number" id="op" value="40" min="0" max="100"></label>
    <label>Kupon ditebus (%)<input type="number" id="rd" value="25" min="0" max="100"></label>
    <label>Order/bulan, kontrol<input type="number" id="a" value="1.6" min="0.1" step="0.1"></label>
    <label>Rata-rata belanja (Rp)<input type="number" id="aov" value="25000" min="1000" step="1000"></label>
    <button id="re">Acak ulang data</button>
  </section>
</div>

<div class="g2">
  <section class="card" aria-labelledby="h3">
    <h2 id="h3">Corong kelompok spin (per putaran)</h2>
    <div class="scroll"><table><thead><tr><th>Tahap</th><th>Jumlah</th><th>Dari tahap sebelumnya</th></tr></thead><tbody id="fun"></tbody></table></div>
  </section>
  <section class="card" aria-labelledby="h4">
    <h2 id="h4">Anggaran hadiah</h2>
    <div class="bar"><div id="bf"></div></div>
    <p id="bt" style="margin:4px 0 0;font-size:14px"></p>
    <p class="sub" style="font-size:13px;margin:10px 0 0">Aturan: jika biaya mencapai 90% batas, kupon bernilai tinggi dinonaktifkan otomatis.</p>
  </section>
</div>
</main>

<script>
var $=function(i){return document.getElementById(i)};
var rp=function(n){return "Rp"+Math.round(n).toLocaleString("id-ID")};
var seed=7;
function rnd(){seed|=0;seed=seed+0x6D2B79F5|0;var t=Math.imul(seed^seed>>>15,1|seed);t=t+Math.imul(t^t>>>7,61|t)^t;return((t^t>>>14)>>>0)/4294967296}
function curve(p,n){
  var out=[],k=1-Math.exp(-30/9),prev=0;
  for(var d=1;d<=30;d++){
    var base=p*(1-Math.exp(-d/9))/k;
    var se=Math.sqrt(Math.max(base,.001)*(1-base)/n);
    var v=Math.min(Math.max(base+(rnd()-.5)*se*.9,prev),1);
    out.push(v);prev=v;
  }
  out[29]=p;return out;
}
var COST={coupon:.10*3000+.05*3000+.02*10000,pts:.30*250+.18*500,couponRate:.17};
function pct(v){return (v*100).toFixed(1)+"%"}
function run(){
  var n=+$("n").value||0,p0=(+$("p0").value||0)/100,up=(+$("up").value||0)/100,op=(+$("op").value||0)/100,rd=(+$("rd").value||0)/100,a0=+$("a").value||0,aov=+$("aov").value||0;
  var p1=Math.min(p0*(1+up),.99);
  var c0=curve(p0,n),c1=curve(p1,n);
  var a1=a0*(1+up);
  var spins=n*op*30,cost=spins*(COST.pts+COST.coupon*rd);
  var rev=n*a1*aov,cp=rev?cost/rev*100:0;
  var pp=(p0+p1)/2,z=(p1-p0)/Math.sqrt(pp*(1-pp)*(2/Math.max(n,1)));
  var lift=function(x,y){return y?((x/y-1)*100):0};
  $("a1").textContent=pct(c1[13]);$("a1d").innerHTML=dl(lift(c1[13],c0[13]),"vs kontrol "+pct(c0[13]));
  $("a2").textContent=pct(p1);$("a2d").innerHTML=dl(lift(p1,p0),"vs kontrol "+pct(p0));
  $("a3").textContent=a1.toFixed(2);$("a3d").innerHTML=dl(lift(a1,a0),"vs kontrol "+a0.toFixed(2));
  $("a4").textContent=cp.toFixed(1)+"%";$("a4d").innerHTML='<span class="'+(cp<=6?"ok":"bad")+'">'+(cp<=6?"dalam batas 6%":"melewati batas 6%")+'</span>';
  draw(c0,c1);
  var v,sig=z>1.96;
  if(cp>6)v="<b>Kurangi hadiah.</b> Biaya "+cp.toFixed(1)+"% melewati batas 6%. Turunkan peluang kupon atau nilai kupon sebelum menambah pengguna.";
  else if(sig)v="<b>Lanjutkan dan perluas.</b> Kenaikan repeat order signifikan (z = "+z.toFixed(2)+") dan biaya masih "+cp.toFixed(1)+"% dari omzet.";
  else v="<b>Belum meyakinkan.</b> Selisih belum signifikan (z = "+z.toFixed(2)+"; perlu lebih dari 1,96). Tambah pelanggan atau perpanjang uji.";
  $("verdict").innerHTML=v;
  var open=Math.round(spins),won=Math.round(spins*COST.couponRate),red=Math.round(won*rd),ret=Math.round(red*.8);
  var rows=[["Putaran (30 hari)",open,""],["Menang kupon",won,pct(open?won/open:0)],["Kupon ditebus",red,pct(won?red/won:0)],["Order dari penebusan (perkiraan 80%)",ret,pct(red?ret/red:0)]];
  $("fun").innerHTML=rows.map(function(r){return "<tr><td>"+r[0]+"</td><td>"+r[1].toLocaleString("id-ID")+"</td><td>"+r[2]+"</td></tr>"}).join("");
  var use=Math.min(cp/6,1.5)*100;
  $("bf").style.width=Math.min(use,100)+"%";$("bf").style.background=cp>6?"var(--bad)":cp>5.4?"var(--gold)":"var(--ok)";
  $("bt").innerHTML="Biaya "+rp(cost)+" dari omzet "+rp(rev)+" = <b>"+cp.toFixed(1)+"%</b> (batas 6%, bar penuh = 6%)";
}
function dl(x,t){var c=x>=0?"ok":"bad";return '<span class="'+c+'">'+(x>=0?"+":"")+x.toFixed(1)+"%</span> "+t}
function draw(c0,c1){
  var W=620,H=300,L=44,R=12,T=14,B=34,mx=Math.max(c1[29],c0[29])*1.15,h="";
  var X=function(d){return L+(W-L-R)*d/29},Y=function(v){return T+(H-T-B)*(1-v/mx)};
  for(var i=0;i<=4;i++){var v=mx*i/4;h+='<line x1="'+L+'" x2="'+(W-R)+'" y1="'+Y(v)+'" y2="'+Y(v)+'" stroke="var(--line)"/><text x="'+(L-6)+'" y="'+(Y(v)+4)+'" text-anchor="end">'+(v*100).toFixed(0)+'%</text>'}
  [1,7,14,21,30].forEach(function(d){h+='<text x="'+X(d-1)+'" y="'+(H-12)+'" text-anchor="middle">H'+d+'</text>'});
  var path=function(c){return c.map(function(v,i){return (i?"L":"M")+X(i).toFixed(1)+" "+Y(v).toFixed(1)}).join("")};
  h+='<path d="'+path(c0)+'" fill="none" stroke="var(--mut)" stroke-width="3" stroke-linejoin="round"/>';
  h+='<path d="'+path(c1)+'" fill="none" stroke="var(--red)" stroke-width="3.5" stroke-linejoin="round"/>';
  h+='<text x="'+(X(29)-4)+'" y="'+(Y(c1[29])-8)+'" text-anchor="end" style="fill:var(--red);font-weight:700">'+pct(c1[29])+'</text>';
  h+='<text x="'+(X(29)-4)+'" y="'+(Y(c0[29])+16)+'" text-anchor="end">'+pct(c0[29])+'</text>';
  $("chart").innerHTML=h;
}
["n","p0","up","op","rd","a","aov"].forEach(function(i){$(i).oninput=function(){seed=7;run()}});
$("re").onclick=function(){seed=Math.floor(Math.random()*1e6);run()};
run();
</script>
</body>
</html>
