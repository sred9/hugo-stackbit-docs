---
title: HTML <noframes> Tag
weight: 2
template: docs
---	
## Description

The `<noframes>` tag specifies fallback content that should be displayed only by the browsers that do not support frames or are configured not to display frames. It can contain all the HTML elements that can be placed inside the `<body>` element of a normal HTML page.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;body&gt;</code> (when used inside <code>&lt;frameset&gt;</code>), block, inline, and text</td>
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

<div class="important">
<p><strong>Warning:</strong> The <code>&lt;frameset&gt;</code>, <code>&lt;frame&gt;</code>, and <code>&lt;noframes&gt;</code> elements has been removed in HTML5 and should no longer be used. You should use HTML <code>&lt;iframe&gt;</code> instead.</p>
</div>

## Syntax

The basic syntax of the `<noframes>` tag is given with:

```html
HTML/XHTML: <noframes name="text"> ... </noframes>
```

The example below shows the `<noframes>` tag in action.

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
    "http://www.w3.org/TR/html4/frameset.dtd">
<html>
<head>
    <title>This is a frameset document.</title>
</head>
<frameset>
    <frame src="sample-a.html" name="frame-a">
    <frame src="sample-b.html" name="frame-b">
<noframes>
    <p>Here is the <a href="noframes.html">non-frame based version of the document.</a></p>
</noframes>
</frameset>
</html>
```

## Tag-Specific Attributes
The <code>&lt;noframes&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<noframes>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<noframes>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;noframes&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

