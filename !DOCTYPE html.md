<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>VaultCodes - Digital Gift Card Store</title>  
  
<style>  
body{  
margin:0;  
font-family:system-ui;  
background:#0b0f1a;  
color:white;  
}  
  
header{  
background:#111827;  
padding:15px;  
display:flex;  
justify-content:space-between;  
align-items:center;  
}  
  
.logo{  
font-size:22px;  
font-weight:bold;  
color:#22c55e;  
}  
  
nav a{  
color:white;  
margin:10px;  
text-decoration:none;  
}  
  
.hero{  
padding:60px 20px;  
text-align:center;  
background:linear-gradient(to right,#0f172a,#020617);  
}  
  
.hero h1{  
color:#22c55e;  
}  
  
.section{  
padding:20px;  
}  
  
.products{  
display:grid;  
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));  
gap:15px;  
}  
  
.product{  
background:#111827;  
padding:20px;  
border-radius:10px;  
}  
  
.product button{  
background:#22c55e;  
border:none;  
padding:10px;  
width:100%;  
margin-top:10px;  
border-radius:6px;  
cursor:pointer;  
}  
  
footer{  
text-align:center;  
padding:20px;  
background:#020617;  
margin-top:20px;  
}  
</style>  
</head>  
  
<body>  
  
<header>  
<div class="logo">VaultCodes</div>  
  
<nav>  
<a href="#">Home</a>  
<a href="#">Gift Cards</a>  
<a href="#">Game Top-Up</a>  
<a href="#">Contact</a>  
</nav>  
</header>  
  
<section class="hero">  
<h1>Secure Digital Code Marketplace</h1>  
<p>Buy gift cards, gaming vouchers and digital codes instantly.</p>  
</section>  
  
<section class="section">  
<h2>Popular Gift Cards</h2>  
  
<div class="products">  
  
<div class="product">  
<h3>Steam Wallet Code</h3>  
<p>Instant Delivery</p>  
<button onclick="buy()">Buy Now</button>  
</div>  
  
<div class="product">  
<h3>PlayStation Store Card</h3>  
<p>Fast & Secure</p>  
<button onclick="buy()">Buy Now</button>  
</div>  
  
<div class="product">  
<h3>Xbox Gift Card</h3>  
<p>Digital Delivery</p>  
<button onclick="buy()">Buy Now</button>  
</div>  
  
<div class="product">  
<h3>Apple Gift Card</h3>  
<p>Safe Payment</p>  
<button onclick="buy()">Buy Now</button>  
</div>  
  
<div class="product">  
<h3>Google Play Card</h3>  
<p>Instant Access</p>  
<button onclick="buy()">Buy Now</button>  
</div>  
  
<div class="product">  
<h3>Roblox Card</h3>  
<p>Trusted Seller</p>  
<button onclick="buy()">Buy Now</button>  
</div>  
  
</div>  
</section>  
  
<footer>  
© 2026 VaultCodes.com | Secure Gift Card Store  
</footer>  
  
<script>  
function buy(){  
alert("VaultCodes: Payment system will be connected soon.");  
}  
</script>  
  
</body>  
</html>  
