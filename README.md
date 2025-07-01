<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sung Lee | Business Analyst & Technical Writer</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #0D3B66;
      --accent: #FAF0CA;
      --highlight: #F4D35E;
      --dark: #1E1E1E;
      --white: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--white);
      color: var(--dark);
      line-height: 1.6;
    }

    header {
      background-color: var(--primary);
      color: var(--white);
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    nav {
      background-color: var(--highlight);
      padding: 1rem;
      text-align: center;
    }

    nav a {
      color: var(--dark);
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      color: var(--primary);
      margin-bottom: 1rem;
      border-bottom: 2px solid var(--highlight);
      display: inline-block;
    }

    .profile-img {
      width: 180px;
      border-radius: 50%;
      margin-bottom: 1rem;
    }

    .about, .skills, .projects, .contact {
      background-color: var(--accent);
      border-radius: 10px;
      padding: 2rem;
      margin-bottom: 2rem;
    }

    ul {
      list-style: none;
    }

    ul li::before {
      content: "✓ ";
      color: var(--primary);
    }

    footer {
      background-color: var(--primary);
      color: var(--white);
      text-align: center;
      padding: 2rem 1rem;
    }

    a.button {
      display: inline-block;
      background: var(--primary);
      color: white;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 1rem;
    }

    a.button:hover {
      background: #092c4c;
    }
  </style>
</head>
<body>

  <header>
    <img src="Profile1.jpg" alt="Sung Lee Headshot" class="profile-img">
    <h1>Hi, I'm Sung Lee</h1>
    <p>Business Analyst & Technical Writer | Bristow, VA | IRS MBI Clearance</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>👋 About Me</h2>
    <p>I am a Business Analyst and Technical Writer with expertise in system documentation, Agile workflows, and client communications. With a strong foundation in both technical analysis and writing, I bring clarity and structure to complex business requirements.</p>
  </section>

  <section id="skills" class="skills">
    <h2>🧠 Core Skills</h2>
    <ul>
      <li>Business Process Modeling (BPMN)</li>
      <li>Agile/Scrum Facilitation</li>
      <li>Technical Documentation (SOPs, User Guides, APIs)</li>
      <li>Tools: Jira, Confluence, MS Visio, ServiceNow</li>
      <li>Client-facing Communication & Stakeholder Engagement</li>
    </ul>
  </section>

  <section id="projects" class="projects">
    <h2>🚀 Projects</h2>
    <ul>
      <li><strong>IRS Modernization:</strong> Led requirement sessions and delivered technical documents under federal compliance standards.</li>
      <li><strong>System Integration Docs:</strong> Developed end-to-end SOPs and system architecture diagrams.</li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h2>📬 Contact</h2>
    <p>Let's connect and discuss how I can help your team grow.</p>
    <p>Email: <a href="mailto:sung.m.lee23@gmail.com">sung.m.lee23@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/sungmlee" target="_blank">linkedin.com/in/sungmlee</a></p>
    <a class="button" href="Sung_Lee_Resume_New_2025.pdf" download>📄 Download My Resume</a>
  </section>

  <footer>
    <p>&copy; 2025 Sung Lee. All rights reserved.</p>
  </footer>

</body>
</html>