<h1 align="center">DOM</h1>

<p align="center">

<img src="https://img.shields.io/badge/Made%20by-Ogabek-yellow" >

<img src="https://img.shields.io/badge/JavaScript-Lesson%20%237-green">

<img src="https://img.shields.io/badge/USING-DOM-red">

<img src="https://img.shields.io/badge/Methods-DOM-red">

<img src="https://img.shields.io/badge/Learn-Javascript-black">

</p>

---

>`DOM (Document Object Model)` is a special tree structure that allows you to manage `HTML` markup from `JavaScript` code. Management usually consists of adding and removing elements, changing their styles and content.

<center><img src="https://www.w3schools.com/js/pic_htmltree.gif"></center>
---

__The browser creates a `DOM`when the page loads, puts it in the `document variable` and reports that the `DOM` has been created using the `DOMContentLoaded` event. Any work with HTML markup in `JavaScript` begins with the document variable.__

***

<center> <h3>DomMethods</h3></center>

* `getElementById` — search for an element by ID;
* `getElementsByClassName` — search for elements by class name;
* `getElementsByTagName` — search for elements by tag name;
* `querySelector` — search for the first element that fits the CSS selector;
* `querySelectorAll` — search for all elements suitable for the CSS selector.

### Changing HTML Elements

* `element.innerHTML` =  new html content Change the inner HTML of an element
* `element.attribute` = new value Change the attribute value of an HTML element
* `element.style.property` = new style Change the style of an HTML element

### Adding and Deleting Elements

* `document.createElement(element)` Create an HTML element
* `document.removeChild(element)` Remove an HTML element
* `document.appendChild(element)` Add an HTML element

### Adding Events Handlers

* `document.getElementById(id).onclick = function(){code}`Adding event handler code to an onclick event

---

