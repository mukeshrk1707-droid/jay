<!DOCTYPE html>
<html>
<head>
<title>HelpNest</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<div class="navbar">
  <div class="logo">HelpNest</div>

  <div class="menu">
    <a href="#">Home</a>
    <a href="cart.html">Booking</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
  </div>

  <input type="text" placeholder="Search services..." class="search">
</div>

<section class="hero">
  <h1>Book Trusted Home Services</h1>
  <p>Electrician • Plumber • AC Repair • Cleaning</p>
  <button onclick="scrollToServices()">Explore Services</button>
</section>

<div class="features">
  <div>✔ Verified Experts</div>
  <div>⚡ Same Day Service</div>
  <div>💰 Affordable Price</div>
</div>

<h2 class="section-title">Our Services</h2>

<div class="services-grid" id="services">

  <a href="ac.html" class="service-box">
    <img src="https://img.icons8.com/color/96/air-conditioner.png">
    <p>A.C.</p>
  </a>

  <a href="plumbing.html" class="service-box">
    <img src="https://img.icons8.com/color/96/plumbing.png">
    <p>Plumber</p>
  </a>

  <a href="electrician.html" class="service-box">
    <img src="https://img.icons8.com/color/96/electrical.png">
    <p>Electrician</p>
  </a>

  <a href="cleaning.html" class="service-box">
    <img src="clean.jpeg">
    <p>Cleaning</p>
  </a>

  <a href="washing.html" class="service-box">
    <img src="washing.jpeg">
    <p>Washing Machine</p>
  </a>

  <a href="fridge.html" class="service-box">
    <img src="fridgr.jpeg">
    <p>Fridge</p>
  </a>

  <a href="geyser.html" class="service-box">
    <img src="https://img.icons8.com/color/96/water-heater.png">
    <p>Geyser</p>
  </a>

  <a href="painting.html" class="service-box">
    <img src="pnt.jpeg">
    <p>Painting</p>
  </a>

</div>

<div class="banner">
  <h2>Get ₹100 OFF on First Booking</h2>
  <button>Book Now</button>
</div>

<footer>
  <h3>HelpNest</h3>
  <p>Fast • Reliable • Affordable Services</p>
  <p>📞 +91 9999999999</p>
</footer>

<script>
function scrollToServices(){
  document.getElementById("services").scrollIntoView({behavior:'smooth'});
}
</script>

</body>
</html>
