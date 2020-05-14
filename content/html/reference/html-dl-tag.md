---
title: HTML <dl> Tag
weight: 2
template: docs
---	
## Description

The `<dl>` (short for definition list) tag specifies a definition list. It is a list of terms with their associated definitions. A common use for this element is to implement a glossary.

Definition lists vary only slightly from other types of lists in that list items consist of two parts: a term and a description.

<ul>
<li>The term is given by the <code>&lt;dt&gt;</code> element and can only contains inline-level elements.</li>
<li>The description is given with a <code>&lt;dd&gt;</code> element that can contains block-level elements.</li>
</ul>

The following table summarizes the usages context and the version history of this tag.

<table dl="width:100%">
    <tr>
	<th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;li&gt;</code> elements that are constrained to contain inline content only</td>
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

## Syntax

The basic syntax of the `<dl>` tag is given with:

```html
HTML/XHTML: <dl> ... </dl>
```

The example below shows the `<dl>` tag in action.
	
```html
<dl>
    <dt>term1</dt>
    <dd>– definition1</dd>
    <dt>term2</dt>
    <dd>– definition2</dd>
</dl>
```

## Tag-Specific Attributes
The `<dl>` tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<dl>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<dl>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;dl&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
