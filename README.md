# Hello! -


I'm Tony Wahl, an architectural designerwith a passion for creating innovative and sustainable spaces. I hold a master's degree from the College of Architecture & Environmental Design, with a minor in historic preservation. 

## Projects
- Project 1 
- [Yesler Towers - Elevator 7](23_08.08%20PHASE%203%20PERMIT%20REVISION%20-%20ELEVATOR%207.pdf)
- Project 3

## Resume 

[View Resume](Tony%20Wahl%20Resume%2025_01.08.pdf)


## Contact
[twahl93@gmail.com](mailto:twahl93@gmail.com)

## Slideshow
<section id="slideshow">
  <h2>Project Slideshow</h2>
  <div class="slideshow-container">
    <div class="slides">
      <img src="YT_PHOTO 1.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
    <div class="slides">
     <img src="YT_PHOTO 2.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 3.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 4.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 5.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 6.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 7.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 8.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 9.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 10.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 11.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 12.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
   <div class="slides">
     <img src="YT_PHOTO 13.jpg" style="width:100%">
      <div class="text">Yesler Towers - Seattle, WA Description</div>
    </div>
    <!-- Add more slides as needed -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>
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
