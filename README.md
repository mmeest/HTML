# HTML ('.htm', '.html', '.xhtml', '.dhtml', '.phtml')
Hyper Text Markup Language Webpage

## Minimum HTML
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

## Style - Sass ('.scss')
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

## Style - Bootstrap
https://getbootstrap.com/ \
Bootstrap is the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins. 

## Script - JavaScript('.js')

## Script - TypeScript('.ts', '.tsx')
https://www.typescriptlang.org/ \
TypeScript is an open-source language which builds on JavaScript, one of the world’s most used tools, by adding static type definitions.

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

## PHP ('.php')
https://www.php.net/ \
PHP is server side scripting language.

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
