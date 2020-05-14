---
title: Materialize Shadow	
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Materialize CSS allows you to easily add shadow effect to any element by adding `z-depth-*` class to any HTML element. The `*` in `z-depth-*` determines how far raised/ close the element to the page is. It can take values 0, 1, 2, 3, 4 or 5, while 0 being the closest.
	
<div class="tip"><p><strong>Tip:</strong> Additonally <code>z-depth-0</code> can be used to remove shadows from elements that have z-depths by default.</p></div>

```html
<div class="col s12 m2">
   <p class="z-depth-1">z-depth-1</p>
</div>
<div class="col s12 m2">
   <p class="z-depth-2">z-depth-2</p>
</div>
<div class="col s12 m2">
   <p class="z-depth-3">z-depth-3</p>
</div>
<div class="col s12 m2">
   <p class="z-depth-4">z-depth-4</p>
</div>
<div class="col s12 m2">
   <p class="z-depth-5">z-depth-5</p>
</div>
```

