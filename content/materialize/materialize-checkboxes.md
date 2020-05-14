---
title: Materialize Checkboxes
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Use checkboxes when looking for yes or no answers. The for attribute is necessary to bind our custom checkbox with the input. Add the input's id as the value of the for attribute of the label.

```html
 <form action="#">
    <p>
      <label>
        <input type="checkbox" />
        <span>Red</span>
      </label>
    </p>
    <p>
      <label>
        <input type="checkbox" checked="checked" />
        <span>Yellow</span>
      </label>
    </p>
    <p>
      <label>
        <input type="checkbox" class="filled-in" checked="checked" />
        <span>Filled in</span>
      </label>
    </p>
    <p>
      <label>
        <input id="indeterminate-checkbox" type="checkbox" />
        <span>Indeterminate Style</span>
      </label>
    </p>
    <p>
      <label>
        <input type="checkbox" checked="checked" disabled="disabled" />
        <span>Green</span>
      </label>
    </p>
    <p>
      <label>
        <input type="checkbox" disabled="disabled" />
        <span>Brown</span>
      </label>
    </p>
  </form>
 ``` 