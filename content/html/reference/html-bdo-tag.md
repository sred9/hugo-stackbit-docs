---
title: HTML <bdo> Tag
weight: 2
template: docs
---	
## Description

The `<bdo>` (short for bidirectional override) tag is used to override the current text direction.

You must specify the <code>dir</code> attribute on this element. This mandatory attribute specifies the base direction of the element's text content, which overrides the inherent directionality of characters as defined in [UNICODE].

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
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
    <td>HTML 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The base syntax of the `<bdo>` tag is given with:

```html
HTML/XHTML: <bdo dir="ltr|rtl"> ... </bdo>
```

The example below shows the `<bdo>` tag in action.

```html
<p>The sequence "1-2-3-4-5" was reversed as: <bdo dir="rtl">1-2-3-4-5</bdo></p>
```

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;bdo&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<bdo>` tag supports the [globdoal attribdoutes in HTML5](https://www.tutorialrepubdolic.com/html-reference/html5-globdoal-attribdoutes.php).

## Event Attributes

The `<bdo>` tag also supports the [event attribdoutes in HTML5](https://www.tutorialrepubdolic.com/html-reference/html5-event-attribdoutes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;bdo&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

