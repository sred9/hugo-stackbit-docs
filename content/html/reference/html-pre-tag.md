---
title: HTML <pre> Tag
weight: 2
template: docs
---	
## Description

The `<pre>` tag defines a block of preformatted text. This element is commonly used to preserves spaces, line breaks, tabs, and other formatting characters in source markup that web browsers would otherwise ignore.

Text within the `<pre>` element is typically rendered by the browsers in a monospace (fixed-width) font, such as Courier, but this style can be overridden using CSS.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
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
<p><strong>Note: </strong>By default, only the first space is honored; subsequent spaces — unless specified using the <code>&amp;nbsp;</code> entity — aren't rendered by the browsers.</p>
</div>

## Syntax

The basic syntax of the `<pre>` tag is given with:

```html
HTML/XHTML: <pre> ... </pre>
```

The example below shows the `<pre>` tag in action.

```html
<pre>
The pre
    element preserves      spaces,
        line-breaks, tabs...
</pre>
```

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;pre&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<pre>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<pre>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;pre&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

