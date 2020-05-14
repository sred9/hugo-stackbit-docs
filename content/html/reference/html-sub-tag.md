---
title: HTML <sub> Tag
weight: 2
template: docs
---	
## Description

<p>The <code>&lt;sub&gt;</code> (short for subscript) tag renders enclosed text as subscript. Subscript text appears half a character's height below the baseline, and is most often used in mathematical (e.g. <code>y = log<sub>a</sub>x</code>) or chemical formulas, like <code>H<sub>2</sub>O</code>.</p>

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
    <td>HTML 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="note">
<p><strong>Usage Notes:</strong></p>
<ul>
<li>]The <code>&lt;sub&gt;</code> tag should be used for typographical reasons only.</li>
<li>This tag must not be used for styling purpose like changing the vertical position of the text. In that case CSS should be used instead: the vertical-align property with the sub value will achieve the same effect.</li>
</ul>
</div>

## Syntax

The basic syntax of the `<sub>` tag is given with:

```html
HTML/XHTML: <sub> ... </sub>
```

The example below shows the `<sub>` tag in action.

```html
<p>The chemical formula of Water is: H<sub>2</sub>O</p>
<p>The chemical formula of Carbon Dioxide is: CO<sub>2</sub></p>
```

<div class="note">
<p><sub>Note:</sub>  The <code>&lt;sub&gt;</code> is identical in purpose to the <code>&lt;s&gt;</code> tag, which also specifies that the enclosed text should be rendered a line through it.</p>
</div>

# Tag-Specific Attributes
The <code>&lt;sub&gt;</code> tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<sub>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<sub>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;sub&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

