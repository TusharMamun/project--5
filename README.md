1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans:-getElementById = used to get a single div or element.
getElementsByClassName = used to get single or multiple elements, it is also array-like (HTMLCollection).
querySelector = used to get the first and single element, and it is defined like CSS selector (.name or #id).
querySelectorAll = used to get all elements and it is array-like (NodeList).

2.How do you create and insert a new element into the DOM?
Ans:-
const divContainer = document.getElementById("unq");
const newElement = document.createElement("div");
newElement.innerHTML = "New Element";
divContainer.append(newElement);


3.What is Event Bubbling and how does it work?
Ans:-Event bubbling works when an event fires, and it goes from the child node to the parent node (bottom to top).

4.What is Event Delegation in JavaScript? Why is it useful?
When an event fires, instead of adding event listeners to every child, we use a single parent listener. It works by using bubbling and is useful for handling multiple or dynamic elements.

5.What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() = used to stop the browser’s default behavior (example: form refresh).
stopPropagation() = used to handle and stop event bubbling.