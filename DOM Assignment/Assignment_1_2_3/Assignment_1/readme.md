## Task 1
**The user has to change "Contacts" to "Projects" and add "Hire Me" in the navbar**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/8b6250be-c75f-4d65-a173-9b6cf58e96e2)

**Solution :**

**Create script.js file**

```Javascript
var unorderList = document.querySelector('ul');

var firstList = unorderList.children[2];
firstList.innerHTML = 'Projects';

var list2 = document.createElement('li');
list2.innerHTML = '<a href="#">Hire Me</a>';
unorderList.appendChild(list2);
```

## Task 2
**The user has to add "search my project" placeholder inside search**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/8ca4907d-e3a9-4df0-aa4b-46d1dff4bc88)


**Solution :**

**Create script.js file**

```Javascript
var input = document.querySelector('input');

input.placeholder = "Search My Project";
```

## Task 3
**The user has to change "Contacts" to "Projects" and changing the paragraph by adding "ineuron"**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/aaffd3c7-e539-49bc-aa12-f5bd92d3317c)


**Solution :**

**Create script.js file**

```Javascript
var unorderList = document.querySelector('ul');
unorderList.children[2].innerHTML = 'Projects';
let text1 = document.querySelectorAll("section div p span")
text1[2].innerText = "iNeuron Intelligence Pvt Ltd"
```

## Task 4
**The user has to change "Contacts" to "Projects" and changing image**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/22ddd844-de1a-4cb4-8b98-f706aeec1523)


**Solution :**

**Create script.js file**

```Javascript
var unorderList = document.querySelector('ul');
unorderList.children[2].innerHTML = 'Projects';
let image = document.querySelector(".hero-right-section img")
image.src = "https://hiteshchoudhary.com/static/a8d73d1aac4c79e9bb689640e6090367/2eaab/person-image.jpg"
```

## Task 5
**The user has to change "Contacts" to "Projects" and adding "Support Me" button in the bottom**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/53855e20-e735-4747-acac-a52649aa2fa3)


**Solution :**

**Create script.js file**

```Javascript
var unorderList = document.querySelector('ul');
unorderList.children[2].innerHTML = 'Projects';
var buttonDiv = document.getElementsByClassName('hero-right-section-btns');
var button = document.createElement('button');
button.innerHTML = 'Support Me';
buttonDiv[0].appendChild(button);
```
