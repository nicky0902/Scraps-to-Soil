[index (3).html](https://github.com/user-attachments/files/33247479/index.3.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Scraps to Soil</title>
<link rel="icon" href="logo.png">
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Fraunces:opsz,wght@9..144,600;9..144,700&display=swap" rel="stylesheet">
<style>
:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#f5eee9;--card:#fffaf3;--ink:#2f3a2c;--muted:#66705f;--line:#e2d8c8;--sage:#6f8a66;--sage2:#78947d;--deep:#3f5a3c;--cream:#f0e8d6;--soil:#5b4630;--worm:#d9a679}
html{scroll-padding-top:env(safe-area-inset-top,0px)}*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 17px/1.7 'DM Sans',system-ui,sans-serif}
h1,h2,h3{font-family:'Fraunces',Georgia,serif;font-weight:700;line-height:1.1;margin:0 0 .6rem;letter-spacing:-.01em}
h1{font-size:clamp(2.4rem,6vw,4rem)}h2{font-size:clamp(1.7rem,3.5vw,2.4rem)}h3{font-size:1.25rem}
p{margin:0 0 1rem;max-width:60ch}.lead{font-size:1.15rem;color:var(--muted)}
.wrap{max-width:1040px;margin:0 auto;padding:0 22px}
.top{position:sticky;top:0;z-index:5;background:color-mix(in srgb,var(--bg) 92%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--line);padding-top:env(safe-area-inset-top,0px)}
.nav{display:flex;align-items:center;gap:4px;padding:10px 0;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;margin-right:auto;font:700 1.15rem 'Fraunces',serif;color:var(--ink);background:none;border:0;cursor:pointer;padding:0}
.brand img{width:44px;height:44px;border-radius:50%}
.nav button.l{background:none;border:0;font:500 .98rem 'DM Sans',sans-serif;color:var(--muted);padding:8px 13px;border-radius:99px;cursor:pointer}
.nav button.l[aria-current="page"]{background:var(--sage);color:#fff}
button:focus-visible,input:focus-visible,textarea:focus-visible,summary:focus-visible{outline:3px solid var(--worm);outline-offset:2px}
.hero{display:grid;grid-template-columns:1.15fr .85fr;gap:30px;align-items:center;padding:54px 0 44px}
@media(max-width:780px){.hero{grid-template-columns:1fr;padding-top:30px}.hero .logo{order:-1;max-width:260px;margin:0 auto}}
.logo{width:100%;max-width:400px;justify-self:center;border-radius:50%;filter:drop-shadow(0 18px 24px rgba(63,90,60,.22))}
.btn{font:700 1rem 'DM Sans',sans-serif;border:0;border-radius:12px;padding:13px 24px;cursor:pointer;background:var(--deep);color:#fff}
.btn.alt{background:transparent;color:var(--deep);border:2px solid var(--sage)}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:8px}
.band{background:var(--sage);color:#fff;border-radius:22px;padding:28px;display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:22px;margin-bottom:56px}
.band b{display:block;font:700 2.6rem 'Fraunces',serif;line-height:1.05}.band small{opacity:.9}
.bar{height:10px;background:rgba(255,255,255,.28);border-radius:99px;overflow:hidden;margin:10px 0 6px}
.bar i{display:block;height:100%;width:0;background:var(--cream);border-radius:99px;transition:width .9s ease}
section.sec{padding:10px 0 50px}.view[hidden]{display:none}
.cols{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:18px;margin-top:20px}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:24px}
.card .ic{width:44px;height:44px;border-radius:12px;background:var(--cream);display:grid;place-items:center;margin-bottom:12px}
.steps{counter-reset:s;display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px;margin-top:20px}
.steps .card{counter-increment:s;position:relative}
.steps .card:before{content:counter(s);font:700 2.4rem 'Fraunces',serif;color:var(--sage);display:block;line-height:1;margin-bottom:8px}
.two{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:20px}@media(max-width:620px){.two{grid-template-columns:1fr}}
.yes{border-top:6px solid var(--sage)}.no{border-top:6px solid var(--worm)}ul{padding-left:1.15rem;margin:0}li{margin:.25rem 0}
details{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:15px 20px;margin:10px 0}
summary{cursor:pointer;font-weight:700}details p{margin:10px 0 0;color:var(--muted)}
.gal{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:16px;margin-top:20px}
.gal figure{margin:0;background:var(--card);border:1px solid var(--line);border-radius:18px;overflow:hidden}
.gal img{width:100%;aspect-ratio:4/3;object-fit:cover;display:block}.gal figcaption{padding:12px 16px;color:var(--muted);font-size:.95rem}
.empty{background:var(--cream);border:2px dashed var(--sage);border-radius:18px;padding:34px;text-align:center;margin-top:20px}.empty p{margin:0 auto}
.row{display:flex;gap:16px;flex-wrap:wrap;align-items:center;margin:12px 0}
label{font-weight:700;display:block;margin-bottom:6px}
input[type=range]{width:100%;accent-color:var(--sage)}
input[type=text],input[type=email],textarea{width:100%;font:inherit;padding:12px 14px;border-radius:12px;border:1px solid var(--line);background:var(--bg);color:var(--ink)}
textarea{min-height:140px}
.stp{display:flex;align-items:center;gap:14px}.stp button{width:46px;height:46px;border-radius:12px;border:0;background:var(--deep);color:#fff;font-size:1.5rem;cursor:pointer}
.stp output{font:700 2.1rem 'Fraunces',serif;min-width:2.2ch;text-align:center}
.res{border-left:6px solid var(--worm)}.res b{display:block;font:700 2rem 'Fraunces',serif;color:var(--deep);line-height:1.1}
.note{color:var(--muted);font-size:.92rem}
footer{background:var(--deep);color:#f0e8d6;padding:30px 0;margin-top:20px}footer .wrap{display:flex;gap:16px;align-items:center;flex-wrap:wrap}footer img{width:54px;height:54px;border-radius:50%}

html{scroll-behavior:smooth}
@keyframes in{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:none}}
.view{animation:in .5s cubic-bezier(.2,.7,.2,1)}
details[open]>p{animation:in .35s ease}
.nav button.l,.brand{transition:background .3s ease,color .3s ease,transform .2s ease}
.nav button.l:hover:not([aria-current]){background:var(--cream);color:var(--ink)}
.brand:hover img{transform:rotate(-8deg)}.brand img{transition:transform .35s cubic-bezier(.3,1.4,.5,1)}
.btn{transition:transform .2s ease,box-shadow .25s ease,background .25s ease,color .25s ease}
.btn:hover{transform:translateY(-2px);box-shadow:0 8px 18px rgba(63,90,60,.25)}
.btn:active,.stp button:active{transform:scale(.97)}
.btn.alt:hover{background:var(--cream)}
.stp button{transition:transform .15s ease,background .25s ease}.stp button:hover{background:var(--sage)}
.card{transition:transform .3s ease,box-shadow .3s ease,border-color .3s ease}
.cols .card:hover,.steps .card:hover{transform:translateY(-4px);box-shadow:0 12px 24px rgba(63,90,60,.12);border-color:var(--sage)}
details{transition:border-color .25s ease,box-shadow .25s ease}details:hover{border-color:var(--sage)}
input,textarea{transition:border-color .25s ease,box-shadow .25s ease}input:focus,textarea:focus{border-color:var(--sage);box-shadow:0 0 0 4px rgba(111,138,102,.18);outline:none}
.logo{transition:transform .6s cubic-bezier(.2,.7,.2,1)}.logo:hover{transform:rotate(4deg) scale(1.03)}
.band b{font-variant-numeric:tabular-nums}
@media (prefers-reduced-motion:reduce){*,*:before{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
.opt{display:flex;gap:10px;align-items:center;font-weight:500;margin:6px 0;cursor:pointer}.opt input{accent-color:var(--sage);width:18px;height:18px}
fieldset{border:0;padding:0;margin:14px 0}legend{font-weight:700;margin-bottom:6px;padding:0}
select{font:inherit;padding:12px 14px;border-radius:12px;border:1px solid var(--line);background:var(--bg);color:var(--ink);min-width:200px}select:focus{border-color:var(--sage);outline:none;box-shadow:0 0 0 4px rgba(111,138,102,.18)}
</style>
</head>
<body>
<div class="top"><div class="wrap"><nav class="nav" aria-label="Main">
<button class="brand" data-v="home"><img src="logo.png" alt="Scraps to Soil logo">Scraps to Soil</button>
<button class="l" data-v="home" aria-current="page">Home</button><button class="l" data-v="learn">How it works</button><button class="l" data-v="gallery">Our farms</button><button class="l" data-v="impact">Your impact</button><button class="l" data-v="contact">Contact</button>
</nav></div></div>

<main class="wrap">
<div class="view" id="home">
<section class="hero">
<div>
<h1>Feed the worms. Feed the soil.</h1>
<p class="lead">Scraps to Soil sets up worm farms for family and friends. Every farm turns kitchen scraps into rich fertiliser and keeps food out of landfill. We make no profit, and we are open about every farm we donate.</p>
<div class="cta"><button class="btn" data-go="contact">Get on the waiting list</button><button class="btn alt" data-go="impact">See your impact</button></div>
</div>
<img class="logo" src="logo.png" alt="Scraps to Soil, established 2026">
</section>
<div class="band">
<div><b id="donated">0</b><small>worm farms donated</small><div class="bar" id="pb" role="progressbar" aria-valuemin="0" aria-valuemax="100"><i id="fill"></i></div><small id="goal"></small></div>
<div><b id="s1">0 kg</b><small>scraps kept from landfill each year</small></div>
<div><b id="s2">0 kg</b><small>CO2e avoided each year (estimate)</small></div>
</div>
<section class="sec"><h2>Why a worm farm?</h2>
<div class="cols">
<div class="card"><div class="ic">&#127793;</div><h3>Less landfill</h3><p class="note" style="margin:0">Food scraps become fertiliser instead of methane.</p></div>
<div class="card"><div class="ic">&#129713;</div><h3>Free fertiliser</h3><p class="note" style="margin:0">Castings and worm tea feed your garden for nothing.</p></div>
<div class="card"><div class="ic">&#127807;</div><h3>Healthier soil</h3><p class="note" style="margin:0">Soil that holds more water and nutrients.</p></div>
<div class="card"><div class="ic">&#128154;</div><h3>Learn together</h3><p class="note" style="margin:0">A hands-on way for kids to learn about nature.</p></div>
</div></section>
</div>

<section class="view sec" id="learn" hidden>
<h2>How it works</h2><p class="lead">Four simple steps. We handle the hard part.</p>
<div class="steps">
<div class="card"><h3>We set it up</h3><p class="note" style="margin:0">We deliver and set up your worm farm so you can start straight away.</p></div>
<div class="card"><h3>Read the handbook</h3><p class="note" style="margin:0">A clear guide covers feeding, moisture and troubleshooting.</p></div>
<div class="card"><h3>Feed your worms</h3><p class="note" style="margin:0">Add scraps a little at a time and keep the bedding damp.</p></div>
<div class="card"><h3>Use the results</h3><p class="note" style="margin:0">Spread castings and worm tea on your garden.</p></div></div>
<h2 style="margin-top:46px">What can go in?</h2>
<div class="two">
<div class="card yes"><h3>Yes please</h3><ul><li>Fruit and vegetable scraps</li><li>Coffee grounds and tea bags</li><li>Crushed eggshells</li><li>Torn cardboard and paper</li></ul></div>
<div class="card no"><h3>Keep out</h3><ul><li>Meat, fish and dairy</li><li>Oily or salty food</li><li>Large amounts of citrus and onion</li><li>Pet waste and anything with chemicals</li></ul></div></div>
<h2 style="margin-top:46px">Questions</h2>
<details><summary>Does a worm farm smell?</summary><p>A healthy one does not. Keep the bedding damp, feed small amounts and avoid meat and dairy.</p></details>
<details><summary>How much space do I need?</summary><p>Very little. A patio, balcony or shady garden corner is enough.</p></details>
<details><summary>How much does it cost?</summary><p>Prices are negotiable. We make no profit, so anything paid only covers costs.</p></details>
<details><summary>What if I go away?</summary><p>Worms cope with a week or two between feeds. Give them a good feed before you leave and keep the farm in the shade.</p></details>
</section>

<section class="view sec" id="gallery" hidden>
<h2>Our farms</h2><p class="lead">Real farms, set up by us.</p>
<div id="galbox"></div>
</section>

<section class="view sec" id="impact" hidden>
<h2>What would you do with a worm farm?</h2><p class="lead">Add farms to our total and see what we could achieve with your help.</p>
<div class="card"><div class="row">
<div><label for="farms">Farms you would add</label><div class="stp"><button id="minus" aria-label="Remove one farm">&minus;</button><output id="farms" aria-live="polite">1</output><button id="plus" aria-label="Add one farm">+</button></div></div>
<div style="flex:1;min-width:230px"><label for="kg">Scraps per farm each week: <span id="kgv">3</span> kg</label><input type="range" id="kg" min="1" max="6" step="0.5" value="3"></div></div></div>
<div class="cols" id="you"></div>
<div class="card" style="margin-top:18px"><h3>Community total with you</h3><p style="margin:0" id="combined"></p></div>
<div class="card" style="margin-top:18px"><h3>How we estimate</h3><ul class="note"><li>Each farm diverts about 3 kg of scraps a week by default (156 kg a year).</li><li>Landfilled food waste is estimated at 0.5 kg CO2e per kg. This is a rough figure and real results vary.</li><li>A petrol car emits about 0.17 kg CO2e per km.</li><li>Community figures use the default of 3 kg per week for every donated farm.</li></ul></div>
</section>

<section class="view sec" id="contact" hidden>
<h2>Get a worm farm</h2><p class="lead">Fill in the form to join our waiting list. No message needed. We will contact you when your worm farm is ready.</p>
<div class="card" id="cform">
<div class="row"><div style="flex:1;min-width:200px"><label for="cn">Name or nickname</label><input type="text" id="cn" autocomplete="name"></div>
<div style="flex:1;min-width:200px"><label for="ce">Email or phone</label><input type="text" id="ce" autocomplete="email"></div></div>
<div class="row"><div style="min-width:200px"><label for="cq">How many worm farms?</label><select id="cq"><option>1</option><option>2</option><option>3</option><option>4</option><option>5 or more</option></select></div></div>
<label for="cm">Anything we should know? (optional)</label><textarea id="cm" style="min-height:90px"></textarea>
<div class="row"><button class="btn" id="send">Join the waiting list</button><span class="note" id="cmsg" role="status"></span></div>
<p class="note" style="margin:0">Your details are private. Only the Scraps to Soil team sees them, and we never show names or contacts on this site.</p></div>
<div class="card" id="cdone" hidden><h3>Almost done</h3><p style="margin:0">Your email app should have opened with your details ready. Press send to finish joining the list. Thank you for helping plant the seed.</p></div>
<div class="row" style="flex-direction:column;justify-content:center;align-items:center;gap:8px;margin-top:28px;text-align:center"><button class="btn alt" id="share">Share this site</button><span class="note" id="shmsg" role="status"></span></div>
</section>
</main>

<footer><div class="wrap"><img src="logo.png" alt=""><div>Scraps to Soil, est. 2026<br><span style="opacity:.8">A non-profit family project, one worm farm at a time.</span></div></div></footer>

<script type="application/json" id="state">{"donated":0,"goal":25}</script>
<script>
/* To change the farm count and goal, edit the numbers in the id="state" block above. */
var S=JSON.parse(document.getElementById("state").textContent),DONATED=S.donated,GOAL=S.goal,CONTACT_EMAIL="nicholasturck11@gmail.com",DEFAULT_KG_WEEK=3;
var PHOTOS=[]; /* e.g. [{src:"data:image/jpeg;base64,...", caption:"Our first farm"}] */
/* ---------------------------------------------- */
var CO2E_PER_KG=.5,CO2E_PER_KM=.17,$=function(i){return document.getElementById(i)};
var fmt=function(n){return Math.round(n).toLocaleString('en-ZA')};
function impact(f,k){var food=f*k*52,co2=food*CO2E_PER_KG;return{food:food,co2:co2,km:co2/CO2E_PER_KM}}
function cards(i,c){return '<div class="card '+c+'"><b>'+fmt(i.food)+' kg</b>scraps kept out of landfill each year</div><div class="card '+c+'"><b>'+fmt(i.co2)+' kg</b>CO2e avoided each year (estimate)</div><div class="card '+c+'"><b>'+fmt(i.km)+' km</b>of car driving, in emissions terms</div>'}
var base=impact(DONATED,DEFAULT_KG_WEEK);
function countUp(el,to,sfx){sfx=sfx||'';if(!to||matchMedia('(prefers-reduced-motion:reduce)').matches){el.textContent=fmt(to)+sfx;return}var t0=performance.now();(function f(t){var p=Math.min(1,(t-t0)/1100),e=1-Math.pow(1-p,3);el.textContent=fmt(to*e)+sfx;if(p<1)requestAnimationFrame(f)})(t0)}
countUp($('donated'),DONATED);countUp($('s1'),base.food,' kg');countUp($('s2'),base.co2,' kg');
var pct=Math.min(100,DONATED/GOAL*100);$('pb').setAttribute('aria-valuenow',Math.round(pct));setTimeout(function(){$('fill').style.width=pct+'%'},200);
$('goal').textContent=DONATED+' of '+GOAL+' farms in our first goal';
$('galbox').innerHTML=PHOTOS.length?'<div class="gal">'+PHOTOS.map(function(p){return '<figure><img src="'+p.src+'" alt="'+p.caption+'"><figcaption>'+p.caption+'</figcaption></figure>'}).join('')+'</div>':'<div class="empty"><h3>Photos coming soon</h3><p>We are setting up our first farms. Real photos of each one will appear here as we donate them.</p></div>';
var farms=1;
function update(){var k=parseFloat($('kg').value);$('farms').textContent=farms;$('kgv').textContent=k;$('you').innerHTML=cards(impact(farms,k),'res');
var y=impact(farms,k);$('combined').textContent=(DONATED+farms)+' worm farms, keeping about '+fmt(base.food+y.food)+' kg of food out of landfill and avoiding about '+fmt(base.co2+y.co2)+' kg CO2e every year.'}
$('plus').onclick=function(){if(farms<50){farms++;update()}};$('minus').onclick=function(){if(farms>0){farms--;update()}};$('kg').oninput=update;update();
var navb=document.querySelectorAll('.nav button.l');
function show(v){document.querySelectorAll('.view').forEach(function(s){s.hidden=s.id!==v});navb.forEach(function(b){b.dataset.v===v?b.setAttribute('aria-current','page'):b.removeAttribute('aria-current')});window.scrollTo(0,0)}
document.querySelectorAll('[data-v],[data-go]').forEach(function(b){b.onclick=function(){show(b.dataset.v||b.dataset.go)}});
$('share').onclick=function(){var u=location.href;if(navigator.share){navigator.share({title:'Scraps to Soil',url:u}).catch(function(){})}else if(navigator.clipboard){navigator.clipboard.writeText(u).then(function(){$('shmsg').textContent='Link copied.'},function(){$('shmsg').textContent='Copy the link from your browser bar.'})}else{$('shmsg').textContent='Copy the link from your browser bar.'}};
$('send').onclick=function(){var n=$('cn').value.trim(),c=$('ce').value.trim();if(!n||!c){$('cmsg').textContent='Please add your name and a way to contact you.';return}
var q=$('cq').value,note=$('cm').value.trim();
location.href='mailto:'+CONTACT_EMAIL+'?subject='+encodeURIComponent('Scraps to Soil waiting list')+'&body='+encodeURIComponent('Waiting list sign-up\n\nName: '+n+'\nContact: '+c+'\nWorm farms wanted: '+q+(note?'\nNote: '+note:''));
$('cform').hidden=true;$('cdone').hidden=false};
</script>
</body>
</html>
