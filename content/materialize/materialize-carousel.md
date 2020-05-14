---
title: Materialize Carousel
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Materialize CSS provides a versatile way to create image and item carousels that are touch compatible making the mobile user experience smooth. 

```html
<div class="carousel">
  <a class="carousel-item" href="#one!"><img src="https://lorempixel.com/250/250/nature/1"></a>
  <a class="carousel-item" href="#two!"><img src="https://lorempixel.com/250/250/nature/2"></a>
  <a class="carousel-item" href="#three!"><img src="https://lorempixel.com/250/250/nature/3"></a>
  <a class="carousel-item" href="#four!"><img src="https://lorempixel.com/250/250/nature/4"></a>
  <a class="carousel-item" href="#five!"><img src="https://lorempixel.com/250/250/nature/5"></a>
</div>
 ``` 
 
## Initialization 

You can initialize the plugin using the following javascript –
 
```javascript
 document.addEventListener('DOMContentLoaded', function() {
    var elems = document.querySelectorAll('.carousel');
    var instances = M.Carousel.init(elems, options);
});
```

Materialize carousel can also be initialized using jQuery by the following javascript. Since jQuery is not a dependency of the Materialize CSS, it should be manually added. 

```javascript
$(document).ready(function() {
    $('.carousel').carousel();
});
```

## Default Options

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| duration | Number | 200 | Transition duration in milliseconds. |
| dist | Number | \-100 | Perspective zoom. If 0, all items are the same size. |
| shift | Number | 0 | Set the spacing of the center item. |
| padding | Number | 0 | Set the padding between non center items. |
| numVisible | Number | 5 | Set the number of visible items. |
| fullWidth | Boolean | false | Make the carousel a full width slider like the second example. |
| indicators | Boolean | false | Set to true to show indicators. |
| noWrap | Boolean | false | Don't wrap around and cycle through items. |
| onCycleTo | Function | null | Callback for when a new slide is cycled to. |

## Full Width Slider

Our carousel has a full width option that makes it into a simple and elegant image carousel. You can also have indicators that show up on the bottom of the slider.

```javascript
var instance = M.Carousel.init({
    fullWidth: true
});

// Or with jQuery

$('.carousel.carousel-slider').carousel({
    fullWidth: true
});
```