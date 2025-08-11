<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pujitha Challagulla — Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0f1724;
      --card: #0b1220;
      --muted: #94a3b8;
      --accent: #7c3aed;
      --glass: rgba(255,255,255,0.04);
      --maxw: 1100px;
    }
    * { box-sizing: border-box; }
    html, body {
      margin: 0;
      height: 100%;
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: #e6eef8;
    }
    a { color: inherit; text-decoration: none; }
    .container { max-width: var(--maxw); margin: 0 auto; padding: 20px; }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 0;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
    }
    nav ul li { font-weight: 600; color: var(--muted); }
    .hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      align-items: center;
    }
    .hero-text h1 {
      font-size: 36px;
      margin: 0;
    }
    .hero-text p {
      color: var(--muted);
    }
    .card {
      background: var(--card);
      padding: 20px;
      border-radius: 10px;
    }
    .section-title {
      font-size: 28px;
      margin-top: 40px;
      margin-bottom: 20px;
      font-weight: 700;
    }
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 15px;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: var(--muted);
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <h2>Pujitha Challagulla</h2>
        <div style="color: var(--muted);">Full Stack Developer | 5+ Years Experience</div>
      </div>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#Education">Education</a></li>
          <li><a href="#experience">Experience</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#certifications">Certifications</a></li>
          <li><a href="#contact">Contact</a></li>
          
        </ul>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-text">
        <h1>Hi, I'm Pujitha</h1>
        <p>Full Stack Developer with 5+ years of experience in Java, J2EE, Spring Boot, Hibernate, and MVC
frameworks. Expertise in developing scalable web applications, RESTful APIs, and microservices.
Skilled in AngularJS, Angular, ReactJS, and developing SPAs. ProVicient in Oracle 11g, SQL, PL/SQL, and
Unix Shell scripting. Hands-on with WebLogic, Tomcat, Maven, Jenkins, Git, and Bitbucket.
Experienced in working with CI/CD, Agile, TDD, JUnit, and test automation tools like Selenium and
Cypress. Adept at engaging stakeholders, optimizing application performance, and delivering high-
quality solutions across distributed teams.</p>
      </div>
      <div class="card">
        <strong>Contact:</strong>
        <p>Email: puj7373@gmail.com</p>
        <p>Phone: +1-940-758-2905</p>
        <p><a href="https://www.linkedin.com/in/challagulla-pujitha-4b217a378/">LinkedIn</a></p>
      </div>
    </section>

    <section id="about">
      <h2 class="section-title">About</h2>
      <div class="card">
        Full Stack Developer with 5+ years of experience in Java, J2EE, Spring Boot, Hibernate, and modern JavaScript frameworks. Proficient in building single-page applications, scalable backend systems, and delivering high-quality software in Agile environments.
      </div>
    </section>

    <section id="skills">
      <h2 class="section-title">Technical Skills</h2>
      <div class="skills-grid">
        <div class="card">Languages: Java, JavaScript (ES6+), TypeScript, Python, C#, Ruby, Golang</div>
        <div class="card">Frameworks: Spring Boot, Hibernate, Angular, React, React Native, Redux</div>
        <div class="card">Databases: Oracle, MySQL, PostgreSQL, MongoDB, Cassandra, Redis</div>
        <div class="card">Cloud/DevOps: AWS, Azure, GCP, Docker, Kubernetes, Jenkins</div>
        <div class="card">Testing: Selenium, Cypress, JUnit, TestNG</div>
        <div class="card">Tools: Git, Maven, Jira, Figma, Tableau</div>
      </div>
    </section>
    <section id="Education">
      <h2 class="section-title">Education</h2>
      <div class="skills-grid">
        <div class="card">University of North Texas | Denton, Texas
Master of Science in Computer Science (GPA: 3.85/4.00)
Courses: Data Mining & Analysis, Software Engineering, Wireless Networks, Data Visualization,
Computer Security.
Graduate Teaching Assistantship: Data Visualization (Fall 2022 & Spring 2023)
Gudlavalleru Engineering College | India
Bachelor of Technology in Computer Science (GPA: 3.52/4.00)
Courses: Data Structures, Cloud Computing, Compiler Design, Software Engineering, C, C++, OOP,
Advanced data structure.</div>
        
      </div>
    </section>

    <section id="experience">
      <h2 class="section-title">Work Experience</h2>
      <div class="card">
        <h3>Virta Health — SDE (July 2023 – Present)</h3>
        <ul>
          <li> Built modular frontend applications using ReactJS, Redux, Webpack module federation, and
TypeScript, improving component reusability by 40%.</li>
<li> Refactored legacy Java code, reducing redundant processing by 40% via multithreading. Built
REST APIs and consumed data from Cassandra and MongoDB, enhancing data retrieval by 35%.</li>
<li> Automated test cases using Selenium and Cypress, improving test efficiency by 30%.</li>

<li>Leveraged Azure Blob Storage, SQL, and Databricks to streamline QA and performance validation
processes.
• Implemented monitoring with Dynatrace, Splunk, and Grafana to enhance system observability
and reduce debugging time by 25%.
• Developed and tested Mobile UI components in React Native for Android/iOS platforms. Actively
participated in scrum activities including stand-ups, code reviews, and bug triages.
• Optimized Spring Boot microservices, achieving 30% faster response times by implementing
caching with Redis and Ehcache, and lazy initialization. Streamlined data workflows and
improved data processing efficiency using Oracle SQL and PL/SQL, contributing to a 20% increase
in operational efficiency and a 15% reduction in operational costs.
• Implemented and maintained CI/CD pipelines using GitLab, Jenkins, Maven, and Git, automating
build, test, and deployment processes, which reduced deployment times by 40%.
• Automated data extraction, transformation, and loading tasks using Informatica ETL and Spring
Batch efficiently handles large volumes of data to improve data processing workflows.
• Developed REST APIs using Scala and Play framework to retrieve processed data from Cassandra
database. Worked with NoSQL databases like MongoDB to manage large data sets, which improved
data processing speed by 40%, enhancing data availability for end-users and reducing data
retrieval time by 35%</li>
        </ul>
      </div>
      <div class="card">
        <h3>Truist — Senior Software Engineer (June 2023 – March 2024)</h3>
        <ul>
          <li>Designed REST API using standard approach for all exposed services and Integrated GIT into
Jenkins to automate the code checkout process.</li>
          <li>Used Spring MVC Transaction Management, Spring/Hibernate Batch Transactions & Hibernate
cache concepts.</li>
          <li>Used a Microservice architecture with Spring Boot-based services interacting through a
combination of REST to build, test, and deploy identity Microservices.</li>
          <li>Developed the application on the NodeJS platform using JavaScript programming. Used NodeJS and
Bootstrap for developing web-enabled applications.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Tata Consultancy Services(CITI) — Senior Software Engineer (June 2023 – March 2024)</h3>
        <ul>
          <li>Integrated Spring Batch with Apache Kafka and Spring Boot for real-time data processing. Built
Angular components and hooks for reusable web applications. Implemented Selenium tests for
front-end components, improving the testing coverage, and reducing regression errors.</li>
          <li>Developed reusable Angular components and integrated Spring Boot microservices.
Implemented GraphQL endpoints and automated testing using Selenium and JUnit.</li>
          <li>Integrated Spring Batch with Spring Boot, RESTful APIs, and Apache Kafka to streamline data
processing workflows, improve scalability, and enhance real-time data integration. Worked
closely with product and engineering teams to drive the test automation strategy, ensuring
Features were released smoothly and on time.</li>
          
        </ul>
      </div>
    </section>
    

    <section id="projects">
      <h2 class="section-title">Projects</h2>
      <div class="project-grid">
        <div class="card">
          <strong>Warehouse Management System</strong>
          <p>Designed database schema, optimized queries, and triggers for performance.</p>
        </div>
        <div class="card">
          <strong>Housing Management System</strong>
          <p>Web-based app built with Java, Spring Boot, HTML, and CSS for property and lease management.</p>
        </div>
        <div class="card">
          <strong>NYC Street Tree Census Report</strong>
          <p>Dashboard in Tableau highlighting species health and issues based on census data.</p>
        </div>
      </div>
    </section>
    <section id="certifications">
  <h2 class="section-title">Certifications</h2>
  <div class="card">
    <a href="https://www.credly.com/users/pujitha-challagulla.c5250dc7/edit#credly">Prompt Design in Vertex AI</a><br>
    Certified Scrum Master<br>
    <a href="https://www.freecodecamp.org/certification/pujitha14/responsive-web-design">Web Design Specialist Certification</a><br>
  </div>
</section>


    <section id="contact">
      <h2 class="section-title">Contact</h2>
      <div class="card">
        Email: <a href="mailto:puj7373@gmail.com">puj7373@gmail.com</a><br>
        Phone: +1-940-758-2905<br>
        LinkedIn: <a href="https://www.linkedin.com/in/challagulla-pujitha-4b217a378/">Profile</a>
      </div>
    </section>

    <footer>
      &copy; 2025 Pujitha Challagulla — All rights reserved.
    </footer>
  </div>
</body>
</html>
