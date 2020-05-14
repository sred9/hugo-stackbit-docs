---
title: HTML <datalist> Tag
weight: 2
template: docs
---	
## Description

The `<datalist>` element specifies a set of pre-defined options for an `<input>` element. It can be used to provide the quick choices for an input field like an "autocomplete" feature. Its not only saves the time of a user but also reduces errors, because the user has less likelihood of making a spelling mistake. The list attribute of the input element is used to bind it together with a datalist element.
	
The following table summarizes the usages context and the version history of this tag.

<table datalist="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>&lt;option&gt; elements</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<datalist>` tag is given with:

```html
HTML/XHTML: <datalist> ... </datalist>

```

The example below shows the `<datalist>` tag in action.

```html
<p>Enter your favorite browser name:</p>
<input type="text" list="browsers">
<datalist id="browsers">
    <option value="Firefox">
    <option value="Chrome">    
    <option value="Internet Explorer">
    <option value="Opera">
    <option value="Safari">
</datalist>                      
```

## Tag-Specific Attributes
The &lt;datalist&gt; tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<datalist>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<datalist>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;datalist&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
