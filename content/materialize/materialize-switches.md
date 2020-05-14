---
title: Materialize Switches	
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Switches are special checkboxes used for displaying binary states such as on / off. 

## Switch
```html
<div class="switch">
   <label>
   Off
   <input type="checkbox">
   <span class="lever"></span>
   On
   </label>
</div>
 ``` 
 
## Disabled Switch

You can create a disabled switch by passing the `disabled` attribute to the `input` tag.

```html
<div class="switch">
   <label>
   Off
   <input disabled type="checkbox">
   <span class="lever"></span>
   On
   </label>
</div>	
 ``` 