<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Path to Success: Achieving Your Career Dreams</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #ffffff;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #ffffff;
      color: #000000;
      padding: 20px 40px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 15px;
    }

    .logo-img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #00bfff;
    }

    .logo span {
      font-size: 1.5rem;
      font-weight: bold;
      color: #000000;
    }

    nav a {
      color: #000000;
      text-decoration: none;
      margin-left: 25px;
      font-size: 1rem;
      padding: 5px 10px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    nav a:hover {
      text-decoration: underline;
    }

    nav a.active {
      background-color: #00bfff;
      color: #ffffff;
      padding: 8px 15px;
      border-radius: 20px;
      transition: background-color 0.3s ease;
    }

    .container {
      text-align: center;
      padding: 60px 20px 20px;
    }

    .title {
      font-size: 2.5rem;
      font-weight: bold;
      animation: fadeInDown 2s;
    }

    .career {
      font-size: 1.2rem;
      margin-top: 10px;
      color: #cccccc;
      animation: fadeInUp 2s;
    }

    .image-banner {
      max-width: 900px;
      width: 100%;
      margin: 40px auto 20px;
    }

    .image-banner img {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .grid-section {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 30px;
      max-width: 900px;
      margin: 0 auto 40px;
      padding: 20px;
      background-color: rgba(30, 30, 30, 0.95);
      border-radius: 10px;
    }

    .grid-section div {
      background-color: rgba(42, 42, 42, 0.95);
      padding: 20px;
      border-radius: 10px;
    }

    .next-section {
      padding: 60px 20px;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      position: relative;
      color: white;
    }

    .next-section::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background: rgba(0, 0, 0, 0.7);
      z-index: 0;
    }

    .next-section-content {
      position: relative;
      z-index: 1;
      text-align: center;
    }

    .next-button {
      display: inline-block;
      padding: 10px 25px;
      background-color: #00bfff;
      color: white;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s;
      font-size: 1rem;
    }

    .next-button:hover {
      background-color: #008ecf;
    }

    .next-button::after {
      content: ' →';
      font-size: 1.2rem;
    }

    footer {
      background-color: #ffffff;
      color: #000000;
      text-align: center;
      padding: 20px;
      font-size: 0.95rem;
      border-top: 1px solid #ccc;
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="King.png" alt="Profile" class="logo-img" />
      <span>Loggadeephan</span>
    </div>
    <nav>
      <a href="Career.html" class="active">Career</a>
      <a href="Step by Step.html">Step-by-Step</a>
      <a href="Inspiration.html">Inspiration & Resources</a>
    </nav>
  </header>

  <div class="container">
    <div class="title">The Path to Success: Achieving Your Career Dreams</div>
    <div class="career">Aspiring Multimedia & Graphic Designer</div>

    <div class="image-banner">
      <img src="Logo.png" alt="Graphic Designer Banner" />
    </div>

    <div class="grid-section">
      <div>
        <h3>My Skills</h3>
        <p>I specialize in multimedia creation, blending creativity with technical precision. My work reflects passion, dedication, and constant learning to keep up with trends in digital design.</p>
      </div>
      <div>
        <h3>Skill Criteria</h3>
        <ul>
          <li>Adobe Illustrator & Photoshop Proficiency</li>
          <li>Video Editing (CapCut, Premiere Pro)</li>
          <li>UI/UX Design Understanding</li>
          <li>Creative Concept Development</li>
        </ul>
      </div>
      <div>
        <h3>Communication</h3>
        <p>Strong communication skills in delivering design ideas clearly and collaborating in team projects effectively.</p>
      </div>
      <div>
        <h3>Technical Abilities</h3>
        <p>Capable of handling both creative design and front-end development using HTML/CSS.</p>
      </div>
    </div>
  </div>

  <div class="next-section">
    <div class="next-section-content">
      <a href="Step by Step.html" class="next-button">Step By Step</a>
    </div>
  </div>

  <footer>
    &copy; 2025 Loggadeephan. All rights reserved. | Designed with passion and creativity.
  </footer>
</body>
</html>

