---
title: HTML <dt> Tag
weight: 2
template: docs
---	
## Description

The `<dt>` (short for definition term) tag represent a term or an item in a definition list.

The following table summarizes the usages context and the version history of this tag.

<table dt="width:100%">
    <th>Parent:</th>
    <td><code>&lt;dl&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Inline and text</td>
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
<p>Note: The <code>&lt;dt&gt;</code> element can only occur inside the definition list i.e. <code>&lt;dl&gt;</code> element and is restricted to inline-level content i.e. can't contain any block-level elements. It is usually followed by a <code>&lt;dd&gt;</code> element.</p>
</div>

## Syntax

The basic syntax of the `<dt>` tag is given with:

```html
HTML/XHTML: <dt> ... </dt>
```

The example below shows the `<dt>` tag in action.
	
```html
<dl>
    <dt>term1</dt>
    <dd>– definition1</dd>
    <dt>term2</dt>
    <dd>– definition2</dd>
</dl>
```

## Tag-Specific Attributes
The `<dt>` tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<dt>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<dt>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;dt&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
