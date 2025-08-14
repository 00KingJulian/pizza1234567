<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>L'Industrie Pizzeria</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fffaf3;
      color: #333;
    }
    header {
      background-color: #d62828;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      background-color: #f77f00;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: white;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .menu-item {
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 1rem;
      background-color: #fff;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: 0;
      margin-top: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>L'Industrie Pizzeria</h1>
    <p>Brooklyn’s Favorite Artisan Pizza</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#visit">Visit</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>Located in the heart of Williamsburg, L’Industrie Pizzeria serves up authentic, delicious pizza crafted with love and tradition. With a blend of Italian techniques and New York attitude, we deliver slices that locals swear by.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <div class="menu-item">
        <h3>Margherita</h3>
        <p>Classic tomato sauce, mozzarella, fresh basil</p>
        <strong>$3.50 / slice</strong>
      </div>
      <div class="menu-item">
        <h3>Pepperoni</h3>
        <p>Spicy pepperoni, tomato sauce, mozzarella</p>
        <strong>$4.00 / slice</strong>
      </div>
      <div class="menu-item">
        <h3>White Pie</h3>
        <p>Ricotta, mozzarella, garlic, olive oil</p>
        <strong>$4.25 / slice</strong>
      </div>
      <div class="menu-item">
        <h3>Truffle Mushroom</h3>
        <p>Wild mushrooms, truffle oil, mozzarella</p>
        <strong>$4.50 / slice</strong>
      </div>
    </div>
  </section>

  <section id="visit">
    <h2>Visit Us</h2>
    <p><strong>Location:</strong> 254 S 2nd St, Brooklyn, NY 11211</p>
    <p><strong>Hours:</strong> Mon–Sun: 11 AM – 10 PM</p>
    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3021.5940604080917!2d-73.96005788459836!3d40.71160527933068!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c25be02249e843%3A0x95c3f90fbb6a4745!2sL&#39;Industrie%20Pizzeria!5e0!3m2!1sen!2sus!4v1712000000000!5m2!1sen!2sus"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have questions or want to place a large order?</p>
    <p>Email us: <a href="mailto:info@lindustriepizzeria.com">info@lindustriepizzeria.com</a></p>
    <p>Phone: <a href="tel:+17182222112">(718) 222-2112</a></p>
  </section>

  <footer>
    <p>&copy; 2025 L'Industrie Pizzeria. All rights reserved.</p>
  </footer>

</body>
</html>
