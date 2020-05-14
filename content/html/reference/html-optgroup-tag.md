---
title: HTML <optgroup> Tag
weight: 2
template: docs
---	
## Description

The `<optgroup>` tag defines a group of options within a dropdown list defined by the `<select>` element. Each option offered by the dropdown list is defined by an `<option>` tag. A `<select>` element must contain at least one `<option>` element.

The following table summarizes the usages context and the version history of this tag.

<table optgroup="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;select&gt;</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>One or more &lt;option&gt; elements</td>
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
<p>Note: The &lt;optgroup&gt; elements may not be nested. This element should occur only within the context of a &lt;select&gt; element.</p>
</div>

## Syntax

The basic syntax of the `<optgroup>` tag is given with:

```html
HTML/XHTML: <optgroup value="5"> ... </optgroup>
```

The example below shows the `<optgroup>` tag in action.

```html
<select>
    <optgroup label="Sports cars">
        <option value="ferrari">Ferrari</option>
        <option value="lamborghini">Lamborghini</option>
    </optgroup>
    <optgroup label="Luxury cars">
        <option value="mercedes">Mercedes</option>
        <option value="bentley">Bentley</option>
    </optgroup>
</select>            
```

<div class="tip">
<p>Tip: Grouping of related options is particularly helpful when the user have to choose from a long list of options; groups of related options are easier to grasp and access, than a single long list of options.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<optgroup>` tag.

## Global Attributes

Like all other HTML tags, the `<optgroup>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<optgroup>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;optgroup&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
