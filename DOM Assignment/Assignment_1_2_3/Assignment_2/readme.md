
## Task 1
**The user has to change the backgound color of "accordian" heading and change "Contacts" to "Projects"**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/cd5129a8-adb0-4775-aab8-2265b2f0314c)


**Solution :**

**Create script.js file**

```Javascript
var ul = document.querySelector("ul");
ul.children[2].innerHTML = "Project";

const accordianHeading = document.querySelectorAll(".accordian h3");
accordianHeading.forEach(element => {
  element.style.backgroundColor ="#dadaf8";
});

const accordianParagraph = document.querySelectorAll(".accordian p");
accordianParagraph.forEach(element => {
  element.style.backgroundColor ="#eeeeff";
});
```

## Task 2
**The user has add "Skills" in the dropdown along with a small description.**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/29cd53df-44af-493d-a70c-67ee1a890bd9)

**Solution :**

**Create script.js file**

```Javascript
// Task 2
let nav = document.querySelectorAll("ul li")
nav[2].innerText ="Projects"

//Adding Skills in dropdown
let drop = document.querySelector(".accordian-wrapper")
let div1 = document.createElement("div")
//console.log(drop);


let heading1 = document.createElement("h3")
heading1.innerText = "Skills"
let para = document.createElement("p")
para.innerText = "I posses a very good command over the Full Stack Development technologies like MERN which can be seen in my work over the Github."


div1.className = "accordian"
drop.appendChild(div1)

div1.appendChild(heading1)
div1.appendChild(para)
console.log(div1);
```
