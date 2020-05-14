---
title: HTML <iframe> Tag
weight: 2
template: docs
---	
## Description

The `<iframe>` (short for inline frame) tag defines an inline frame that contains external objects including other web page.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Any block, inline, and text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 4 and 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<iframe>` tag is given with:

```html
HTML/XHTML: <iframe src="URL" scrolling="auto|no|yes"> ... </iframe>
```

The example below shows the `<iframe>` tag in action.

```html
<iframe src="hello.html" width="400" height="300"
    scrolling="auto">
    <p>[Your browser does not support frames or is currently configured not to display frames. However, you may visit <a href="optional.html">the related document.</a>]</p>
</iframe>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;iframe&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<iframe>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<iframe>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;iframe&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

