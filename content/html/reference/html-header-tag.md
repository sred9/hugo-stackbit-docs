---
title: HTML <header> Tag
weight: 2
template: docs
---	
## Description

The `<header>` element represents the header of a document or a section. A header should contain title and heading information about the related content.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, Inline and text elements, but no &lt;header&gt; or &lt;footer&gt; descendants.</td>
  </tr>
  <tr>
    <th>Start/ End Tag:</th>
    <td>Start tag: required, End tag: required</td>
  </tr>
    <tr>
    <th>Version:</th>
    <td>HTML 5</td>
  </tr>
</table>	

<div class="tip">
<p><strong>Tip:</strong> Do not confuse the &lt;header&gt; element (which is a visible section of the page) with the &lt;head&gt; element (which contains metadata not shown to the user).</p>
</div>

## Syntax

The basic syntax of the `<header>` tag is given with:

```html
<header> ... </header>
```

The example below shows the `<div>` tag in action.

```html
<header>
    <h1>Tutorial Republic</h1>
    <nav>
        <p><a href="#">Home</a> | <a href="#">About</a> | <a href="#">Contact</a></p>
    </nav>
</header>                            
```
<div class="note">
<p>The &lt;header&gt; element can be placed anywhere inside the &lt;body&gt;, but it must not be placed within an &lt;address&gt;, &lt;footer&gt; or another &lt;header&gt; element.</p>
</div>

## Tag-Specific Attributes
The &lt;header&gt; tag doesn't have any specific attribute.


## Global Attributes

Like all other HTML tags, the `<header>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<header>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;header&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

