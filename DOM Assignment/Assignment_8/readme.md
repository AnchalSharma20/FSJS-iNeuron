### Before Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/b8a7f4ac-5206-4d21-8100-de58ab7db4bb)

## Task 1
**The User has to make a scrollable sidebar and make a red border around sidebar**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/8a9633da-4f42-45b0-a78a-fe1793f3e855)

**Solution :**

**Create script.js file**

```Javascript
let aSide = document.querySelector("aside")
  aSide.style.overflowY = "scroll"
  let hrLine = document.createElement('hr')
  hrLine.setAttribute("class", "hr-line")
  let newH2 = document.createElement('h2')
  newH2.setAttribute("class", "new-head")
  newH2.textContent = "This is my custom Heading"
  let newP2 = document.createElement('p')
  newP2.setAttribute("class", "new-p")
  newP2.textContent = "Private funding by VC firms is down 50% YOY. We take a look at what that means."
  aSide.append(hrLine,newH2,newP2)
  let asideParent = aSide.parentNode
  let div = document.createElement("div")
  asideParent.replaceChild(div, aSide)
  div.appendChild(aSide)
  div.setAttribute("class", "col-lg-4")
  aSide.removeAttribute("class")
  aSide.setAttribute("class", "new")
  div.style.border = "4px solid red"
  div.style.padding = "10px 5px"
  div.style.height = "490px"
  ```


## Task 2
**The User has to remove the background image.**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/95490903-437b-43ca-bea3-79f01e92fb45)

**Solution :**

**Create script.js file**

```Javascript
//Task 2
document.body.style.backgroundImage = "none"
```

## Task 3
**The User has to open the hamburger menu.**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/db39c637-9f06-4122-83af-f44f14e7b221)

**Solution :**

**Create script.js file**

```Javasript
// Task 3
let nav = document.querySelector(".navbar-toggler")
nav.addEventListener("click", () => {
    document.querySelector("#navbarTogglerDemo01").classList.toggle("collapse")
})
console.log(document.querySelector("#navbarTogglerDemo01").classList)
```






