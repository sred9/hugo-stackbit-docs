---
title: HTML <center> Tag
weight: 2
template: docs
---	
## Description

The `<center>` element aligns contents in the center of the enclosing block.

Usually, centers are rendered visually by indentation. A URL for the source of the quotation may be given using the <code>cite</code> attribute, while a text representation of the source can be given using the <code>&lt;cite&gt;</code> element.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td>Block, inline and text</td>
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
<p><strong>Warning:</strong> Don't use this tag since it is a non-standard tag and has been deprecated in HTML 4.01 and obsolete since HTML5. Use CSS instead, to center content.</p>
</div>

## Syntax

The basic syntax of the `<center>` tag is given with:

```html
HTML/XHTML: <center> ... </center>
```

The example below shows the `<center>` tag in action.

```html
<!--Example of bad usage. Don't use this tag-->
<center>This paragraph will be centered.</center>
<!--Alternative-->
<p style="text-align: center;">This paragraph will be centered using CSS.</p>
```

<div class="tip">
<p><strong>Tip:</strong>  To give a similar effect to the center tag, use the CSS text-align property, which can be applied to the <code>&lt;div&gt;</code> element or to an individual <code>&lt;p&gt;</code>.</p>
</div>

# Tag-Specific Attributes
The <code>&lt;center&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<center>` tag supports the [glocenteral Attributes in HTML5](https://www.tutorialrepucenterlic.com/html-reference/html5-glocenteral-Attributes.php).

## Event Attributes

The `<center>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepucenterlic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;center&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

