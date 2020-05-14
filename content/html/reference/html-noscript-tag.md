---
title: HTML <noscript> Tag
weight: 2
template: docs
---	
## Description

The `<noscript>` tag is used to provide an alternate content for users that have disabled scripts in their browser or the browser doesn't recognize the scripting language, or have a browser that doesn't support client-side scripting.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, inline, and text when it isn't a descendant of the <code>&lt;head&gt;</code> element; Otherwise <code>&lt;link&gt;</code>, <code>&lt;style&gt;</code>, and <code>&lt;meta&gt;</code> elements.</td>
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
<ul>
<p>The content inside the <code>&lt;noscript&gt;</code> element will only be displayed by a browser if:</p>
<li>The browser is configured not to evaluate scripts.</li>
<li>The browser doesn't support the scripting language invoked by a <code>&lt;script&gt;	</code> element earlier in the document.</li>
<li>Or, the browser doesn't support client-side scripts.</li>
</ul>
</div>

## Syntax

The basic syntax of the `<noscript>` tag is given with:

```html
HTML/XHTML: <noscript> ... </noscript>
```

The example below shows the `<noscript>` tag in action.

```html
<script type="text/javascript">
    document.write("Hello World!")
</script>
<noscript>Your browser does not support JavaScript!</noscript>
```

## Tag-Specific Attributes
The `<noscript>` tag doesn't have any specific attribute.

## Global Attributes

Like all other HTML tags, the `<noscript>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<noscript>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;noscript&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |
