# ← HTML →

# Q.1 `<!DOCTYPE html>` is it a tag of html? If not, what is it and why do we use it?

😃**Solution :**

Yes, `<!DOCTYPE html>` is indeed a tag in HTML, but it is more accurately referred to as a document type declaration (DTD) rather than a tag. The `<!DOCTYPE html>` declaration is placed at the very beginning of an HTML document to specify the version of HTML being used. The purpose of the document type declaration is to ensure that the HTML document is rendered correctly by web browsers. It helps the browser  determine how to interpret and display the content. Different versions  of HTML have different rules and features, so specifying the document type helps ensure compatibility and consistency across browsers.


# Q.2 Explain Semantic tags in html? And why do we need it?

😃**Solution :**

Semantic tags in HTML are special HTML elements that provide meaning and structure to the content they wrap. They convey the purpose or role of the content within the document. Unlike non-semantic tags (e.g., `<div> or <span>`), which are generic and don't provide any specific information about the content, semantic tags have predefined meanings and convey the semantics of the content they contain.

Some examples of semantic tags introduced in HTML5 are `<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>, <figure>`, and many more. These tags give meaning to the structure of the document and help search engines, screen readers, and other tools to understand and interpret the content better.

#### Here are some reasons why semantic tags are important and beneficial in HTML:
- Accessibility: Semantic tags improve accessibility by providing additional context and meaning to assistive technologies like screen readers. These technologies can understand the structure of the content and convey it more effectively to users with disabilities.
- Search Engine Optimization (SEO): Semantic tags help search engines understand the hierarchy and organization of the content. Using semantic tags appropriately can improve the search engine ranking of a website and make it more discoverable by users.
- Readability and Maintainability: Semantic tags make the HTML code more readable and maintainable. By using tags like `<header>, <footer>, and <nav>`, it becomes easier for developers and designers to understand the purpose and role of different sections within the document.
- Collaboration and Consistency: Semantic tags promote better collaboration among developers and designers by providing a common vocabulary and understanding of the structure of the document. It enables consistent coding practices and improves code readability across the team.

By using semantic tags, you make your HTML code more meaningful, accessible, and maintainable. They enhance the overall quality of the web page and contribute to a better user experience. It is recommended to use semantic tags whenever appropriate to provide clearer and more structured content within your HTML documents.
  
  
# Q.3 Differentiate between HTML Tags and Elements?

😃**Solution :**

HTML Tags:
HTML tags are used to define the structure and content of an HTML document. Tags are represented by angled brackets (< and >) and are placed around HTML elements. Tags are used to mark the beginning and end of an element, and they provide instructions to the web browser on how to interpret and render the content.

HTML Elements:
HTML elements consist of both the HTML tags and the content between them. An HTML element is a complete unit that represents a specific part of a web page. It includes the opening tag, the closing tag, and the content within those tags.

```Javascript
<p>This is a paragraph.</p>
/*
HTML Tags:
<p> is the opening tag, and </p> is the closing tag.

HTML Elements:
<p> is the opening tag, "This is a paragraph" is the content, and </p> is the closing tag. 
Together, they form the complete paragraph element.
*/
```

# Q.4 Build Your Resume using HTML only.


# Q.5 Write Html code so that it looks like the given image 

<img width="260" alt="html" src="https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/d98f5dae-ae38-473d-840d-477449e8336a">


# Q.6 What are some of the advantages of HTML5 over its previous versions?

😃**Solution :**

HTML5 introduced several significant advancements and features compared to its previous versions, bringing various benefits to web developers and users. 
### Here are some of the advantages of HTML5 over its predecessors:
#### Semantics: 
HTML5 introduced new semantic elements, such as `<header>, <footer>, <nav>, <section>, and <article>`. These elements provide better structure and meaning to the content, making it more accessible for assistive technologies and search engines. It allows developers to create cleaner and more meaningful markup.
#### Multimedia Support: 
HTML5 includes native support for audio and video playback without the need for third-party plugins like Flash. The `<audio> and <video>` elements allow embedding media content directly into web pages, making it easier to integrate and control multimedia elements.
#### Canvas: 
The `<canvas>` element in HTML5 provides a powerful API for drawing graphics and animations on the fly using JavaScript. It enables developers to create interactive games, data visualizations, and other dynamic content without relying on external plugins.
#### Offline and Storage: 
HTML5 introduced features like the Application Cache and Local Storage, enabling web applications to work offline and store data locally on the user's device. This allows users to access and use web applications even when they're not connected to the internet, improving the user experience and productivity.
#### Form Enhancements: 
HTML5 introduced several new form input types and attributes, such as email, URL, date, range, and more. It also introduced the `<datalist>` element for providing a predefined list of options. These enhancements improve the user experience and provide better input validation and data entry options.
#### Geolocation: 
HTML5 added the Geolocation API, which allows websites to request and access the user's geographical location. This enables developers to create location-based applications and provide personalized content or services based on the user's location.
#### Improved Performance: 
HTML5 introduced various performance improvements, such as asynchronous script loading with the async and defer attributes, which optimize the loading and execution of scripts. It also introduced new APIs for efficient data transfer, like WebSockets and Web Workers, which enable real-time communication and background processing, respectively.
#### Mobile Support: 
HTML5 includes features specifically designed for mobile devices, such as the ability to handle touch events, geolocation, and device orientation. It provides a more consistent and optimized experience across different devices and screen sizes.


# Q.7 Create a simple Music player using html only.


# Q.8 What is the difference between `<figure>` tag and `<img>` tag?

😃**Solution :**

##### `<img>` tag:
The `<img>` tag is specifically used to embed an image into an HTML document. It is a self-closing tag that does not require a closing tag. The <img> tag is primarily responsible for displaying the image on the page.
```Javascript
<img src="image.jpg" alt="Image description">
```
##### `<figure>` tag:
The `<figure>` tag is used to group together and semantically associate a self-contained content block with an optional caption. It is typically used to encapsulate media content like images, illustrations, videos, audio, etc., along with their captions or explanations.
```Javascript
<figure>
  <img src="image.jpg" alt="Image description">
  <figcaption>Caption for the image</figcaption>
</figure>
```


# Q.9 What’s the difference between html tag and attribute and give example of some global attributes?

😃**Solution :**

##### HTML Tags:
HTML tags are used to mark the beginning and end of an HTML element. They define the structure and semantics of the content within the element. Tags are represented by angled brackets (< and >) and are placed around HTML elements. Tags can be either opening tags or self-closing tags.

Examples:

`<p>`: Represents a paragraph element.

`<h1>`: Represents a heading level 1 element.

`<div>`: Represents a division or container element.

`<a>`: Represents an anchor or hyperlink element.

##### HTML Attributes:
HTML attributes provide additional information or properties to HTML elements. They are placed within the opening tag of an element and modify the behavior or appearance of the element. Attributes consist of a name and a value, separated by an equal sign (=). Multiple attributes can be added to an element, each separated by a space.

Examples:

`class`: Specifies one or more CSS classes to apply to an element for styling or targeting with CSS or JavaScript.

`id`: Provides a unique identifier for an element, which can be used for targeting the element with CSS or JavaScript.

`src`: Specifies the source URL or file path for media elements like images, audio, or video.

`href`: Specifies the destination URL for anchor elements.

##### Global Attributes:
Global attributes are attributes that can be used on any HTML element. They are not specific to any particular element and can be applied universally. 

Here are some examples of global attributes:

`class`: Specifies one or more CSS classes for styling or targeting elements.

`id`: Provides a unique identifier for an element.

`style`: Allows inline CSS styling to be applied directly to an element.

`title`: Adds a tooltip or additional information about an element.

`lang`: Specifies the language of the content within an element.


# Q.10 Build Table which looks like the given image
![Screenshot 2023-05-25 at 14-35-51 2T7Y1 gif (GIF Image 472 × 278 pixels)](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/fcff3c94-e498-4377-bc45-ebc281bca4c1)

  
  
# ← CSS →

# Q.11 Whats Box Model in CSS & Which CSS Properties are part of it ?

😃**Solution :**


# Q.12 What are the Different Types of Selectors in CSS & what are the advantages of them?

😃**Solution :**


# Q.13 What is VW/VH & How its different from PX?

😃**Solution :**


# Q.14 Whats difference between Inline, Inline Block and block ?

😃**Solution :**


# Q.15 How is Border-box different from Content Box?

😃**Solution :**


# Q.16 What’s z-index and How does it Function ?

😃**Solution :**


# Q.17 What’s Grid & Flex and difference between them?

😃**Solution :**


# Q.18 Difference between absolute and relative and sticky and fixed position explain with example.

😃**Solution :**

In CSS, positioning properties are used to control the layout and positioning of elements on a web page.

### Absolute Positioning (position: absolute):

- Elements with position: absolute are positioned relative to their nearest positioned ancestor, or the initial containing block if there is no positioned ancestor.
- When an element is positioned absolutely, it is taken out of the normal document flow and can overlap other elements.
- You can use offset properties (top, right, bottom, left) to specify the exact position of the element.
```Javascript
.container {
  position: relative;
}

.box {
  position: absolute;
  top: 50px;
  left: 100px;
}
```

### Relative Positioning (position: relative):

- Elements with position: relative are positioned relative to their normal position in the document flow.
- When an element is positioned relatively, you can use offset properties like top, right, bottom, and left to move the element from its original position.
- Other elements on the page will still occupy the space where the relatively positioned element would have been if it were not moved.

```Javascript
.container {
  position: relative;
}

.box {
  position: relative;
  top: 20px;
  left: 30px;
}
```

### Sticky Positioning (position: sticky):

- Elements with position: sticky are positioned based on the user's scroll position.
- A sticky element is initially positioned according to the normal flow of the document but becomes fixed (like position: fixed) once the user scrolls to a specific threshold (the "sticky" point)
- The element will remain in its sticky position until it reaches the end of its parent container.

```Javascript
.container {
  height: 800px; /* Add height to create a scrolling container */
  overflow-y: scroll;
}

.sticky-element {
  position: sticky;
  top: 20px;
}
```
### Fixed Positioning (position: fixed):

- Elements with position: fixed are positioned relative to the viewport, meaning they stay in the same position even if the page is scrolled.
- Fixed elements are removed from the normal document flow and do not affect the positioning of other elements.
- You can use offset properties (top, right, bottom, left) to specify the exact position of the element relative to the viewport.

```Javascript
.fixed-element {
  position: fixed;
  top: 20px;
  right: 20px;
}
```


# Q.19 Build Periodic Table as shown in the below image 
![Screenshot 2023-05-25 at 14-28-53 Assessment Documents for Full Stack Web Development - FSJS2 0 Assignment pdf](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/cdb5e2a3-2529-46f3-8a8c-bf1ae140940a)


# Q.20 Build given layout using grid or flex see below image for reference .
![Screenshot 2023-05-25 at 14-38-26 Assessment Documents for Full Stack Web Development - FSJS2 0 Assignment pdf](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/48d163c6-ca1c-44e3-b924-85b89ca724ec)


# Q.21 Build Responsive Layout both desktop and mobile and Tablet, see below image for reference ?
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/4bed6137-0e6e-4f83-9d94-eb8f03c6aec9)


# Q.22 Build Complete Homepage of Ineuron [Link](https://ineuron.ai/) with responsiveness.


# Q.23 What are Pseudo class in CSS & How its different From Pseudo Elements?

😃**Solution :**

In CSS, pseudo-classes and pseudo-elements are used to select and style specific parts of an element's content based on certain conditions or states. While both pseudo-classes and pseudo-elements enhance the styling capabilities of CSS, they have different purposes and target different parts of the element.

**Pseudo-classes**: Pseudo-classes select elements based on a specific state or condition. They are preceded by a colon (:) and target elements based on user interactions, such as hovering over an element, clicking on it, or focusing on it. Pseudo-classes are used to change the style of an element in response to user actions or dynamic states.

Here are some examples of commonly used pseudo-classes:

:hover - Selects an element when the user hovers over it.

:active - Selects an element while it is being clicked or activated.

:focus - Selects an element that has keyboard focus.

:first-child - Selects the first child element of its parent.

:nth-child() - Selects elements based on their position within a parent element.
    
**Pseudo-elements**: Pseudo-elements, on the other hand, select and style specific parts of an element's content. They are preceded by two colons (::) and create virtual elements that can be styled independently. Pseudo-elements are used to add decorative or structural elements to the content of an element, such as inserting generated content before or after an element.

Here are some examples of commonly used pseudo-elements:

::before - Inserts content before the content of an element.

::after - Inserts content after the content of an element.

::first-letter - Selects the first letter of the text content within an element.

::first-line - Selects the first line of the text content within an element.

In summary, pseudo-classes are used to select elements based on states or conditions, while pseudo-elements are used to select and style specific parts of an element's content.



# ← JavaScript →

# Q.24 What is Hoisting in Javascript ?

😃**Solution :**

Hoisting is a behavior in JavaScript where variable and function declarations are moved to the top of their containing scope during the compilation phase. This means that regardless of where the variables and functions are declared in the code, they are treated as if they are declared at the top of their scope.

In JavaScript, there are two types of hoisting: variable hoisting and function hoisting.

### 1. Variable Hoisting: 
When variables are hoisted, the declaration of the variable is moved to the top of its scope, but not the initialization. This means that you can access the variable before it is declared in the code, although its value will be undefined until it is assigned a value.
```Javascript
console.log(x); // undefined
var x = 5;
console.log(x); // 5
```
### 2. Function Hoisting: 
Function declarations are also hoisted to the top of their scope. This means that you can call a function before it is declared in the code.
```Javascript
greet(); // "Hello"

function greet() {
  console.log("Hello");
}
```


# Q.25 What are different higher order functions in JS? What is the difference between .map() and .forEach() ?

😃**Solution :**


# Q.26 What is the difference between .call() .apply() and .bind()? explain with an example.

😃**Solution :**


# Q.27 Explain Event bubbling and Event Capturing in JavaScript with suitable examples.

😃**Solution :**


# Q.28 What is function currying with example?

😃**Solution :**


# Q.29 Explain execution context diagram of following code snippets, use white board to draw execution context diagram
Code Snippet 1
```
console.log('First');
setTimeout(() => console.log('Second'), 0);
console.log('Third');
```

Code Snippet 2
```
console.log('First');
function secondCall() {
console.log('Second');
}
setTimeout(secondCall, 2000);
setTimeout(() => console.log('Third'), 0);
console.log('Third');
```

😃**Solution :**

Code Snippet 1:
Execution Context Diagram:

![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/27946252-4487-441e-a5a2-4ed30a82207c)

Explanation:
1. The global execution context is initially created.
2. The console.log('First') statement is executed, printing "First" to the console.
3. The setTimeout function is called with a callback function and a timeout of 0 milliseconds. This schedules the callback function to be executed after the current execution context is completed.
4. The console.log('Third') statement is executed, printing "Third" to the console.
5. The global execution context is completed, and the callback function is executed from the event queue.
6. The callback function console.log('Second') is executed, printing "Second" to the console.

So, the final output is "First", "Third", and then "Second".

Code Snippet 2:
Execution Context Diagram:

![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/8b2c4678-6303-493d-8c04-5bacedb8e6c9)

Explanation:
1. The global execution context is initially created.
2. The console.log('First') statement is executed, printing "First" to the console.
3. The setTimeout function is called with the secondCall function and a timeout of 2000 milliseconds. This schedules the secondCall function to be executed after a delay of 2000 milliseconds.
4. The second setTimeout function is called with a callback function and a timeout of 0 milliseconds. This schedules the callback function to be executed after the current execution context is completed.
5. The console.log('Third') statement is executed, printing "Third" to the console.
6. The global execution context is completed, and the secondCall function is executed after a delay of 2000 milliseconds, printing "Second" to the console.

So, the final output is "First", "Third", "Third", and then "Second".


# Q.30 What are promises? What are the different states of a promise? Support your answer with an example where you need to create your own promise.

😃**Solution :**


# Q.31 What is ‘this’ keyword in JavaScript? explain with an example & create.

😃**Solution :**

In JavaScript, the this keyword refers to the context in which a function is invoked. It provides a way to access and manipulate the current object or context within a function. The value of this depends on how a function is called or invoked.
```Javascript
function Person(name) {
  this.name = name;
}

const john = new Person('John');
console.log(john.name); // Outputs "John"
```


# Q.32 Explain event loop Call Stack Callback queue and Micro Task queue in Your Words.

😃**Solution :**


# Q.33 Explain Debouncing and Create a project where you are using Debouncing.

😃**Solution :**


# Q.34 Explain Closures and Use cases of Closures.

😃**Solution :**


# Q.35 Create a Blog web app using JavaScript
- Fetch data from https://jsonplaceholder.typicode.com/posts and show it to ui
- User can also add new blog
- Add Delete functionality also



# ← React →



# Q.36 What’s React and What are the advantages of it?

😃**Solution :**


# Q.37 What's Virtual Dom in React & What are the advantages of it?

😃**Solution :**


# Q.38 Explain LifeCycle of React Components?

😃**Solution :**


# Q.39 Whats the difference between Functional Components and Class Components?

😃**Solution :**

### Functional Components:
#### Syntax: 
Functional components are defined as JavaScript functions. They are simpler and have a more concise syntax compared to class components.
#### State management: 
Until React 16.7, functional components were stateless and couldn't manage their own state. However, with the introduction of React Hooks, functional components can now use the useState hook to manage state. Hooks provide a way to use state and other React features in functional components, making them more powerful and flexible.
#### Lifecycle methods: 
Functional components can use lifecycle-related hooks like useEffect and useLayoutEffect to perform side effects and handle component lifecycle events. Hooks provide a more unified and concise approach compared to the traditional lifecycle methods used in class components.
#### Context: 
Functional components can consume context using the useContext hook, providing access to context values without wrapping the component in a context consumer.
#### Performance: 
Functional components can be more performant due to optimizations made by React with the introduction of Hooks. Functional components can also leverage the benefits of the React Fiber architecture for more efficient rendering and updates.

### Class Components:
#### Syntax: 
Class components are defined as JavaScript classes that extend the React.Component class. They require a more verbose syntax with the use of render() method and lifecycle methods.
#### State management: 
Class components have built-in support for managing state using the this.state and this.setState() methods. They can handle state changes and trigger re-rendering of the component.
#### Lifecycle methods: 
Class components have a range of lifecycle methods such as componentDidMount(), componentDidUpdate(), and componentWillUnmount(), which allow you to perform actions at specific points in the component's lifecycle.
#### Context: 
Class components can consume context using the this.context property or by wrapping the component with a context consumer.
#### Legacy usage: 
Class components have been the traditional way of defining components in React and are still widely used in existing codebases. They provide compatibility with older versions of React and certain third-party libraries that rely on class components.
    
    
# Q.40 What are the hooks in React & Can we use Hooks in Class Components?

😃**Solution :**

Hooks are a feature introduced in React 16.8 that allow you to use state and other React features in functional components. They provide a way to reuse stateful logic and manage component state without the need for class components.

Hooks enable you to break down complex components into smaller, reusable functions that are easier to read, test, and maintain.

#### Some commonly used React hooks include:
- useState: Allows functional components to manage local state.
- useEffect: Enables performing side effects in functional components, such as data fetching, subscriptions, or modifying the DOM.
- useContext: Provides access to a React context from within a functional component.
- useReducer: Allows state management with a reducer function, similar to how it's done in Redux.
- useCallback: Memoizes a function to prevent unnecessary re-renders in child components.
- useMemo: Memoizes the result of a function to optimize expensive calculations.
- useRef: Provides a mutable reference that persists across re-renders.

Regarding the use of hooks in class components, hooks are designed specifically for functional components. They cannot be directly used in class components. However, if you have a class component and you want to use hooks functionality, you can consider using the react-hooks-helper library or converting the class component into a functional component using the function syntax.


# Q.41 What are the LifeCycle method and the advantages of it?

😃**Solution :**

In React, lifecycle methods are special methods that are invoked at different stages of a component's lifecycle. They allow you to perform specific actions at key points in the lifecycle, such as when a component is mounted, updated, or unmounted. However, it's important to note that with the introduction of React Hooks, some lifecycle methods are being replaced by Hooks.

#### Advantages of Lifecycle Methods:
- Control over component behavior: Lifecycle methods give you control over what happens at each stage of a component's lifecycle. This allows you to perform initialization, cleanup, or additional logic as needed.
- Optimization and performance: By using lifecycle methods effectively, you can optimize the rendering and updating process of components. For example, you can avoid unnecessary re-renders or perform conditional updates based on specific conditions.
- Integration with external libraries and APIs: Lifecycle methods are often used to integrate with external libraries or APIs. For example, you can initialize and clean up subscriptions, set up event listeners, or interact with third-party JavaScript libraries.
-Access to the DOM: Certain lifecycle methods provide access to the DOM, allowing you to manipulate the DOM directly or perform actions that require knowledge of the DOM structure.
- Side effects and asynchronous operations: Lifecycle methods provide opportunities to perform side effects, such as making AJAX requests, updating state asynchronously, or performing animations.


# Q.42 What’s useState Hook & Advantages of it?

😃**Solution :**

In React, the useState hook is a built-in hook that allows functional components to manage state. It provides a way to declare and update state variables within a component without the need for class components or using the this keyword.

The useState hook returns an array with two elements: the current state value and a function to update the state. You can initialize the state with an initial value, and the hook returns the current value and a function to modify it. Whenever the state is updated using the state update function, React re-renders the component and reflects the new state value.

Here's an example of how to use useState:
```Javascript
import React, { useState } from 'react';

const Counter = () => {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(count + 1);
  };

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={increment}>Increment</button>
    </div>
  );
};
```
#### Advantages of useState:
- Simplicity: useState simplifies state management in functional components by providing a straightforward API. It eliminates the need for class components and the complexities associated with them, making the code more concise and easier to understand.
- Functional purity: With useState, state updates are done immutably, preserving the functional programming principle of immutability. The state update function provided by useState creates a new state value based on the previous state, ensuring that updates do not mutate the existing state directly.
- Multiple state variables: Unlike the traditional this.state in class components, useState allows you to declare multiple independent state variables within a single component. You can call useState multiple times to manage different pieces of state within the same component, providing better organization and modularity.
- Automatic re-rendering: When the state is updated using the state update function, React automatically re-renders the component and reflects the new state value. This enables seamless UI updates based on the current state, ensuring that the component always stays in sync with the data it manages.
- Hooks integration: useState is part of the Hooks API in React, which allows you to use other hooks and build custom hooks. Hooks provide a consistent way to manage state, side effects, and other features in functional components, promoting code reuse and modularity.

Overall, useState is a fundamental hook in React that enables functional components to manage state. It offers simplicity, functional purity, automatic re-rendering, and integration with other hooks, making state management in React more intuitive and efficient


# Q.43 Explain useEffect & Advantages of it.

😃**Solution :**

In React, the useEffect hook is a built-in hook that allows you to perform side effects in functional components. Side effects refer to any code that interacts with the external world, such as fetching data, subscribing to events, manipulating the DOM, or setting up timers.

The useEffect hook takes two arguments: a function that represents the side effect and an optional dependency array.

Here's an example of how to use useEffect:
```Javascript
import React, { useEffect, useState } from 'react';

const Timer = () => {
  const [seconds, setSeconds] = useState(0);

  useEffect(() => {
    // Update the document title with the current seconds
    document.title = `Timer: ${seconds}`;

    // Clean up the effect by stopping the timer
    return () => {
      clearInterval(timerId);
    };
  }, [seconds]);

  const timerId = setInterval(() => {
    setSeconds(prevSeconds => prevSeconds + 1);
  }, 1000);

  return <div>Seconds: {seconds}</div>;
};
```
#### Advantages of useEffect:
- Separation of concerns: useEffect allows you to separate side effects from the main component logic. By encapsulating side effects within the effect function, you can keep your component code focused on rendering UI and managing state, improving code readability and maintainability.
- Lifecycle management: useEffect covers the functionality of lifecycle methods in class components, such as componentDidMount, componentDidUpdate, and componentWillUnmount. You can handle side effects when the component mounts, updates, or unmounts by using the appropriate dependencies and cleanup functions.
- Asynchronous operations: useEffect is capable of handling asynchronous operations within the effect function. You can make API calls, fetch data, or perform any other asynchronous tasks using promises or async/await syntax. This allows you to manage asynchronous logic and update the component state accordingly.
- Dependency tracking: The dependency array in useEffect allows you to specify the dependencies that trigger the re-execution of the effect. This ensures that the effect runs only when the specified dependencies change, avoiding unnecessary re-execution and optimizing performance.
- Cleanup mechanism: useEffect provides a cleanup mechanism through the optional return function. This function is invoked when the component unmounts or when the dependencies change before the next effect execution. It allows you to clean up any resources or subscriptions created by the effect, preventing memory leaks and unnecessary computations.

Overall, useEffect is a versatile and powerful hook in React that enables you to manage side effects, handle asynchronous operations, and control the lifecycle of functional components. It promotes clean code organization, encapsulation of side effects, and efficient rendering.


# Q.44 Explain Context Api and create a minor project on it
- Create dashboard and with button on clicking on that change theme to dark and light


# Q.45 Explain useReducer and Its advantages.

😃**Solution :**

In React, useReducer is a built-in hook that provides an alternative to using the useState hook for managing complex state logic. It is primarily used when you have state transitions that are more intricate and involve multiple sub-values or require advanced state management.

The useReducer hook takes two arguments: a reducer function and an initial state. It returns an array with two elements: the current state and a dispatch function. The reducer function receives the current state and an action, and it returns the new state based on the action type.

Here's an example of how to use useReducer:
```Javascript
import React, { useReducer } from 'react';

// Reducer function
const reducer = (state, action) => {
  switch (action.type) {
    case 'INCREMENT':
      return { count: state.count + 1 };
    case 'DECREMENT':
      return { count: state.count - 1 };
    default:
      return state;
  }
};

// Component using useReducer
const Counter = () => {
  const [state, dispatch] = useReducer(reducer, { count: 0 });

  const increment = () => {
    dispatch({ type: 'INCREMENT' });
  };

  const decrement = () => {
    dispatch({ type: 'DECREMENT' });
  };

  return (
    <div>
      <p>Count: {state.count}</p>
      <button onClick={increment}>Increment</button>
      <button onClick={decrement}>Decrement</button>
    </div>
  );
};
```

#### Advantages of useReducer:
- Simplified state management: useReducer is useful when managing complex state transitions. It allows you to handle state changes based on different actions in a single centralized reducer function, making the state management logic easier to understand and maintain.
- Centralized logic: By using a reducer function, you can centralize all state transitions and side effects related to a specific piece of state. This improves code organization and reduces duplication of logic.
- Predictable state updates: useReducer follows the same principles as the traditional reducer pattern, making state updates predictable. The reducer function takes the current state and an action and returns the new state, ensuring that updates are consistent and deterministic.
- Suitable for complex state: When your state contains multiple sub-values or requires more advanced logic, such as updating multiple state properties simultaneously or performing asynchronous operations, useReducer provides a more flexible solution compared to useState.
- Integration with context: useReducer can be used in conjunction with the Context API in React, allowing you to manage global state or share state across components without the need for prop drilling.

Overall, useReducer is a powerful hook that provides a structured and predictable approach to managing state in complex scenarios. It promotes code organization, reduces duplication, and improves maintainability of your React components.


# Q.46 build a Todo Web App Using React and useReducer Hook.


# Q.47 Build A simple counter app using React.


# Q.48 Build Calculator Using React Only.


# Q.49 Build a Tic Tac Toe Game using Class Component of React.


# Q.50 Explain Prop Drilling & How can we avoid it?

😃**Solution :**

Prop drilling occurs when a parent component passes data down to its children and then those children pass the same data down to their own children. This process can continue indefinitely. At the end, it's a long chain of component dependencies that can be difficult to manage and maintain.

Prop drilling can lead to several issues:
- It adds unnecessary complexity and verbosity to the codebase.
- It can make the code harder to understand and maintain as the number of components increases.
- It tightly couples components together, making it difficult to modify or refactor them independently.

To avoid prop drilling, you can employ a couple of techniques:
- Context API: The Context API in React allows you to create a shared state or data that can be accessed by multiple components without passing props explicitly. You can define a context at a higher level in the component tree and provide the required values to it. Then, the nested components can access these values without the need for prop drilling. Context API provides a way to avoid prop drilling by establishing a direct connection between the source of the data and the consuming components.
- Redux or other state management libraries: Redux is a popular state management library for React applications. It allows you to centralize and manage the state of your application in a single store. By using Redux or similar libraries, you can store the required data in the global state and access it from any component in the application without the need for prop drilling.
    
# Q.51 Create a task manager where user can create tasks and see his task
- Redirect him to task dashboard section after login
- Use https://reqres.in/ api to authenticate user and redirect him to task manager dashboard where he can see his task and create


# ← Express →



# Q.52 Create a simple server using Express and connect with backend and create an endpoint “/post” which sends 20 posts.


# Q.53 Explain a middleware and create a middleware that checks is user authenticated or not then send data of post.


# Q.54 Create a backend for blog app, where user can perform crud operations
- Add blog
- Delete blog
- Update blog
- Replace blog


# Q.55 What is the difference between authentication and authorization?

😃**Solution :**

Authentication: Authentication is the process of verifying the identity of a user or entity attempting to access a system. It confirms that the user is who they claim to be. Authentication typically involves presenting credentials such as a username and password, biometric information, security tokens, or digital certificates to prove identity. The goal of authentication is to ensure that only legitimate users gain access to the system.

Authorization: Authorization, on the other hand, is the process of granting or denying permissions and privileges to authenticated users. Once a user's identity has been established through authentication, authorization determines what actions or resources the user is allowed to access within the system. Authorization is based on predefined rules, access control lists (ACLs), or roles assigned to users. It ensures that authenticated users have appropriate rights and permissions to perform specific actions or access certain resources.

Notes--> authentication is about verifying the identity of a user, while authorization is about determining what the user is allowed to do or access once their identity has been established.


# Q.56 What is he difference between common JS and EJS module?

😃**Solution :**

CommonJS (CJS):
- CommonJS is a module system primarily used in server-side JavaScript environments, such as Node.js.
- It uses the require() function to import modules and the module.exports or exports object to define the exports of a module.
- CJS modules have a synchronous nature, where dependencies are resolved at runtime.

```Javascript
// greet.js
const message = 'Hello, ';

function greet(name) {
  console.log(message + name);
}

module.exports = greet;
```
```Javascript
// main.js
const greet = require('./greet');

greet('John'); // Output: Hello, John
```

EJS (ECMAScript Modules):
- It uses import and export statements to handle module imports and exports.
- EJS modules are asynchronous and have a static nature, where dependencies are resolved statically at the time of module loading.

```Javascript
// greet.js
const message = 'Hello, ';

export function greet(name) {
  console.log(message + name);
}
```

```Javascript
// main.js
import { greet } from './greet';

greet('John'); // Output: Hello, John
```


# Q.57 What is JWT and what we can achieve with that create a minor project with jwt
- Login and sign up
- Add authentication using jwt


# Q.58 What should we do with the password of a user before storing it into DB?

😃**Solution :**

When handling user passwords, it is essential to follow security best practices to protect sensitive information. Here are some recommended steps to handle user passwords before storing them in a database:
- Hashing: Passwords should never be stored in plain text. Instead, they should be hashed using a strong cryptographic hashing algorithm, such as bcrypt, Argon2, or scrypt. Hashing is a one-way process that transforms the password into a fixed-length string of characters. The resulting hash cannot be reverse-engineered to obtain the original password.
- Salt: To further enhance the security of hashed passwords, it is recommended to use a unique salt for each user. A salt is a random value that is added to the password before hashing. Salting helps prevent attacks such as rainbow table attacks, where precomputed hash values are compared against stored hashes.
- Strong Hashing Algorithm: Choose a secure and widely accepted hashing algorithm, such as bcrypt or Argon2, which are specifically designed for password hashing. These algorithms incorporate features like adjustable work factor and memory hardness to protect against brute-force attacks.
- Work Factor and Iterations: Configure the hashing algorithm with an appropriate work factor or iteration count. A higher work factor or iteration count increases the computational cost required to hash the password, making it more difficult for attackers to crack passwords using brute-force or dictionary attacks.
- Server-Side Hashing: Perform password hashing on the server-side rather than on the client-side. This ensures that the plaintext password never leaves the server and reduces the risk of interception or tampering.
- Secure Transport: When transmitting passwords over a network, use secure protocols such as HTTPS to encrypt the communication and prevent interception or eavesdropping.
- Strong Access Controls: Protect the database that stores user passwords with strong access controls. Only authorized personnel should have access to the database.

By following these practices, you can significantly enhance the security of user passwords and minimize the risk of unauthorized access to user accounts.


# Q.59 Whats event loop in NodeJS?

😃**Solution :**

In Node.js, the event loop is a fundamental part of its runtime environment. It is responsible for handling asynchronous operations, such as I/O operations, timers, and callbacks, in an efficient and non-blocking manner.

The event loop allows Node.js to handle multiple concurrent operations without getting blocked, which is crucial for building scalable and high-performance applications. It enables Node.js to handle a large number of concurrent connections efficiently.

Let's go through an example to illustrate how the event loop works in Node.js.

```Javascript
console.log("Start");

setTimeout(function() {
  console.log("Callback 1");
}, 2000);

setTimeout(function() {
  console.log("Callback 2");
}, 1000);

console.log("End");
/*
Output:
Start
End
Callback 2
Callback 1
*/
```


# Q.60 Create a Full Stack Ecommerce website with all major functionalities.
