---
title: Materialize Preloader
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: materialize
---
If you have content that will take a long time to load, you should give the user feedback. For this reason we provide a number activity + progress indicators.

## Linear

### Determinate

Note: This is also touch compatible! Try swiping with your finger to scroll through the carousel.

```html
div class="progress">
	<div class="determinate" style="width: 70%"></div>
</div>        
 ``` 
 
### Indeterminate

 ```html
<div class="progress">
	<div class="indeterminate"></div>
</div>
```

## Circular

### Static Colors

Note: This is also touch compatible! Try swiping with your finger to scroll through the carousel.

```html
<div class="preloader-wrapper big active">
   <div class="spinner-layer spinner-blue-only">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
</div>
<div class="preloader-wrapper active">
   <div class="spinner-layer spinner-red-only">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
</div>
<div class="preloader-wrapper small active">
   <div class="spinner-layer spinner-green-only">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
</div>       
 ``` 
 
### Flashing Colors

 ```html
<div class="preloader-wrapper big active">
   <div class="spinner-layer spinner-blue">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
   <div class="spinner-layer spinner-red">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
   <div class="spinner-layer spinner-yellow">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
   <div class="spinner-layer spinner-green">
      <div class="circle-clipper left">
         <div class="circle"></div>
      </div>
      <div class="gap-patch">
         <div class="circle"></div>
      </div>
      <div class="circle-clipper right">
         <div class="circle"></div>
      </div>
   </div>
</div>
```