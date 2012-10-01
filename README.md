Starlet
=======


Starlet is a small set of CSS classes and some javacript that allow you to create grid layouts that are fluid and each grid element is square and has no margin. 

Usage
-----

Include the starlet CSS file along with jQuery and whatever else your page requires (Starlet works great with Bootstrap). There's also some Javascript that must be executed when your page loads (this will be moved to a plugin soon).

In your HTML, add the starlet-row class to each row and the appropriate class to your column cells:
``` html
<div class="starlet-row">
  <div class="starlet-sixth">
    <a href="http://github.com"><img src="example-images/1.jpg"></a>
  </div>
  <div class="starlet-sixth">
    <img src="example-images/2.jpg">
  </div>
  <div class="starlet-sixth">
    <img src="example-images/3.jpg">
  </div>
  <div class="starlet-sixth">
    <img src="example-images/4.jpg">
  </div>
  <div class="starlet-sixth">
    <img src="example-images/5.jpg">
  </div>
  <div class="starlet-sixth">
    <img src="example-images/6.jpg">
  </div>
</div>
```

