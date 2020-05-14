---
title: HTML <meter> Tag
weight: 2
template: docs
---	
## Description

The `<meter>` element represents a scalar measurement within a known range, or a fractional value. This is also known as a gauge.

The following table summarizes the usages context and the version history of this tag.

<table meter="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Inline and text, but no &lt;meter&gt; among its descendants</td>
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

The basic syntax of the `<meter>` tag is given with:

```html
HTML/XHTML: <meter value="5"> ... </meter>
```

The example below shows the `<meter>` tag in action.

```html
<p>Disk Usage: <meter value="0.8">80%</meter></p>
<p>Total Score: <meter value="6" min="0" max="10">6 out of 10</meter></p>
<p>Pollution Level: <meter low="60" high="80" max="100" value="85">Very High</meter></p>            
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<meter>` tag.

## Global Attributes

Like all other HTML tags, the `<meter>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<meter>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;meter&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
