---
title: Materialize CSS Transitions	
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Materialize CSS comes with custom CSS animation classes with necessary styles that makes transitioning content such as scaling easy, without the need of any javascript. 

## Scale

To scale in and out elements, first add the base transition class `scale-transition` to the element. Then you can add the class `scale-out` to scale the element down until it is hidden and add the class `scale-in` to scale the element up until it is visible.

```html
<!-- Scaled in -->
<a id="scale-demo" href="#!" class="btn-floating btn-large scale-transition">
<i class="material-icons">add</i>
</a>
<!-- Scaled out -->
<a id="scale-demo" href="#!" class="btn-floating btn-large scale-transition scale-out">
<i class="material-icons">add</i>
</a>
```

| CSS Class | Description                                |
|-----------|--------------------------------------------|
| scale-transition  | Base transition class |
| scale-in  | Scales down the element |
| scale-out | Scales up the element	 |
