---
title: HTML <menu> Tag
weight: 2
template: docs
---	
## Description

The `<menu>` element defines a list (or menu) of commands that a user can perform.

The following table summarizes the usages context and the version history of this tag.

<table menu="wimenuh:100%">
   <tr>
   <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;menu&gt;</code>, <code>&lt;menuitem&gt;</code>, <code>&lt;li&gt;</code>, <code>&lt;hr&gt;</code> and <code>&lt;script&gt;</code></td>
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

<div class="note"><p>
Note: The <code>&lt;menu&gt;</code> tag was deprecated in HTML 4.01, but reintroduced in HTML5. However, it is better to avoid using this tag, because it is not supported by the major web browsers like Chrome, IE, Safari and Opera.</p></div>

## Syntax

The basic syntax of the `<menu>` tag is given with:

```html
HTML/XHTML: <menu> ... </menu>
```

The example below shows the `<menu>` tag in action.
	
```html
<img src="sky.jpg" id="sky" width="250" alt="Cloudy Sky" contextmenu="skymenu">
<menu type="context" id="skymenu">
    <menuitem label="Zoom In" icon="zoom-in.png" onclick="zoomin()">
    <menuitem label="Zoom Out" icon="zoom-out.png" onclick="zoomout()">
    <menuitem label="Reload Image" icon="reload.png" onclick="window.location.reload();">
</menu>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<menu>` tag.

## Global Attributes

Like all other HTML tags, the `<menu>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<menu>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;menu&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
