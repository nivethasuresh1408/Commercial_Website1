# Ex02 Commercial Website
## Date: 18-02-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html>
<head>
<title>GlowGlam Cosmetics</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<div class="logo">GlowGlam</div>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="products.html">Products</a></li>
<li><a href="about.html">About</a></li>
<li><a href="contact.html">Contact</a></li>
<li><a href="account.html">Account</a></li>
</ul>
</nav>
</header>

<section class="hero">
<div class="hero-content">
<h1>Reveal Your Inner Glow ✨</h1>
<p>Luxury Beauty for Modern Women</p>
<br>
<button class="btn">Shop Now</button>
</div>
</section>

<footer>
© 2026 GlowGlam Cosmetics | Beauty Redefined 💄
</footer>

</body>
</html>
```
products.html
```
<!DOCTYPE html>
<html>
<head>
<title>Best Sellers</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<div class="logo">GlowGlam</div>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="products.html">Products</a></li>
<li><a href="about.html">About</a></li>
<li><a href="contact.html">Contact</a></li>
<li><a href="account.html">Account</a></li>
</ul>
</nav>
</header>

<section class="products">
<h2>Best Selling Cosmetics</h2>

<div class="product-container">

<div class="card">
<img src="Screenshot 2026-02-18 144224.png">
<h3>Matte Lipstick</h3>
<p>₹799</p>
</div>

<div class="card">
<img src="foundation.jpg">
<h3>Liquid Foundation</h3>
<p>₹1299</p>
</div>

<div class="card">
<img src="serum.jpeg">
<h3>Glow Serum</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="eyelinear1.png">
<h3>Eyelinear</h3>
<p>₹1200</p>
</div>

<div class="card">
<img src="blush1.jpeg">
<h3>Blush</h3>
<p>₹3000</p>
</div>

<div class="card">
<img src="mascara.webp">
<h3>Mascara</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="spray.webp">
<h3>Setting spray</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="eyeshadow.avif">
<h3>Eyeshadow</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="tools.webp">
<h3>Tools and brushes</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="Highlighter.jpg">
<h3>Highlighter</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="primer.webp">
<h3>Face primer</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="bath and body.jpeg">
<h3>Bath & Body</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="lip balm.webp">
<h3>Lip balm</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="toner.webp">
<h3>Toner</h3>
<p>₹999</p>
</div>

<div class="card">
<img src="mask.jpeg">
<h3>Mask and peel</h3>
<p>₹999</p>
</div>

</div>
</section>

<footer>
© 2026 GlowGlam Cosmetics
</footer>

</body>
</html>
```
about.html
```
<!DOCTYPE html>
<html>
<head>
<title>About Us - GlowGlam</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<div class="logo">GlowGlam</div>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="products.html">Products</a></li>
<li><a href="about.html">About</a></li>
<li><a href="contact.html">Contact</a></li>
<li><a href="account.html">Account</a></li>
</ul>
</nav>
</header>

<!-- BRAND SECTION -->
<section class="section">
<h2>Our Beauty Story 🌸</h2>
<br>

<img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9" 
style="width:30%; border-radius:5px; margin-bottom:10px;">

<p>
GlowGlam creates premium, cruelty-free cosmetics designed to enhance 
natural beauty with confidence and elegance.
</p>

</section>

<!-- SALE SECTION -->
<section class="section">

<h2>🎉 Special Sale Offers</h2>
<br>

<img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519" 
style="width:30%; border-radius:5px; margin-bottom:10px;">

<p>
✨ Flat 20% OFF on Lipsticks  
<br>
💄 Buy 2 Get 1 Free – Skincare  
<br>
🌸 Festive Discounts up to 40%
</p>

</section>

<!-- PRODUCT DEVELOPMENT -->
<section class="section">

<h2>🧪 Product Development</h2>
<br>

<img src="https://images.unsplash.com/photo-1581092334394-1f8f5b9d0f89" 
style="width:70%; border-radius:15px; margin-bottom:20px;">

<p>
Dermatologically tested, skin-safe ingredients,  
100% cruelty-free & high-performance formulas.
</p>

</section>

<footer>
© 2026 GlowGlam Cosmetics | Beauty Redefined 💕
</footer>

</body>
</html>
```
categories.html
```
<!DOCTYPE html>
<html>
<head>
<title>Categories - GlowGlam</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<div class="logo">GlowGlam</div>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="products.html">Products</a></li>
<li><a href="about.html">About</a></li>
<li><a href="contact.html">Categories</a></li>
<li><a href="account.html">Account</a></li>
</ul>
</nav>
</header>

<section class="products">
<h2>Shop by Categories 💄</h2>

<div class="product-container">

<div class="card">
<img src="makeup.jpg">
<h3>Makeup</h3>
<p>Lipsticks, Foundations, Eyeshadow</p>
<button class="btn">Explore</button>
</div>

<div class="card">
<img src="skincare.jpeg">
<h3>Skincare</h3>
<p>Serums, Moisturizers, Face Wash</p>
<button class="btn">Explore</button>
</div>

<div class="card">
<img src="haircare.jpg">
<h3>Haircare</h3>
<p>Shampoo, Conditioner, Oils</p>
<button class="btn">Explore</button>
</div>

<div class="card">
<img src="nailart.jpg">
<h3>Nail Products</h3>
<p>Nail Polish, Nail Care</p>
<button class="btn">Explore</button>
</div>

<div class="card">
<img src="gift.webp">
<h3>Gift Sets</h3>
<p>Beauty Combos & Special Kits</p>
<button class="btn">Explore</button>
</div>

</div>

</section>

<footer>
© 2026 GlowGlam Cosmetics | Discover Your Beauty 💕
</footer>

</body>
</html>
```
account.html
```
<!DOCTYPE html>
<html>
<head>
<title>My Account - GlowGlam</title>
<link rel="stylesheet" href="style.css">
<style>

/* ACCOUNT PAGE */
.account-container{
    padding:60px 10%;
}

.account-header{
    text-align:center;
    margin-bottom:40px;
}

.account-header h2{
    font-family:'Playfair Display', serif;
}

.account-grid{
    display:flex;
    flex-wrap:wrap;
    gap:30px;
    justify-content:center;
}

.account-card{
    width:260px;
    background:white;
    border-radius:15px;
    box-shadow:0 8px 18px rgba(0,0,0,0.1);
    padding:25px;
    text-align:center;
    transition:0.4s;
}

.account-card:hover{
    transform:translateY(-8px);
}

.account-card h3{
    margin-bottom:10px;
    font-family:'Playfair Display', serif;
}

.account-card p{
    font-size:14px;
    margin-bottom:15px;
}

.icon{
    font-size:35px;
    margin-bottom:10px;
}

/* LOGOUT BUTTON */
.logout-section{
    text-align:center;
    margin-top:50px;
}

.logout-btn{
    padding:12px 30px;
    background:linear-gradient(45deg,#ff416c,#ff4b2b);
    border:none;
    border-radius:30px;
    color:white;
    font-size:16px;
    cursor:pointer;
    transition:0.4s;
}

.logout-btn:hover{
    transform:scale(1.1);
    background:linear-gradient(45deg,#ff1e56,#ff0000);
}

</style>
</head>

<body>

<header>
<div class="logo">GlowGlam</div>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="products.html">Products</a></li>
<li><a href="about.html">About</a></li>
<li><a href="contact.html">Categories</a></li>
<li><a href="account.html">Account</a></li>
</ul>
</nav>
</header>

<section class="account-container">

<div class="account-header">
<h2>Welcome Back, Beautiful 👑</h2>
<p>Manage your orders, rewards and beauty preferences.</p>
</div>

<div class="account-grid">

<div class="account-card">
<div class="icon">📦</div>
<h3>My Orders</h3>
<p>Track and manage your purchases.</p>
<button class="btn">View Orders</button>
</div>

<div class="account-card">
<div class="icon">🔁</div>
<h3>Buy Again</h3>
<p>Reorder your favorite products.</p>
<button class="btn">Reorder</button>
</div>

<div class="account-card">
<div class="icon">🎟</div>
<h3>My Coupons</h3>
<p>Exclusive discounts & promo codes.</p>
<button class="btn">Check Coupons</button>
</div>

<div class="account-card">
<div class="icon">💰</div>
<h3>Wallet</h3>
<p>Cashback & reward balance details.</p>
<button class="btn">View Wallet</button>
</div>

<div class="account-card">
<div class="icon">👑</div>
<h3>Glam Membership</h3>
<p>Premium benefits & early access sales.</p>
<button class="btn">Upgrade</button>
</div>

<div class="account-card">
<div class="icon">❤️</div>
<h3>Wishlist</h3>
<p>Your saved beauty favorites.</p>
<button class="btn">View Wishlist</button>
</div>

<div class="account-card">
<div class="icon">🛠</div>
<h3>Help Centre</h3>
<p>Customer support & FAQs.</p>
<button class="btn">Get Help</button>
</div>

</div>

<!-- LOGOUT BUTTON -->
<div class="logout-section">
<br><br>
<button class="logout-btn">Logout</button>
</div>

</section>

<footer>
© 2026 GlowGlam Cosmetics | Beauty Redefined 💕
</footer>

</body>
</html>
```

## OUTPUT
<img width="1919" height="994" alt="Screenshot 2026-02-18 211818" src="https://github.com/user-attachments/assets/52730192-84ca-48af-ac53-591147e1fa37" />

<img width="1919" height="1012" alt="Screenshot 2026-02-18 211830" src="https://github.com/user-attachments/assets/c9ac550d-2254-4303-913c-d1421e5daedd" />

<img width="1919" height="1008" alt="Screenshot 2026-02-18 211845" src="https://github.com/user-attachments/assets/3c73036f-fe1a-4574-af16-c8d283cef534" />

<img width="1919" height="1007" alt="Screenshot 2026-02-18 211857" src="https://github.com/user-attachments/assets/a1d8a2bd-6d67-4fa5-8a54-70f666038138" />

<img width="1919" height="1004" alt="Screenshot 2026-02-18 211910" src="https://github.com/user-attachments/assets/5ff5c252-cfdf-45d2-aa29-1925f55f3377" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
