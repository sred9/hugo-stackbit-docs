---
title: HTML <audio> Tag
weight: 2
template: docs
---	
## Description

The `<audio>` element is used to embed audio content in an HTML document without requiring any additional plug-in like Flash player.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;source&gt;</code>, <code>&lt;track&gt;</code>, and text</td>
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

The basic syntax of the `<audio>` tag is given with:

```html
HTML/XHTML: <audio> ... </audio>
```

<div class="note">
<p><strong>Note:</strong>  In HTML, the end tag for the <code>&lt;audio&gt;</code> tag is forbidden. In XHTML, the <code>&lt;audio&gt;</code>  tag must be closed with a trailing slash, like this: <code>&lt;audio /&gt;</code> . See empty elements.</p>
</div>

The example below shows the `<audio>` tag in action.

```html
<audio controls="controls" src="birds.mp3">
    Your browser does not support the HTML5 Audio element.
</audio>               
```

An audio, using the browser default set of controls, with alternative sources.

```html
<audio controls="controls">
    <source src="birds.mp3" type="audio/mpeg">
    <source src="birds.ogg" type="audio/ogg">
    Your browser does not support the HTML5 Audio element.
</audio>              
```

<div class="tip">
<p><strong>Tip:</strong> You can place content such as text or download link inside an audio element to provide alternate content in case, if the browser does not support the audio content or somehow failed to download the audio source file.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;audio&gt; tag.

## Global Attributes

Like all other HTML tags, the `<audio>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<audio>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;audio&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

