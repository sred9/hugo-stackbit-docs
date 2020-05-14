---
title: HTML <frame> Tag
weight: 2
template: docs
---	
## Description

The `<frame>` tag defines a single frame within a `<frameset>`. Each `<frame>` in a `<frameset>` can have different attributes, such as border, scrolling, the ability to resize, etc.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;frameset&gt;</td>
  </tr>
  <tr>
    <th>Placement:</th>
    <td>Block</td>
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
    <td>HTML 4 and 4.01 (frameset)</td>
  </tr>
</table>	

<div class="important">
<p><strong>Warning:</strong> Do not use this tag since it is a non-standard tag. This tag has been removed in HTML5 and shouldn't be used anymore. Use HTML <code>&lt;iframe&gt;</code>, instead.</p>
</div>

## Syntax

The basic syntax of the `<frame>` tag is given with:

```html
HTML:<frame src="URL">; XHTML:<frame src="URL" />
```

The example below shows the `<frame>` tag in action.

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
    "http://www.w3.org/TR/html4/frameset.dtd">
<html>
<head>
    <title>This is a frameset document</title>
</head>
<frameset>
    <frame src="sample-a.html" name="frame-a">
    <frame src="sample-b.html" name="frame-b">
</frameset>
</html>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;frame&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<frame>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<frame>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;frame&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

