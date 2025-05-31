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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Step-by-Step</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      font-family: 'Arial', sans-serif;
      background-color: #121212;
      color: #ffffff;
      overflow-x: hidden;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #ffffff;
      padding: 20px 40px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    /* Logo container: image + text side by side on left */
    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    /* Image style */
    .logo-img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #00bfff;
      animation: float 3s ease-in-out infinite;
    }

    /* Text next to image */
    .logo-text {
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

    nav a.active {
      background-color: #00bfff;
      color: #ffffff;
      padding: 8px 15px;
      border-radius: 20px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 80px 20px 40px;
      background: linear-gradient(135deg, #1e1e1e, #2e2e2e);
      animation: fadeIn 2s ease-in-out;
    }

    .hero h1 {
      font-size: 3rem;
      font-weight: bold;
      margin-bottom: 10px;
      color: #00bfff;
      animation: glow 2s infinite alternate;
    }

    .hero p {
      font-size: 1.2rem;
      color: #cccccc;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #00bfff, 0 0 20px #00bfff;
      }
      to {
        text-shadow: 0 0 20px #00ffff, 0 0 30px #00ffff;
      }
    }

    .steps-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 40px 20px;
    }

    .step {
      background-color: #1e1e1e;
      padding: 20px;
      width: 300px;
      border-radius: 15px;
      text-align: center;
      transition: transform 0.3s ease;
      box-shadow: 0 0 15px rgba(0, 191, 255, 0.2);
    }

    .step:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 25px rgba(0, 191, 255, 0.4);
    }

    .step img {
      width: 60px;
      margin-bottom: 15px;
      animation: float 3s ease-in-out infinite;
    }

    .step h3 {
      font-size: 1.4rem;
      color: #00bfff;
    }

    .step p {
      font-size: 1rem;
      color: #bbbbbb;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    .snake-row {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
      padding: 60px 20px;
    }

    .snake-column {
      flex: 1;
      min-width: 320px;
    }

    .snake-step {
      background-color: #1e1e1e;
      padding: 20px;
      border-radius: 15px;
      margin-bottom: 30px;
      box-shadow: 0 0 15px rgba(0,191,255,0.2);
      transition: transform 0.3s ease;
    }

    .snake-step:hover {
      transform: translateY(-8px);
      box-shadow: 0 0 25px rgba(0,191,255,0.4);
    }

    .snake-step .text h3 {
      font-size: 1.6rem;
      color: #00bfff;
      margin-bottom: 10px;
    }

    .snake-step .text p {
      color: #dddddd;
      font-size: 1rem;
    }

    .snake-step button {
      margin-top: 15px;
      background-color: #00bfff;
      color: #ffffff;
      padding: 10px 20px;
      font-size: 1rem;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .snake-step button:hover {
      background-color: #0099cc;
    }

    footer {
      background-color: #ffffff;
      color: #000000;
      text-align: center;
      padding: 20px;
      font-size: 0.95rem;
      animation: fadeInUp 2s ease-in;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
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
      <div class="logo-text">Loggadeephan</div>
    </div>
    <nav>
      <a href="Career.html">Career</a>
      <a href="Step by step.html" class="active">Step-by-Step</a>
      <a href="Inspiration.html">Inspiration & Resources</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Your Journey to Success</h1>
    <p>Follow these steps to turn your career dreams into reality.</p>
  </section>

  <section class="steps-container">
    <div class="step">
      <img src="Research.png" alt="Research Icon" />
      <h3>Step 1: Explore</h3>
      <p>Research your passion and discover your strengths in the creative industry.</p>
    </div>
    <div class="step">
      <img src="Skilss.png" alt="Skill Icon" />
      <h3>Step 2: Learn Skills</h3>
      <p>Master design tools like Adobe Illustrator, Photoshop, and CapCut.</p>
    </div>
    <div class="step">
      <img src="Practice.png" alt="Practice Icon" />
      <h3>Step 3: Practice</h3>
      <p>Build your portfolio by creating real and imaginative projects regularly.</p>
    </div>
    <div class="step">
      <img src="C1.png" alt="Connect Icon" />
      <h3>Step 4: Network</h3>
      <p>Connect with professionals and share your work on platforms like LinkedIn or Behance.</p>
    </div>
    <div class="step">
      <img src="Grow.png" alt="Grow Icon" />
      <h3>Step 5: Apply</h3>
      <p>Apply for internships or freelance jobs to gain experience and grow your resume.</p>
    </div>
  </section>

  <!-- Snake Row Two-Column Section -->
  <section class="snake-row">
    <!-- Left Column -->
    <div class="snake-column">
      <div class="snake-step">
        <div class="text">
          <h3>Develop Your Personal Brand</h3>
          <p>Create a personal logo, build an online presence, and showcase your unique style across all platforms.</p>
          <button onclick="alert('Entering Personal Brand Section...')">Enter</button>
        </div>
      </div>
      <div class="snake-step">
        <div class="text">
          <h3>Master Time Management</h3>
          <p>Balance study, projects, and self-improvement with tools like calendars and productivity apps.</p>
          <button onclick="alert('Entering Time Management Section...')">Enter</button>
        </div>
      </div>
      <div class="snake-step">
        <div class="text">
          <h3>Embrace Feedback & Growth</h3>
          <p>Seek feedback from peers, mentors, and lecturers. Use it to refine your craft and improve continuously.</p>
          <button onclick="alert('Entering Feedback Section...')">Enter</button>
        </div>
      </div>
    </div>

    <!-- Right Column -->
    <div class="snake-column">
      <div class="snake-step">
        <div class="text">
          <h3>Tips & Tools</h3>
          <p>Use apps like Notion, Trello, Google Calendar, Canva, and Adobe Express to stay productive and creative.</p>
          <button onclick="alert('Opening Tools Section...')">Explore Tools</button>
        </div>
      </div>
    </div>

  </section>
<div class="next-section">
    <div class="next-section-content">
      <a href="Career.html" class="next-button">Career</a>
    </div>
  </div>


  <footer>
   &copy; 2025 Loggadeephan. All rights reserved. | Designed with passion and creativity
  </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Page 3 - The Path to Success</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      font-family: 'Arial', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: #fff;
      overflow-x: hidden;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    /* HEADER */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #ffffff;
      padding: 20px 40px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .header-left {
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

    .logo-text {
      font-size: 1.5rem;
      font-weight: bold;
      color: #000000;
    }

    nav {
      display: flex;
      align-items: center;
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

    nav a.active {
      background-color: #00bfff;
      color: #ffffff;
      padding: 8px 15px;
      border-radius: 20px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* PREVIOUS BUTTON */
    .previous-button-container {
      max-width: 1200px;
      margin: 20px auto 0 auto;
      padding: 0 20px;
    }

    .previous-button {
      background-color: #00bfff;
      color: #ffffff;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      border-radius: 20px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }

    .previous-button:hover {
      background-color: #009acd;
    }

    /* MAIN */
    main {
      flex: 1;
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto 40px auto;
    }

    .section {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      margin-bottom: 60px;
      opacity: 0;
      animation: fadeInUp 1.2s ease forwards;
      animation-delay: 0.3s;
    }

    .section:nth-child(even) {
      flex-direction: row-reverse;
    }

    .section img {
      width: 100%;
      max-width: 450px;
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,191,255,0.4);
      transition: transform 0.5s;
      opacity: 0;
      animation-fill-mode: forwards;
      animation-duration: 1.5s;
    }

    .section:nth-child(odd) img {
      animation-name: slideInLeft, floatUpDown;
      animation-delay: 0.3s, 1.8s;
      animation-timing-function: ease-out, ease-in-out;
      animation-iteration-count: 1, infinite;
      animation-direction: normal, alternate;
    }

    .section:nth-child(even) img {
      animation-name: slideInRight, floatUpDown;
      animation-delay: 0.3s, 1.8s;
      animation-timing-function: ease-out, ease-in-out;
      animation-iteration-count: 1, infinite;
      animation-direction: normal, alternate;
    }

    @keyframes floatUpDown {
      0% { transform: translateY(0); }
      100% { transform: translateY(-15px); }
    }

    @keyframes slideInLeft {
      0% { opacity: 0; transform: translateX(-100px); }
      100% { opacity: 1; transform: translateX(0); }
    }

    @keyframes slideInRight {
      0% { opacity: 0; transform: translateX(100px); }
      100% { opacity: 1; transform: translateX(0); }
    }

    .text-content {
      flex: 1;
      padding: 20px;
      opacity: 0;
      animation: fadeInText 1.2s ease forwards;
      animation-delay: 1.2s;
    }

    .text-content h2 {
      font-size: 1.6rem;
      color: #00bfff;
      margin-bottom: 12px;
    }

    /* JUSTIFY TEXT */
    .text-content p {
      font-size: 1rem;
      line-height: 1.6;
      color: #ddd;
      text-align: justify;
    }

    footer {
      background-color: #ffffff;
      color: #000000;
      text-align: center;
      padding: 20px;
      font-size: 0.95rem;
      animation: fadeInUp 2s ease-in;
    }

    @keyframes fadeInUp {
      to { opacity: 1; transform: translateY(0); }
      from { opacity: 0; transform: translateY(30px); }
    }

    @keyframes fadeInText {
      to { opacity: 1; }
      from { opacity: 0; }
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
        gap: 15px;
      }

      nav {
        width: 100%;
        justify-content: center;
        flex-wrap: wrap;
      }

      .section {
        flex-direction: column !important;
        text-align: center;
      }

      .section img {
        max-width: 90%;
        margin-bottom: 20px;
      }

      /* Center previous button on small screens */
      .previous-button-container {
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="header-left">
      <img src="King.Png" alt="Profile" class="logo-img" />
      <div class="logo-text">Loggadeephan</div>
    </div>
    <nav>
      <a href="Career.html">Career</a>
      <a href="Step by step.html">Step-by-Step</a>
      <a href="Inspiration.html" class="active">Inspiration & Resources</a>
    </nav>
  </header>

   <main>
    <div class="section">
      <img src="zach-king.png" alt="Founding Stage" />
      <div class="text-content">
        <h2>Zach King</h2>
        <p>Zach King is an American content creator known for his mind-blowing magic videos that use clever visual effects and seamless editing. Born in 1990, he rose to fame on Vine and later became one of the most followed creators on TikTok. His videos, often called “digital magic,” have captivated millions worldwide, including his record-breaking Harry Potter illusion. He is admired for combining creativity, storytelling, and tech to make everyday moments feel magical.</p>
      </div>
    </div>

    <div class="section">
      <img src="Joshua.jpg" alt="Growth & Progress" />
      <div class="text-content">
        <h2>Joshmadj</h2>
        <p>Joshmadj, also known as Joshua Michael, is a Malaysian content creator celebrated for his comedic skits, relatable POVs, and engaging social commentary on TikTok. Since joining the platform in 2019, he has amassed over 473,000 followers and 15 million likes, captivating audiences with his humorous takes on everyday scenarios and cultural observations.Joshmadj, also known as Joshua Michael, is featured in the Tamil-language web series Inthu Dealing Pudichereku. This series showcases his acting skills in various comedic and dramatic roles, contributing to his growing popularity in the Malaysian entertainment scene.</p>
      </div>
    </div>

    <div class="section">
      <img src="Sofyank.jpg" alt="Next Chapter" />
      <div class="text-content">
        <h2>Sofyank</h2>
        <p>Mohamad Sofian bin Abdullah, known online as Sofyank, is a Malaysian digital content creator and VFX artist celebrated for his captivating visual effects and storytelling. Born on November 30, 1996, in Wakaf Bharu, Kelantan, he began his creative journey with limited resources, often editing videos using a borrowed laptop and self-taught techniques.Building on his success, Sofyank has collaborated with Hollywood stars such as Paul Rudd and Jonathan Majors, creating VFX content for Ant-Man and the Wasp: Quantumania. His work has also caught the attention of actor Will Smith, who shared one of his edited videos on social media .</p>
      </div>
    </div>
  </main>
<div class="previous-button-container">
    <a href="Step by Step.html" class="previous-button" aria-label="Go to previous page">← Step By Step</a>
  </div>


  <footer>
   &copy; 2025 Loggadeephan. All rights reserved. | Designed with passion and creativity
  </footer>

</body>
</html>

