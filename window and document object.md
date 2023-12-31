### **Document Object:**
The document object represents a web page that is loaded in the browser. By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. The document object can be accessed with a window.document or just document.
---
| **document**      | **window** |
| ----------- | ----------- |
| It represents any HTML document or web page that is loaded in the browser.      | It represents a browser window or frame that displays the contents of the webpage.         |
| It is loaded inside the window.   | It is the very first object that is loaded in the browser.        |
| It is the object of window property. | It is the object of the browser.
| All the tags, elements with attributes in HTML are part of the document. | Global objects, functions, and variables of JavaScript are members of the window object.
| We can access the document from a window using the window.document |We can access the window from the window only. i.e. window.window
| The document is part of BOM (browser object model) and dom (Document object model) |The window is part of BOM, not DOM.
|  Properties of document objects such as title, body, cookies, etc can also be accessed by a window like this window. document.title |Properties of the window object cannot be accessed by the document object.
| **syntax:** document.propertyname;   | **syntax:** window.propertyname;
| **example:** document.title :  will return the title of the document |**example:** window.innerHeight : will return the height of the content area of the browser
