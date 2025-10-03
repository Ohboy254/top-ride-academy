- Grade 1: 18 learners
- Grade 2: 24 learners
- Grade 3: 23 learners
- Grade 4: 20 learners
- Grade 5: 27 learners
- Grade 6: 18 learners
- Grade 7: 24 learners
- Grade 8: 22 learners
- Grade 9: 18 learners<!DOCTYPE html>
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
    <p>We provide quality education and nurturing environment for learners.</p><section id="teachers">
  <h2>Our Teachers</h2>
  <div class="teacher-list">
    
    <!-- Teacher 1 -->
    <div class="teacher">
      <img src="teacher1.jpg" alt="Mr. John Doe">
      <h3>Mr. John Doe</h3>
      <p>Mathematics</p>
    </div>

    <!-- Teacher 2 -->
    <div class="teacher">
      <img src="teacher2.jpg" alt="Ms. Jane Smith">
      <h3>Ms. Jane Smith</h3>
      <p>English</p>
    </div>

    <!-- Teacher 3 -->
    <div class="teacher">
      <img src="teacher3.jpg" alt="Mr. Peter Otieno">
      <h3>Mr. Peter Otieno</h3>
      <p>Science</p>
    </div>

    <!-- Add more teachers below in the same format -->
    
  </div>
</section>

<style>
  #teachers {
    padding: 30px;
    background: #f4f7fa;
    text-align: center;
  }

  #teachers h2 {
    font-size: 28px;
    margin-bottom: 20px;
    color: #2c3e50;
  }

  .teacher-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 25px;
    justify-content: center;
  }

  .teacher {
    background: #fff;
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.2s ease-in-out;
  }

  .teacher:hover {
    transform: scale(1.05);
  }

  .teacher img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 12px;
  }

  .teacher h3 {
    margin: 12px 0 5px;
    font-size: 20px;
    color: #34495e;
  }

  .teacher p {
    font-size: 16px;
    color: #777;
  }
</style>
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
