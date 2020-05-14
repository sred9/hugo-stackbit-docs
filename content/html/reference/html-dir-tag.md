---
title: HTML <dir> Tag
weight: 2
template: docs
---	
## Description

The `<dir>` (short for directory) tag specifies a directory list. It was designed to be used for creating multicolumn directory lists.

The following table summarizes the usages context and the version history of this tag.

<table dir="width:100%">
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;li&gt;</code> elements that are constrained to contain inline content only</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01</td>
  </tr>
</table>	

<div class="warning">
<p>
Warning: Do not use this tag as it has been deprecated in HTML 4.01 and obsolete since HTML5. Use the <code>&lt;ul&gt;</code> tag instead.</p>
</div>

## Syntax

The basic syntax of the `<dir>` tag is given with:

```html
HTML/XHTML: <dir> ... </dir>
```

The example below shows the `<dir>` tag in action.

```html
<!--Example of bad usage. Don't use this tag-->
<dir>
    <li>examples</li>
    <li>tutorials</li>
</dir>
<!--Alternative-->
<ul>
    <li>examples</li>
    <li>tutorials</li>
</ul>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<dir>` tag.

## Global Attributes

Like all other HTML tags, the `<dir>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<dir>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;dir&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
