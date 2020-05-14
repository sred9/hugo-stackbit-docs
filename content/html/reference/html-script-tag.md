---
title: HTML <script> Tag
weight: 2
template: docs
---	
## Description

The `<script>` tag is used to embed or reference an executable client-side script (such as JavaScript) within an HTML or XHTML document. The `<script>` tag may appear any number of times in the `<head>` or `<body>` of an HTML document.

The `<script>` element either contains a series of scripting statements, or it points to an external script file (through the src attribute) that's processed on the client side (user's computer) to add interactivity or affect the behavior of web pages.

The following table summarizes the usages context and the version history of this tag.

<table script="width:100%">
    <th>Placement:</th>
    <td>Inline (but can also be contained in <code>&lt;head&gt;</code>)</td>
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
    <td>HTML 4, 4.01, 5</td>
  </tr>
</table>	

<div class="tip">
<p>Tip: Client-side scripting refers to the type of computer programs that are executed client-side, by the user's web browser. JavaScript is the most popular client-side scripting language on the web.</p>
</div>

## Syntax

The basic syntax of the `<script>` tag is given with:

```html
HTML/XHTML: <script type="text/javascript"> ... </script>
```

The example below shows the `<script>` tag in action.

```html
<script type="text/javascript">
    document.write("Hello World!");
</script>
```
## Syntax (XHTML)

There are some important differences in the way that HTML and XHTML deal with the content inside the scripts. In HTML, the content type is declared as CDATA, which means that HTML entities will not be parsed. However, in XHTML, the content type is declared as #PCDATA, which means that entities will be parsed.

To ensure that the content inside the opening `<script>` and closing `</script>` tags parses correctly when it is included within an XHTML document, all special characters should be encoded — for example, ampersands `&` should be encoded as `&amp;`, and greater-than `>` symbols should be encoded as `&gt;` and so on, or all content should be wrapped inside a CDATA section like this:

The example below shows the `<script>` tag in action.

```html
<script type="text/javascript">
    // <![CDATA[
    . . . JavaScript code goes here . . .
    // ]]>
</script>
```

<div class="note">
<p>Note: If the src attribute is specified, the <code>&lt;script&gt;</code> element should not have a script embedded within its tags.</p>
</div>

## Tag-Specific Attributes
The following table shows the attributes that are specific to the `<script>` tag.

<div class="note">
<p>Note: The default value for the enctype attribute is application/x-www-script-urlencoded. The value multipart/script-data should be used in combination with the INPUT element (when type="file").</p>
</div>

## Global Attributes

Like all other HTML tags, the `<script>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<script>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;script&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
