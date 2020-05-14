---
title: HTML <form> Tag
weight: 2
template: docs
---	
## Description

The `<form>` tag defines an HTML form that contains interactive controls which enable a user to submit information to a web server. An HTML form is used to capture user information such as username, password, address details, credit card information, and so on.

Information can be captured in the form using many different form controls, such as `<input>`, `<textarea>`, `<select>`, `<option>`, `<button>`	. There are also labeling and grouping controls, which include the `<optgroup>`, `<fieldset>`, `<legend>`, and `<label>` elements.

The following table summarizes the usages context and the version history of this tag.

<table form="width:100%">
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, inline, and text, but not containing <code>&lt;form&gt;</code> elements</td>
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

The basic syntax of the `<form>` tag is given with:

```html
HTML/XHTML: <form action="URL" method="get|post"> ... </form>
```

The example below shows the `<form>` tag in action.

```html
<form action="action.php" method="post">
    <p>
        First name: <input type="text" name="first-name">
        <button type="submit" value="Submit">Submit</button>
        <button type="reset" value="Reset">Reset</button>
    </p>
</form>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<form>` tag.

<div class="note">
<p>Note: The default value for the enctype attribute is application/x-www-form-urlencoded. The value multipart/form-data should be used in combination with the INPUT element (when type="file").</p>
</div>

## Global Attributes

Like all other HTML tags, the `<form>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<form>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;form&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
