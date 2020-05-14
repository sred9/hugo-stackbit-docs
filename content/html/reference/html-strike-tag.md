---
title: HTML <strike> Tag
weight: 2
template: docs
---	
## Description

The `<strike>` (short for strikethrough) element renders the enclosed text in strikethrough style i.e. with a line drawn through it.

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
    <td>HTML 3.2, 4, 4.01 (transitional)</td>
  </tr>
</table>	

<div class="important">
<p><strong>Warning:</strong> Do not use this tag as it has been deprecated in HTML 4.01 and obsolete in HTML5. Use the <code>&lt;del&gt;</code> element instead if enclosed text represents deleted text, otherwise use the CSS text-decoration property, with the line-through value.</p>
</div>

## Syntax

The basic syntax of the `<strike>` tag is given with:

```html
HTML/XHTML: <strike> ... </strike>
```

The example below shows the `<strike>` tag in action.

```html
<!--Example of bad usage. Don't use this tag-->
<p>Here is some <strike>strikethrough</strike> text.</p>
<!--Alternative-->
<p>Here is a good example of <span style="text-decoration: line-through;">strikethrough</span> text.</p>
```

<div class="note">
<p><strong>Note:</strong>  The <code>&lt;strike&gt;</code> is identical in purpose to the <code>&lt;s&gt;</code> tag, which also specifies that the enclosed text should be rendered a line through it.</p>
</div>

# Tag-Specific Attributes
The <code>&lt;strike&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<strike>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<strike>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;strike&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

