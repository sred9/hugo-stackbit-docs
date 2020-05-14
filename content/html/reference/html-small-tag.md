---
title: HTML <small> Tag
weight: 2
template: docs
---	
## Description

The `<small>` tag decreases the text font size by one size smaller than a document's base font size; for example, from medium to small, or from x-large to large. Each nested `<small>` element will further decrease the size by one size smaller.

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
    <td>HTML 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="note">
<p><strong>Usage Notes:</strong></p>
<ul>
<li>The <code>&lt;small&gt;</code> tag is only intended for short runs of text. It should not be used for extended spans of text, such as multiple paragraphs, or sections of text.</li>
<li>It doesn't convey any semantic information about the enclosed text — it simply renders the text in a "small" font.</li>
<li>However, this element is not deprecated and also valid in HTML5, but is used less frequently now, as there are better methods for controlling text size such as CSS font-size property.</li>
</ul>
</div>

## Syntax

The basic syntax of the `<small>` tag is given with:

```html
HTML/XHTML: <small> ... </small>
```

The example below shows the `<small>` tag in action.

```html
<p>It's <small>small <small>smaller <small>smallest</small></small></small></p>
<!--Alternative-->
<p style="font-size:small;">This is a sample text.</p>
```

# Tag-Specific Attributes
The <code>&lt;small&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<small>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<small>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;small&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

