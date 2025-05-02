<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kiranmai Reddy | Business Analyst Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }
    body { margin: 0; font-family: 'Montserrat', sans-serif; background: #ffffff; color: #333; }
    header {
      background: linear-gradient(to right, #a18cd1, #fbc2eb);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    .header-content {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .header-photo {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid white;
      margin-bottom: 15px;
    }
    header h1 { margin: 0; font-size: 3em; }
    header p { font-size: 1.2em; margin-top: 10px; }

    nav {
      background: #6c63ff;
      padding: 12px 0;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 500;
    }
    nav a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 50px 20px;
    }
    .section {
      margin-bottom: 60px;
      background: #f5f7fa;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    .skills span {
      display: inline-block;
      background: #dee2e6;
      padding: 8px 12px;
      border-radius: 20px;
      margin: 6px;
      font-size: 0.95em;
    }
    h2 {
      color: #6c63ff;
      border-left: 5px solid #6c63ff;
      padding-left: 12px;
    }
    ul { padding-left: 20px; }
    .btn {
      display: inline-block;
      margin-top: 15px;
      background: #6c63ff;
      color: white;
      padding: 12px 20px;
      border-radius: 5px;
      text-decoration: none;
      transition: background 0.3s ease;
    }
    .btn:hover { background: #5146d8; }
    footer {
      background: #6c63ff;
      color: white;
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9em;
    }
    .contact a {
      color: #ffd966;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <div class="header-content">
      <img src="IMG_6839.jpg" alt="Kiranmai Reddy" class="header-photo">
      <h1>Kiranmai Reddy</h1>
      <p><h2>Business Analyst </h2></p>
    </div>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <div class="section" id="about">
      <h2>About Me</h2>
      <p>I’m a creative and analytical Business Analyst with 4 years of experience turning data into decisions. I specialize in translating stakeholder needs into technical solutions, visualizing trends through Power BI/Tableau, and optimizing Agile delivery cycles. I recently completed my Master’s in Data Analytics Engineering from George Mason University, and I’m passionate about bridging data and business insights.</p>
    </div>

    <div class="section" id="skills">
      <h2>Skills</h2>
      <div class="skills">
        <span>SQL</span><span>Power BI</span><span>Tableau</span><span>Excel</span><span>Python</span>
        <span>JIRA</span><span>Confluence</span><span>BRD</span><span>FRD</span><span>UAT</span>
        <span>Agile</span><span>Stakeholder Engagement</span><span>Data Visualization</span>
      </div>
    </div>

    <div class="section" id="Work Experience">
      <h2>Work Experience</h2>
      <h3>DXC Technology</h3>
      <h4>Business Analyst</h4>
      <ul>
        <li><strong>Problem:</strong> No central dashboard to track client KPIs</li>
        <li><strong>Tools:</strong> Power BI, Excel</li>
        <li><strong>Role:</strong> Built dashboards, created wireframes, supported UAT</li>
        <li><strong>Outcome:</strong> 30% faster reporting, 15% fewer user complaints</li>
      </ul>

      <h3>Software Upgrade – Accenture</h3>
      <ul>
        <li><strong>Problem:</strong> Lack of traceable documentation and testing for release</li>
        <li><strong>Tools:</strong> JIRA, Tableau, Python</li>
        <li><strong>Role:</strong> Created 200+ user stories, wrote test cases, ran UAT</li>
        <li><strong>Outcome:</strong> 99% defect-free deployment, 20% faster delivery</li>
      </ul>
    </div>

    <div class="section" id="resume">
      <h2>Resume</h2>
      <a class="btn" href="resume.pdf" download>Download Resume (PDF)</a>
    </div>

    <div class="section" id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:kiranmaireddy@gmail.com">kiranmaireddy@gmail.com</a><br>
         LinkedIn: <a href="https://www.linkedin.com/in/kiranmaireddyvarakantam/" target="_blank">Connect with me</a></p>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Kiranmai Reddy. All Rights Reserved.</p>
  </footer>
</body>
</html>
