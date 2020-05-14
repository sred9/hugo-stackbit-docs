---
title: HTML <table> Tag
weight: 2
template: docs
---	
## Description

The `<table>` tag is used to represents data in a grid-like fashion (in rows and columns).

The following table summarizes the usages context and the version history of this tag.

<table>
   <tr>
   <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>An optional <code>&lt;caption&gt;</code>, zero or more <code>&lt;col&gt;</code> or <code>&lt;table&gt;</code> tags, optional <code>&lt;thead&gt;</code> and <code>&lt;tfoot&gt;</code>, zero or more <code>&lt;tbody&gt;</code> tags and at least one <code>&lt;tr&gt;</code></td>
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

<div class="note">
<p>Usage Notes</p>
<ul>
<li>Tables are used to organize data like, text, images, links, forms, form fields, other tables, etc. into rows and columns of cells.</li>
<li>At its most basic, a table is built using the <code>&lt;table&gt;</code> element and one or more, <code>&lt;tr&gt;</code>, <code>&lt;th&gt;</code> and <code>&lt;td&gt;</code> elements. Where the <code>&lt;tr&gt;</code> element defines a table row, the <code>&lt;th&gt;</code> element defines a table header, and the <code>&lt;td&gt;</code> element defines a table cell.</li>
<li>A more complex table may also include a <code>&lt;caption&gt;</code>, <code>&lt;col&gt;</code> and <code>&lt;table&gt;</code> elements; and the structural <code>&lt;thead&gt;</code>, <code>&lt;tbody&gt;</code>, and <code>&lt;tfoot&gt;</code> elements, which are used to identify the different regions in the table.</li>
</ul>
</div>

## Syntax

The basic syntax of the `<table>` tag is given with:

```html
HTML/XHTML: <table> ... </table>
```

The example below shows the `<table>` tag in action.
	
```html
<table>
    <caption>User Details</caption>
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

<div class="tip">
<p>Tip: Consider describing the structure of the table in a <code>&lt;caption>&gt;</code> element or, simplify the structure of the table so that no description is needed.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<table>` tag.

## Global Attributes

Like all other HTML tags, the `<table>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<table>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;table&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
