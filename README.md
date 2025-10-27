<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Study Point - Coaching Centre</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #e6f0ff, #ffffff 70%);
      color: #003366;
      overflow-x: hidden;
    }

    header {
      background: linear-gradient(135deg, #003366, #0055cc);
      color: white;
      padding: 25px;
      text-align: center;
      font-size: 2em;
      letter-spacing: 1.2px;
      text-shadow: 0 0 20px rgba(255,255,255,0.5);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 25px;
      background: white;
      padding: 12px 0;
      border-bottom: 2px solid #003366;
      position: sticky;
      top: 80px;
      z-index: 999;
    }

    nav a {
      color: #003366;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    nav a:hover {
      color: #007bff;
      transform: scale(1.1);
    }

    section {
      padding: 70px 20px;
      text-align: center;
      perspective: 1000px;
    }

    .hero {
      background: linear-gradient(135deg, #003366, #0055cc);
      color: white;
      border-radius: 20px;
      padding: 80px 30px;
      margin: 40px auto;
      width: 85%;
      max-width: 1000px;
      transform: rotateY(0deg);
      animation: heroFloat 6s ease-in-out infinite;
      box-shadow: 0 0 30px rgba(0,0,50,0.3);
    }

    @keyframes heroFloat {
      0%, 100% { transform: rotateY(0deg) translateY(0); }
      50% { transform: rotateY(10deg) translateY(-10px); }
    }

    .hero h1 {
      font-size: 2.8em;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 1.2em;
      margin-bottom: 20px;
      opacity: 0.9;
    }

    .btn {
      background-color: white;
      color: #003366;
      border: none;
      padding: 12px 25px;
      font-size: 1em;
      border-radius: 30px;
      cursor: pointer;
      transition: 0.3s;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .btn:hover {
      background-color: #007bff;
      color: white;
      transform: scale(1.1);
    }

    .courses {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      margin-top: 40px;
    }

    .course {
      width: 260px;
      padding: 25px;
      border-radius: 15px;
      background: white;
      border: 2px solid #003366;
      transition: all 0.5s ease;
      box-shadow: 0 8px 15px rgba(0,0,0,0.1);
      transform-style: preserve-3d;
    }

    .course:hover {
      transform: rotateY(10deg) translateY(-8px);
      box-shadow: 0 15px 25px rgba(0,0,100,0.2);
    }

    footer {
      background: linear-gradient(135deg, #003366, #0055cc);
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 1em;
      letter-spacing: 0.5px;
    }

    .contact-info {
      font-size: 1.1em;
      line-height: 1.8;
    }

    .note {
      margin-top: 25px;
      font-weight: bold;
      font-size: 1.1em;
    }

    @media (max-width: 600px) {
      .hero h1 { font-size: 2em; }
      .hero p { font-size: 1em; }
      .course { width: 90%; }
    }
  </style>
</head>
<body>

  <header>Study Point</header>

  <nav>
    <a href="#home">Home</a>
    <a href="#courses">Subjects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <div class="hero">
      <h1>Welcome to Study Point</h1>
      <p>Empowering young minds through quality education and guidance.</p>
      <p><strong>Admissions open for students of Class 3 to 10.</strong></p>
      <p>Every week, a chapter-wise test is conducted to ensure consistent progress and mastery.</p>
      <button class="btn" onclick="scrollToSection('courses')">View Subjects</button>
    </div>
  </section>

  <section id="courses">
    <h2>Subjects We Offer</h2>
    <div class="courses">
      <div class="course">
        <h3>English</h3>
        <p>Enhance grammar, vocabulary, and communication with expert guidance.</p>
      </div>
      <div class="course">
        <h3>Assamese</h3>
        <p>Master your mother tongue with a deep understanding of grammar and literature.</p>
      </div>
      <div class="course">
        <h3>Hindi</h3>
        <p>Strengthen your Hindi speaking and writing skills with our simplified approach.</p>
      </div>
      <div class="course">
        <h3>Social Studies</h3>
        <p>Understand history, geography, and civics with interesting real-life examples.</p>
      </div>
      <div class="course">
        <h3>Mathematics</h3>
        <p>Build a strong foundation in concepts, logic, and problem-solving techniques.</p>
      </div>
      <div class="course">
        <h3>Science</h3>
        <p>Learn concepts through visualization and practical understanding.</p>
      </div>
    </div>
  </section>

  <section id="contact" style="background-color: #e6f0ff;">
    <h2>Contact Us</h2>
    <div class="contact-info">
      <p><strong>📍 Location:</strong> In front of Prashanti Tourist Lodge, Golaghat, Assam 785621</p>
      <p><strong>📞 Contact:</strong> +91 91014 50453</p>
    </div>
  </section>

  <footer>
    Designed by Delta Web Studio | © 2025 Study Point
  </footer>

  <script>
    function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({ behavior: "smooth" });
    }
  </script>

</body>
</html># deltawebstudio
