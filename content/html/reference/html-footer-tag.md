---
title: HTML <footer> Tag
weight: 2
template: docs
---	
## Description

The `<footer>` element represents the footer of a document or a section.

A footer typically contains information about the author of the document, copyright information, links to related documents etc. The following table summarizes the usages context and the version history of this tag.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Block</td>
  </tr>
  <tr>
    <th>Content:</th>
    <td>Block, Inline and text, but no &lt;footer&gt; or &lt;header&gt;</td>
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


## Syntax

The basic syntax of the `<footer>` tag is given with:

```html
HTML/XHTML: <footer> ... </footer>
```

The example below shows the `<footer>` tag in action.

```html
<footer>
	<nav>
		<p>
			<a href="https://www.tutorialrepublic.com/terms-of-use.php">Terms of Use</a> |
			<a href="https://www.tutorialrepublic.com/privacy-policy.php">Privacy Policy</a>
		</p>
	</nav>
	<p>Copyright &copy; 2014 Tutorial Republic</p>
</footer>                            
```
<div class="note">
<p>Note: The &lt;footer&gt; element can be placed anywhere inside the &lt;body&gt;, but it must not be placed within an &lt;address&gt;, &lt;header&gt; or another &lt;footer&gt; element.</p>
</div>

## Tag-Specific Attributes
The &lt;footer&gt; tag doesn't have any specific attribute.


## Global Attributes

Like all other footer tags, the `<footer>` tag supports the [global attributes in footer5](https://www.tutorialrepublic.com/footer-reference/footer5-global-attributes.php).

## Event Attributes

The `<footer>` tag also supports the [event attributes in footer5](https://www.tutorialrepublic.com/footer-reference/footer5-event-attributes.php).
## Browser Compatibility
|  Element |<i class="cfooterome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;footer&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

