Web Optimization - Pizza

Resized imgs:  pizzeria.jpg and profilepic.jpg

Getting Rid of Jank:
Optimized main.js
    Resized Pizza's - removed the determinDX
    Reduce rendering time -  moved calcs from within loops to get them assigned once
	Reduce rendering time - reduced the # of sliding pizzas on the screen from 200.  


Improve PageSpeed score:	
Update style.css
font-family from Helvetica to Open Sans

Update index.html
  updated to async 
  removed:  <!-- Hmm, what is the impact of web fonts on speed? Measure it... -->
    <script async src="//fonts.googleapis.com/css?family=Open+Sans:400,700"></script>
  moved the GoogleAnalyticsObject script to the bottom
  removed <link href="css/style.css" rel="stylesheet"> and placed CSS inline
  added media query to css/print/css
  
  
 How to run:
 located on https://github.com/bennja224/frontend-nanodegree-mobile-portfolio
 Access index.html to retrieve url for PageSpeed
 In the Views folder access pizza.html to open and check the performance using dev tools in Chrome.