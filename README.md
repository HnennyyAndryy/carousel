# Breeze Carousel
Modification of carousel initially created by Max Rolon (http://www.barrelny.com/blog/building-a-jquery-slideshow-plugin-from-scratch/)

## Installation

Load jQuery(2.1.4+) and include Breeze Carousel plugin files

```html
<!-- stylesheet -->
<link rel="stylesheet" href="breeze-carousel.css">
  
<!-- js plugin -->
<script src="breeze-carousel.js"></script>
```

## Usage

You can add Breeze Carousel on your page like that : 

```html
	<div class="carousel carousel-autoresize">
    		<div class="captions">
          		<div class="caption active">First</div>
          		...
          		<div class="caption">Last</div>
		    </div>
        	<div class="inner">
      			<div class="slide active" data-image="image-first-url"></div>
      			...
     			<div class="slide" data-image="image-last-url"></div>
    		</div>
   		    <div class="arrow arrow-left"></div>
    		<div class="arrow arrow-right"></div>
  	</div>
```
Note that you should add **_'carousel-autoresize'_** class to make carousel changing its height automatically (keeping aspect ratio of every image). Otherwise you should explicitly set height either on carousel's container or on carousel's style attribute.  

Also, you can use **_'carousel-autofix'_** class. It will set carousel's height corresponding to the most 'slender' image. Therefore, height won't be changing on every slide transition. 
