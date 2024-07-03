## Discuss DOM

## What is DOM

DOM (Document Object Method) is a programming interface for web documents.
It represents the structure of a webpage as a tree of objects.
Each node in this tree coresponds to a part of the doument e.g(elements, attributese.etc)

## What is the importance of DOM

The DOM allows Javascript to interact with and manipulate the structure, style, and content of a webpage dynamically.
This means that you can change elements, attributes and text after the webpage has loaded.
It basically catalogues the webpage into individual objects that we can select and manipulate .


## How is DOM Created

DOM is created when the webpage loads from HTML/CSS/JavaScript that the web server provides to the browser.


## Accessing DOM Elements

You can access Dom elements using various methods in JavaScript

  ## 1.document.getElementById(id:)
  Selects an element by it Id

  ## 2.document.getElements By Tag Name(tagName)
  Selects elements by their tag name

  ## 3. document.getElements By Class Name(className)
  Selects elements by their class name

  ## 4. document.querySelector(selector)
  Selects the first element that matches a CSS selector

  ## 5. document.querySelectorAll(selector)
  Selects all elements that match a CSS selector


## Modifying DOM Elements

  You can modify elements using various properties and methods

   # 1. Change Content
     element.textContent
     element.innerHTML

   # 2. Change attributes
    element.setAttributes(attr value)
    element.attr = value

   # 3. Change Styles
    element.style.property = value
 
  
## Adding and Removing Elements

   # 1. Create new elements
   document.createElement(tagName)

   # 2. Append elements
   parent.appendChild(child)

   # 3. Remove elements
   parent.removeChild(child)