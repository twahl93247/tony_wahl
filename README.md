<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Tony Wahl</title>
  <style>
    /* Add basic styles for alignment */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    section {
      padding: 20px;
      margin: 20px auto;
      max-width: 800px;
    }
    h2 {
      text-align: center;
    }
    .bio-container {
      display: flex;
      align-items: center;
      flex-wrap: wrap;
      gap: 20px;
    }
    .bio-photo {
      max-width: 150px;
      border-radius: 50%;
    }
    .bio-text {
      flex: 1;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin: 10px 0;
    }
    .resume-link {
      color: blue;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <!-- About Me Section -->
  <section id="bio">
    <h2>About Me</h2>
    <div class="bio-container">
      <img src="your-photo.jpg" alt="Tony Wahl's Photo" class="bio-photo" />
      <div class="bio-text">
        <p>Hello, I'm Tony Wahl, an architectural designer with a passion for creating innovative and sustainable spaces. I hold a master's degree from the College of Architecture and Environmental Design, with a focus on historic preservation. My work combines modern design practices with an appreciation for the history and character of existing structures.</p>
        <p>Feel free to explore my projects and contact me if you're interested in working together.</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li><a href="project1.html">Project 1</a></li>
      <li><a href="project2.html">Project 2</a></li>
      <li><a href="project3.html">Project 3</a></li>
    </ul>
  </section>

  <!-- Resume Section -->
  <section id="resume">
    <h2>My Resume</h2>
    <p>Click the link below to view my resume:</p>
    <a href="Tony Wahl Resume 25_01.04.pdf" target="_blank" class="resume-link">View Resume</a>
  </section>
</body>
</html>
