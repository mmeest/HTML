# HTML
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
  
## Style - CSS
There are 3 ways to add styling to the page:

* **Inline** - by using the style attribute inside HTML elements

```
<h1 style="color:blue;">A Blue Heading</h1>
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

## Script
