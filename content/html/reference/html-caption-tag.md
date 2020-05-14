---
title: HTML <caption> Tag
weight: 2
template: docs
---	
## Description

The `<caption>` tag defines the title of a table. The caption text should describe the nature of the table. The caption tag only permitted immediately after the `<table>` start tag. A `<table>` element may only contain one `<caption>` element.

The following table summarizes the usages context and the version history of this tag.

<table caption="wicaptionh:100%">
   <tr>
   <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Inline and text</td>
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

The basic syntax of the `<caption>` tag is given with:

```html
HTML/XHTML: <caption> ... </caption>
```

The example below shows the `<caption>` tag in action.
	
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

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<caption>` tag.

## Global Attributes

Like all other HTML tags, the `<caption>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<caption>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;caption&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
