---
title: HTML <base> Tag
weight: 2
template: docs
---	
## Description

The `<base>` tag defines the base URL and a common target to for all relative URLs contained within a document. There must be no more than one `<base>` tag per document.

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

The basic syntax of the `<base>` tag is given with:

```html
HTML:<base href="URL">; XHTML:<base href="URL" />
```

The example below shows the `<div>` tag in action.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Example of HTML base tag</title>
    <base href="https://www.tutorialrepublic.com/">
</head>
<body>
    <p>Learn <a href="css-tutorial/">CSS</a>.</p>	
</body>
</html>                            
```
The relative URL "css-tutorial/" would resolve to: https://www.tutorialrepublic.com/css-tutorial/


<div class="note">
<p>Note: If multiple &lt;base&gt; tags are specified, only the first 'href' and first 'target' attribute's value are used, all others are ignored.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;base&gt; tag.

## Global Attributes

Like all other HTML tags, the `<base>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<base>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;base&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

