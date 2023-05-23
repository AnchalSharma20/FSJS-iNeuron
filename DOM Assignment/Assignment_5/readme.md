### Before Update :

![image](https://user-images.githubusercontent.com/113786234/235341027-631abc7e-51e8-4223-a874-4078551d16e9.png)

## Task
**The user has to change the reciepe color, add card to it and add a "Pro Subscription" button in the top.**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/9bf5d713-2f55-4fe7-9c64-1524bd382420)

**Solution :**

**Create script.js file**

```Javascript

var addButton = document.getElementsByClassName('nav-center')[0].children[2];

console.log(addButton);

var buttonElement = document.createElement('a');
addButton.appendChild(buttonElement);
buttonElement.setAttribute('href', '#');
buttonElement.setAttribute('class', 'btn');
buttonElement.innerText= 'Pro Subcriptions';

var cardSection = document.getElementsByClassName('recipe-gallery');

var addCard = document.createElement('div');
cardSection[0].appendChild(addCard);
addCard.setAttribute('class', 'card');

var aTag = document.createElement('a');
addCard.appendChild(aTag);
aTag.setAttribute('href','#');
aTag.setAttribute('class', 'recipe-text');

var imageTag = document.createElement('img');
aTag.appendChild(imageTag);
imageTag.setAttribute('src', './img/recipe-5.jpeg');
imageTag.setAttribute('class', 'recipe-img');

var titleTag = document.createElement('h5');
aTag.appendChild(titleTag);
titleTag.setAttribute('class','recipe-name');
titleTag.innerText = 'Chicken Tikka';

var pTag = document.createElement('p');
aTag.appendChild(pTag);
pTag.setAttribute('class','recipe-disp');
pTag.innerText = 'I have cretaed this using js';
```


