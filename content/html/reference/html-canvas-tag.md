---
title: HTML <canvas> Tag
weight: 2
template: docs
---	
## Description

The `<canvas>` element defines a region in the document, which can be used to draw graphics on the fly via scripting (usually JavaScript). For example, it can be used to draw path and shapes, graphs or even perform animations.

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

The basic syntax of the `<canvas>` tag is given with:

```html
HTML/XHTML: <canvas> ... </canvas>
```

The example below shows the `<canvas>` tag in action.

```html
<canvas id="myCanvas" width="300" height="200"></canvas>
<script type="text/javascript">
    window.onload = function(){
        var canvas = document.getElementById("myCanvas");
        var context = canvas.getContext("2d");
        context.moveTo(50, 150);
        context.lineTo(250, 50);
        context.stroke();
    };
</script>              
```

<div class="note">
<p><strong>Note:</strong> You may (and should) provide alternate content inside the canvas element. That content will be rendered both on older browsers that don't support canvas and in browsers with JavaScript disabled.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;canvas&gt; tag.

## Global Attributes

Like all other HTML tags, the `<canvas>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<canvas>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;canvas&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

