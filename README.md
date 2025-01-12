<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio - Tony Wahl</title>
  <style>
    /* Basic styling for the body */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
    }

    header {
      padding: 20px;
      background-color: #ffffff;
    }

    header h1 {
      margin: 0;
      font-size: 1.5em;
      text-align: left;
    }

    section {
      padding: 20px;
      margin: 20px;
    }

    h2 {
      font-size: 1.4em;
      margin-bottom: 10px;
    }

    .bio-container {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    li {
      margin: 10px 0;
    }

    a {
      color: blue;
      text-decoration: underline;
    }

    /* Responsive Design */
    @media (max-width: 600px) {
      body {
        font-size: 16px;
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>About Me</h1>
  </header>

  <!-- About Me Section -->
  <section id="bio">
    <div class="bio-container">
      <p>Hello, I'm Tony Wahl, an architectural designer with a passion for creating innovative and sustainable spaces. I hold a master's degree from the College of Architecture and Environmental Design, with a focus on historic preservation. My work combines modern design practices with an appreciation for the history and character of existing structures.</p>
      <p>Feel free to explore my projects and contact me if you're interested in working together.</p>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li><a href="project1.html">- Yesler Towers- floor plans</a></li>
      <li><a href="project2.html">- Yesler Towers- Elevator 7</a></li>
      <li><a href="project3.html">Project 3</a></li>
    </ul>
  </section>

  <!-- Resume Section -->
  <section id="resume">
    <h2>My Resume</h2>
    <p>Click the link below to view my resume:</p>
    <a href="Tony Wahl Resume 25_01.08.pdf" target="_blank">View Resume</a>
  </section>
    <script>
    let slideIndex = 1;
    showSlides(slideIndex);

    function plusSlides(n) {
      showSlides(slideIndex += n);
    }

    function showSlides(n) {
      let i;
      let slides = document.getElementsByClassName("slides");
      if (n > slides.length) {slideIndex = 1}
      if (n < 1) {slideIndex = slides.length}
      for (i = 0; i < slides.length; i++) {
          slides[i].style.display = "none";
      }
      slides[slideIndex-1].style.display = "block";
    }
  </script>
</body>
</html>
