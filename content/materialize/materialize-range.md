---
title: Materialize Range	
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Add a range slider for values with a wide range. This one is set to be a number between 0 and 100. We have two different types of sliders. nouiSlider is a 3rd party plugin which we've modified. To use the noUiSlider, you will have to manually link the nouislider.css and nouislider.js files located in the extras folder.

## noUiSlider

See noUiSlider's official documentation here to see a variety of slider options



You can easily vertically center things by adding the class valign-wrapper to the container holding the items you want to vertically align.

```html
<div id="test-slider"></div>
 ``` 

```javascript
var slider = document.getElementById('test-slider');
noUiSlider.create(slider, {
    start: [20, 80],
    connect: true,
    step: 1,
    orientation: 'horizontal', // 'horizontal' or 'vertical'
    range: {
        'min': 0,
        'max': 100
    },
    format: wNumb({
        decimals: 0
    })
});
```

## HTML5 Range

```html
<form action="#">
  <p class="range-field">
    <input type="range" id="test5" min="0" max="100" />
  </p>
</form>
```

These classes are for horizontally aligning content: .left-align, .right-align and .center-align.

```html
<div>
  <h5 class="left-align">This should be left aligned</h5>
</div>
<div>
  <h5 class="right-align">This should be right aligned</h5>
</div>
<div>
  <h5 class="center-align">This should be center aligned</h5>
</div>
```


