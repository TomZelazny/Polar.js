# Polar.js
Place html elements using polar coordinates
--------------------------------------------------

A couple of fiddles that mess with the concept:

<ul>
<li><a href='https://jsfiddle.net/TomZelazny/byp6hubL/'>placing elements at angle+radius</a>
<li><a href='https://jsfiddle.net/TomZelazny/osvyj71j/'>placing elements at the border of root</a>
<li><a href='https://jsfiddle.net/TomZelazny/0y1esLre/'>basic structure of the polar class</a>
</ul>

<p>I think the interface should look like this:</p>
<code>
  Polar("css-element") // returns PolarBaseElement\n
  .appendElement("html/domElement") // returns polarOrbitElement (adds to polarBase children)\n
  .placeAt("deg","radius/border") // return polarOrbitElement\n
  .animate("cssAnimation") // return polarOrbitElement\n
  .show(); // return polarOrbitElement\n
</code>

this is probably helpful:
<ul>
<li>http://benice-equation.blogspot.co.il/2016/10/equation-of-rounded-rectangle.html</li>
<li>http://math.stackexchange.com/questions/1649714/whats-the-equation-for-a-rectircle-perfect-rounded-corner-rectangle-without-s</li>
</ul>
