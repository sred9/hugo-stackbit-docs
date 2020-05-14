---
title: HTML <a> Tag
weight: 2
template: docs
---

## Description

The `<a>` (short for *anchor*) tag defines a hyperlink.

An anchor i.e. the `<a>` element can be used in two ways:

-   To create a link to another document, by using the `href` attribute.
-   To create a bookmark inside a document, by using the `id` attribute.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Inline, and text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required , End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

```html
<a href="https://www.w3.org/">W3C Website</a>
```

This link designates the home page of the 'World Wide Web Consortium' website. When a user click on it, the web browser will retrieve the resource, in this case, an HTML document.
<hr>

<div class="note">
  <strong>Note:</strong>
The most important attribute of the &lt;a&gt; tag is the href attribute, which indicates the destination of an hyperlink.
</div>

By default, links will appear as follows in most of the browsers:

-   An unvisited link is underlined and blue.
-   A visited link is underlined and purple.
-   An active link is underlined and red.

However you can overwrite this using CSS. Learn more about [styling links](https://www.tutorialrepublic.com/css-tutorial/css-links.php).
## Syntax

The basic syntax of the `<a>` tag is given with:

```html
HTML/XHTML:* <a href\="*URL*"> ... </a>
```

The example below shows the `<a>` tag in action.

```html
<a href="https://www.tutorialrepublic.com/">Tutorial Republic</a>
<a href="kites.jpg"><img src="kites-thumb.jpg" alt="kites"></a>
<a href="https://www.google.com/">Google Search</a>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<a>` tag.
## Global Attributes

Like all other HTML tags, the `<a>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<a>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;a&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

