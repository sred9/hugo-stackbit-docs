---
title: HTML <title> Tag
weight: 2
template: docs
---	
## Description

The `<title>` tag defines the title of the document. The `<title>` element should be the first element defined in the head section of the document. The title should be meaningful because it summarizes the content or purpose of the document.

The `<title>` element is very important, because its content is used by the:

### Web browsers

-   To display the page title in the web browser's title (top of a browser) and tab(s).
-   To label the web page when it is bookmarked or added as a favorite.

### Search engines

-   To display a clickable headline for the web page when it listed on the Search Engine Result Pages (SERPs).
-   To determine the topic of the web page. Search Engine spiders or crawlers analyze the content of the page title and then decide the page topic.
	
The following table summarizes the usages context and the version history of this tag.

<table title="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;head&gt;</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Text</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="note">
<p>Note: Every HTML document must contain one and exactly one &lt;title&gt; element in the head section. The title should ideally be 65 characters in length.</p>
</div>

## Syntax

The basic syntax of the `<title>` tag is given with:

```html
HTML/XHTML: <title> ... </title>

```

The example below shows the `<title>` tag in action.

```html
<!DOCTYPE html>
<html>
<head>
    <title>A simple HTML document</title>
</head>
<body>
    <p>Hello World!</p>
</body>
</html>                       
```

## Tag-Specific Attributes
The &lt;title&gt; tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<title>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<title>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;title&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
