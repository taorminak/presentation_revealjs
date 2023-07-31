# Presentation: React Virtual DOM
## Presenter: Ostanina Anna

Welcome, everyone! Today, we will explore the revolutionary concept of React Virtual DOM. In this presentation, we'll start with how HTML serves as the building blocks of the DOM, enabling web browsers to create a structured representation of web pages. This understanding will set the stage for us to focus on a key player in this domain - React DOM. React, a popular JavaScript library, revolutionized user interface development with its innovative approach to managing the DOM using the Virtual DOM. We will uncover how it boosts performance, efficiency, and reactivity in single page applications.

## Slide 1.

HTML provides a set of instructions that a web browser follows to construct the Document Object Model (DOM). When the browser renders the user interface, the elements from the HTML document's markup are converted into DOM elements. The Document Object Model treats an HTML or XML document as a tree structure where each node is an object representing a part of the document. As an example, Here we can see that the root element has two children: a heading and an unordered list of medical supplies. Traditionally, there are several independent HTML pages on a website. When the user navigates those pages, the browser loads different HTML documents. However, in Single Page Applications (SPAs), the browser loads only one HTML document, and the user stays on the same page, which significantly improves performance. While updating and changing existing DOM elements is relatively easy, inserting new elements can be a slower process, potentially impacting the application's performance.

## Slide 2: What is React DOM?

React DOM is a critical part of the React library. When we talk about React DOM, we are referring to the module responsible for interacting with the Document Object Model (DOM) in the context of React applications. When data changes in a React application, React DOM is responsible for efficiently updating the actual DOM to reflect these changes. One of the key features of React DOM is its implementation of the Virtual DOM. The Virtual DOM is a lightweight copy of the actual DOM, maintained by React. Here's how it works:
- Whenever data changes in a React component, React creates a new Virtual DOM representation of the entire component tree.
- React then compares this new Virtual DOM with the previous one.
- It identifies the minimal number of changes needed to be made in the actual DOM to bring it in sync with the Virtual DOM.
- React efficiently applies these changes to the real DOM, minimizing unnecessary updates and re-renders.

React's Virtual DOM offers several advantages:
- Performance: React's Virtual DOM updates only the necessary parts of the actual DOM, making the process faster and resulting in a more responsive user interface.
- Efficiency: The Virtual DOM's reconciliation process optimizes updates, avoiding direct manipulation of the real DOM whenever possible. This optimization leads to better performance and smoother interactions.
- Abstraction: Working with React's Virtual DOM allows developers to abstract away the complexities of manual DOM manipulation. This means they can focus more on managing the application state and logic, making development easier and more manageable.
- Cross-platform: React's Virtual DOM can work with different rendering targets. It is suitable for web browsers, mobile devices, various platforms, and devices.

## Slide 4: React Virtual DOM - Game Changer

In conclusion, React DOM revolutionized how we build user interfaces in web applications. React has become a powerful and efficient tool for developers. It's important to consider React's Virtual DOM as a key differentiator when comparing frameworks. Its performance benefits, efficiency, and cross-platform support make it a top choice for modern web development.

## Slide 5: Angular DOM and VUE Virtual DOM

Angular, like React, provides a mechanism for managing the DOM. However, its approach is slightly different. Angular utilizes a real DOM and follows a two-way data binding strategy. When changes occur, Angular automatically updates the real DOM and keeps it in sync with the application's data.

Vue, similar to React, adopts the concept of a Virtual DOM. It efficiently tracks changes in the application data and performs minimal DOM updates to ensure high performance. Vue's reactivity system and Virtual DOM work hand in hand to keep the actual DOM synchronized with the application state.

Comparing the performance of React, Angular, and Vue concerning DOM manipulation, several studies could be explored, analyzing real-world benchmarks and exploring the strengths and real numbers in DOM updating of each framework. React's Virtual DOM is highly efficient due to its ability to minimize updates and perform selective rerendering. On the other hand, Angular and Vue have their ways of optimizing updates and ensuring efficient DOM management.

Choosing the right framework for a project depends on its specific requirements and use cases. React, Angular, and Vue have distinct strengths and are well-suited for different scenarios.

All the benchmarks presented below come from Stefan Krause's excellent analysis.

## Slide 6: Conclusion

In conclusion, React's Virtual DOM offers significant advantages in terms of performance, efficiency, and reactivity. While Angular and Vue have their strengths, React's approach to DOM manipulation has proven to be highly effective for building modern web applications.

In conclusion, today we discussed the very important concept of the React Library, React's Virtual DOM, and its transformative impact on web development. Thank you very much for your attention and goodbye!


