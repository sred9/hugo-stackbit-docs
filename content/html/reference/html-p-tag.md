---
title: HTML <p> Tag
weight: 2
template: docs
---	
## Description

The `<p>` tag defines a paragraph. The `<p>` element is the most commonly used block-level element. However, it cannot contain block-level elements (including `<p>` itself).

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Inline and text	</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: optional</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="note">
<ol>
<li>As a logical element, empty paragraphs are ignored by the browsers, so do not use empty &lt;p&gt; elements to add blank lines in your web pages. To create blank lines use the &lt;br&gt; tag, or use the CSS margin property instead.</li>
<li>When you use the &lt;p&gt; element to begin a paragraph, it automatically creates some space (margin) above and below the content. This space is applied by the browser's built-in style sheets, but you can override it using CSS margin property.</li>
</ol>
</div>

## Syntax

The basic syntax of the `<p>` tag is given with:

```html
HTML/XHTML: <p> ... </p>
```

The example below shows the `<div>` tag in action.

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>                       
```
<div class="note">
<p>Note: In HTML, the end tag for the &lt;p&gt; element may be omitted. In XHTML, the &lt;p&gt; tag must be properly closed i.e. both start tag and end tag are required.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;p&gt; tag.



## Global Attributes

Like all other HTML tags, the `<p>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<p>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;p&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

