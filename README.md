
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>BABYCOW — Tiny Moo, Big Energy</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#f6f2df;color:#18271d;font-family:Arial,sans-serif}
header{padding:22px 7%;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid #c5c6ae}
.logo{font-weight:900;font-size:22px}
a{color:inherit;text-decoration:none}
.btn{display:inline-block;padding:13px 20px;border:2px solid #18271d;border-radius:40px;font-weight:bold;margin:5px}
.dark{background:#18271d;color:white}
.hero{padding:70px 7%;display:grid;grid-template-columns:1fr 1fr;align-items:center;gap:30px}
h1{font-size:clamp(55px,9vw,100px);letter-spacing:-6px;line-height:.88;margin:25px 0}
h1 span{color:#679638}
p{line-height:1.8;color:#53604e}
.mascot{background:#b9e86d;border:3px solid #18271d;border-radius:48%;padding:35px;text-align:center;box-shadow:10px 10px #18271d}
.cow{font-size:clamp(130px,24vw,240px);line-height:1.4}
.tag{display:inline-block;background:#d9f6a8;border:1px solid #18271d;border-radius:30px;padding:10px 14px;font-size:12px;font-weight:bold}
section{padding:65px 7%}
h2{font-size:clamp(35px,6vw,58px);letter-spacing:-3px;margin:12px 0}
.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:15px;margin-top:25px}
.card{padding:24px;border:2px solid #18271d;border-radius:20px;background:#fffdf2}
.card:nth-child(2){background:#d9f6a8}
.card:nth-child(3){background:#ffb7bd}
.card h3{font-size:22px}
.token{background:#b9e86d;border:2px solid #18271d;border-radius:24px;padding:30px;overflow-wrap:anywhere}
button{background:#18271d;color:white;border:0;border-radius:30px;padding:13px 20px;font-weight:bold;margin-top:10px}
footer{text-align:center;padding:30px 7%;background:#18271d;color:#f6f2df;font-size:12px}
@media(max-width:650px){.hero{grid-template-columns:1fr;padding-top:45px}.mascot{margin:10px 12px}.cards{grid-template-columns:1fr}h1{letter-spacing:-4px}header{padding:18px 5%}}
</style>
</head>
<body>
<header>
  <div class="logo">🐮 BABYCOW</div>
  <a class="btn dark" href="#community">JOIN THE HERD ↗</a>
</header>

<main>
<section class="hero">
  <div>
    <span class="tag">✳ FRESH FROM THE PASTURE</span>
    <h1>TINY MOO.<br><span>BIG ENERGY.</span></h1>
    <p>The internet's tiniest cow is ready to make some noise. No suits, no serious faces. Just a little moo and a whole lot of community.</p>
    <a class="btn dark" href="#community">Meet the herd ↗</a>
    <a class="btn" href="#token">Explore $BABYCOW ↓</a>
  </div>
  <div class="mascot">
    <div class="cow">🐮</div>
    <strong>100% SMOL MOO ENERGY</strong>
  </div>
</section>

<section style="background:#e8e5cd">
  <span class="tag">01 / THE LITTLE LEGEND</span>
  <h2>Born to moo.<br>Built by the herd.</h2>
  <p>BabyCow brings fun back to the timeline. A tiny mascot, big memes, and a community making its own noise.</p>
  <div class="cards">
    <div class="card"><h3>🐄 Community first</h3><p>A place for meme lovers and people who enjoy building something together.</p></div>
    <div class="card"><h3>🌱 Small cow energy</h3><p>Small cow. Big dreams. Bring your creativity and join the herd.</p></div>
    <div class="card"><h3>⚡ Moo different</h3><p>Make memes, spread the word, and keep the timeline entertaining.</p></div>
  </div>
</section>

<section>
  <span class="tag">02 / GET STARTED</span>
  <h2>Three steps.<br>One happy cow.</h2>
  <div class="cards">
    <div class="card"><h3>01. Get a wallet</h3><p>Use a wallet that supports the blockchain where the token launches.</p></div>
    <div class="card"><h3>02. Verify the CA</h3><p>Always verify the official contract address before making a transaction.</p></div>
    <div class="card"><h3>03. Join the herd</h3><p>Follow the official socials and share your favorite BabyCow memes.</p></div>
  </div>
</section>

<section id="token">
  <div class="token">
    <span class="tag">03 / TOKEN DETAILS</span>
    <h2>Keep it moooving.</h2>
    <p>Token: $BABYCOW</p>
    <p id="ca">Contract address: ADD_YOUR_CA_HERE</p>
    <button onclick="copyCA()">COPY CONTRACT ADDRESS</button>
    <p id="notice" style="color:#18271d"></p>
  </div>
</section>

<section id="community" style="text-align:center;background:#ffb7bd">
  <span class="tag">04 / COME SAY MOO</span>
  <h2>Your timeline needs more cow.</h2>
  <p>Join the community and help BabyCow find its people.</p>
  <a class="btn dark" href="https://x.com/" target="_blank">FOLLOW ON X ↗</a>
  <a class="btn" href="https://t.me/" target="_blank">JOIN TELEGRAM ↗</a>
</section>
</main>

<footer>
  © 2026 BABYCOW · TINY MOO, BIG ENERGY.<br><br>
  Meme coin for entertainment only. Crypto assets are risky. No guaranteed returns. DYOR.
</footer>

<script>
function copyCA(){
 const ca="ADD_YOUR_CA_HERE";
 if(ca==="ADD_YOUR_CA_HERE"){
  document.getElementById("notice").textContent="Add your real contract address first.";
  return;
 }
 navigator.clipboard.writeText(ca).then(()=>{
  document.getElementById("notice").textContent="Copied!";
 }).catch(()=>{
  document.getElementById("notice").textContent=ca;
 });
}
</script>
</body>
</html>

