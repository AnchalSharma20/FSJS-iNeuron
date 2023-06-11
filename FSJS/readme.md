# ← HTML →

Q.1 `<!DOCTYPE html>` is it a tag of html? If not, what is it and why do we use it?

**Solution :**

```
Yes, `<!DOCTYPE html>` is indeed a tag in HTML, but it is more accurately referred to as a document type declaration (DTD)
rather than a tag. The `<!DOCTYPE html>` declaration is placed at the very beginning of an HTML document to specify the
version of HTML being used. The purpose of the document type declaration is to ensure that the HTML document is rendered 
correctly by web browsers. It helps the browser  determine how to interpret and display the content. Different versions 
of HTML have different rules and features, so specifying the document type helps ensure compatibility and consistency 
across browsers.
```


Q.2 Explain Semantic tags in html? And why do we need it?

😃**Solution :**

Q.3 Differentiate between HTML Tags and Elements?

😃**Solution :**

Q.4 Build Your Resume using HTML only.

Q.5 Write Html code so that it looks like the given image 

<img width="260" alt="html" src="https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/d98f5dae-ae38-473d-840d-477449e8336a">


Q.6 What are some of the advantages of HTML5 over its previous versions?

😃**Solution :**

Q.7 Create a simple Music player using html only.

Q.8 What is the difference between `<figure>` tag and `<img>` tag?

😃**Solution :**

Q.9 What’s the difference between html tag and attribute and give example of some global attributes?

😃**Solution :**

Q.10 Build Table which looks like the given image


![Screenshot 2023-05-25 at 14-35-51 2T7Y1 gif (GIF Image 472 × 278 pixels)](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/fcff3c94-e498-4377-bc45-ebc281bca4c1)

  
  
# ← CSS →

Q.11 Whats Box Model in CSS & Which CSS Properties are part of it ?

😃**Solution :**

Q.12 What are the Different Types of Selectors in CSS & what are the advantages of them?

Q.13 What is VW/VH & How its different from PX?

😃**Solution :**

Q.14 Whats difference between Inline, Inline Block and block ?

😃**Solution :**

Q.15 How is Border-box different from Content Box?

😃**Solution :**

Q.16 What’s z-index and How does it Function ?

😃**Solution :**


Q.17 What’s Grid & Flex and difference between them?

😃**Solution :**


Q.18 Difference between absolute and relative and sticky and fixed position explain with example.

😃**Solution :**

In CSS, positioning properties are used to control the layout and positioning of elements on a web page.

Absolute Positioning (position: absolute):

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

Relative Positioning (position: relative):

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

Sticky Positioning (position: sticky):

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
Fixed Positioning (position: fixed):

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

Q.19 Build Periodic Table as shown in the below image ![Screenshot 2023-05-25 at 14-28-53 Assessment Documents for Full Stack Web Development - FSJS2 0 Assignment pdf](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/cdb5e2a3-2529-46f3-8a8c-bf1ae140940a)


Q.20 Build given layout using grid or flex see below image for reference .
![Screenshot 2023-05-25 at 14-38-26 Assessment Documents for Full Stack Web Development - FSJS2 0 Assignment pdf](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/48d163c6-ca1c-44e3-b924-85b89ca724ec)


Q.21 Build Responsive Layout both desktop and mobile and Tablet, see below image for reference ?
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/4bed6137-0e6e-4f83-9d94-eb8f03c6aec9)


Q.22 Build Complete Homepage of Ineuron [Link](https://ineuron.ai/) with responsiveness.

Q.23 What are Pseudo class in CSS & How its different From Pseudo Elements?

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

Q.24 What is Hoisting in Javascript ?

😃**Solution :**

Hoisting is a behavior in JavaScript where variable and function declarations are moved to the top of their containing scope during the compilation phase. This means that regardless of where the variables and functions are declared in the code, they are treated as if they are declared at the top of their scope.

In JavaScript, there are two types of hoisting: variable hoisting and function hoisting.

1. Variable Hoisting: When variables are hoisted, the declaration of the variable is moved to the top of its scope, but not the initialization. This means that you can access the variable before it is declared in the code, although its value will be undefined until it is assigned a value.
```Javascript
console.log(x); // undefined
var x = 5;
console.log(x); // 5
```
2. Function Hoisting: Function declarations are also hoisted to the top of their scope. This means that you can call a function before it is declared in the code.
```Javascript
greet(); // "Hello"

function greet() {
  console.log("Hello");
}
```

Q.25 What are different higher order functions in JS? What is the difference between .map() and .forEach() ?

Q.26 What is the difference between .call() .apply() and .bind()? explain with an example.

Q.27 Explain Event bubbling and Event Capturing in JavaScript with suitable examples.

Q.28 What is function currying with example?

Q.29 Explain execution context diagram of following code snippets, use white board to draw execution context diagram

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

Q.30 What are promises? What are the different states of a promise? Support your answer with an example where you need to create your own promise.

Q.31 What is ‘this’ keyword in JavaScript? explain with an example & create.

Q.32 Explain event loop Call Stack Callback queue and Micro Task queue in Your Words.

Q.33 Explain Debouncing and Create a project where you are using Debouncing.

Q.34 Explain Closures and Use cases of Closures.

Q.35 Create a Blog web app using JavaScript
- Fetch data from https://jsonplaceholder.typicode.com/posts and show it to ui
- User can also add new blog
- Add Delete functionality also

# ← React →

Q.36 What’s React and What are the advantages of it?

Q.37 What's Virtual Dom in React & What are the advantages of it?

Q.38 Explain LifeCycle of React Components?

Q.39 Whats the difference between between Functional Components and Class Components?

Q.40 What are the hooks in React & Can we use Hooks in Class Components?

Q.41 What are the LifeCycle method and the advantages of it?

Q.42 What’s useState Hook & Advantages of it?

Q.43 Explain useEffect & Advantages of it

Q.44 Explain Context Api and create a minor project on it
- Create dashboard and with button on clicking on that change theme to dark and light

Q.45 Explain useReducer and Its advantages.

Q.46 build a Todo Web App Using React and useReducer Hook.

Q.47 Build A simple counter app using React

Q.48 Build Calculator Using React Only

Q.49 Build a Tic Tac Toe Game using Class Component of React.

Q.50 Explain Prop Drilling & How can we avoid it?

Q.51 Create a task manager where user can create tasks and see his task
- Redirect him to task dashboard section after login
- Use https://reqres.in/ api to authenticate user and redirect him to task manager dashboard where he can see his task and create

# ← Express →

Q.52 Create a simple server using Express and connect with backend and create an endpoint “/post” which sends 20 posts.

Q.53 Explain a middleware and create a middleware that checks is user authenticated or not then send data of post.

Q.54 Create a backend for blog app, where user can perform crud operations
- Add blog
- Delete blog
- Update blog
- Replace blog

Q.55 What is the difference between authentication and authorization?

😃**Solution :**

Authentication: Authentication is the process of verifying the identity of a user or entity attempting to access a system. It confirms that the user is who they claim to be. Authentication typically involves presenting credentials such as a username and password, biometric information, security tokens, or digital certificates to prove identity. The goal of authentication is to ensure that only legitimate users gain access to the system.

Authorization: Authorization, on the other hand, is the process of granting or denying permissions and privileges to authenticated users. Once a user's identity has been established through authentication, authorization determines what actions or resources the user is allowed to access within the system. Authorization is based on predefined rules, access control lists (ACLs), or roles assigned to users. It ensures that authenticated users have appropriate rights and permissions to perform specific actions or access certain resources.

Notes--> authentication is about verifying the identity of a user, while authorization is about determining what the user is allowed to do or access once their identity has been established.

Q.56 What is he difference between common JS and EJS module?

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
Q.57 What is JWT and what we can achieve with that create a minor project with jwt
- Login and sign up
- Add authentication using jwt

Q.58 What should we do with the password of a user before storing it into DB?

😃**Solution :**

When handling user passwords, it is essential to follow security best practices to protect sensitive information. Here are some recommended steps to handle user passwords before storing them in a database:
- Hashing: Passwords should never be stored in plain text. Instead, they should be hashed using a strong cryptographic hashing algorithm, such as bcrypt, Argon2, or scrypt. Hashing is a one-way process that transforms the password into a fixed-length string of characters. The resulting hash cannot be reverse-engineered to obtain the original password.

    Salt: To further enhance the security of hashed passwords, it is recommended to use a unique salt for each user. A salt is a random value that is added to the password before hashing. Salting helps prevent attacks such as rainbow table attacks, where precomputed hash values are compared against stored hashes.

    Strong Hashing Algorithm: Choose a secure and widely accepted hashing algorithm, such as bcrypt or Argon2, which are specifically designed for password hashing. These algorithms incorporate features like adjustable work factor and memory hardness to protect against brute-force attacks.

    Work Factor and Iterations: Configure the hashing algorithm with an appropriate work factor or iteration count. A higher work factor or iteration count increases the computational cost required to hash the password, making it more difficult for attackers to crack passwords using brute-force or dictionary attacks.

    Server-Side Hashing: Perform password hashing on the server-side rather than on the client-side. This ensures that the plaintext password never leaves the server and reduces the risk of interception or tampering.

    Secure Transport: When transmitting passwords over a network, use secure protocols such as HTTPS to encrypt the communication and prevent interception or eavesdropping.

    Strong Access Controls: Protect the database that stores user passwords with strong access controls. Only authorized personnel should have access to the database.
Q.59 Whats event loop in NodeJS?

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
Q.60 Create a Full Stack Ecommerce website with all major functionalities.
