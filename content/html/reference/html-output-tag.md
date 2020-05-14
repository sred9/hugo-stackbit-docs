---
title: HTML <output> Tag
weight: 2
template: docs
---	
## Description

The `<output>` element represents the result of a calculation. Typically this element defines a region that will be used to display text output from some calculation that is usually performed by a client-side script (usually JavaScript).

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

The basic syntax of the `<output>` tag is given with:

```html
HTML/XHTML: <output> ... </output>
```

The example below shows the `<output>` tag in action.

```html
<form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
    <input type="range" id="a" value="50"> +
    <input type="number" id="b" value="100"> =
    <output name="result" for="a b"></output>
</form>
```

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;output&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<output>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<output>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;output&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

