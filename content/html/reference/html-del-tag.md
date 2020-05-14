---
title: HTML <del> Tag
weight: 2
template: docs
---	
## Description

The `<del>` (short for delete) tag is used to markup a range of text that has been deleted from a document. Browsers will normally render the deleted text as strike-through text, however you can overwrite this using CSS <code>text-decoration</code> property.

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

<div class="tip">
<p><strong>Tip:</strong> Also look at the counterpart of <code>&lt;del&gt;</code> tag; the <code>&lt;ins&gt;</code> tag, which is used to markup the inserted text in a document.</p></div>

## Syntax

The basic syntax of the `<del>` tag is given with:

```html
HTML/XHTML: <del datetime="datetime"> . . . </del>
```

The example below shows the `<del>` tag in action.

```html
<h1>To Do</h1>
<ul>
    <li>Buy some cookies</li>
    <li>Do some cleaning</li>
    <li><del>Relaxation time</del></li>
    <li>Visit a doctor</li>
</ul>
```

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;del&gt;</code> tag.


## Global Attributes

Like all other HTML tags, the `<del>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<del>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;del&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

