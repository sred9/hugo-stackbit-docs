---
title: HTML <object> Tag
weight: 2
template: docs
---	
## Description

The `<object>` tag defines an embedded object within an HTML document. It is used to include a variety of different kinds of media files into a document such as videos, audio, Java applets, ActiveX, PDF document, Flash animations or even images. You can also use the `<object>` element to embed another webpage into your HTML document.

<div class="note"><p><strong>Note:</strong> The <code>&lt;param&gt;</strong> element is used to pass parameters to the plugins that have been embedded with the <code>&lt;object&gt;</strong> element.</p></div>

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td>Block, inline, and text; any <code>&lt;param&gt;</code> elements must come first</td>
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

The basic syntax of the `<object>` tag is given with:

```html
HTML/XHTML: <object data="URL" type="content-type"> ... </object>
```

The example below shows the `<object>` tag in action.

```html
<object type="application/x-shockwave-flash">
    <param name="movie" value="video/blur.swf">
</object>
```

<div class="tip"><p><strong>Tip:</strong> It is recommended to use the type when data is specified since it allows the browser to avoid loading information for unsupported content types.</p></div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;object&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<object>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<object>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;object&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

