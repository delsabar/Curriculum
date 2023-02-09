# HTML 101

## HTML forms the structure of all webpages

HTML -> Hyper Text Markup Language

The `<head>` tag configures the page and is not rendered by the browser.
The `<title>` contains the name of the page and is rendered in the browser's tab.
Tags that have opening `<>` and closing `</>` elements are known as container elements.
Tags that do not have opening and closing elements are not conatiner elements and are called self-closing tags (` />`).
To make reading and HTML file easier, lines are nested within their parent element.
Browsers read HTML, and, in a sense, HTML is like a big, long string.
Browsers can read files or you can start a server in VS Code with **Go Live**

### Some of the most common elements are
#### Semantic elements include
```
<ul> - Unordered List
<ol> - Ordered List
<li> - List Item, must be contained by a `<ul>` or `<ol>`
<header> - The header area of the page
<main> - The main area of the page
<body> - Contains all other rendering HTML elements
<footer> - The footer area of the page
<nav> - Contains navigation elements, usually found inside  `<header>`
<p> - Used for a single paragraph of text
<img /> - Used for images (self-closing), must have a `src` attribute
<a> - Anchor tag, used to hyperlink elementswith the `href` attribute
<h1> - header text (largest)
<h2> - header text
<h3> - header text
<h4> - header text
<h5> - header text
<h6> - header text (smallest)
```
#### Generic elements include
```
<div> - Generic containing element
<section> -  Defines a section for child elements
```
#### Tags used inside of `<head>`
```
<link> - Used to link a stylesheet, only found in the `<head>`
```