<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tejaswini Chandravamsam | Tech Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; scroll-behavior: smooth; }
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(120deg, #0e0e0e 0%, #1a1a1a 100%);
      color: #f5f5f5;
      padding: 0 2rem;
      position: relative;
      overflow-x: hidden;
    }
    body::before {
      content: "";
      position: absolute;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle, rgba(0,255,255,0.2) 0%, transparent 70%),
                  radial-gradient(circle, rgba(57,255,20,0.1) 10%, transparent 60%);
      top: 0;
      left: 0;
      pointer-events: none;
      animation: pulse 15s infinite ease-in-out;
    }
    @keyframes pulse {
      0%, 100% {
        transform: scale(1);
        opacity: 0.8;
      }
      50% {
        transform: scale(1.05);
        opacity: 1;
      }
    }
    header { text-align: center; padding: 3rem 0 2rem 0; animation: fadeIn 1s ease-in-out; position: relative; z-index: 1; }
    nav {
      background-color: rgba(26, 26, 26, 0.9);
      padding: 1rem;
      display: flex;
      justify-content: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      backdrop-filter: blur(5px);
    }
    nav a {
      color: #00ffff;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #39ff14;
    }
    h1 { font-size: 2.5rem; font-weight: 700; color: #00ffff; }
    h2 { margin-top: 2rem; font-size: 1.75rem; color: #00ced1; animation: slideIn 0.8s ease-in-out; }
    p, li { font-size: 1rem; margin: 0.5rem 0; line-height: 1.6; }
    section {
      margin-bottom: 3rem;
      opacity: 0;
      transform: translateY(30px);
      animation: fadeUp 1s ease-out forwards;
      animation-delay: 0.3s;
      padding-top: 3rem;
      position: relative;
      z-index: 1;
    }
    ul { margin-left: 1.5rem; }
    a { color: #1e90ff; text-decoration: none; }
    a:hover { text-decoration: underline; }
    .contact p, .contact a { margin-bottom: 0.5rem; display: block; color: #aaa; }
    .highlight { color: #39ff14; font-family: 'Fira Code', monospace; }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideIn {
      from { opacity: 0; transform: translateX(-40px); }
      to { opacity: 1; transform: translateX(0); }
    }

    @keyframes fadeUp {
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <nav>
    <a href="#summary">About</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#projects">Projects</a>
    <a href="#certifications">Certifications</a>
    <a href="#education">Education</a>
  </nav>

  <header>
    <h1>&lt; Tejaswini Chandravamsam /&gt;</h1>
    <div class="contact">
      <p>📍 <span class="highlight">Houston, Texas</span></p>
      <p>📞 <span class="highlight">+1-281-898-2977</span></p>
      <a href="mailto:tejaswinichandravamsam@gmail.com">📧 tejaswinichandravamsam@gmail.com</a>
    </div>
  </header>

  <section id="summary">
    <h2>🚀 Professional Summary</h2>
    <p>I am a <span class="highlight">Software Engineer & Application Analyst</span> with over 4 years of experience in <strong>enterprise application support</strong>, <strong>system optimization</strong>, and <strong>production troubleshooting</strong>. With a robust background in <span class="highlight">Java</span>, <span class="highlight">SQL</span>, and <span class="highlight">API integrations</span>, I’ve contributed to mission-critical projects for clients like Toyota Motors North America. Passionate about improving system performance, automating manual processes, and delivering clean, scalable solutions.</p>
  </section>

  <section id="skills">
    <h2>🛠️ Technical Skills</h2>
    <ul>
      <li><strong>Languages:</strong> C, C++, Java, Python, R, SQL, JavaScript, MATLAB</li>
      <li><strong>Web Development:</strong> Angular, HTML, CSS, Bootstrap, REST APIs</li>
      <li><strong>DevOps & Tools:</strong> AWS, Git, DataDog, Kibana, ServiceNow, MongoDB</li>
      <li><strong>Frameworks:</strong> Microservices, Agile, JIRA</li>
      <li><strong>System:</strong> Linux Shell, Windows OS, SDLC, CI/CD</li>
      <li><strong>Soft Skills:</strong> Team Leadership, Communication, Analytical Thinking</li>
    </ul>
  </section>

  <section id="experience">
    <h2>💼 Work Experience</h2>
    <p><strong class="highlight">ProdigitalWorx PVT Limited</strong> – <em>Project Support Analyst (Nov 2020 - Dec 2022)</em></p>
    <ul>
      <li>Maintained production systems for <strong>Toyota Motors North America</strong>, improving uptime by 15%.</li>
      <li>Resolved critical issues using root cause analysis and system-level debugging.</li>
      <li>Managed AWS S3/Glacier storage for optimized backup and retrieval.</li>
      <li>Integrated API enhancements, led documentation for SOX compliance.</li>
    </ul>
    <p><strong class="highlight">Freelance Developer</strong> – <em>Software Engineer (Jan 2023 - Present)</em></p>
    <ul>
      <li>Provided ongoing support for enterprise systems on-demand, enhancing reliability and API coverage.</li>
      <li>Streamlined bug tracking, release processes, and integrated version control using Git.</li>
    </ul>
    <p><strong class="highlight">University of Houston-Clear Lake</strong></p>
    <ul>
      <li>Graduate Assistant – Supported data analytics research and statistical modeling.</li>
      <li>Orientation Leader – Led onboarding events for new students.</li>
      <li>AI Summer Camp Instructor – Taught Machine Learning to high schoolers.</li>
    </ul>
    <p><strong class="highlight">Ridhan Technologies</strong> – <em>Frontend Developer Intern</em></p>
    <ul>
      <li>Created responsive UIs using HTML/CSS/JS. Implemented Angular Material components.</li>
    </ul>
  </section>

  <section id="projects">
    <h2>📁 Projects</h2>
    <ul>
      <li><strong>DSP-CPU Command Interface:</strong> Built real-time signal processing software using TMS320C6000 DSP.</li>
      <li><strong>SCRUM-based Agile Website:</strong> Developed a tutorial web page explaining Agile with QA and iterative improvements.</li>
      <li><strong>Disease Correlation (ML):</strong> Developed predictive models for disease using health datasets and classification algorithms.</li>
      <li><strong>Himalaya Life Line:</strong> Built customer data dashboard using Angular and REST APIs, deployed on secure stack.</li>
    </ul>
  </section>

  <section id="certifications">
    <h2>🏅 Certifications</h2>
    <ul>
      <li>MATLAB, Python & Deep Learning, Machine Learning, Data Science, Cybersecurity, Android, Java</li>
    </ul>
  </section>

  <section id="education">
    <h2>🎓 Education</h2>
    <ul>
      <li><strong>MS – Software Engineering</strong> | University of Houston-Clear Lake | GPA: 3.15/4.0</li>
      <li><strong>B.Tech – Computer Science</strong> | Avanthi Institute of Engineering & Technology | GPA: 7.49/10</li>
    </ul>
  </section>
</body>
</html>
