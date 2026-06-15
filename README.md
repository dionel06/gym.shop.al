# gym.shop.al
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>IRONFIT - Gym Store</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

:root{
  --blue:#2563eb;
  --dark:#0f172a;
  --card:#1e293b;
  --text:#ffffff;
  --muted:#cbd5e1;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins',sans-serif;
}

body{
  background:linear-gradient(135deg,#0f172a,#1e3a8a,#2563eb);
  color:var(--text);
}

/* HEADER */
header{
  position:fixed;
  top:0;
  width:100%;
  background:rgba(15,23,42,0.9);
  backdrop-filter:blur(10px);
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:18px 8%;
  z-index:1000;
  border-bottom:1px solid rgba(255,255,255,0.1);
}

.logo{
  font-size:26px;
  font-weight:700;
}

.logo span{
  color:var(--blue);
}

nav a{
  color:white;
  text-decoration:none;
  margin:0 15px;
  font-weight:500;
  transition:0.3s;
}

nav a:hover{
  color:var(--blue);
}

.btn{
  background:linear-gradient(45deg,#2563eb,#38bdf8);
  padding:10px 20px;
  border-radius:25px;
  color:white;
  text-decoration:none;
  transition:0.3s;
}

.btn:hover{
  transform:translateY(-3px);
}

/* HERO */
.hero{
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:0 8%;
  background:
  linear-gradient(rgba(15,23,42,0.7),rgba(37,99,235,0.6)),
  url('https://images.unsplash.com/photo-1534438327276-14e5300c3a48?w=1600');
  background-size:cover;
  background-position:center;
}

.hero h1{
  font-size:60px;
}

.hero p{
  margin:20px 0;
  color:var(--muted);
  font-size:18px;
}

/* SECTIONS */
section{
  padding:100px 8%;
}

.title{
  text-align:center;
  font-size:36px;
  margin-bottom:50px;
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
}

/* CARD */
.card{
  background:rgba(30,41,59,0.9);
  border-radius:15px;
  overflow:hidden;
  transition:0.3s;
  border:1px solid rgba(255,255,255,0.1);
}

.card:hover{
  transform:translateY(-10px);
}

.card img{
  width:100%;
  height:220px;
  object-fit:cover;
}

.card-content{
  padding:15px;
}

.price{
  color:#38bdf8;
  font-weight:700;
  margin-top:10px;
}

/* OFFER */
.offer{
  background:linear-gradient(45deg,#1e3a8a,#2563eb);
  padding:50px;
  border-radius:20px;
  text-align:center;
}

/* TESTIMONIAL */
.testimonial{
  background:rgba(30,41,59,0.9);
  padding:30px;
  border-radius:15px;
}

/* NEWSLETTER */
.newsletter{
  text-align:center;
  background:#0f172a;
}

.newsletter input{
  padding:12px;
  width:250px;
  border:none;
  border-radius:20px;
}

/* FOOTER */
footer{
  background:#0b1220;
  text-align:center;
  padding:40px;
  color:var(--muted);
}

@media(max-width:768px){
  .hero h1{font-size:38px;}
  nav{display:none;}
}

</style>
</head>

<body>

<header>
  <div class="logo">IRON<span>FIT</span></div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Offers</a>
    <a href="#">New</a>
    <a href="#">Best Sellers</a>
  </nav>
  <a class="btn" href="#">Shop Now</a>
</header>

<!-- HERO -->
<section class="hero">
  <div>
    <h1>Build Your Strongest Body</h1>
    <p>Premium gym equipment, dumbbells, and fitness gear for champions.</p>
    <a class="btn" href="#">Explore Products</a>
  </div>
</section>

<!-- OFFERS -->
<section>
  <h2 class="title">🔥 Special Offers</h2>
  <div class="offer">
    <h2>Up to 40% OFF Gym Equipment</h2>
    <p>Limited time offer on dumbbells, benches & more</p>
  </div>
</section>

<!-- NEW PRODUCTS -->
<section>
  <h2 class="title">🆕 New Products</h2>
  <div class="grid">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?w=800">
      <div class="card-content">
        <h3>Adjustable Dumbbells</h3>
        <div class="price">$199</div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1517836357463-d25dfeac3438?w=800">
      <div class="card-content">
        <h3>Kettlebell Set</h3>
        <div class="price">$89</div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1581009146145-b5ef050c2e1e?w=800">
      <div class="card-content">
        <h3>Bench Press</h3>
        <div class="price">$249</div>
      </div>
    </div>

  </div>
</section>

<!-- BEST SELLERS -->
<section>
  <h2 class="title">⭐ Best Sellers</h2>
  <div class="grid">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1597452485669-2c7bb5fef90d?w=800">
      <div class="card-content">
        <h3>Pro Dumbbells</h3>
        <div class="price">$179</div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1518611012118-696072aa579a?w=800">
      <div class="card-content">
        <h3>Olympic Barbell</h3>
        <div class="price">$299</div>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1581009137042-c552e485697a?w=800">
      <div class="card-content">
        <h3>Gym Rack</h3>
        <div class="price">$499</div>
      </div>
    </div>

  </div>
</section>

<!-- TESTIMONIAL -->
<section>
  <h2 class="title">💬 Reviews</h2>
  <div class="testimonial">
    ⭐⭐⭐⭐⭐
    <p>"Best gym equipment I ever bought. High quality and fast delivery!"</p>
  </div>
</section>

<!-- NEWSLETTER -->
<section class="newsletter">
  <h2>Join Our Fitness Community</h2>
  <br>
  <input type="email" placeholder="Enter email">
  <a class="btn" href="#">Subscribe</a>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 IRONFIT Gym Store. All rights reserved.</p>
</footer>

</body>
</html>
