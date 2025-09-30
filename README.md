<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>About Us — Aditya Kirana And General Store</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <a class="brand" href="index.html">Aditya Kirana And General Store</a>
      <nav>
        <a href="index.html">Home</a>
        <a href="about.html" class="active">About</a>
        <a href="services.html">Services</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <h1>About Us</h1>
    <p>
      Welcome to <strong>Aditya Kirana And General Store</strong>, your trusted
      neighborhood shop for everyday essentials. Located near Gandhi Statue, Miyapur,
      we pride ourselves on offering high-quality products at affordable prices.
    </p>

    <p>
      From groceries and snacks to household items and daily necessities, we stock
      everything you need under one roof. Our goal is to make shopping simple and
      convenient for you and your family.
    </p>

    <h2>Why Choose Us?</h2>
    <ul>
      <li>Wide range of essential and household products</li>
      <li>Friendly and helpful customer service</li>
      <li>Convenient location in Miyapur</li>
      <li>Affordable prices with great quality</li>
    </ul>
  </main>

  <footer class="site-footer">
    <div class="wrap">
      <div class="footer-left">
        <strong>Aditya Kirana And General Store</strong>
        <p>Near Gandhi Statue, Miyapur • 9515483714 • 
           <a href="mailto:gubbaramakrishna841@gmail.com">gubbaramakrishna841@gmail.com</a></p>
      </div>
    </div>
  </footer>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Services — Aditya Kirana And General Store</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <a class="brand" href="index.html">Aditya Kirana And General Store</a>
      <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="services.html" class="active">Services</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <h1>Our Products & Services</h1>
    <p>
      At <strong>Aditya Kirana And General Store</strong>, we offer a wide
      variety of essentials and household items to meet your daily needs.
    </p>

    <section class="service-list">
      <article>
        <h2>Groceries & Essentials</h2>
        <p>
          Rice, wheat, pulses, oil, sugar, and all your everyday kitchen essentials.
        </p>
      </article>

      <article>
        <h2>Household Items</h2>
        <p>
          Cleaning supplies, toiletries, personal care products, and more — everything to keep your home running smoothly.
        </p>
      </article>

      <article>
        <h2>Snacks & Beverages</h2>
        <p>
          Chips, biscuits, cold drinks, dairy products, and quick bites for all ages.
        </p>
      </article>
    </section>
  </main>

  <footer class="site-footer">
    <div class="wrap">
      <div class="footer-left">
        <strong>Aditya Kirana And General Store</strong>
        <p>Near Gandhi Statue, Miyapur • 9515483714 • 
           <a href="mailto:gubbaramakrishna841@gmail.com">gubbaramakrishna841@gmail.com</a></p>
      </div>
    </div>
  </footer>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Contact Us — Aditya Kirana And General Store</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <a class="brand" href="index.html">Aditya Kirana And General Store</a>
      <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="services.html">Services</a>
        <a href="contact.html" class="active cta">Contact</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <h1>Contact Us</h1>
    <p>
      We’d love to hear from you! Feel free to call, email, or visit us at our store.
    </p>

    <section class="contact-info">
      <p><strong>Phone:</strong> <a href="tel:9515483714">9515483714</a></p>
      <p><strong>Email:</strong> <a href="mailto:gubbaramakrishna841@gmail.com">gubbaramakrishna841@gmail.com</a></p>
      <p><strong>Address:</strong> Near Gandhi Statue, Miyapur</p>
    </section>

    <h2>Find Us on the Map</h2>
    <iframe
      src="https://www.google.com/maps?q=Miyapur&output=embed"
      width="100%"
      height="350"
      style="border:0;"
      allowfullscreen=""
      loading="lazy">
    </iframe>
  </main>

  <footer class="site-footer">
    <div class="wrap">
      <div class="footer-left">
        <strong>Aditya Kirana And General Store</strong>
        <p>Near Gandhi Statue, Miyapur • 9515483714 • 
           <a href="mailto:gubbaramakrishna841@gmail.com">gubbaramakrishna841@gmail.com</a></p>
      </div>
    </div>
  </footer>
</body>
</html>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

/* General layout */
.wrap {
  width: 90%;
  max-width: 1100px;
  margin: 0 auto;
}

/* Header */
.site-header {
  background: #4CAF50;
  color: white;
  padding: 1rem 0;
}

.site-header .brand {
  font-size: 1.8rem;
  font-weight: bold;
  text-decoration: none;
  color: white;
}

.site-header nav {
  float: right;
}

.site-header nav a {
  color: white;
  margin-left: 1.5rem;
  text-decoration: none;
  font-weight: bold;
}

.site-header nav a.cta {
  background: white;
  color: #4CAF50;
  padding: 0.4rem 0.8rem;
  border-radius: 4px;
}

.site-header nav a.active {
  text-decoration: underline;
}

/* Hero Section */
.hero {
  background: #f4f4f4;
  text-align: center;
  padding: 3rem 1rem;
}

.hero h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.hero p.lead {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.hero .button {
  background: #4CAF50;
  color: white;
  padding: 0.6rem 1.2rem;
  text-decoration: none;
  border-radius: 4px;
}

/* Features */
.features {
  display: flex;
  justify-content: space-between;
  margin: 2rem 0;
}

.features article {
  flex: 1;
  margin: 0 1rem;
  background: #e8f5e9;
  padding: 1rem;
  border-radius: 6px;
  text-align: center;
}

/* About preview */
.about-preview {
  display: flex;
  flex-wrap: wrap;
  margin: 2rem 0;
  align-items: center;
}

.about-preview img {
  max-width: 400px;
  margin-left: 2rem;
  flex: 1;
}

/* Services & contact */
.service-list article, .contact-info {
  margin-bottom: 1.5rem;
}

.service-list h2 {
  color: #4CAF50;
  margin-bottom: 0.5rem;
}

/* Footer */
.site-footer {
  background: #333;
  color: white;
  padding: 1.5rem 0;
  margin-top: 2rem;
  text-align: center;
}

.site-footer a {
  color: #f4f4f4;
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 768px) {
  .features {
    flex-direction: column;
  }

  .features article {
    margin: 1rem 0;
  }

  .about-preview {
    flex-direction: column;
  }

  .about-preview img {
    margin: 1rem 0 0 0;
  }

  .site-header nav {
    float: none;
    text-align: center;
    margin-top: 1rem;
  }

  .site-header nav a {
    display: inline-block;
    margin: 0.5rem;
  }
}
