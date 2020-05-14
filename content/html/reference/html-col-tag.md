---
title: HTML <col> Tag
weight: 2
template: docs
---	
## Description

The `<col>` tag represents one or more columns in the column-group defined by the `<colgroup>` element. It is useful for applying style rules to entire columns, rather than repeating the styles for each cell, row after row.

The following table summarizes the usages context and the version history of this tag.

<table>
   <tr>
   <th>Parent:</th>
    <td><code>&lt;colgroup&gt;</code>, <code>&lt;table&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>None. It is an empty element.</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: forbidden</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 4, 4.01, 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<col>` tag is given with:

```html
HTML:<col>; XHTML:<col />
```

The example below shows the `<col>` tag in action.
	
```html
<table>
    <colgroup>
        <col style="background-color:#adff2f;">
        <col span="2" style="background-color:#f0e68c;">
    </colgroup>
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
The following table shows the attributes that are specific to the `<col>` tag.

## Global Attributes

Like all other HTML tags, the `<col>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<col>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;col&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
