HTML/CSS

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

HTML Formatting Elements
Formatting elements were designed to display special types of text:

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text


❗❗Colors:

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
❗Color Values:
In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.
 -> The following three <div> elements have their background color set with RGB, HEX, and HSL values:
    rgb(255, 99, 71) ->  red, Green, Blue -> This means that there are 256 x 256 x 256 = 16777216 possible colors!
    #ff6347
    hsl(9, 100%, 64%)

    RGBA -> RGBA color values are an extension of RGB color values with an Alpha channel - which specifies the opacity for a color.
    An RGBA color value is specified with: rgba(red, green, blue, alpha)
    The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all)

    - - > A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color.

    Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

        For example, #ff0000 is displayed as red, because red is set to its highest value (ff), and the other two (green and blue) are set to 00 : #rrggbb

        Another example, #00ff00 is displayed as green, because green is set to its highest value (ff), and the other two (red and blue) are set to 00.
        To display black, set all color parameters to 00, like this: #000000.
        To display white, set all color parameters to ff, like this: #ffffff.

    - - > HSL stands for hue, saturation, and lightness.
          HSLA color values are an extension of HSL with an Alpha channel (opacity).


Note: HTML is Not Case Sensitive


HTML tags are not case sensitive: <P> means the same as <p>.
The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.


 - - > 
 - - > CSS: stands for Cascading Style Sheets.

❗ CSS saves a lot of work. It can control the layout of multiple web pages all at once.
    Cascading Style Sheets (CSS) is used to format the layout of a webpage.


❗❗ What is CSS?

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

❗Using CSS

CSS can be added to HTML documents in 3 ways:

Inline - by using the style attribute inside HTML elements
Internal - by using a <style> element in the <head> section
External - by using a <link> element to link to an external CSS file
The most common way to add CSS, is to keep the styles in external CSS files. However, in this tutorial we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.


CSS Padding - - > The CSS padding property defines a padding (space) between the text and the border.


