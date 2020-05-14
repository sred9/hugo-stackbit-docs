---
title: HTML <option> Tag
weight: 2
template: docs
---	
## Description

The `<option>` element represents an option in a dropdown list defined by the `<select>` element. A dropdown list must contain at least one `<option>` element.

The following table summarizes the usages context and the version history of this tag.

<table option="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;select&gt;, &lt;optgroup&gt;</td>
  </tr>
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: optional</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2. 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<option>` tag is given with:

```html
HTML/XHTML: <option value="optional-value"> ... </option>
```

<div class="note"><p>Note: In HTML, the end tag for the &lt;option&gt; tag is not mandatory. In XHTML, the &lt;option&t; tag must be properly closed i.e. both start tag and end tag are required.</p></div>

The example below shows the `<option>` tag in action.

```html
<select>
    <option value="ferrari">Ferrari</option>
    <option value="mercedes">Mercedes</option>
   <option value="porsche">Porsche</option>
</select>        
```

<div class="tip">
<p>Tip: You can use the &lt;optgroup&gt; tag for grouping related options within a dropdown list. It will make your forms more accessible for the users, particularly when the user have to choose from a long list of options.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<option>` tag.

## Global Attributes

Like all other HTML tags, the `<option>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<option>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;option&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
