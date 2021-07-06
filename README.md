## HTML
HTML stands for Hyper Text Markup Language. It is the standard markup language for creating Web pages. It describes the structure of a Web page. 
All HTML documents must start with a document type declaration: 

```<!DOCTYPE html>.```

The HTML document itself begins with <html> and ends with </html>.
The visible part of the HTML document is between <body> and </body>.

The **<!DOCTYPE>** Declaration
The **<!DOCTYPE>** declaration represents the document type, and helps browsers to display web pages correctly.
It must only appear once, at the top of the page (before any HTML tags).
The **<!DOCTYPE>** declaration is not case sensitive.

## HTML Elements
The HTML element is everything from the start tag to the end tag:

```<tagname>Content goes here...</tagname>```
 

Comments
You can add comments to your HTML source by using the following syntax:

```<!-- Write your comments here -->```

***Note: Comments are not displayed by the browser, but they can help document your HTML source code.***

## Heading Element
Headings Are Important. Search engines use the headings to index the structure and content of your web pages.
Users often skim a page by its headings. It is important to use headings to show the document structure.
<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.

## HTML Paragraph
The HTML <p> element defines a paragraph.
A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

## HTML Attributes
HTML attributes provide additional information about HTML elements.All HTML elements can have attributes. Attributes provide additional information about elements. Attributes are always specified in the start tag. They usually come in name/value pairs like: name="value"
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
  
```<img src="img_girl.jpg">```

## HTML Links
Links are found in nearly all web pages. Links allow users to click their way from page to page.
HTML links are hyperlinks. You can click on a link and jump to another document. When you move the mouse over a link, the mouse arrow will turn into a little hand.
The HTML <a> tag defines a hyperlink. It has the following syntax:
  
```<a href="url">link text</a>```
  
***Note: A link does not have to be text. A link can be an image or any other HTML element!***

## HTML Images
The HTML <img> tag is used to embed an image in a web page. Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.
The <img> tag has two required attributes:
  
**src** - Specifies the path to the image
**alt** - Specifies an alternate text for the image

## HTML Lists
HTML lists allow web developers to group a set of related items in lists. Two types of lists are mostly used in html. Ordered and Unordered lists.

## Ordered Lists 
An ordered list starts with the **<ol>** tag. Each list item starts with the **<li>** tag.
The list items will be marked with numbers by default:

## Unordered Lists
An unordered list starts with the **<ul>** tag. Each list item starts with the **<li>** tag.
The list items will be marked with bullets (small black circles) by default:

## HTML Tables
HTML tables allow web developers to arrange data into rows and columns.
The **<table>** tag defines an HTML table.
Each table row is defined with a **<tr>** tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a **<td>** tag.
By default, the text in **<th>** elements are bold and centered.
By default, the text in **<td>** elements are regular and left-aligned.
  
***Note: The <td> elements are the data containers of the table.***

They can contain all sorts of HTML elements; text, images, lists, other tables, etc.	

## HTML Forms
The HTML **<form>** element is used to create an HTML form for user input:
The **<form>** element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.



