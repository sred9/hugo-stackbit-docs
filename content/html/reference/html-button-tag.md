---
title: HTML <button> Tag
weight: 2
template: docs
---	
## Description

The `<button>` tag creates a clickable button in an HTML form.

Buttons created with the `<button>` element function just like buttons created with the input element, but they offer richer rendering possibilities; as you can put content, like text or images inside the button element. For example, a `<button>` element that contains an image functions like and may resemble an `<input>` element whose type is set to `<image>`.

The following table summarizes the usages context and the version history of this tag.

<table button="width:100%">
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Any block, inline, and text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 4, 4.01, 5</td>
  </tr>
</table>	


<div class="note">
<ul>
<li>If you use the &lt;button&gt; tag in an HTML form, different browsers may submit different values. Internet Explorer, prior version 9, will submit the text contained between the opening and closing tag of the button element, while other browsers will submit the content of the value attribute.</li>
<li>In IE7 when submitting a form with <code>&lt;button type="submit" name="myButton" value="foo"&gt;Click me&lt;/button&gt;</code>, the POST data sent will result in <code>myButton=Click me</code> instead of <code>myButton=foo</code>.</li>
</ul>
</div>


## Syntax

The basic syntax of the `<button>` tag is given with:

```html
HTML/XHTML: <button type="button|reset|submit"> ... </button>
```

The example below shows the `<button>` tag in action.

```html
<form action="action.php" method="post">
    <p>
        First name:<input type="text" name="firstname">
        <button type="submit" value="Submit">Submit</button>
        <button type="reset" value="Reset">Reset</button>
    </p>
</form>
```

<div class="tip">
<p>Tip: You can use the &lt;optgroup&gt; tag for grouping related buttons within a dropdown list. It will make your forms more accessible for the users, particularly when the user have to choose from a long list of buttons.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<button>` tag.

## Global Attributes

Like all other HTML tags, the `<button>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<button>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;button&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
