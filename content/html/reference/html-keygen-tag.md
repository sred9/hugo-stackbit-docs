---
title: HTML <keygen> Tag
weight: 2
template: docs
---	
## Description

The `<keygen>` element generates an encryption key for passing encrypted data to a server. When an HTML form is submitted, the browser will generate a key pair and store the private key in the browser's local key storage and send the public key to the server.

The following table summarizes the usages context and the version history of this tag.

<table keygen="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
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
    <td>HTML 5</td>
  </tr>
</table>	

## Syntax

The basic syntax of the `<keygen>` tag is given with:

```html
HTML: <keygen>; XHTML: <keygen />

```

The example below shows the `<keygen>` tag in action.

```html
<form action="process-key.php" method="post">
    <label>Username: <input type="text" name="username"></label>
    <label>Encryption: <keygen name="key"></label>
    <input type="submit" value="Submit">
</form>                   
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<keygen>` tag.

## Global Attributes

Like all other HTML tags, the `<keygen>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<keygen>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;keygen&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
