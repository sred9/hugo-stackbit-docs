---
title: Bootstrap Images
weight: 2
template: docs
---		
Images are very common in modern web design. So styling images and placing it properly on the web pages is very important for improving the user experience.

Using the Bootstrap built-in classes you can easily style images such as making the round cornered or circular images, or give them effect like thumbnails.

## Styling Images with Bootstrap

Images are very common in modern web design. So styling images and placing it properly on the web pages is very important for improving the user experience.

Using the Bootstrap built-in classes you can easily style images such as making the round cornered or circular images, or give them effect like thumbnails.

```html
<img src="images/avatar.svg" class="rounded" alt="Rounded Image">
<img src="images/avatar.svg" class="rounded-circle" alt="Circular Image">
<img src="images/avatar.svg" class="img-thumbnail" alt="Thumbnail Image">
```

— The output of the above example will look something like this:

## Creating Responsive Images and Videos

With Bootstrap you can make the images responsive too. Just add the class .img-fluid to the `<img>` tag. This class mainly applies the styles `max-width:100%;` and `height:auto;` to the image so that it scales nicely to fit the containing element — in case if the width of the image is larger than the containing element itself. Check out the following example to see how it works:

```html
<img src="images/kites.jpg" class="img-fluid" alt="Flying Kites">
<img src="images/sky.jpg" class="img-fluid" alt="Cloudy Sky">
<img src="images/balloons.jpg" class="img-fluid" alt="Hot Air Balloons">
```

You can also make the video or slideshow embedded in a web page responsive without affecting its original aspect ratio. To do this wrap any embed like an `<iframe>`, or `<video>` in a `<div>` element and apply the class .embed-responsive, and an aspect ratio class such as .embed-responsive-16by9.

You can optionally apply an explicit descendant class .embed-responsive-item on the embedded element to match the styling for other attributes. Here's is an example:

```html
<!-- 21:9 aspect ratio -->
<div class="embed-responsive embed-responsive-21by9">
    <iframe class="embed-responsive-item" src="//www.youtube.com/embed/YE7VzlLtp-4"></iframe>
</div>

<!-- 16:9 aspect ratio -->
<div class="embed-responsive embed-responsive-16by9">
    <iframe class="embed-responsive-item" src="//www.youtube.com/embed/YE7VzlLtp-4"></iframe>
</div>

<!-- 4:3 aspect ratio -->
<div class="embed-responsive embed-responsive-4by3">
    <iframe class="embed-responsive-item" src="//www.youtube.com/embed/YE7VzlLtp-4"></iframe>
</div>

<!-- 1:1 aspect ratio -->
<div class="embed-responsive embed-responsive-1by1">
    <iframe class="embed-responsive-item" src="//www.youtube.com/embed/YE7VzlLtp-4"></iframe>
</div>
```

In the above example, we've created the 4 responsive videos with 4 different aspect ratios (21:9, 16:9, 4:3, and 1:1) by using the classes `.embed-responsive-21by9`, `.embed-responsive-16by9`, `.embed-responsive-4by3`, and `.embed-responsive-1by1`, respectively.

## Horizontal Alignment of Images

You can align the images left or right within a larger box using the `.pull-left` or `.pull-right` classes. You can also use the text alignment classes such as `.text-left`, `.text-right`, and `.text-center` on the parent container to align the inline images horizontally left, right, and center.

However, to center align the block-level images you need to use the .mx-auto margin utility class.

Let's take a look at the following example to see how it works:

```html
<!-- Horizontal alignment using float classes -->
<div class="box clearfix">
    <img src="images/avatar.svg" class="pull-left" alt="Sample Image">
    <img src="images/avatar.svg" class="pull-right" alt="Sample Image">
</div>

<!-- Left alignment using text alignment classes -->
<div class="box text-left">
    <img src="images/avatar.svg" alt="Sample Image">
</div>

<!-- Right alignment using text alignment classes -->
<div class="box text-right">
    <img src="images/avatar.svg" alt="Sample Image">
</div>

<!-- Center alignment using text alignment classes -->
<div class="box text-center">
    <img src="images/avatar.svg" alt="Sample Image">
</div>

<!-- Center alignment of block-level image using auto margin -->
<div class="box">
    <img src="images/avatar.svg" class="d-block mx-auto" alt="Sample Image">
</div>
```
