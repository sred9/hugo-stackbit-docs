---
title: HTML <ruby> Tag
weight: 2
template: docs
---	
## Description

The `<ruby>` element represents a ruby annotation. Ruby annotations are used for showing pronounciation of East Asian characters, like Chinese and Japanese Chinese.

The `<ruby>` element is used with the `<rt>` element to create annotations or pronunciation guides for words and phrases. The base text should be enclosed in a `<ruby>` tag; the annotation, enclosed in an `<rt>` tag, will appear as smaller text above the base text.

The optional `<rp>` element can be used to wrap parentheses around the ruby text to indicate the presence of a ruby annotation for browsers that do not support this formatting.	

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
    <td>HTML 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<ruby>` tag is given with:

```html
HTML/XHTML: <ruby> ... </ruby>
```

The example below shows the `<ruby>` tag in action.

```html
<ruby>
  漢 <rp>(</rp><rt>Kan</rt><rp>)</rp>
  字 <rp>(</rp><rt>ji</rt><rp>)</rp>
</ruby>
```

# Tag-Specific Attributes
The <code>&lt;ruby&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<ruby>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<ruby>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;ruby&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

