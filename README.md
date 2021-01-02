<p align="center">
  <image src="img/34022590.jpg" width="300px" style="border-radius:50%">
</p style="border-radius:50%">

<h1 align="center">
  HTML - Hyper Text Markup Language Webpage
</h1>

<h3 align="center">
	<a target="_blank" href="https://sass-lang.com/">Sass</a>
	<span> · </span>
  <a target="_blank" href="https://getbootstrap.com/">Bootstrap</a>
	<span> · </span>
  <a target="_blank" href="https://www.javascript.com/">JavaScript</a>
	<span> · </span>
  <a target="_blank" href="https://www.typescriptlang.org/">TypeScript</a>
	<span> · </span>
  <a target="_blank" href="https://jquery.com/">JQuery</a>
	<span> · </span>
  <a target="_blank" href="https://www.php.net/">PHP</a>
</h3>



<image src="img/html.png" width="100px">

## Minimum HTML ('.htm', '.html', '.xhtml', '.dhtml', '.phtml')
Minimum code for HTML page

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>title</title
  </head>
  <body>
    <!-- page content -->
  </body>
</html>
```

Different resources for webpage are usually stored in different folders. For example
* **img** - for images resources('.jpg', '.png', '.gif')
* **style** - for styling files('.css')
* **script** - for scripts used on webpage('.js')

**<!DOCTYPE html>** - The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.

Declaration in HTML 4.01:\
**<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">**

Declaration in XHTML 1.1:\
**<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">**

* **!DOCTYPE** is not case sensitive

**<head>** - Inside head section are declared char set of the page; styling; scripts;
  
**<meta charset="utf-8">** - Page character encoding\
https://www.w3schools.com/charsets/

**<title>My Page</title>** - Page title, displayed on head of browser tab.
  
<image src="img/css.png" width="100px">

## Style - CSS ('.css')
There are 3 ways to add styling to the page:

* **Inline** - by using the style attribute inside HTML elements

```
<h1 style="color:blue;">A Blue Heading</h1>
```

```
<p style="display: flex; align-items: center;">
```

* **Internal** - by using a <style> element in the <head> section 

```
<head>
  <style>
  body {background-color: powderblue;}
  h1   {color: blue;}
  p    {color: red;}
  </style>
</head>
```

* **External** - by using a <link> element to link to an external CSS file
```
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

<image src="img/sass.png" width="100px">

## Style - Sass ('.scss')
https://sass-lang.com/ \
**Sass** - **S**yntactically **A**wesome **S**tyle**s**heet\
Sass is CSS styling extention. While CSS is interpeted straight in the browser. Sass needs pre-processor.

Sass can store values as variables. For example:
```
/* define variables for the primary colors */
$primary_1: #a2b9bc;
$primary_2: #b2ad7f;
$primary_3: #878f99;

/* use the variables */
.main-header {
  background-color: $primary_1;
}

.menu-left {
  background-color: $primary_2;
}

.menu-right {
  background-color: $primary_3;
}
```

<image src="img/bootstrap.png" width="100px">

## Style - Bootstrap
https://getbootstrap.com/ \
Bootstrap is the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins. 

**Adding bootstrap to your HTML**
1. Download Compiled CSS and JS from https://getbootstrap.com/ downloads section
2. Extract downloaded zip file.
3. Copy extracted folders('css' and 'js') into HTML project folder.
4. Add links to your HTML file header:
```
	<link href="css/bootstrap.min.css" rel="stylesheet"/>
	<script src="js/bootstrap.min.js"></script>
```	

<image src="img/js.jpg" width="100px">

## Script - JavaScript('.js')

<image src="img/ts.png" width="100px">

## Script - TypeScript('.ts', '.tsx')
https://www.typescriptlang.org/ \
TypeScript is an open-source language which builds on JavaScript, one of the world’s most used tools, by adding static type definitions.

<image src="img/jquery.png" width="100px">

## Script - JQuery('.js')
https://jquery.com/ \
jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. 

Example: Get the <button> element with the class 'continue' and change its HTML to 'Next Step...'
  
```
$( "button.continue" ).html( "Next Step..." )
```

Show the #banner-message element that is hidden with display:none in its CSS when any button in #button-container is clicked.

```
var hiddenBox = $( "#banner-message" );
$( "#button-container button" ).on( "click", function( event ) {
  hiddenBox.show();
});
```

<image src="img/php.png" width="100px">

## PHP ('.php')
https://www.php.net/ \
PHP is server side scripting language. While HTML, CSS and JavaScript can run directly from web browser PHP needs to be interpreted by the PHP interpeter program, called php. Interpeter makes PHP scripts understandable to web browsers. 

Example:
```
 <!DOCTYPE html>
<html>
<body>

<?php
echo "My first PHP script!";
?>

</body>
</html> 
```
