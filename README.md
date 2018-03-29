# HTML-Elements-and-Structure
To make sure your document is forever interpreted correctly, always include <!DOCTYPE html> at the very beginning of your HTML documents.

HTML code is always saved in a file with an .html extension.

The Structure
To create HTML structure and content, we must add opening and closing <html> tags after declaring <!DOCTYPE html>:

<!DOCTYPE html>
<html>

</html>


<head> element is part of this HTML metaphor. It goes above our <body> element.
  
  <html>
  
  <head></head>
  
  A browser's tab displays the title specified in the <title> tag. The <title> tag is always inside of the <head>.
  
  <!DOCTYPE html>
<html>
  <head>
    <title>My Coding Journal</title>
  </head>
</html>



You can add links to a web page by adding an anchor element <a> and including the text of the link in between the opening and closing tags.
  
  <a href="https://www.wikipedia.org/">This Is A Link To Wikipedia</a>
  
  
  
  For a link to open in a new window, the target attribute requires a value of _blank. The target attribute can be added directly to the opening tag of the anchor element, just like the href attribute.
  
  
 <a href="https://en.wikipedia.org/wiki/Brown_bear" target="_blank">The Brown Bear</a>
 
 The target="_blank" attribute, when used in modern browsers, will open new websites in a new tab.
 
 When making multi-page static websites, web developers often store HTML files in the root directory, or a main folder where all the files for the project are stored. As the size of the projects you create grows, you may use additional folders within the main project folder to organize your code.
 
 project-folder/
|—— about.html
|—— contact.html
|—— index.html

The example above shows three different files — about.html, contact.html, and index.html in one folder.

Because the the files are stored in the same folder, we can link web pages together using a relative path.

<a href="./contact.html">Contact</a>

 HTML allows you to turn nearly any element into a link by wrapping that element with an anchor element. With this technique, it's possible to turn images into links by simply wrapping the <img> element with an <a> element.
  
  <a href="https://en.wikipedia.org/wiki/Opuntia" target="_blank"><img src="#" alt="A red prickly pear fruit"/></a>
  
  In order to link to a target on the same page, we must give the target an id, like this:
  
  <p id="top">This is the top of the page!</p>
<h1 id="bottom">This is the bottom! </h1>

the <p> element is assigned an id of "top" and the <h1> element is assigned "bottom." An id can be added to most elements on a webpage.


An id should be descriptive to make it easier to remember the purpose of a link. The target link is a string containing the # character and the target element's id.

<ol>
  <li><a href="#top">Top</a></li>
  <li><a href="#bottom">Bottom</a></li>
</ol>

 the links to <p id="top"> and <h1 id="bottom"> are embedded in an ordered list. These links appear in the browser as a numbered list of links. An id is especially helpful for organizing content belonging to a div!
  
  White Spaces and Indentations are useful for html: they make it easie to read your code
  
  You can add comments to the code via: <!-- -->
  
  
  This is the lesson overview
  
The <!DOCTYPE html> declaration should always be the first line of code in your HTML files. This lets the browser know what version of HTML to expect.

The <html> element will contain all of your HTML code.
  
Information about the web page, like the title, belongs within the <head> of the page.
  
You can add a title to your web page by using the <title> element, inside of the head.
  
A webpage's title appears in a browser's tab.

Anchor tags (<a>) are used to link to internal pages, external pages or content on the same page.
  
You can create sections on a webpage and jump to them using <a> tags and adding ids to the elements you wish to jump to.
  
Whitespace between HTML elements helps make code easier to read while not changing how elements appear in the browser.

Indentation also helps make code easier to read. It makes parent-child relationships visible.

Comments are written in HTML using the following syntax: <!-- comment -->.
