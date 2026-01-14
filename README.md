<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HealthCare Plus</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background-color: #f5f9ff;
  color: #333;
  line-height: 1.6;
}

header {
  background: #0d6efd;
  color: #fff;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  font-size: 24px;
}

nav a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  background: linear-gradient(rgba(13,110,253,0.85), rgba(13,110,253,0.85)),
              url('https://images.unsplash.com/photo-1580281657527-47a8f39c1c85');
  background-size: cover;
  background-position: center;
  color: #fff;
  padding: 100px 40px;
  text-align: center;
}

.hero h2 {
  font-size: 40px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
}

.btn {
  background: #fff;
  color: #0d6efd;
  padding: 12px 25px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
}

.btn:hover {
  background: #e6e6e6;
}

section {
  padding: 60px 40px;
  max-width: 1100px;
  margin: auto;
}

.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.card {
  background: #fff;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  text-align: center;
}

.card h3 {
  margin-bottom: 15px;
  color: #0d6efd;
}

.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  align-items: center;
}

.about img {
  width: 100%;
  border-radius: 10px;
}

.contact {
  background: #0d6efd;
  color: #fff;
  border-radius: 10px;
  padding: 40px;
}

.contact form {
  display: grid;
  gap: 15px;
}

.contact input,
.contact textarea {
  padding: 10px;
  border-radius: 5px;
  border: none;
}

.contact button {
  background: #fff;
  color: #0d6efd;
  padding: 12px;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  background: #082c61;
  color: #fff;
  margin-top: 40px;
}

@media (max-width: 768px) {
  .about {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<header>
  <h1>HealthCare Plus</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero">
  <h2>Your Health, Our Priority</h2>
  <p>Providing quality healthcare services with care and compassion.</p>
  <a href="#contact" class="btn">Book Appointment</a>
</div>

<section id="services">
  <h2 style="text-align:center; margin-bottom:40px;">Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>General Checkup</h3>
      <p>Comprehensive health checkups.</p>
    </div>
    <div class="card">
      <h3>Emergency Care</h3>
      <p>24/7 emergency medical services.</p>
    </div>
    <div class="card">
      <h3>Specialist Doctors</h3>
      <p>Experienced medical specialists.</p>
    </div>
  </div>
</section>

<section id="about">
  <div class="about">
    <div>
      <h2>About Us</h2>
      <p>We deliver trusted healthcare services with modern facilities.</p>
    </div>
    <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118" alt="Hospital">
  </div>
</section>

<section id="contact">
  <div class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>
</section>

<footer>
  <p>&copy; 2026 HealthCare Plus</p>
</footer>

</body>
</html>


