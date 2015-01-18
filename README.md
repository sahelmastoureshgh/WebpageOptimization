Website Performance Optimization portfolio project

Here how I optimize this webpage

Created webpage in github with following url

   http://sahelmastoureshgh.github.io/WebpageOptimization/
Compress images

I compressed images by using following tools

google+
http://jpeg-optimizer.com/
https://tinypng.com/
Compress css and using media query

I compressed css file by using TextMate compress format I moved style.css in index.html, project-2048.html, project-mobile.html and project-pref.html as following

<script>
   var cb = function() {
       var l = document.createElement('link'); l.rel = 'stylesheet';
       l.href = 'css/style.css';
       var h = document.getElementsByTagName('head')[0]; h.parentNode.insertBefore(l, h);
   };
   var raf = requestAnimationFrame || mozRequestAnimationFrame ||
   webkitRequestAnimationFrame || msRequestAnimationFrame;
   if (raf) raf(cb);
   else window.addEventListener('load', cb);
I used media attribute as following

<link href="css/print.css" rel="stylesheet" media=“print">
Using async tag for javascript files and move analytic google part to separate js file

<script async src = "js/analytic.js" ></script>
<script async src="http://www.google-analytics.com/analytics.js"></script>
<script async src="js/perfmatters.js “></script>
Using viewport tag in pizza.html

Optimize main.js file to reach 60fps
