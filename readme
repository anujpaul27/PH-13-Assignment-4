### 1. Difference between getElementById, getElementsByClassName, and querySelector/querySelectorAll
getElementById: Selects one element by ID.
```javascript
document.getElementById("title");
```
getElementsByClassName: Selects multiple elements.
```javascript
document.getElementsByClassName("box");
```
querySelector: Selects the first matching element .
```javascript
// For Class Name
document.querySelector(".box");
// For ID name
document.querySelector("#title");
// For tag name
document.querySelector("div");
```
querySelectorAll: Selects all matching elements .
```javascript
document.querySelectorAll(".box");
```

---

### 2. How to create and insert a new element into the DOM?
**Create Set Class** then **Append,** this are simple step of create and insert a new element

```javascript
// Create 
const div = document.createElement('div');

// Adding class,text
div.className = 'card bg-gray-800 p-4';
div.innerHTML = '<h2>New Job Added</h2>';

// Append
const container = document.querySelector('.container');
container.appendChild(div); 
```

---

### 3. What is Event Bubbling? And how does it work?
Event Bubbling is a mechanism where an event starts from the specific target element where it was triggered and then "bubbles up" then its parent elements in the DOM tree until it reaches the window object.

Example: If you click a button inside a div, the click event first triggers on the button, then the div, then body.

---

### 4. What is Event Delegation in JavaScript? Why is it useful?
Event Delegation is a design pattern in JavaScript where instead of adding an event listener to every individual child element, we add a single event listener to a common Parent Element.
Instead of giving instructions to every son, you just tell the father. When any son is clicked, the father knows and completes the task!

--- 
### 5.What is the difference between preventDefault() and stopPropagation() methods?
event.preventDefault() is Stopping the browser's default behavior and event.stopPropagation() Stop event propagation
