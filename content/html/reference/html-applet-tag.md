---
title: HTML <applet> Tag
weight: 2
template: docs
---	
## Description

The `<applet>` tag embeds a Java applet (mini Java applications) on the page. An applet is a program written in the Java programming language that can be included in an HTML page, much in the same way an image is included in a page.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, inline, and text; any <code>&lt;param&gt;</code> elements must come first</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01 (transitional)</td>
  </tr>
</table>	

<div class="important">
<p><strong>Warning:</strong> Do not use this tag since it is a non-standard tag and has been deprecated with all its attributes in HTML 4.01 and obsolete since HTML5. Use the more generic <code>&lt;object&gt;</code> element instead.</p>
</div>

## Syntax

The basic syntax of the `<applet>` tag is given with:

```html
HTML/XHTML: <applet code="URL" width="length" height="length"> ... </applet>
```

The example below shows the `<applet>` tag in action.

```html
<applet code="Animate.class" width="400" height="300">
    <param name="delay" value="30">
    <param name="time" value="120">
</applet>                         
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;applet&gt; tag.

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;applet&gt;  |No   |Yes   |No   |No   |No   |

