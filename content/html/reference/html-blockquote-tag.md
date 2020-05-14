---
title: HTML <blockquote> Tag
weight: 2
template: docs
---	
## Description

The `<blockquote>` tag indicates that the enclosed text is an extended quotation.

Usually, blockquotes are rendered visually by indentation. A URL for the source of the quotation may be given using the <code>cite</code> attribute, while a text representation of the source can be given using the <code>&lt;cite&gt;</code> element.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
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
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="note">
<p><strong>Note:</strong> XHTML allows the <code>&lt;blockquote&gt;</code> element to contain only other block-level elements (i.e. not an inline-level element).</p>
</div>

## Syntax

The basic syntax of the `<blockquote>` tag is given with:

```html
HTML/XHTML: <blockquote cite="URL"> ... </blockquote>
```

The example below shows the `<blockquote>` tag in action.

```html
<blockquote>
    <p>This is an example of a long quotation.</p>
</blockquote>
```

<div class="tip">
<p><strong>Tip:</strong>  The <code>&lt;blockquote&gt;</code> tag is for long quotations (block-level content). For short quotations (inline-level content), use <code>&lt;q&gt;</code> tag that don't require paragraph breaks.</p>
</div>

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;blockquote&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<blockquote>` tag supports the [globlockquoteal Attributes in HTML5](https://www.tutorialrepublockquotelic.com/html-reference/html5-globlockquoteal-Attributes.php).

## Event Attributes

The `<blockquote>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepublockquotelic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;blockquote&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

