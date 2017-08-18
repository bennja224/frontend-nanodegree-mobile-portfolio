Web Optimization - Pizza

Compressed imgs:  pizzeria1.jpg and profilepic.jpg

Getting Rid of Jank:
Optimized main.js
    Resized Pizza's - removed the determinDX
    Reduce rendering time -  moved calcs from within loops to get them assigned once
	Reduce rendering time - reduced the # of sliding pizzas on the screen from 200.  


	
Update style.css
font-family from Helvetica to Open Sans

Update index.html
  updated to async 
  removed:  <!-- Hmm, what is the impact of web fonts on speed? Measure it... -->
    <script async src="//fonts.googleapis.com/css?family=Open+Sans:400,700"></script>
  moved the GoogleAnalyticsObject script to the bottom