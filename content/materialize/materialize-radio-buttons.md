---
title: Materialize Radio Buttons
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Radio Buttons are used when the user must make only one selection out of a group of items. The for attribute is necessary to bind our custom radio button with the input. Add the input's id as the value of the for attribute of the label.

Add radio buttons to a group by adding the name attribute along with the same corresponding value for each of the radio buttons in the group. Create disabled radio buttons by adding the disabled attribute as shown below.

Radio buttons are used when the user has to make one selection out of multiple items. 
```html
<form action="#">
   <p>
      <label>
      <input name="group1" type="radio" checked />
      <span>Red</span>
      </label>
   </p>
   <p>
      <label>
      <input name="group1" type="radio" />
      <span>Yellow</span>
      </label>
   </p>
   <p>
      <label>
      <input class="with-gap" name="group1" type="radio"  />
      <span>Green</span>
      </label>
   </p>
   <p>
      <label>
      <input name="group1" type="radio" disabled="disabled" />
      <span>Brown</span>
      </label>
   </p>
</form>
 ``` 
