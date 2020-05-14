---
title: HTML <select> Tag
weight: 2
template: docs
---	
## Description

The `<select>` element defines a selection list within a `<form>`. The selection list typically displayed in the browser as a pull-down menu (i.e. a drop-down list) from which a user can select one or more options depending on its attributes. Each option offered by the selection list is defined by an `<option>` element.

The following table summarizes the usages context and the version history of this tag.

<table select="width:100%">
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>One or more of `<optgroup>` and/or `<option>`</td>
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

<div class="note">
<p>
Note: A &lt;select&gt; element must contain at least one &lt;option&gt; element. Options can be pre-selected for the user if attribute selected="selected" is specified to the start tag of the &lt;option&gt; element.</p>
</div>
## Syntax

The basic syntax of the `<select>` tag is given with:

```html
HTML/XHTML: <select> ... </select>
```

The example below shows the `<select>` tag in action.

```html
<select>
    <option value="ferrari">Ferrari</option>
    <option value="mercedes">Mercedes</option>
   <option value="porsche">Porsche</option>
</select>        
```

<div class="tip">
<p>Tip: You can use the &lt;optgroup&gt; tag for grouping related selects within a dropdown list. It will make your forms more accessible for the users, particularly when the user have to choose from a long list of selects.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<select>` tag.

## Global Attributes

Like all other HTML tags, the `<select>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<select>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;select&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
