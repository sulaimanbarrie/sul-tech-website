<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sul Tech Solutions</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #111;
      color: #fff;
      line-height: 1.6;
      transition: background 0.3s, color 0.3s;
    }

    .light-mode {
      background: #f9f9f9;
      color: #111;
    }

    header {
      background: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.5rem;
    }

    nav a {
      margin-left: 1rem;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
    }

    nav a:hover {
      color: #00bcd4;
    }

    .hero {
      padding: 4rem 2rem;
      text-align: center;
      background: #222;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .btn {
      padding: 0.8rem 1.5rem;
      background: #00bcd4;
      border: none;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      margin-top: 1rem;
      transition: transform 0.3s;
    }

    .btn:hover {
      transform: scale(1.05);
    }

    section {
      padding: 2rem;
    }

    .services, .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .card {
      background: #1a1a1a;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
    }

    .card h3 {
      margin-bottom: 0.5rem;
    }

    .card p {
      font-size: 0.9rem;
    }

    .contact {
      text-align: center;
    }

    .contact input, .contact textarea {
      width: 80%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border-radius: 4px;
      border: none;
    }

    .dark-light-toggle {
      cursor: pointer;
      background: none;
      color: white;
      border: 1px solid white;
      padding: 0.4rem 0.8rem;
      margin-left: 1rem;
      border-radius: 4px;
    }

    footer {
      background: #000;
      padding: 1rem;
      text-align: center;
      font-size: 0.8rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      nav {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
      }
      nav a {
        margin: 0.5rem 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>⚙️ Sul Tech Solutions</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
      <button class="dark-light-toggle" onclick="toggleMode()">🌙</button>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Tech Made Easy, Ideas Made Real</h2>
    <p>We build Websites, Logos, Apps and more — Fast and Affordable!</p>
    <a href="#contact"><button class="btn">Get Started</button></a>
  </section>

  <section id="services">
    <h2>💼 Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Logo Design</h3>
        <p>From Le 200 – Le 500</p>
      </div>
      <div class="card">
        <h3>Website Design</h3>
        <p>From Le 550 – Le 1600</p>
      </div>
      <div class="card">
        <h3>App UI Design</h3>
        <p>From Le 400 – Le 1200</p>
      </div>
      <div class="card">
        <h3>Flyer / Banner</h3>
        <p>From Le 150 – Le 350</p>
      </div>
      <div class="card">
        <h3>Tech Tutoring</h3>
        <p>Le 60/hr – Le 150/hr</p>
      </div>
      <div class="card">
        <h3>Resume Design</h3>
        <p>From Le 200 – Le 800</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>🧠 Sample Projects</h2>
    <div class="portfolio">
      <div class="card"><h3>Business Website</h3><p>Responsive & fast</p></div>
      <div class="card"><h3>Event Flyer</h3><p>Designed for social media</p></div>
      <div class="card"><h3>Portfolio App UI</h3><p>Modern & smooth</p></div>
    </div>
  </section>

  <section id="contact">
    <h2>📞 Book Us Now</h2>
    <div class="contact">
      <form action="https://formspree.io/f/mzbnyvpe" method="POST">
        <input type="text" name="name" placeholder="Your Name" required /><br />
        <input type="email" name="email" placeholder="Your Email" required /><br />
        <textarea name="message" rows="4" placeholder="What do you need?" required></textarea><br />
        <button class="btn" type="submit">Send Message</button>
      </form>
      <br />
      <a href="https://wa.me/23231010135" target="_blank">
        <button class="btn">📲 Message on WhatsApp</button>
      </a>
    </div>
  </section>

  <footer>
    &copy; 2025 Sul Tech Solutions. Built by Students. For Students & Small Businesses.
  </footer>

  <script>
    function toggleMode() {
      document.body.classList.toggle('light-mode');
    }
  </script>
</body>
</html>