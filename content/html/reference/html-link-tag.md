---
title: HTML <link> Tag
weight: 2
template: docs
---	
## Description

The `<link>` tag defines a link between the current document and an external resource.

The `<link>` element may only appear in the head section of a document, although it may appear any number of times. It is mostly used in linking style sheets to the HTML document.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;head&gt;</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>None. It is an empty element.</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: forbidden</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<link>` tag is given with:

```html
HTML:<link rel="link-type" href="URL">
XHTML:<link rel="link-type" href="URL" />
```

The example below shows the `<link>` tag in action.

```html
<head>
    <title>HTML Document</title>
    <link rel="stylesheet" href="default.css">
</head>                         
```
<div class="note">
<p><strong>Note:</strong> When used for referencing external style sheets, the <link> element is supported in all major browsers, but there's no real support for anything else.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;link&gt; tag.

## Global Attributes

Like all other HTML tags, the `<link>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<link>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;link&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
