QUESTION AND ANSWER:

1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById  : Finds a single element by ID.
getElementsByClassName : Finds multiple elements by class (in the form of an HTMLCollection).
querySelector  : Works like a CSS selector, returns the first matching element.
querySelectorAll : Returns all elements (in the form of a NodeList).

2. How do you create and insert a new element into the DOM?
For Create a new element , We can use [document.createElement("tagName")].
For insert a new element into the DOM, We can use [element.textContent = "Something"] to set content and then we can use [parent.appendChild(element)] to insert the new element into the DOM.

3. What is Event Bubbling and how does it work?
Event bubbling means that when an event occurs on an element, it first acts on that element, then its parent, then the parent's parent and so on.

4. What is Event Delegation in JavaScript? Why is it useful?
Event Delegation means placing an event listener on the parent element and handling the events of the child elements inside it.

5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault(): Blocks browser default actions, such as closing a form before it is submitted, not auto-checking a checkbox, etc.
stopPropagation(): Stops event propagation (bubbling or capturing). That is, the event will no longer be passed to the parent element.
