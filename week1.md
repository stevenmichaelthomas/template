
#### The basic structure of an HTML file:
```html
<!-- This is a comment in an HTML file, it won't ever show up on the page -->

<!doctype html>
<html>
  <head>
    <!-- This is all fairly low-level configuration -->
    <meta charset="utf-8">
    <meta content="IE=edge,chrome=1" http-equiv="X-UA-Compatible">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Page description">
    <title><!-- Page title --></title>

    <!-- These next two lines tell your website where to find CSS and -->
    <!-- javascript files -->
    <link rel="stylesheet" type="text/css" href="stylesheet_file.css">
    <script src='javascript_file.js'>
  </head>

  <body>
    <!-- The visual content of the website goes here -->
  </body>
</html>
```

#### Basic HTML tags:
```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
<p></p>
<b></b>
<div></div>
<span></span>
<section></section>
<a href="#"></a>
<img src="">
```

#### CSS, and class selectors

In HTML
```html
<div class="hello"></div>
```

In CSS
```
.hello {
  background-color: pink;
}
```


#### SASS (Scss) and nested CSS
```html
<div class="hello">
  <h1>Hello</h1>
</div>
```

This will select all H1 elements nested inside of the .hello class:
```scss
.hello {
  background-color: pink;

  h1 {
    font-size: 48px;
  }
}
```
