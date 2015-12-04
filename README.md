
#### Getting started

Note:  code for this project is hosted in GitHub repository https://github.com/dazmera/Web-Optimization-_Udacity-P4.git
	  Application can be accessed by cloning the github repositary at the above address.   
	   
#### Part 1: Optimize PageSpeed Insights score for index.html

Steps taken:

1- Added CSS Information to Index.html and removed link to style.css file
2- Added async to google analytics Java Script
3- Inlined print css
4- Inlined javascript from perfmatters
5- Added height/width attributes to pictures, alt text
6- Removed Google Font from index.html added font to CSS on page.
7- Used Kraken to minify profile pic and pizzeria picture

#### Part 2: Optimize Frames per Second in pizza.html

Steps taken:

1- Cached Math.sin calculation outside the for loop in
updatePositions(); 
2- Cached querySelectorAll() and simplified newWidth
calculation in changePizzaSizes();
3- Use screen height to calculate number of pizzas to display rather than 
having it hard coded to 200 pizzas (see inline comments - line 522)



 - minified the main.js file and made pizza.html point to that file.


#### Resources

https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path?hl=en
https://kraken.io/web-interface
http://jscompress.com/



#### Files used and modified in this project

readme.md
index.html (optimized CRP for PageSpeed)
project-2048.html
project-mobile.html
project-webperf.html
css/print.css (added media print so only used for printing)
css/style.css (inlined this css, removed link to this page)
img/2048.png
img/cam_be_like.jpg
img/mobilewebdev.jpg
img/profilepic.jpg (minified with Kraken)
views/pizza.html (modified to point to minified main.js)
views/css/bootstrap-grid.css
views/css/style.css
views/images/pizza-slider.png
views/images/pizza.png
views/images/pizzeria.jpg (minified with Kraken)
views/js/main.js (optimized for web performance)
views/js/main.min.js (minified version for improved performance)







