<h1 align="center">HTML Notes</h1>

### Table of contents:

- [HTML Introduction](#html-introduction)
  - [What is HTML:](#what-is-html)
  - [A Simple  HTML Document](#a-simple--html-document)
  - [Difference Between Element, Tag and Attributes:](#difference-between-element-tag-and-attributes)
    - [What is an HTML Element](#what-is-an-html-element)
    - [What is HTML Tag:](#what-is-html-tag)
    - [What is HTML Attribute:](#what-is-html-attribute)

---

## HTML Introduction 

### What is HTML: 
HTML is the standard markup language for creating web pages. Its element tells the browser how to display the content.  

HTML stands for = Hyper Text Markup Language  

Hyper Text = Hyper Text is text with clickable links that take you to other pages or different parts of the same page.  

Markup Language = Markup Language is a way to write text using special tags and rules that tell a browser how to organize and display the content.

### A Simple  HTML Document
```html
<!DOCTYPE html>
<html>
	<head>
    		<title>Page Title</title>
   	 </head>
<body>	

</body>
</html>
```  
**Explanation:**  
- The <!DOCTYPE html> declaration defines that this document is an HTML5 document    
- The ```<html>``` element is the root element of an HTML page.
  - Root Element = The root element is the topmost element in a document that contains all the other elements. The ```<html>``` element is the root element because it wraps all the content of the page, including the ```<head>``` and ```<body>``` sections
- The ```<head>``` element in HTML is a container for metadata and links to external resources related to the webpage.  
  - Meta information = Meta information is data about the HTML page that isn’t directly visible to users but helps browsers and search engines understand the page better.  
- The ```<title>``` element specifies a title for the HTML page which is shown the browser’s page’s tab.  
- The ```<body>``` element defines the document’s body and is a container for all the visible contents.


### Difference Between Element, Tag and Attributes:
![images-1-differenceBetweenElementTagAttribute.png](/assets/images/images-1-differenceBetweenElementTagAttribute.png)

#### What is an HTML Element
An HTML element is defined by a start tag, some content, and an end tag:

```html 
<tagName>Content Goes Here....</tagName>
```
**Note:** Some HTML elements have no content and end tag. These elements are called empty elements like(```<img>, <br>, <hr>, <input>```). 

#### What is HTML Tag:
A tag in HTML is a piece of code enclosed in angle bracket<>, that are used to create elements like (```<h1></h1>, <p></p>,<img>, <a>)```).  

#### What is HTML Attribute: 
HTML attributes provide additional information about HTML elements. Attributes are always specified in the start tag and come in name/value pairs like: name =”value”.

**Common HTML Attributes:**
- id → gives a unique identifier to an element
- class → assigns one or more class names (used for styling or JS)
- style → adds inline CSS styles
- alt → alternative text for images
- src → source for images, scripts, iframe
- href → link reference 
- type → defines type of input, script, button, etc.
- name → gives a name to form elements (used to send form data)
- value → sets the value for input, option, button, etc.
- placeholder → hint text inside input fields
- disabled → disables input/button elements
- readonly → makes input fields uneditable
- required → makes form input mandatory 
- target → specifies where to open a link (_blank, _self, etc.)  