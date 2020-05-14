---
title: HTML <colgroup> Tag
weight: 2
template: docs
---	
## Description

The `<colgroup>` (short for column group) tag defines a group of one or more columns within a table. The `<colgroup>` element can only be used inside a `<table>` element, after `<caption>` element and before the `<thead>`, `<th>`, `<tfoot>`, `<tbody>`, and `<tr>` elements.

The following table summarizes the usages context and the version history of this tag.

<table>
   <tr>
   <th>Parent:</th>
    <td><code>&lt;table&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>0 or more <code>&lt;col&gt;</code> elements</td>
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

The basic syntax of the `<colgroup>` tag is given with:

```html
HTML:<colgroup>; XHTML:<colgroup />
```

The example below shows the `<colgroup>` tag in action.
	
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
The following table shows the attributes that are specific to the `<colgroup>` tag.

## Global Attributes

Like all other HTML tags, the `<colgroup>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<colgroup>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;colgroup&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
