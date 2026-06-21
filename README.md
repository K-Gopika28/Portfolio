<!DOCTYPE html>
<html>
<head>
  <title>K Gopika | Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  
<!-- Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

</head>
<body>

<nav>
  <h2>K Gopika</h2>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#journey">Journey</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<section class="hero">
  <div class="hero-text">
    <h1>Hi, I am <span>K Gopika</span></h1>
    <h3>Computer Science Engineering Student</h3>
    <p>Interested in Software Development and Artificial Intelligence.</p>
    <a class="btn" href="#projects">View Projects</a>
  </div>
  <img src="profile.jpg" class="hero-img" alt="Profile Picture">
</section>

<section id="about" class="card">
  <h2>About Me</h2>
  <p>
   Hi, I'm K Gopika, a B.Tech Computer Science and Engineering student passionate about technology, software development, and Artificial Intelligence. I enjoy learning new skills, exploring emerging technologies, and taking part in workshops and certification programs. I am eager to grow as a software developer and contribute to innovative projects while continuously expanding my knowledge in AI and computer science.
  </p>
  <p>
    Beyond academics, I have a strong passion for reading, writing, and exploring the arts. I enjoy travelling, experiencing diverse cultures, and embracing opportunities to learn new things. These experiences broaden my perspective and inspire me to approach technology with creativity, curiosity, and an open mind.
  </p>
  <p>I am passionate about Software Development and artificial intelligence, IoT, and cloud computing. I enjoy developing web-based projects, designing interactive portfolios, and learning new technologies that enhance my skills. My goal is to become a well-rounded engineer who combines technical excellence with innovation to create impactful solutions.
  </p>
</section>



<section id="skills" class="card">
  <h2>Skills</h2>
  <div class="skills-grid">
    <div class="skill"><i class="fab fa-python"></i><p>Python</p></div>
    <div class="skill"><i class="fab fa-java"></i><p>C programming</p></div>
    <div class="skill"><i class="fab fa-html5"></i><p>HTML</p></div>
    <div class="skill"><i class="fab fa-css3-alt"></i><p>CSS</p></div>
    <div class="skill"><i class="fab fa-js"></i><p>JavaScript</p></div>
  </div>
</section>


<section id="projects" class="card">
  <h2>Projects</h2>
  <div class="projects">

    <!--My Portfolio Website -->
    <div class="project" data-title="My Portfolio Website– Project" data-desc="Based on HTML,CSS,Javascript.">
      <i class="fas fa-tint project-icon"></i>
      <h3>My Portfolio Website – Project</h3>
      <p>Based on HTML,CSS,Javascript.</p>
    </div>
</section>


<section id="journey" class="card">
  <h2>My Project Journey</h2>
  <div class="timeline">
    <div class="timeline-item">
      <div class="timeline-icon"><i class="fas fa-globe"></i></div>
      <div class="timeline-content">
        <h3>First Project – Webpage</h3>
        
      </div>
    </div>
<div class="timeline-item">
      <div class="timeline-icon"><i class="fas fa-lightbulb"></i></div>
      <div class="timeline-content">
        <h3>My Portfolio Website –  Project</h3>
        <p>Designed an HTML based Portfolio for an innovative project.</p>
      </div>
    </div>
   
    </div>
  </div>
</section>
<section id="achievements" class="card">
  <h2>Achievements</h2>
  <div class="timeline">
    <div class="timeline-item" data-title="NASSCOM Digit Edge 101 Gold Medal" data-desc="Awarded for outstanding performance in digital edge program.">
      <div class="timeline-icon"><i class="fas fa-medal"></i></div>
      <div class="timeline-content">
        <h3>NASSCOM Digial Edge 101 Gold Medal</h3>
        <p>Recognized for Silver Medal.</p>
      </div>
    </div>
    <div class="timeline-item" data-title="S1 SGPA 9.23" data-desc="Achieved SGPA of 9.23 in Semester 1.">
      <div class="timeline-icon"><i class="fas fa-graduation-cap"></i></div>
      <div class="timeline-content">
        <h3>S1 SGPA 9.23</h3>
        <p>Strong academic performance in first semester.</p>
      </div>
    </div>
       
    
</section>

<section id="certificates" class="card">
  <h2>Certificates & Workshops</h2>
  <div class="cert-gallery">
    <div class="cert" data-title="Modern Ai Systems" data-desc="Modern AI Systems.">
      <i class="fas fa-file-alt"></i>Course
    </div>
    <div class="cert" data-title="Course" data-desc="Web Development-My Captain.">
      <i class="fas fa-chalkboard-teacher"></i>Course
    </div>
   
    <div class="cert" data-title="NASSCOM Certificate" data-desc="NASSCOM Digit Edge 101 recognition.">
      <i class="fas fa-award"></i> NASSCOM Certificate
    </div>
  </div>
</section>


<section class="contact-card" id="contact">
  <div class="contact-header">
    <i class="fas fa-user-circle"></i>
    <h2>Contact Me</h2>
  </div>

  <p><i class="fas fa-envelope"></i>gopika2822007@gmail.com</p>
  <p><i class="fas fa-phone"></i> +91 8590847505</p>
  <p><i class="fas fa-map-marker-alt"></i> Kollam, Kerala, India</p>

  <div class="social-links">
    <a href="https://www.linkedin.com/in/k-gopika28" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-linkedin"></i> LinkedIn
    </a>
    <a href="https://github.com/K-Gopika28" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-github"></i> GitHub
    </a>
  </div>

 
</section>



<!-- Popup Modal -->
<div id="modal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <h2 id="modal-title"></h2>
    <p id="modal-desc"></p>
  </div>
</div>


</body>
</html>
