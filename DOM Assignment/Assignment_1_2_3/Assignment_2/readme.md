
## Task 1
**The user has to change the backgound color of "accordian" heading**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/ef0e8342-3395-4b68-b73e-aee447669770)

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
**The user has to change "Contacts" to "Projects" and add "Skills" in the dropdown along with a small description.
**

### After Update :

**Solution :**

**Create script.js file**

```Javascript

```
