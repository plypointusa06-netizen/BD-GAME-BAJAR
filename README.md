# BD-GAME-BAJAR
BD Game bajar  free fire daimond top up 
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BD GAME BAJAR</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#10131e;color:white;font-family:Arial,sans-serif}
header{background:#191e30;padding:22px;text-align:center}
header h1{color:#ffb800;margin:0}
header p{color:#ccc}
.hero{text-align:center;padding:35px 15px;background:linear-gradient(135deg,#242b48,#10131e)}
.hero h2{color:#ffbd24}
.container{max-width:650px;margin:auto;padding:15px}
.pack{background:#20263a;border:1px solid #39415c;border-radius:12px;padding:17px;margin:12px 0;display:flex;justify-content:space-between;align-items:center}
.price{color:#ffc02e;font-weight:bold}
button{background:#ffb800;border:0;padding:12px 18px;border-radius:8px;font-weight:bold}
input,select{width:100%;padding:13px;margin:8px 0;background:#20263a;color:white;border:1px solid #59617b;border-radius:8px}
h3{color:#ffbd24}
footer{text-align:center;color:#aaa;padding:25px}
</style>
</head>
<body>
<header>
<h1>BD GAME BAJAR</h1>
<p>Free Fire Diamond Top Up</p>
</header>
<section class="hero">
<h2>Welcome to BD GAME BAJAR</h2>
<p>Choose your Diamond Package</p>
</section>
<div class="container">
<h3>💎 Diamond Packages</h3>
<div id="packages">Loading packages...</div>
<h3>Order Form</h3>
<form onsubmit="event.preventDefault();alert('এটি শুধু ডেমো। অর্ডার এখনো জমা হচ্ছে না।');">
<input placeholder="Free Fire Player UID" required>
<select id="package" required>
<option value="">Select Diamond Package</option>
</select>
<button type="submit">Place Demo Order</button>
</form>
</div>
<footer>© 2026 BD GAME BAJAR</footer>
<script>
const packages=[
["25 Diamonds",25],
["50 Diamonds",38],
["115 Diamonds",80],
["240 Diamonds",160],
["610 Diamonds",400],
["850 Diamonds",560],
["1240 Diamonds",799],
["2530 Diamonds",1570]
];
const list=document.getElementById("packages");
const select=document.getElementById("package");
list.innerHTML="";
packages.forEach(p=>{
list.innerHTML+=`<div class="pack"><span>${p[0]}</span><span class="price">৳${p[1]}</span></div>`;
select.innerHTML+=`<option value="${p[0]}">${p[0]} - ৳${p[1]}</option>`;
});
</script>
</body>
</html>
