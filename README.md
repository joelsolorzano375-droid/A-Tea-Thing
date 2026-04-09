<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>A Tea Thing</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: #6b4f4f;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #4a3434;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #6b4f4f;
    }
    .menu-items {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .reviews {
      background: #fff;
      border-left: 4px solid #6b4f4f;
      padding: 10px 15px;
      margin-bottom: 15px;
    }
    footer {
      background: #4a3434;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .btn {
      display: inline-block;
      background: #6b4f4f;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      border-radius: 5px;
      text-decoration: none;
    }
  </style>
</head>
<body>

<header>
  <h1>A Tea Thing</h1>
  <p>Specialty Milk Teas & Handcrafted Drinks</p>
  <p>⭐ 4.6 • 328 Reviews</p>
</header>

<nav>
  <a href="#menu">Menu</a>
  <a href="#about">About</a>
  <a href="#reviews">Reviews</a>
  <a href="#contact">Contact</a>
</nav>

<section id="menu">
  <h2>Customer Favorites</h2>
  <div class="menu-items">
    <div class="card">
      <h3>Brown Sugar Boba Milk Tea</h3>
      <p>Rich brown sugar syrup with fresh milk and chewy tapioca pearls.</p>
    </div>
    <div class="card">
      <h3>Matcha Latte</h3>
      <p>Premium ceremonial grade matcha with your choice of milk.</p>
    </div>
    <div class="card">
      <h3>Strawberry Matcha Croffle</h3>
      <p>Crispy croffle topped with strawberry sauce and matcha drizzle.</p>
    </div>
    <div class="card">
      <h3>Vietnamese Coffee</h3>
      <p>Bold Vietnamese coffee with sweet condensed milk over ice.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>About Us</h2>
  <p>
    Located in the heart of Reseda, A Tea Thing is a cozy cafe serving specialty milk teas,
    refreshing fruit teas, tornado blends, and delicious croffles.
  </p>
  <p>
    We use premium ingredients to craft every drink fresh, every time.
    Whether you're craving a classic brown sugar boba or a mango tornado blend,
    our friendly staff is here to help you find your perfect drink.
  </p>
</section>

<section id="reviews">
  <h2>What Our Customers Say</h2>

  <div class="reviews">
    <p>"Great service, sweet staff & great drinks! The brown sugar boba is my absolute favorite."</p>
    <strong>— Sarah M.</strong>
  </div>

  <div class="reviews">
    <p>"Thai tea smoothie with egg pudding was an amazing combo!"</p>
    <strong>— James L.</strong>
  </div>

  <div class="reviews">
    <p>"So many options and everything is delicious!"</p>
    <strong>— Michelle K.</strong>
  </div>

  <div class="reviews">
    <p>"Clean, warm, and inviting environment. The mango tornado blend is incredible."</p>
    <strong>— David P.</strong>
  </div>

</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p><strong>📍 Address:</strong> 7620 Reseda Blvd, Reseda, CA 91335</p>
  <p><strong>📞 Phone:</strong> (818) 938-9217</p>
  <p><strong>⏰ Hours:</strong> Open Daily · Closes 9:30 PM</p>

  <a href="#" class="btn">Call to Order</a>
  <a href="#" class="btn">Get Directions</a>
</section>

<footer>
  <p>© 2026 A Tea Thing. All rights reserved.</p>
</footer>
