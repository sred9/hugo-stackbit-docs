---
title: HTML <dd> Tag
weight: 2
template: docs
---	
## Description

The `<dd>` (short for definition description) tag represents the description or definition of an item in a description list. This element can contain block-level elements such as headings, paragraphs, blockquotes, etc. as well as inline-level elements such as span, em, strong, etc.

The following table summarizes the usages context and the version history of this tag.

<table dd="width:100%">
    <th>Parent:</th>
    <td><code>&lt;dl&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, inline, and text</td>
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
<p>
Note: The <code>&lt;dd&gt;</code> element can only occur inside the definition list i.e. <code>&lt;dl&gt;</code> element and it must follow a definition term defined by the <code>&lt;dt&gt;</code> element.</p>
</div>

## Syntax

The basic syntax of the `<dd>` tag is given with:

```html
HTML/XHTML: <dd> ... </dd>
```

The example below shows the `<dd>` tag in action.

```html
<dl>
    <dt>term1</dt>
    <dd>– definition1</dd>
    <dt>term2</dt>
    <dd>– definition2</dd>
</dl>
```

## Tag-Specific Attributes
The `<dd>` tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<dd>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<dd>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;dd&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
