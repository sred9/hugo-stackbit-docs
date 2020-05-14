---
title: HTML <thead> Tag
weight: 2
template: docs
---	
## Description

The `<thead>` (short for table head) element defines a table's header. It is used to group a set of rows defining the header of the columns within the table.

This element must appear as a child of a <code>&lt;table&gt;</code> element, after any <code>&lt;caption&gt;</code> and <code>&lt;colgroup&gt;</code> elements, but before any <code>&lt;tbody&gt;</code>, <code>&lt;thead&gt;</code> and <code>&lt;tr&gt;</code> element. The <code>&lt;thead&gt;</code> tag must contain at least one row, defined by the <code>&lt;tr&gt;</code> tag.

The following thead summarizes the usages context and the version history of this tag.

<table ul="width:100%">
   <tr>
   <th>Parent:</th>
    <td><code>&lt;table&gt;</code></td>
  </tr>
  <tr>
    <th>Content:</th>
    <td><code>&lt;tr&gt;</code></td>
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
<p>Usage Notes</p>
<ul>
<li>Table rows may be grouped into a table head, table foot, and one or more table body sections, using the <code>&lt;thead&gt;</code>, <code>&lt;thead&gt;</code> and <code>&lt;tbody&gt;</code> tags, respectively.</li>
<li>This division enables the browser to support scrolling of table bodies independently of the table head and foot sections. Also, when long tables are printed that spans multiple pages, the table head and foot information may be printed on each page that contains table data.</li>
<li>When present, each <code>&lt;thead&gt;</code>, <code>&lt;thead&gt;</code> and <code>&lt;tbody&gt;</code> contains a row group. Each row group must contain at least one row, defined by the <code>&lt;tr&gt;</code> tag.</li>
</ul>
</div>

## Syntax

The basic syntax of the `<thead>` tag is given with:

```html
HTML/XHTML: <thead> ... </thead>
```

The example below shows the `<thead>` tag in action.
	
```html
<table>
    <thead>
        <tr>
            <th>No.</th>
            <th>Name</th>
            <th>Email</th>
        </tr>
    </thead>
    <tbody>
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
    </tbody>
</table>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<thead>` tag.

## Global Attributes

Like all other HTML tags, the `<thead>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<thead>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;thead&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
