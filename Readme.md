Q1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Answer: getElementById → returns one element by unique ID.
getElementsByClassName → returns multiple elements with a class.
querySelector → returns the first element matching a CSS selector.
querySelectorAll → returns all elements matching a CSS selector.

Q2. How do you create and insert a new element into the DOM?
Answer: At first I create the element, set its text/attributes, then insert it into the parent element (at the start, end, or before another element).

Q3. What is Event Bubbling and how does it work?
Answer: When an event occurs, it first triggers on the target element, then moves upward through its parent elements until the root (document).

Q4. What is Event Delegation in JavaScript? Why is it useful?
Answer: Attaching a single event listener to a parent to handle events from its children. It reduces memory usage and works for dynamically added elements.

Q5. What is the difference between preventDefault() and stopPropagation()?
Answer: preventDefault() → stops the browser’s default action (e.g., link navigation, form submission).
stopPropagation() → stops the event from bubbling up to parent elements.