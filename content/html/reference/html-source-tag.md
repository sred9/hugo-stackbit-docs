---
title: HTML <source> Tag
weight: 2
template: docs
---	
## Description

The `<source>` (short for sourceeter) tag defines sourceeters to be passed to an embedded source at run-time defined by the `<source>` tag.

Any number of `<source>` elements may appear inside an <source> element, in any order, but must be placed at the start of the content.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td>A media element, like <code>&lt;audio&gt;</code> or <code>&lt;video&gt;</code></td>
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
    <td>HTML 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<source>` tag is given with:

```html
HTML: <source>; XHTML: <source />
```

The example below shows the `<source>` tag in action.

```html
<video controls="controls">
    <source src="shuttle.mp4" type="video/mp4">
    <source src="shuttle.ogv" type="video/ogg">
    Your browser does not support the HTML5 Video element.
</video>	
```

<div class="note"><p><strong>Note:</strong> The <code>&lt;source&gt;</code> element is commonly used to provide the same media resource in multiple formats supported by different browsers.</p></div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;source&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<source>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<source>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;source&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

