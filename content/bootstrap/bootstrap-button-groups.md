---
title: Bootstrap Breadcrumbs 
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
	

A breadcrumb is a navigation scheme that indicates current page's location to the user within a website or application. Breadcrumb navigation can greatly enhance the accessibility of a website having a large number of pages or complex navigational hierarchy.

You can create static breadcrumbs layouts with Bootstrap simply using the class `.breadcrumb` on the ordered lists, as demonstrated in the following example:

```html
	<nav>
		<ol class="breadcrumb">
			<li class="breadcrumb-item"><a href="#">Home</a></li>
			<li class="breadcrumb-item"><a href="#">Products</a></li>
			<li class="breadcrumb-item active">Accessories</li>
		</ol>
	</nav>
```

— The output of the above example will look something like this:

The default breadcrumb separator is `/`. But, you can change it with a little custom CSS, for example, if you want to use `>` as separator, you can apply the following style rules:

```css
	.breadcrumb-item + .breadcrumb-item::before {
		content: ">";
	}
```

— The output of the above example will look something like this:

<div class="tip"><p><strong>Tip:</strong>Separators inside the breadcrumb components are added automatically via CSS through the `::before` pseudo-element and the `content` property.</p>
</div>