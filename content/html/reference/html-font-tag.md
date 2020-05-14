---
title: HTML <font> Tag
weight: 2
template: docs
---	
## Description

The `<font>` tag defines font styles for its content. This tag was typically used to define the font size, color and face for the text in its contents.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td>Inline and text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 3.2, 4, 4.01 (transitional)</td>
  </tr>
</table>	

<div class="important">
<p><strong>Warning:</strong> Do not use this tag since it is a non-standard tag and has been deprecated in HTML 4.01. It has been removed in HTML5 and shouldn't be used anymore. You should use CSS font property, instead.</p>
</div>

## Syntax

The basic syntax of the `<font>` tag is given with:

```html
HTML/XHTML: <font size="number" color="color" face="font-family, ..."> ... </font>
```

The example below shows the `<font>` tag in action.

```html
<!--Example of bad usage-->
<p>This is the <font size="3" color="red" face="Verdana,Arial,sans-serif">wrong way</font> to style text.</p>
<!--Alternative-->
<p>This is the <span style="font-size:16px; color:green; font-family:Verdana,Arial,sans-serif;">right way</span> to style text.</p>
```

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;font&gt;</code> tag.
		
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;font&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

