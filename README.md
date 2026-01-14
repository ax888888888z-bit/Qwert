<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hope Foundation</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    header {
      background: #0a6cf1;
      color: #fff;
      padding: 20px 0;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 15px;
      font-weight: bold;
    }
    .hero {
      background: #f4f6f8;
      padding: 60px 0;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.1rem;
      margin-bottom: 20px;
    }
    .btn {
      display: inline-block;
      background: #0a6cf1;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
    }
    section {
      padding: 50px 0;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <nav>
        <h2>Hope Foundation</h2>
        <div>
          <a href="#about">About</a>
          <a href="#programs">Programs</a>
          <a href="#donate">Donate</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Together We Can Make a Difference</h1>
      <p>Supporting education, healthcare, and community development.</p>
      <a href="#donate" class="btn">Donate Now</a>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>About Us</h2>
      <p>
        Hope Foundation is a non-profit organization dedicated to improving lives
        through education, healthcare, and sustainable community projects.
      </p>
    </div>
  </section>

  <section id="programs">
    <div class="container">
      <h2>Our Programs</h2>
      <div class="grid">
        <div class="card">
          <h3>Education</h3>
          <p>Providing access to quality education for underprivileged children.</p>
        </div>
        <div class="card">
          <h3>Healthcare</h3>
          <p>Supporting basic healthcare services in rural communities.</p>
        </div>
        <div class="card">
          <h3>Community Development</h3>
          <p>Empowering communities with sustainable development initiatives.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="donate">
    <div class="container">
      <h2>Support Our Cause</h2>
      <p>Your contribution helps us reach more people and change more lives.</p>
      <a href="#" class="btn">Make a Donation</a>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Email: info@hopefoundation.org</p>
      <p>Phone: +1 234 567 890</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2026 Hope Foundation. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
