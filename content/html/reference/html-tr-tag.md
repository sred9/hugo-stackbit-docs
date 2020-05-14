---
title: HTML <tr> Tag
weight: 2
template: docs
---	
## Description

The `<tr>` (short for table row) element defines a row of cells in a table. The `<tr>` element acts as a container for table cells and contains one or more `<th>` or `<td>` elements.

The following table summarizes the usages context and the version history of this tag.

<table ul="width:100%">
   <tr>
   <th>Parent:</th>
    <td><code>&lt;thead&gt;</code>, <code>&lt;tfoot&gt;</code>, <code>&lt;tbody&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;th&gt;</code>, <code>&lt;td&gt;</code></td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: optional</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 3.2, 4, 4.01, 5</td>
  </tr>
</table>			

## Syntax

The basic syntax of the `<tr>` tag is given with:

```html
HTML/XHTML: <tr> ... </tr>
```

The example below shows the `<tr>` tag in action.
	
```html
<table>
    <tr>
        <th>No.</th>
        <th>Name</th>
        <th>Email</th>
    </tr>
    <tr>
        <td>1</td>
        <td>John Carter</td>
        <td>johncarter@mail.com</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Peter Parker</td>
        <td>peterparker@mail.com</td>
    </tr>
    <tr>
        <td>3</td>
        <td>John Rambo</td>
        <td>johnrambo@mail.com</td>
    </tr>
</table>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<tr>` tag.

## Global Attributes

Like all other HTML tags, the `<tr>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<tr>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;tr&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
