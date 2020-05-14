---
title: HTML <area> Tag
weight: 2
template: docs
---	
## Description

The `<area>` tag defines a hot-spot region on an image, and associates it with a hypertext link. This element is used only within a `<map>` element.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td><code>&lt;map&gt;</code></td>
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

The basic syntax of the `<area>` tag is given with:

```html
HTML/XHTML: <area code="URL" width="length" height="length"> ... </area>
```

<div class="note">
<p><strong>Note:</strong>  In HTML, the end tag for the <code>&lt;area&gt;</code> tag is forbidden. In XHTML, the <code>&lt;area&gt;</code>  tag must be closed with a trailing slash, like this: <code>&lt;area /&gt;</code> . See empty elements.</p>
</div>

The example below shows the `<area>` tag in action.

```html
<img src="shapes.png" usemap="#shapes" alt="Geometrical Shapes">
<map name="shapes">
    <area shape="circle" coords="40,40,40" href="circle.html" alt="Circle">
    <area shape="poly" coords="148,2,104,80,193,80" href="triangle.html" alt="Triangle">
    <area shape="rect" coords="226,2,323,80" href="rectangle.html" alt="Rectangle">
    <area shape="poly" coords="392,2,352,32,366,80,418,80,432,32" href="pentagon.html" alt="Pentagon">
</map>                       
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;area&gt; tag.

## Global Attributes

Like all other HTML tags, the `<area>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<area>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;area&gt;  |Ye   |Yes   |Yes   |Yes   |Yes   |

