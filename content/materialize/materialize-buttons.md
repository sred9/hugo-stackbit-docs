---
title: Materialize Buttons	
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
There are 3 main button types described in material design. The raised button is a standard button that signify actions and seek to give depth to a mostly flat page. The floating circular action button is meant for very important functions. Flat buttons are usually used within elements that already have depth like cards or modals.

```html
<a class="waves-effect waves-light btn">button</a>
<a class="waves-effect waves-light btn"><i class="material-icons left">cloud</i>button</a>
<a class="waves-effect waves-light btn"><i class="material-icons right">cloud</i>button</a>
```

## Floating Button

```html
<a class="btn-floating btn-large waves-effect waves-light red"><i class="material-icons">add</i></a>
```

## Flat Button

Flat buttons are used to reduce excessive layering. For example, flat buttons are usually used for actions within a card or modal so there aren't too many overlapping shadows.

```html
<a class="waves-effect waves-teal btn-flat">Button</a>
```

## Submit Button

When you use a button to submit a form, instead of using a input tag, use a button tag with a type submit

```html
<button class="btn waves-effect waves-light" type="submit" name="action">Submit
  <i class="material-icons right">send</i>
</button>
```

## Large Button

This button has a larger height for buttons that need more attention.

```html
<a class="waves-effect waves-light btn-large">Button</a>
<a class="waves-effect waves-light btn-large"><i class="material-icons left">cloud</i>button</a>
<a class="waves-effect waves-light btn-large"><i class="material-icons right">cloud</i>button</a>
```

## Small Button

When mouse and keyboard are the primary input methods, this smaller button is useful for denser UI layouts.

```html
<a class="waves-effect waves-light btn-large">Button</a>
<a class="waves-effect waves-light btn-large"><i class="material-icons left">cloud</i>button</a>
<a class="waves-effect waves-light btn-large"><i class="material-icons right">cloud</i>button</a>
```  
    
## Disabled Button

This style can be applied to all button types

```html
<a class="btn-large disabled">Button</a>
<a class="btn disabled">Button</a>
<a class="btn-flat disabled">Button</a>
<a class="btn-floating disabled"><i class="material-icons">add</i></a>
```   