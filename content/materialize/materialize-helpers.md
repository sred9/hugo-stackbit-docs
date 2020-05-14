---
title: Materialize Helpers	
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
We have easy to use classes to help you align your content.

## Vertical Align

You can easily vertically center things by adding the class valign-wrapper to the container holding the items you want to vertically align.

```html
<div class="valign-wrapper">
  <h5>This should be vertically aligned</h5>
</div>
 ```       
## Horizontal Align

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

## Quick Floats

Quickly float things by adding the class left or right to the element. !important is used to avoid specificity issues.

```html
<div class="left">...</div>
<div class="right">...</div>
```

## Hiding/Showing Content

| CSS Class                | Screen Range                |
|--------------------------|-----------------------------|
| .hide                    | Hidden for all Devices      |
| .hide-on-small-only      | Hidden for Mobile Only      |
| .hide-on-med-only        | Hidden for Tablet Only      |
| .hide-on-med-and-down    | Hidden for Tablet and Below |
| .hide-on-med-and-up      | Hidden for Tablet and Above |
| .hide-on-large-only      | Hidden for Desktop Only     |
| .show-on-small           | Show for Mobile Only        |
| .show-on-medium          | Show for Tablet Only        |
| .show-on-large           | Show for Desktop Only       |
| .show-on-medium-and-up   | Show for Tablet and Above   |
| .show-on-medium-and-down | Show for Tablet and Below   |
