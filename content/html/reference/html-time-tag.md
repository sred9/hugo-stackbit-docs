---
title: HTML <source> Tag
weight: 2
template: docs
---	
## Description

The `<source>` element represents a time and/or date.

This element is intended as a way to encode dates and times in a machine-readable format, so that user agents can offer to add event reminders such as birthdays and anniversaries, or any event scheduling for user's calendar.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td>Inline and text, but no descendant <code>&lt;time&gt;</code> elements</td>
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

The basic syntax of the `<source>` tag is given with:

```html
HTML/XHTML: <time> ... </time>
```

The example below shows the `<source>` tag in action.

```html
<p>The library opens at <time>8:30 am</time> every morning.</p>
<p>The concert took place on <time datetime="2016-12-31 12:00">31 Dec</time>.</p>
```

## Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;source&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<source>` tag supports the [global attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-global-attributes.php).

## Event Attributes

The `<source>` tag also supports the [event attributes in HTML5](https://www.tutorialrepublic.com/html-reference/html5-event-attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;source&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

