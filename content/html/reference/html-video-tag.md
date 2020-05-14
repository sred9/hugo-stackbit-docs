---
title: HTML <video> Tag
weight: 2
template: docs
---	
## Description

The `<video>` element is used to embed video content in an HTML document without requiring any additional plugin like Flash player. Support for the `<video>` element varies accross browsers. At the moment, there are three main video formats that is supported for the video element: MP4, Ogg and WebM.

This element is intended as a way to encode dates and times in a machine-readable format, so that user agents can offer to add event reminders such as birthdays and anniversaries, or any event scheduling for user's calendar.

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

The basic syntax of the `<video>` tag is given with:

```html
HTML/XHTML: <video> ... </video>
```

The example below shows the `<video>` tag in action.

```html
<video controls="controls" src="shuttle.mp4">
    Your browser does not support the HTML5 Video element.
</video>
```

A video, using the browser default set of controls, with alternative sources.

```html
<video controls="controls">
    <source src="shuttle.mp4" type="video/mp4">
    <source src="shuttle.ogv" type="video/ogg">
    Your browser does not support the HTML5 Video element.
</video>
```

<div class="tip"><p><strong>Tip:</strong> You can place content such as text or download link inside a video element to provide alternate content in case, if the browser does not support the video content or somehow failed to download the video source file.</p></div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;video&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<video>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<video>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;video&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

