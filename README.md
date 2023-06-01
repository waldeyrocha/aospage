# aospage

Fantastic Animals
This is an HTML/CSS project that displays information about fantastic animals. It uses the AOS (Animate On Scroll) library to create fade animations when scrolling the page.

Project Structure
The project is structured as follows:

index.html: The main file that contains the HTML structure of the project.
css/style.css: CSS file that defines the visual style of the project.
dist/aos.css: AOS library CSS file, responsible for providing styles for the animations.
dist/aos.js: AOS library JavaScript file, responsible for controlling the animations.
Dependencies
The project depends on the following libraries:

AOS (Animate On Scroll): Library used to create fade animations when scrolling the page.
Make sure to include the dependencies correctly in your project.

Usage
To use this project, follow the instructions below:

Copy all the files to your project directory.
Include the CSS and JavaScript files in your HTML file:
html
Copy code
<link rel="stylesheet" type="text/css" href="css/style.css"
      
      Add the aos class to the elements you want to animate. For example:
html
Copy code
<nav class="menu" data-aos="fade-down">
  <!-- Menu content -->
</nav>
<section class="grid-section animais" id="animais" data-aos="fade-up" data-aos-duration="3000">
  <!-- Section content -->
</section>

Initialize the AOS library in your JavaScript file:
javascript
Copy code
AOS.init();

By following these steps, fade animations will be applied to the elements with the aos class as you scroll the page.

Contribution
This project is open to contributions. Feel free to create issues, send pull requests, or propose improvements
