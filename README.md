*** Start learning using a Notepad or TextEdit to write your first lines of code while you learn! 😁
(Open the Start Screen the window symbol at the bottom left on your screen Type Notepad)
(Give the file a name and save it as html extension)

** View HTML Source Code:
💻 Click CTRL + U in an HTML page, or right-click on the page and select "View Page Source". This will open a new tab containing the HTML source code of the page.

Now, start writing your first lines of code! 🧑‍🏫

HTML Introduction  
HTML is the standard markup language for creating Web pages.

❓ What is HTML?

HTML stands for Hyper Text Markup Language
HTML is the standard markup language for creating Web pages
HTML describes the structure of a Web page
HTML consists of a series of elements
HTML elements tell the browser how to display the content
HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

❗Example Explained -
The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.


❓ What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:
<tagname> Content goes here... </tagname>


❗The HTML element is everything from the start tag to the end tag:

<h1>My First Heading</h1>
<p>My first paragraph</p>

The <h1> element defines a large heading -
The <p> element defines a paragraph -

❗❗❗Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).
All HTML documents consist of nested HTML elements.


-- HTML Page Structure --
Below is a visualization of an HTML page structure:

<html>
<head>
<title>Page title</title>
</head>
<body>
<h1>This is a heading</h1>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
</body>
</html>

Note: The content inside the <body> section will be displayed in a browser. The content inside the <title> element will be shown in the browser's title bar or in the page's tab.
***However, never rely on this! Unexpected results and errors may occur if you forget the end tag!

❗❗HTML Headings
HTML headings are defined with the <h1> to <h6> tags.
<h1> defines the most important heading. <h6> defines the least important heading.

❗❗HTML Paragraphs
HTML paragraphs are defined with the <p> tag.

❗❗HTML Links
HTML links are defined with the <a> tag:

<a href="https://www.w3schools.com">This is a link</a>

*** The link's destination is specified in the href attribute. 
*** Attributes are used to provide additional information about HTML elements.

-- Empty HTML Elements --
HTML elements with no content are called empty elements.

The <br> tag defines a line break, and is an empty element without a closing tag:

👌 Example
<p>This is a <br> paragraph with a line break.</p>

❗❗HTML Attributes

All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element

❗❗Style
The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

The HTML Style Attribute
Setting the style of an HTML element, can be done with the style attribute.

The HTML style attribute has the following syntax:

<tagname style="property:value;">
The property is a CSS property. The value is a CSS value.




Note: HTML is Not Case Sensitive


HTML tags are not case sensitive: <P> means the same as <p>.
The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.


