---
title: HTML <summary> Tag
weight: 2
template: docs
---	
## Description

The `<summary>` element defines a summary for the `<details>` element.

The `<summary>` element is used along with the `<details>` element to provide a summary visible to the user. When the user clicks the summary, the additional information or content placed inside the `<details>` element which was previously hidden becomes visible.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Permitted Parent:</th>
    <td>&lt;details&gt;</td>
  </tr>
  <tr>
    <th>Content</th>
    <td>Inline and text</td>
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

The basic syntax of the `<summary>` tag is given with:

```html
HTML/XHTML: <summary> ... </summary>
```

The example below shows the `<summary>` tag in action.

```html
<details> 
	<summary>What is HTML?</summary> 
	<p>HTML is a markup language for describing the structure of web pages.</p> 
</details>
```

<div class="note">
<p>Note:  The <code>&lt;summary&gt;</code> element should be the first child element of the <code>&lt;details&gt;</code> element. If it is omitted or not specified the heading "Details" will be used.</p>
</div>

## Tag-Specific Attributes
The &lt;summary&gt; tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<summary>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<summary>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;summary&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

