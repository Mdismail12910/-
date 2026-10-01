
-
Repository navigation
Code
Issues
Pull requests
Actions
Commit e12930a
Mdismail12910
Mdismail12910
authored
2 minutes ago
Verified
https://github.com/Mdismail12910/-.git
main
1 parent 
467b750
 commit 
e12930a
1 file changed

+75
Lines changed: 75 additions & 0 deletions
Search within code
 
‎mdismail_gaming_website.html‎
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,75 @@
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>🅜🅓🅘🅢🅜🅐🅘🅛 | Gaming Zone</title>
<style>
*{box-sizing:border-box}body{margin:0;font-family:Arial,sans-serif;background:#070812;color:#fff}
header{position:sticky;top:0;z-index:10;background:#0b0d18ee;backdrop-filter:blur(10px);border-bottom:1px solid #25283d}
nav{max-width:1100px;margin:auto;padding:15px 20px;display:flex;justify-content:space-between;align-items:center}
.logo{font-size:22px;font-weight:900;letter-spacing:2px;color:#00e5ff}
nav a{color:#ddd;text-decoration:none;margin-left:18px;font-size:14px}
.hero{min-height:500px;display:flex;align-items:center;justify-content:center;text-align:center;padding:60px 20px;background:radial-gradient(circle at 50% 20%,#152b54 0,#080914 55%,#05060b 100%)}
.hero h1{font-size:clamp(42px,9vw,82px);margin:0;text-shadow:0 0 25px #00d9ff}
.hero p{color:#b9bfd6;font-size:18px}.btn{display:inline-block;padding:13px 22px;border-radius:12px;background:#00d9ff;color:#001018;font-weight:bold;text-decoration:none;margin:8px}
section{max-width:1100px;margin:auto;padding:60px 20px}h2{text-align:center;font-size:32px;margin-bottom:30px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
.card{background:#101321;border:1px solid #252a42;border-radius:18px;padding:25px;text-align:center;box-shadow:0 10px 35px #0005}
.card .icon{font-size:40px}.card h3{margin:12px 0 8px}.card p{color:#aab0c4;line-height:1.5}
.topup{border-color:#00d9ff}.price{font-size:24px;font-weight:bold;color:#00e5ff;margin:15px}
input,select{width:100%;padding:13px;margin:7px 0;background:#080a12;color:#fff;border:1px solid #30354e;border-radius:10px}
footer{text-align:center;padding:30px;color:#777;border-top:1px solid #202337}
.small{font-size:12px;color:#858ba0}
</style>
</head>
<body>
<header><nav>
<div class="logo">🅜🅓🅘🅢🅜🅐🅘🅛</div>
<div><a href="#home">Home</a><a href="#gaming">Gaming</a><a href="#topup">Top Up</a><a href="#contact">Contact</a></div>
</nav></header>
<main id="home">
<div class="hero">
<div>
<div class="small">WELCOME TO</div>
<h1>🅜🅓🅘🅢🅜🅐🅘🅛</h1>
<p>GAMING • FREE FIRE • TOP UP • NAME STYLE</p>
<a class="btn" href="#topup">🔥 FREE FIRE TOP UP</a>
<a class="btn" href="#gaming">🎮 ENTER GAMING</a>
</div>
</div>
<section id="gaming"><h2>🎮 Gaming Zone</h2><div class="grid">
<div class="card"><div class="icon">🔥</div><h3>Free Fire</h3><p>Gaming profile, updates and Free Fire related content.</p></div>
<div class="card"><div class="icon">🏆</div><h3>Achievements</h3><p>Show your gaming achievements and memorable moments.</p></div>
<div class="card"><div class="icon">⚡</div><h3>Gaming Setup</h3><p>Tips, settings and gaming content for mobile gamers.</p></div>
</div></section>
<section id="topup"><h2>💎 Free Fire Top Up</h2><div class="grid">
<div class="card topup"><div class="icon">💎</div><h3>100 Diamonds</h3><div class="price">Contact</div><p>Send your Player ID and order details.</p><a class="btn" href="#contact">Order</a></div>
<div class="card topup"><div class="icon">💎</div><h3>310 Diamonds</h3><div class="price">Contact</div><p>Fast order request section.</p><a class="btn" href="#contact">Order</a></div>
<div class="card topup"><div class="icon">💎</div><h3>520 Diamonds</h3><div class="price">Contact</div><p>Choose your package and contact us.</p><a class="btn" href="#contact">Order</a></div>
</div></section>
<section><h2>✨ Name Style</h2><div class="grid">
<div class="card"><h3>🅜🅓🅘🅢🅜🅐🅘🅛</h3><p>Gaming name style</p></div>
<div class="card"><h3>亗 ISMAIL 亗</h3><p>Elite style</p></div>
<div class="card"><h3>么ISMAIL么</h3><p>Pro gamer style</p></div>
</div></section>
<section id="contact"><h2>📩 Contact / Order</h2><div class="card" style="max-width:600px;margin:auto">
<input id="uid" placeholder="Free Fire Player ID">
<select id="pkg"><option>100 Diamonds</option><option>310 Diamonds</option><option>520 Diamonds</option></select>
<a class="btn" href="#" onclick="order()">Send Order</a>
<p id="msg" class="small"></p>
</div></section>
</main>
<footer>© 2026 🅜🅓🅘🅢🅜🅐🅘🅛 Gaming Zone • Made for gamers</footer>
<script>
function order(){
 const uid=document.getElementById('uid').value.trim(),pkg=document.getElementById('pkg').value;
 document.getElementById('msg').textContent=uid?`Order ready: ${pkg} • Player ID: ${uid}. Add your WhatsApp/contact number in the HTML to receive orders.`:'Please enter your Player ID first.';
}
</script>
</body></html#index.html -
Welcome to 🅘🅢🅜🅐🅘🅛  website
