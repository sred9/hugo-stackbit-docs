---
title: HTML <textarea> Tag
weight: 2
template: docs
---	
## Description

The `<textarea>` tag defines a multi-line text input control within a form. The text inside the textarea usually rendered in browser's default monospace (fixed-width) font such as Courier. A text area can hold unlimited number of characters.

The following table summarizes the usages context and the version history of this tag.

<table textarea="width:100%">
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Text</td>
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

The basic syntax of the `<textarea>` tag is given with:

```html
HTML/XHTML: <textarea cols="number" rows="number" > ... </textarea>
```

The example below shows the `<textarea>` tag in action.

```html
<form>
    <p>Leave your Comment: 
        <textarea cols="60" rows="5">write here...</textarea>
    </p>
</form>     
```

<div class="tip">
<p>Tip: You can use the &lt;optgroup&gt; tag for grouping related textareas within a dropdown list. It will make your forms more accessible for the users, particularly when the user have to choose from a long list of textareas.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<textarea>` tag.

## Global Attributes

Like all other HTML tags, the `<textarea>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<textarea>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;textarea&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
