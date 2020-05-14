---
title: HTML <basefont> Tag
weight: 2
template: docs
---	
## Description

The `<basefont>` tag specifies the base font i.e. default font-color, font-size, or font-family for all the text in an HTML document.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;head&gt;</td>
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
    <td>HTML 2, 3.2, 4, 4.01</td>
  </tr>
</table>	

<div class="important">
<p><strong>Warning:</strong> Don't use this tag since it is a non-standard tag and has been deprecated in HTML 4.01 and obsolete since HTML5. Use CSS font's properties, instead.</p>
</div>

## Syntax

The basic syntax of the `<basefont>` tag is given with:

```html
HTML:<basefont>; XHTML:<basefont />
```

The example below shows the `<basefont>` tag in action.

```html
<head>
    <title>The HTML Document</title>		
    <basefont color="red" size="5" face="arial, sans-serif">
</head>                           
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;basefont&gt; tag.

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;basefont&gt;  |No   |Yes   |No   |No   |No   |

