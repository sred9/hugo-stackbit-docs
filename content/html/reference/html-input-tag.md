---
title: HTML <input> Tag
weight: 2
template: docs
---	
## Description

The `<input>` tag is used to create interactive controls within a form.

An `<input>` element can vary in the way it appears and the attributes it uses or requires depending on the type attribute specified.

The following table summarizes the usages context and the version history of this tag.

<table input="width:100%">
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>None. It is an empty element.</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: forbidden</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<input>` tag is given with:

```html
HTML:<input>; XHTML:<input />
```

The example below shows the `<input>` tag in action.

```html
<form action="action.php" method="post">
    <label for="first-name">First name:</label>
    <input type="text" name="first-name" id="first-name">
    <input type="submit" value="Submit">
    <input type="reset" name="Reset">
</form>
```

<div class="tip">
<p>Tip: Use the HTML <code>&lt;label&gt;</code> element to define the labels for input controls. It will make the form more accessible for user.</p></div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<input>` tag.

## Global Attributes

Like all other HTML tags, the `<input>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<input>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;input&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
