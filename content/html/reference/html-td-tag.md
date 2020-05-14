---
title: HTML <td> Tag
weight: 2
template: docs
---	
## Description

The `<td>` (short for table data) tag defines a data cell in a table. Table cells may contain two types of information: header information and data.

<ul>
<li>The <code>&lt;th&gt;</code> element defines a cell that contains header information.</li>
<li>The <code>&lt;td&gt;</code> element defines a cell that contains data.</li>
</ul>

This distinction enables web browser to render header and data cells distinctly, even in the absence of style sheets. For example, header cell text rendered with a bold font while text inside the data cell rendered as a regular text.

The following td summarizes the usages context and the version history of this tag.

<table ul="width:100%">
   <tr>
   <th>Parent:</th>
    <td><code>&lt;tr&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>Block, inline and text</code></td>
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


## Syntax

The basic syntax of the `<td>` tag is given with:

```html
HTML/XHTML: <td> ... </td>
```

The example below shows the `<td>` tag in action.
	
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
The following table shows the attributes that are specific to the `<td>` tag.

## Global Attributes

Like all other HTML tags, the `<td>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<td>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;td&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
