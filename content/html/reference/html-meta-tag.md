---
title: HTML <meta> Tag
weight: 2
template: docs
---	
## Description

The `<meta>` tag provides structured metadata about the document. The `<meta>` element may only appear in the head section of a document, although it may appear any number of times.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Parent:</th>
    <td>&lt;head&gt;</td>
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
    <td>HTML 2, 3.2, 4, 4.01, 5</td>
  </tr>
</table>	

<div class="note">
<p>Note: Metadata is data (information) about data – for example, keywords and description that relate to the document.</p>
</div> 

The `<meta>` tag commonly used to provide keywords, descriptions, author information, and other metadata that may be used by the browser to render the document correctly, or it may be used by the search engines for indexing purposes. Here's some real world examples to help you understand `<meta>` tag.

Example 1: Define the character encoding for the document
&lt;meta charset=&quot;UTF-8&quot;&gt;

Example 2: Defines the author name of the document

&lt;meta name=&quot;author&quot; content=&quot;John Smith&quot;&gt;
Example 3: Defines a list of keywords for search engines

&lt;meta name=&quot;keywords&quot; content=&quot;HTML,CSS,Tutorials,References,Examples&quot;&gt;
Example 4: Define a brief summery/description of the web page

&lt;meta name=&quot;description&quot; content=&quot;HTML/CSS Tutorials and References&quot;&gt;
Example 5: Enable zooming in mobile devices

&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1&quot;&gt;

## Syntax

The basic syntax of the `<meta>` tag is given with:

```html
HTML:<meta name="text" content="text">
XHTML:<meta name="text" content="text" />
```

The example below shows the `<meta>` tag in action.

```html
<head>
    <title>Example of HTML meta tag</title>
    <meta http-equiv="content-type" content="text/html;charset=UTF-8">
    <meta name="description" content="Free Web tutorials">
    <meta name="keywords" content="HTML,CSS,References,Examples">
</head>                         
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the &lt;meta&gt; tag.

## Global Attributes

Like all other HTML tags, the `<meta>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<meta>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;meta&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
