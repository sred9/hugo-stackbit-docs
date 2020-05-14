---
title: Bootstrap Buttonssadfas
weight: 2
template: docs
---		
Buttons are the integral part of a website and application. They are used for various purposes like, submit or reset an HTML form, performing interactive actions such as showing or hiding something on a web page on click of the button, redirecting user to another page, and so on. Bootstrap provides a quick and easy way to create and customize the buttons.

## Button Styles
Different classes are available in Bootstrap for styling the buttons as well as to indicate the different states or semantic. Button styles can be applied to any element. However, it is applied normally to the `<a>`, `<input>`, and `<button>` elements for the best rendering.

The following example will show you how to create different styles of buttons in Bootstrap:

```html
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>    
<button type="button" class="btn btn-dark">Dark</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-link">Link</button>
```

— The output of the above example will look something like this:

## Outline Buttons

You can also create outline buttons by replacing the button modifier classes, like this:

```html
<button type="button" class="btn btn-outline-primary">Primary</button>
<button type="button" class="btn btn-outline-secondary">Secondary</button>
<button type="button" class="btn btn-outline-success">Success</button>
<button type="button" class="btn btn-outline-danger">Danger</button>
<button type="button" class="btn btn-outline-warning">Warning</button>
<button type="button" class="btn btn-outline-info">Info</button>
<button type="button" class="btn btn-outline-dark">Dark</button>
<button type="button" class="btn btn-outline-light">Light</button>
```

— The output of the above example will look something like this:

## Button Sizes

Bootstrap gives you option further to scaling a button up or down. You can make buttons larger or smaller through adding an extra class `.btn-lg` or `.btn-sm`, like this:

```html
<button type="button" class="btn btn-primary btn-lg">Large</button>
<button type="button" class="btn btn-primary">Default</button>
<button type="button" class="btn btn-primary btn-sm">Small</button>
```

— The output of the above example will look something like this:


## Block Level Buttons

You can also create block level buttons (buttons that covers the full width of the parent elements) by adding an extra class .btn-block to the buttons, like this:

```html
<button type="button" class="btn btn-primary btn-lg btn-block">Block level button</button>
<button type="button" class="btn btn-secondary btn-lg btn-block">Block level button</button>
```

— The output of the above example will look something like this:

## Disabled Buttons

Sometimes we need to disable a button for certain reasons, for example, a user in case is not eligible to perform this particular action, or we want to ensure that user should performed all other required actions before proceed to this particular action. Let's see how to do that.

Buttons created through `<button>` or `<input>` tag can be disabled by adding the disabled attribute to the respective element, as shown in the following example:

```html
<button type="button" class="btn btn-primary btn-lg" disabled>Primary button</button>
<button type="button" class="btn btn-secondary btn-lg" disabled>Button</button>
```

Creating Disabled Buttons Using Anchor Elements

Buttons created through <a> tag can be disabled by adding the class .disabled, like this:

```html
<a href="#" class="btn btn-primary btn-lg disabled">Primary link</a>
<a href="#" class="btn btn-secondary btn-lg disabled">Link</a>
```

— The output of the above example will look something like this:


<div class="note">
<p><strong>Note:</strong> The .disabled class only make links visually appear like disabled, however the link will remain clickable unless you remove the href attribute from it. Alternatively, you could implement custom JavaScript to prevent those clicks.</p>
</div>



## Active Buttons

Moreover, you can also apply the class .active to force the buttons look like active (i.e. pressed). Usually you don't need to add this class to the buttons, as their active state is automatically styled by the Bootstrap using CSS :active pseudo-class. Here's an example:

```html
<a href="#" class="btn btn-primary btn-lg active" role="button" aria-pressed="true">Primary link</a>
<a href="#" class="btn btn-secondary btn-lg active" role="button" aria-pressed="true">Link</a>
```

— The output of the above example will look something like this:

## Spinner Buttons

With Bootstrap you can easily include spinner icon in a button to indicate the loading state in your application. Check out the following example to see how it works:
```html
	<button type="button" class="btn btn-primary" disabled>
    <span class="spinner-border spinner-border-sm"></span>
</button>
<button type="button" class="btn btn-primary" disabled>
    <span class="spinner-border spinner-border-sm"></span> Loading...
</button>
<button type="button" class="btn btn-primary" disabled>
    <span class="spinner-grow spinner-grow-sm"></span> Loading...
</button>
```

— The output of the above example will look something like this:


```html
HTML/XHTML: <address> ... </address>
```

