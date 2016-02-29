
Critical Rendering Path Optimizations for Index.html
	Goal: Achieve PageSpeed score of above 90 on both mobile and desktop

Added 'Media = Print' to link href statement
Inline Style CSS file to Head section of index.html
Reduce .jpeg size.


Framerate Optimizations for Pizza.html
	Goal: Achieve consistent framerate of 60 fps when scrolling.  Time to resize pizzas is less than 5 ms per browser console.
	
In main.js, reduced var i, number of pizzas upon page load, from 200 to 30.
Replace querySelectorAll with more efficient getElementsByClassName
Optimize updatePosition function by creating an array containing the 5 needed values, and utilizing them in the subsequent for loop.






