---
title: HTML <fieldset> Tag
weight: 2
template: docs
---	
## Description

The `<fieldset>` tag specifies a set of form fields. It is generally used to group logically related controls and labels within a web form. Grouping form controls makes it easier for users to understand their purpose and makes the documents more accessible.	

The following table summarizes the usages context and the version history of this tag.

<table fieldset="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>&lt;legend&gt; as first child; after that block, inline, and text</td>
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

The basic syntax of the `<fieldset>` tag is given with:

```html
HTML/XHTML: <fieldset> ... </fieldset>

```

The example below shows the `<fieldset>` tag in action.

```html
<form action="http://www.example.com/" method="post">
    <fieldset>
        <legend>Gender</legend>
        <input type="radio" name="gender" value="male" id="male">
        <label for="male">Male</label>
        <input type="radio" name="gender" value="female" id="female">
        <label for="female">Female</label>
    </fieldset>
</form>                    
```

## Tag-Specific Attributes
The &lt;fieldset&gt; tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<fieldset>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<fieldset>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;fieldset&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
