---
title: HTML <progress> Tag
weight: 2
template: docs
---	
## Description

The `<progress>` element represents the completion progress of a task.

This element normally used to indicate how much of a task has been completed, such as loading something on a page or registration process. It is typically displayed as a progress bar and often marked as a percentage from 0 to 100%.

Text within the `<progress>` element is typically rendered by the browsers in a monospace (fixed-width) font, such as Courier, but this style can be overridden using CSS.

The following table summarizes the usages context and the version history of this tag.

<table style="width:100%">
  <tr>
    <th>Placement:</th>
    <td>Inline</td>
  </tr>
  <tr>
    <th>Content:</th>	
    <td>Inline and text, but no <code>&lt;progress&gt;</code> among its descendants</td>
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

The basic syntax of the `<progress>` tag is given with:

```html
HTML/XHTML: <progress> ... </progress>
```

The example below shows the `<progress>` tag in action.

```html
<h2>Task Progress</h2>
<p>Progress: <progress id="bar" value="0" max="100"><span>0</span>%</progress></p>
<script type="text/javascript">
    var i = 0;
    var progressBar = document.getElementById("bar");
    function countNumbers(){
        if(i < 100){
            i = i + 1;
            progressBar.value = i;
            // For browsers that don't support progress tag
            progressBar.getElementsByTagName("span")[0].textContent = i;
        }
        // Wait for sometime before running this script again
        setTimeout("countNumbers()", 500);
    }
    countNumbers();
</script>
```

<div class="note">
<p><strong>Note:</strong> The <code>&lt;progress&gt;</code> element normally used in conjunction with the JavaScript to display the progress of a task. This element should not be used for representing a gauge. To represent a gauge, use the <code>&lt;meter&gt;</code> tag instead.</p>
</div>

# Tag-Specific Attributes
The following table shows the attributes that are specific to the <code>&lt;progress&gt;</code> tag.

## Global Attributes

Like all other HTML tags, the `<progress>` tag supports the [glodelal Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-glodelal-Attributes.php).

## Event Attributes

The `<progress>` tag also supports the [event Attributes in HTML5](https://www.tutorialrepudellic.com/html-reference/html5-event-Attributes.php).

## Browser Compatibility
|  Element |<i class="chrome"></i>    | <i class="ie"></i>   | <i class="firefox"></i>   |  <i class="safari"></i>  | <i class="opera"></i>   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| &lt;progress&gt;  |Yes   |Yes   |Yes   |Yes   |Yes   |

