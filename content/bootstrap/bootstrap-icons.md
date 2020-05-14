---
title: Bootstrap Icons 
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
The new Bootstrap 4 version doesn't include an icon library by default, unlike the previous Bootstrap 3 version that includes Glyphicons in the font format in its core.

However, you can still include icons in your project using several external font based icon library. The most popular and highly compatible icon library for Bootstrap is Font Awesome. It provides 675 icons which are available in font format for better usability and scalability.

The advantage of using font icons is, you can create icons of any color just through applying the CSS `color` property. Let's see how to include font-awesome icons in a web page.

## How to Include Font Awesome

To use font-awesome icons in your code you'll require an `<i>` tag along with a base class .fa and an individual icon class `.fa-*`. The general syntax for using font-awesome icons is:

```html
<i class="fa fa-class-name"></i>
```

## How to Use Font Awesome Icons in Your Code

To use font-awesome icons in your code you'll require an `<i>` tag along with a base class `.fa` and an individual icon class `.fa-*`. The general syntax for using font-awesome icons is:

```html
<i class="fa fa-class-name"></i>
```

Where fa-class-name is the name of the particular icon class (e.g. `fa-search`, `fa-user`, `fa-star`, `fa-calendar`, `fa-globe`, etc.) defined in font-awesome.min.css file.

For example, to use search icon you can place the following code just about anywhere:

```html
<button type="submit" class="btn btn-primary"><span class="fa fa-search"></span> Search</button>
<button type="submit" class="btn btn-secondary"><span class="fa fa-search"></span> Search</button>
```

— The output of the above example will look something like this:

Similarly, you can place icons inside the headings, paragraphs, tables, or anywhere you want. In the next chapter you will see how to use these icons in Bootstrap nav components.

<div class="note"><p><strong>Note:</strong> Remember to leave a space after the closing tag of icon element (i.e. after `</i>` tag), when using the icons along with the strings of text such as inside buttons or navigation links, to ensure proper spacing between the icon and text.</p></div>