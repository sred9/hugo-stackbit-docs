---
title: HTML <ins> Tag
weight: 2
template: docs
---	
## Description

The `<ins>` (short for inserted) tag specifies a block of inserted text. This tag is typically used to markup a range of text that has been added to the document. Browsers will normally render the inserted text as underlined text, however you can overwrite this using the CSS text-decoration property.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block or inline, depending on the content</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td>Any block, inline, and text (but cannot contain block content when used as an inline element)</td>
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

<div class="note">
<p><strong>Note:</strong> Also look at the counterpart of <code>&lt;ins&gt;</code> tag; the <code>&lt;del&gt;</code> tag, which is used to markup the deleted text in a document. Use these elements to markup updates and modifications in your document.</p>
</div>

## Syntax

The basic syntax of the `<ins>` tag is given with:

```html
HTML/XHTML: <ins datetime="datetime"> ... </ins>
```

The example below shows the `<ins>` tag in action.

```html
<h1>To Do</h1>
<ul>
    <li>Buy some cookies</li>
    <li><ins>Do some cleaning</ins></li>
    <li><del>Relaxation time</del></li>
    <li><ins>Visit a doctor</ins></li>
</ul>
```

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;ins&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<ins>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<ins>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;i&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

