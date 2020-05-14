---
title: HTML <figure> Tag
weight: 2
template: docs
---	
## Description

The `<figure>` element represents a unit of content, optionally with a caption, that is self-contained and typically referenced as a single unit. Usually this is an image, an illustration, a diagram, or a code snippet that is referenced in the main text.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>A <code>&lt;figcaption&gt;</code> element, followed by the Block, Inline, and text elements and vice versa</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<figure>` tag is given with:

```html
HTML/XHTML: <figure> ... </figure>
```

The example below shows the `<figure>` tag in action.

```html
<figure>
    <img src="discovery.jpg" alt="Space Shuttle">
    <figure>NASA - Space Shuttle Discovery</figure>
</figure>
```

<div class="note">
<p><strong>Note:</strong> The content of the <code>&lt;figure&gt;</code> element is however related to the main flow, but its position is independent of the main flow and it can be moved away from the main flow of the document without affecting the document's meaning.</p>
</div>

## Tag-Specific Attributes
The <code>&lt;figure&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<figure>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<figure>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;figure&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

