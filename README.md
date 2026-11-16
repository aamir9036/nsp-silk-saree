# nsp-silk-saree
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>NSP SILK & SAREE</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Arial,sans-serif;background:#fffaf5;color:#38251c}
header{background:#681b32;color:white;text-align:center;padding:28px 12px}
header h1{margin:0;font-size:28px}
header p{margin:9px 0 0}
nav{background:#f5e4d5;padding:13px;text-align:center}
nav a{color:#681b32;margin:0 10px;text-decoration:none;font-weight:bold}
.hero{text-align:center;padding:45px 15px;background:#f8e5e4}
.hero h2{font-size:29px;color:#681b32}
.hero p{line-height:1.6}
.products{padding:25px 15px;max-width:1000px;margin:auto}
.products h2{text-align:center;color:#681b32}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.product{background:white;border-radius:12px;overflow:hidden;text-align:center;padding-bottom:15px;box-shadow:0 2px 9px #0001}
.photo{height:145px;background:#ead5d0;display:flex;align-items:center;justify-content:center;color:#681b32;font-size:15px}
.product h3{font-size:16px;margin:12px 5px 5px}
.product p{margin:7px;color:#681b32;font-weight:bold}
button{background:#681b32;color:white;border:0;padding:11px 15px;border-radius:6px;font-weight:bold}
footer{text-align:center;background:#681b32;color:white;padding:25px 12px;margin-top:30px}
@media(min-width:650px){.grid{grid-template-columns:repeat(3,1fr)}.photo{height:220px}}
</style>
</head>
<body>
<header>
<h1>NSP SILK & SAREE</h1>
<p>Traditional Elegance • Beautiful Collections</p>
</header>
<nav>
<a href="#home">Home</a>
<a href="#products">Collections</a>
<a href="#contact">Contact</a>
</nav>
<section class="hero" id="home">
<h2>Discover Beautiful Sarees</h2>
<p>Explore elegant silk sarees and beautiful traditional collections.<br>Shop from anywhere in India!</p>
<a href="#products"><button>Explore Collection</button></a>
</section>
<section class="products" id="products">
<h2>Our Saree Collection</h2>
<div class="grid">
<div class="product">
<div class="photo">Add Saree Photo 1</div>
<h3>Kanjivaram Silk Saree</h3>
<p>Price: Contact us</p>
<button onclick="order('Kanjivaram Silk Saree')">Enquire Now</button>
</div>
<div class="product">
<div class="photo">Add Saree Photo 2</div>
<h3>Soft Silk Saree</h3>
<p>Price: Contact us</p>
<button onclick="order('Soft Silk Saree')">Enquire Now</button>
</div>
<div class="product">
<div class="photo">Add Saree Photo 3</div>
<h3>Designer Saree</h3>
<p>Price: Contact us</p>
<button onclick="order('Designer Saree')">Enquire Now</button>
</div>
</div>
</section>
<footer id="contact">
<h3>NSP SILK & SAREE</h3>
<p>For orders and enquiries, contact us on WhatsApp.</p>
<p>Serving customers across India.</p>
</footer>
<script>
function order(product){
const phone="91XXXXXXXXXX";
const message=encodeURIComponent("Hello NSP SILK & SAREE, I am interested in "+product+". Please share details.");
window.open("https://wa.me/"+phone+"?text="+message,"_blank");
}
</script>
</body>
</html>
