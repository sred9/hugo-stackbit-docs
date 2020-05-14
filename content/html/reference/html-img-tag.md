---
title: HTML <img> Tag
weight: 2
template: docs
---	
## Description

The `<img>` (short for image) tag defines an image in an HTML document. Images are not directly inserted into the document; they are linked to the HTML pages. The `<img>` element creates a holding space to embed the referenced image designated by the src attribute.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
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

<div class="note">
<p><strong>Note:</strong> The browser may replace the image with the alternative text defined in this element's alt attribute in the case of non-graphical browsers, or if the browser is unable to display the image because it is invalid or an unsupported type.</p>
</div>

## Syntax

The basic syntax of the `<img>` tag is given with:

```html
HTML:<img src="URL" alt="text">; XHTML:<img src="URL" alt="text" />
```

The example below shows the `<img>` tag in action.

```html
<img src="kites.jpg" alt="Flying Kites">
<img src="sky.jpg" alt="Cloudy Sky">
<img src="ballons.jpg" alt="Hot Air Ballons">
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;img&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<img>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<img>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;img&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

