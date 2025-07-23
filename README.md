# sul-tech-website
official website for sul tech solutions empowering tech &amp; design.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sul Tech Solutions</title>
  <link rel="stylesheet" href="style.css"/>
  <script defer src="script.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <header>
    <div class="logo">Sul Tech</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
      <button id="toggle-theme"><i class="fas fa-moon"></i></button>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Tech Made Easy, Ideas Made Real</h1>
    <a href="#contact" class="btn">Get Started</a>
  </section>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <div class="cards">
      <div class="card"><i class="fas fa-pen-nib"></i><h3>Logo Design</h3><p>Le200 - Le500</p></div>
      <div class="card"><i class="fas fa-code"></i><h3>Website Dev</h3><p>Le550 - Le1600</p></div>
      <div class="card"><i class="fas fa-mobile-alt"></i><h3>App UI Design</h3><p>Le400 - Le1200</p></div>
      <div class="card"><i class="fas fa-image"></i><h3>Flyer/Banner</h3><p>Le150 - Le350</p></div>
      <div class="card"><i class="fas fa-chalkboard-teacher"></i><h3>Tech Tutoring</h3><p>Le60 - Le150/hr</p></div>
      <div class="card"><i class="fas fa-file-alt"></i><h3>Résumé Design</h3><p>Le200 - Le800</p></div>
    </div>
  </section>

  <section id="portfolio" class="section">
    <h2>Our Portfolio</h2>
    <div class="portfolio">
      <img src="https://via.placeholder.com/250x150" alt="Project 1"/>
      <img src="https://via.placeholder.com/250x150" alt="Project 2"/>
      <img src="https://via.placeholder.com/250x150" alt="Project 3"/>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form action="https://formspree.io/f/your-id" method="POST">
      <input type="text" name="name" placeholder="Your name" required>
      <input type="email" name="_replyto" placeholder="Your email" required>
      <textarea name="message" placeholder="Your message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <a class="whatsapp" href="https://wa.me/232XXXXXXXXX" target="_blank"><i class="fab fa-whatsapp"></i> Chat on WhatsApp</a>
  </section>

  <footer>
    <p>&copy; 2025 Sul Tech Solutions. All rights reserved.</p>
  </footer>
</body>
</html>
