# ← HTML →

Q.1 `<!DOCTYPE html>` is it a tag of html? If not, what is it and why do we use it?
```
Yes, `<!DOCTYPE html>` is indeed a tag in HTML, but it is more accurately referred to as a document type declaration (DTD)
rather than a tag. The `<!DOCTYPE html>` declaration is placed at the very beginning of an HTML document to specify the
version of HTML being used. The purpose of the document type declaration is to ensure that the HTML document is rendered 
correctly by web browsers. It helps the browser  determine how to interpret and display the content. Different versions 
of HTML have different rules and features, so specifying the document type helps ensure compatibility and consistency 
across browsers.
```


Q.2 Explain Semantic tags in html? And why do we need it?

Q.3 Differentiate between HTML Tags and Elements?

Q.4 Build Your Resume using HTML only.

Q.5 Write Html code so that it looks like the given image 

<img width="260" alt="html" src="https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/d98f5dae-ae38-473d-840d-477449e8336a">


Q.6 What are some of the advantages of HTML5 over its previous versions?

Q.7 Create a simple Music player using html only.

Q.8 What is the difference between `<figure>` tag and `<img>` tag?
  
Q.9 What’s the difference between html tag and attribute and give example of some global attributes?
  
Q.10 Build Table which looks like the given image


![Screenshot 2023-05-25 at 14-35-51 2T7Y1 gif (GIF Image 472 × 278 pixels)](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/fcff3c94-e498-4377-bc45-ebc281bca4c1)

  
  
# ← CSS →

Q.11 Whats Box Model in CSS & Which CSS Properties are part of it ?

Q.12 What are the Different Types of Selectors in CSS & what are the advantages of them?

Q.13 What is VW/VH & How its different from PX?

Q.14 Whats difference between Inline, Inline Block and block ?

Q.15 How is Border-box different from Content Box?

Q.16 What’s z-index and How does it Function ?

Q.17 What’s Grid & Flex and difference between them?

Q.18 Difference between absolute and relative and sticky and fixed position explain with example.

Q.19 Build Periodic Table as shown in the below image ![Screenshot 2023-05-25 at 14-28-53 Assessment Documents for Full Stack Web Development - FSJS2 0 Assignment pdf](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/cdb5e2a3-2529-46f3-8a8c-bf1ae140940a)


Q.20 Build given layout using grid or flex see below image for reference .
![Screenshot 2023-05-25 at 14-38-26 Assessment Documents for Full Stack Web Development - FSJS2 0 Assignment pdf](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/48d163c6-ca1c-44e3-b924-85b89ca724ec)


Q.21 Build Responsive Layout both desktop and mobile and Tablet, see below image for reference ?
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/4bed6137-0e6e-4f83-9d94-eb8f03c6aec9)


Q.22 Build Complete Homepage of Ineuron [Link](https://ineuron.ai/) with responsiveness.

Q.23 What are Pseudo class in CSS & How its different From Pseudo Elements?

# ← JavaScript →

Q.24 What is Hoisting in Javascript ?

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

Q.52 Create a simple server using Express and connect with backend and create an endpoint
“/post” which sends 20 posts.

Q.53 Explain a middleware and create a middleware that checks is user authenticated or not
then send data of post

Q.54 Create a backend for blog app, where user can perform crud operations
- Add blog
- Delete blog
- Update blog
- Replace blog

Q.55 What is the difference between authentication and authorization?

Q.56 What is he difference between common JS and EJS module?

Q.57 What is JWT and what we can achieve with that create a minor project with jwt
- Login and sign up
- Add authentication using jwt

Q.58 What should we do with the password of a user before storing it into DB?

Q.59 Whats event loop in NodeJS?

Q.60 Create a Full Stack Ecommerce website with all major functionalities.
