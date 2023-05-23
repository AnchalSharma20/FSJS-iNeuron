### Before Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/ea348a70-6c16-402e-aede-50c766d4d6bd)

## Task 1
**Remove the languages that have 2.0 in their name(Every alternative language)**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/0e9803e2-9a89-4c8c-a009-351d4f5e66c1)
**Solution :**

**Create script.js file**

```Javascript
//Task 1
var languageOffered = document.getElementsByClassName('main__languages')[0];
var aTags = languageOffered.getElementsByTagName('a');

for (var i = 0; i < aTags.length; i++) {
    if (aTags[i].textContent.includes('2.0')) {
    languageOffered.removeChild(aTags[i]);
}
}
```

## Task 2

**Use JavaScript to write something in the input box and submit the form. This should refresh the page and the languages in the left card should come back.**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/e9c3e554-cf1e-4ce8-8c56-e0c088bacf90)

**Solution :**

**Create script.js file**

```Javascript
//Task 2
var input = document.querySelector(".main__form-input");

input.removeAttribute("disabled");
input.setAttribute("placeholder","iNeuron");

var submit = document.querySelector(".main__form-btn");
submit.removeAttribute("disabled");

document.addEventListener("load",()=>{

});
```
