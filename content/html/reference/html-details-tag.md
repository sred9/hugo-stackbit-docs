---
title: HTML <details> Tag
weight: 2
template: docs
---

## Description

The `<details>` element represents a control from which the user can obtain additional information on-demand. It can be used to create an interactive widget that the user can show or hide (like expand and collapse) to retrieve the additional information or controls. Any sort of element can be placed inside the details element.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, inline and text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required , End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<body>` tag is given with:

```html
HTML/XHTML: <details> ... </details>
```

The example below shows the `<details>` tag in action.

```html
<details>
    <summary>What is HTML?</summary>
    <p>HTML is a markup language for describing the structure of web pages.</p>
</details>
```

<div class="note">
<p>Note: You may (and should) provide alternate content inside the &lt;details&gt; element. That content will be rendered both on older browsers that don't support details and in browsers with JavaScript disabled.</p></div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<details>` tag.


## Global Attributes

Like all other HTML tags, the `<details>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<details>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;body&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

