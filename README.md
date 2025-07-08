<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SAI SURYA TEJASWINI CHANDRAVAMSAM | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; scroll-behavior: smooth; }
    body {
      font-family: 'Inter', sans-serif;
      background: #fdfbfb;
      color: #222;
      padding: 0;
      overflow-x: hidden;
    }
    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle, rgba(0, 128, 255, 0.1) 10%, transparent 11%),
                  radial-gradient(circle, rgba(0, 255, 128, 0.1) 10%, transparent 11%);
      background-size: 80px 80px;
      animation: moveBg 60s linear infinite;
      z-index: -1;
    }
    @keyframes moveBg {
      from { background-position: 0 0, 0 0; }
      to { background-position: 1000px 1000px, -1000px -1000px; }
    }
    .slide {
      height: 100vh;
      padding: 4rem 2rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      opacity: 0;
      transform: translateY(40px);
      animation: slideIn 1s forwards;
    }
    .slide:nth-child(even) {
      background-color: #ffffffcc;
    }
    h1 {
      font-size: 2.5rem;
      color: #005c99;
      font-family: 'Fira Code', monospace;
    }
    h2 {
      font-size: 2rem;
      color: #007acc;
      margin-bottom: 1rem;
    }
    p, li {
      font-size: 1rem;
      max-width: 800px;
      line-height: 1.6;
      margin-bottom: 0.5rem;
    }
    ul {
      text-align: left;
      max-width: 800px;
    }
    li {
      margin-left: 1.5rem;
    }
    @keyframes slideIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="slide">
    <h1>SAI SURYA TEJASWINI CHANDRAVAMSAM</h1>
    <p>📍 300 Cyberonics Blvd, Houston, Texas-77058</p>
    <p>📞 +1-281-898-2977</p>
    <p>📧 tejaswinichandravamsam@gmail.com</p>
  </div>

  <div class="slide">
    <h2>Professional Summary</h2>
    <p>Application Analyst and Software Engineer with 4+ years of experience in application support, production troubleshooting, and system optimization. Skilled in Java, SQL, and API integrations with proven ability to maintain enterprise applications and collaborate with cross-functional teams. Experienced in SDLC, agile methodologies, and supporting mission-critical systems for global clients.</p>
  </div>

  <div class="slide">
    <h2>Work Experience – Freelance Software Engineer (Jan 2023 - Present)</h2>
    <ul>
      <li>Continued collaboration with ProdigitalWorx supporting TMNA systems.</li>
      <li>Performed system testing, performance tuning, and incremental deployments.</li>
      <li>Resolved API issues and documented changes for auditing and compliance.</li>
    </ul>
  </div>

  <div class="slide">
    <h2>Work Experience – ProdigitalWorx PVT Limited (Nov 2020 - Dec 2022)</h2>
    <ul>
      <li>Provided production support for Toyota Motors North America (TMNA), ensuring system stability and adherence to SDLC.</li>
      <li>Resolved incidents, managed API integrations, and documented activities for audits.</li>
      <li>Performed root cause analysis, debugging, and implemented enhancements.</li>
      <li>Supported enterprise applications from design to deployment.</li>
      <li>Collaborated with stakeholders to troubleshoot and optimize workflows.</li>
      <li>Led workflow improvements that reduced issue resolution time by 15%.</li>
      <li>Managed cloud storage using AWS S3 and Glacier.</li>
      <li>Contributed to documentation for compliance and improved service delivery.</li>
    </ul>
  </div>

  <div class="slide">
    <h2>University Roles – University of Houston-Clear Lake</h2>
    <ul>
      <li>Graduate Assistant (Sep 2023 - Aug 2024): Supported data collection and analysis for analytical projects.</li>
      <li>Orientation Leader (Apr 2023 - Aug 2023): Guided new students and organized orientation sessions.</li>
      <li>AI Summer Camp Instructor (June 2023): Taught AI/ML concepts to high school students under Dr. Soma Datta.</li>
    </ul>
  </div>

  <div class="slide">
    <h2>Internship – Ridhan Technologies (May 2019 - Jul 2019)</h2>
    <ul>
      <li>Developed and implemented web apps using HTML, CSS, and JavaScript.</li>
      <li>Enhanced UX by optimizing UI components and debugging frontend issues.</li>
    </ul>
  </div>

  <div class="slide">
    <h2>Technical Skills</h2>
    <ul>
      <li>Programming Languages: C, C++, Java, Python, R, SQL, JavaScript, MATLAB</li>
      <li>Web Development: Angular, HTML, CSS, Bootstrap</li>
      <li>Tools & Technologies: AWS, Git, JIRA, MongoDB, DataDog, Kibana, ServiceNow, REST APIs, Microservices</li>
      <li>Machine Learning & Data Science: Deep Learning, AI, Data Analysis, Cybersecurity</li>
      <li>Software Development & Testing: Agile, Software Architecture, Production Support</li>
      <li>Soft Skills: Leadership, Problem Solving, Communication, Teamwork, Presentation Skills</li>
      <li>Productivity Tools: MS Office Suite</li>
      <li>Scripting & System: Linux Shell Scripting, Windows OS, SDLC, System Troubleshooting</li>
      <li>Platforms: IBM WebSphere (familiarity), Open Source tools, Cloud-based application deployment</li>
    </ul>
  </div>

  <div class="slide">
    <h2>Education</h2>
    <ul>
      <li>Master of Science, Software Engineering – University of Houston-Clear Lake (2023 - 2024), GPA: 3.15/4.0</li>
      <li>Bachelor of Technology, Computer Science & Engineering – Avanthi Institute of Engineering and Technology, GPA: 7.49/10</li>
    </ul>
  </div>

  <div class="slide">
    <h2>Projects</h2>
    <ul>
      <li><strong>DSP and CPU Interface (Command-Based)</strong>: Real-time signal processing between TMS320C6000 DSP and CPU.</li>
      <li><strong>Agile SCRUM Website</strong>: Interactive site detailing Agile practices and iterative testing improvements.</li>
      <li><strong>Correlation of Diseases</strong>: ML-based predictive model for heart disease and cancer using health data.</li>
      <li><strong>Himalaya Life Line Web Page</strong>: Secure Angular + REST app for customer data management.</li>
    </ul>
  </div>

  <div class="slide">
    <h2>Certifications</h2>
    <ul>
      <li>MATLAB Onramp: MathWorks (2023)</li>
      <li>Python & Deep Learning Essential Bootcamp: LetsUpgrade (2022)</li>
      <li>Machine Learning Bootcamp for Beginners: Learn Mall (2021)</li>
      <li>Python for Data Engineers: AntWalk (2021)</li>
      <li>Python with ML Fundamentals: Perfect eLearning (2021)</li>
      <li>Python Programming Language: Cursa (2020)</li>
      <li>Data Science Foundation: Apponix Technologies (2020)</li>
      <li>Android Development: Udemy (2020)</li>
      <li>JAVA Programming Language: Datapro (2019)</li>
      <li>Android Workshop: Subrains Technology (2018)</li>
      <li>Cyber Security Essentials: Cisco Networking Academy (2018)</li>
    </ul>
  </div>
</body>
</html>
