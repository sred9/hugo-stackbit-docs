---
title: HTML <legend> Tag
weight: 2
template: docs
---	
## Description

The `<legend>` tag is used to assign a caption to a set of form controls defined by the `<fieldset>` element.

The following table summarizes the usages context and the version history of this tag.

<table legend="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;fieldset&gt;</td>
  </tr>
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Inline and text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<legend>` tag is given with:

```html
HTML/XHTML: <legend> ... </legend>
```

The example below shows the `<legend>` tag in action.

```html
<form action="http://www.example.com/" method="post">
    <fieldset>
        <legend>Gender</legend>
        <input type="radio" name="gender" value="male" id="male">
        <label for="male">Male</label>
        <input type="radio" name="gender" value="female" id="female">
        <label for="female">Female</label>
    </fieldset>
</form>                 
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<legend>` tag.

## Global Attributes

Like all other HTML tags, the `<legend>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<legend>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;legend&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
