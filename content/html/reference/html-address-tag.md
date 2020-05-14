---
title: HTML <address> Tag
weight: 2
template: docs
---	
## Description

The `<address>` tag specifies the author's contact information.

This element is used to mark up the contact details for the author or owner of the document, so that the reader may use these details to contact the document's owner. The `<address>` element often appears at the beginning or end of a document.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td><code>&lt;p&gt;</code> inline and text</td>
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
<p><strong>Usage Notes:</strong></p>
<ul>
<li>The address tag must not be used to represent arbitrary addresses (i.e. addresses that are not relevant to the contact information).</li>
<li>The address tag must not contain information other than contact information, like a publication date (which belongs in a <code>&lt;time&gt;</code> tag).</li>
<li>Typically, the address tag should be included inside the <code>&lt;footer&gt;</code> section.</li>
</ul>
</div>

## Syntax

The basic syntax of the `<address>` tag is given with:

```html
HTML/XHTML: <address> ... </address>
```

The example below shows the `<address>` tag in action.

```html
<footer>
    <address>
        <p><a href="https://www.w3.org/Consortium/contact-mit">MIT</a></p>
    </address>
</footer>
```

<div class="note">
<p><strong>Note:</strong> Although the text content of the <code>&lt;address&gt;</code> element usually renders with the same default styling as the <code>&lt;i&gt;</code> or <code>&lt;em&gt;</code>, but it is more appropriate to use when dealing with contact information, as it conveys additional semantic information.</p>
</div>

# Tag-Specific Attributes
The <code>&lt;address&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<address>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<address>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;address&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

