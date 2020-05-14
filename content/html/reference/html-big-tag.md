---
title: HTML <big> Tag
weight: 2
template: docs
---	
## Description

The `<big>` tag increases the text font size by one size bigger than a document's base font size; for example, from small to medium, or from large to x-large. Each nested big element will further increase the size by one size bigger.

You must specify the <code>dir</code> attribute on this element. This mandatory attribute specifies the base direction of the element's text content, which overrides the inherent directionality of characters as defined in [UNICODE].

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
    <td>HTML 3, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="warning">
<p><strong>Warning:</strong>  As it was purely presentational, this tag has been removed in HTML5 and shouldn't be used anymore. You should use CSS font properties, instead.</p>
</div>

## Syntax

The base syntax of the `<big>` tag is given with:

```html
HTML/XHTML: <big> ... </big>
```

The example below shows the `<big>` tag in action.

```html
<!--Example of bad usage. Don't use this tag-->
<p>It's<big>big<big>bigger<big>biggest</big></big></big></p>
<!--Alternative-->
<p style="font-size:large;">This is a sample text.</p>
```

<div class="tip">
<p><strong>Tip:</strong> Use CSS font-size property to specify the font size for the text in a document. See the tutorial on CSS Fonts to learn more about font styling.</p>
</div>

# Tag-Specific Attributes
The <code>&lt;big&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<big>` tag supports the [globigal Attributes in HTML5](https://www.tutorialrepubiglic.com/html-reference/html5-globigal-Attributes.php).

## Event Attributes

The `<big>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepubiglic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;big&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

