---
title: HTML <param> Tag
weight: 2
template: docs
---	
## Description

The `<param>` (short for parameter) tag defines parameters to be passed to an embedded param at run-time defined by the `<param>` tag.

Any number of `<param>` elements may appear inside an <param> element, in any order, but must be placed at the start of the content.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td><code>&lt;param&gt;</code>, <code>&lt;applet&gt;</code></td>
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
    <td>HTML 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<param>` tag is given with:

```html
HTML:<param name="text">; XHTML:<param name="text" />
```

<div class="note"><p><strong>Note:</strong> In HTML, the end tag for the <code>&lt;param&gt;</code> tag is forbidden. In XHTML, the <code>&lt;param&gt;</code> tag must be closed with a trailing slash, like this: <code>&lt;param /&gt;</code>.</p></div>

The example below shows the `<param>` tag in action.

```html
<object type="application/x-shockwave-flash">
    <param name="movie" value="video/blur.swf">
</object>	
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;param&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<param>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<param>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;param&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

