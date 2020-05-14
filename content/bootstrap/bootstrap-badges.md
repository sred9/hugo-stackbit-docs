---
title: Bootstrap Badges 
excerpt: >-
  In this section you'll learn how to add syntax highlighting, examples,
  callouts and much more.
template: docs
---
Badges are generally used to indicate some valuable information on the web pages such as important heading, warning messages, notification counter, etc.

The following example will show you how to create inline badges using the Bootstrap.

```html
<h1>Bootstrap heading <span class="badge badge-secondary">New</span></h1>
<h2>Bootstrap heading <span class="badge badge-secondary">New</span></h2>
<h3>Bootstrap heading <span class="badge badge-secondary">New</span></h3>
<h4>Bootstrap heading <span class="badge badge-secondary">New</span></h4>
<h5>Bootstrap heading <span class="badge badge-secondary">New</span></h5>
<h6>Bootstrap heading <span class="badge badge-secondary">New</span></h6>
```

— The output of the above example will look something like this:

## Contextual Classes for Badges

There are some contextual or modifier classes to change the appearance of the badges.

```html
<span class="badge badge-primary">Primary</span>
<span class="badge badge-secondary">Secondary</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-danger">Danger</span>
<span class="badge badge-warning">Warning</span>
<span class="badge badge-info">Info</span>
<span class="badge badge-dark">Dark</span>
<span class="badge badge-light">Light</span>
```

— The output of the above example will look something like this:

## Creating Pill Badges

Similarly, you can create pill shape badges (i.e. badges with more rounded corners) using the .badge-pill modifier class, as demonstrated in the following example:

```html
<span class="badge badge-pill badge-primary">Primary</span>
<span class="badge badge-pill badge-secondary">Secondary</span>
<span class="badge badge-pill badge-success">Success</span>
<span class="badge badge-pill badge-danger">Danger</span>
<span class="badge badge-pill badge-warning">Warning</span>
<span class="badge badge-pill badge-info">Info</span>
<span class="badge badge-pill badge-dark">Dark</span>
<span class="badge badge-pill badge-light">Light</span>
```

— The output of the above example will look something like this:

## Showing Counter with Badges

You can also use badges as part of links or buttons to provide a counter, such as number of received or unread messages, number of notifications etc. They're most commonly found in email clients, application dashboards, social networking websites, etc. Here's an example:

```html
<ul class="nav nav-pills">
    <li class="nav-item">
        <a href="#" class="nav-link">Home</a>
    </li>
    <li class="nav-item">
        <a href="#" class="nav-link">Profile</a>
    </li>
    <li class="nav-item">
        <a href="#" class="nav-link active">Messages <span class="badge badge-light">24</span></a>
    </li>
    <li class="nav-item">
        <a href="#" class="nav-link">Notification <span class="badge badge-primary">5</span></a>
    </li>
</ul>
```

— The output of the above example will look something like this:
