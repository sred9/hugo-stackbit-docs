---
title: HTML <map> Tag
weight: 2
template: docs
---	
## Description

The `<map>` tag specifies a client-side image map.

An image map is a list of coordinates relating to a specific image, created in order to hyperlink areas of the image to various destinations (as opposed to a normal image link, in which the entire area of the image links to a single destination).

For example, a map of the world may have each country hyperlinked to further information about that country. The intention of an image map is to provide an easy way of linking various parts of an image without dividing the image into separate image files.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block and <code>&lt;area&gt;</code></td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: forbidden</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<map>` tag is given with:

```html
HTML/XHTML: <map name="text"> ... </map>
```

The example below shows the `<map>` tag in action.

```html
<img src="shapes.png" usemap="#shapes" alt="Geometrical Shapes">
<map name="shapes">
    <area shape="circle" coords="40,40,40" href="circle.html" alt="Circle">
    <area shape="poly" coords="148,2,104,80,193,80" href="triangle.html" alt="Triangle">
    <area shape="rect" coords="226,2,323,80" href="rectangle.html" alt="Rectangle">
    <area shape="poly" coords="392,2,352,32,366,80,418,80,432,32" href="pentagon.html" alt="Pentagon">
</map>
```

<div class="note">
<p><strong>Note:</strong> An image may be associated with an image map, via a usemap attribute. The usemap attribute, if specified, must be a string beginning with a hash character <code>#</code> followed by the value of the name attribute of the <code>&lt;map&gt;</code> element.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;map&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<map>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<map>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;map&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

