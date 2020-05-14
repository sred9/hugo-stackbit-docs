---
title: HTML <style> Tag
weight: 2
template: docs
---	
## Description

The `<style>` tag is used to define style rules at a page-level (i.e. within the document). The style rules inside the `<style>` element tell a browser how to present the document. You can place any number of style elements in a document, but it must appear inside the head section (i.e. `<head>` element). Learn more about style rules.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;head&gt;</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Style information</td>
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

<div class="note">
<p>Note: However the &lt;style&gt; element is a good method of experimenting with style sheets, but it has disadvantages. The best way to attach style sheets to your documents is with external style sheets.</p>
</div>

## Syntax

The basic syntax of the `<style>` tag is given with:

```html
HTML/XHTML: <style type="text/css"> ... </style>

```

The example below shows the `<style>` tag in action.

```html
<head>
    <title>Presentation Demo<title>
    <style type="text/css">
        h1 {color: #666;}
    </style>
</head>                        
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;style&gt; tag.

## Global Attributes

Like all other HTML tags, the `<style>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<style>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;style&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
