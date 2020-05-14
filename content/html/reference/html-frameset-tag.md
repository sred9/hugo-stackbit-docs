---
title: HTML <frameset> Tag
weight: 2
template: docs
---	
## Description

The `<frameset>` tag defines a collection of frames or other framesets.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;frameset&gt;</code>, <code>&lt;frame&gt;</code>, <code>&lt;noframes&gt;</code></td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 4 and 4.01 (framesetset)</td>
  </tr>
</table>	

<div class="important">
<p><strong>Warning:</strong> Do not use this tag since it is a non-standard tag. This tag has been removed in HTML5 and shouldn't be used anymore. Use HTML <code>&lt;iframe&gt;</code>, instead.</p>
</div>

## Syntax

The basic syntax of the `<frameset>` tag is given with:

```html
HTML/XHTML: <frameset cols="[ number | percentage | * ] ,..." rows="[ number | percentage | * ] ,..."> ... </frameset>
```

The example below shows the `<frameset>` tag in action.

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
</frameset>
</html>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;frameset&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<frameset>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<frameset>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;frameset&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

