<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My School Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to Our School</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Our School</h2>
    <p>We provide quality education and nurturing environment for learners.</p>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="images/school1.jpg" alt="School Building">
      <img src="images/school2.jpg" alt="Classroom">
      <img src="images/logo.png" alt="School Logo">
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p id="msg"></p>
  </section>

  <script src="script.js"></script>
</body>
</html>
