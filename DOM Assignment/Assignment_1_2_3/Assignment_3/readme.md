## Task 1
**The user has to add placeholder for input and output board**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/4bc2f658-f834-4350-ba73-4d9b554782c7)


**Solution :**

**Create contact.js file**

```Javascript
// User Output Board
const userOutputBoardInput = document.querySelectorAll('.mainLeftDetails input');
const userOutputBoardTextArea = document.querySelectorAll(".mainLeftDetails textarea");

let inputValue = ["FSJS 2.0","fsjs@ineuron.ai"];
let textAreaValue = ["hello world"];
let inputList = [];
let textAreaList = [];

userOutputBoardInput.forEach((input) => {
    inputList.push(input);
});

userOutputBoardTextArea.forEach((textarea) => {
    textAreaList.push(textarea);
});

for (let i = 0; i < inputList.length; i++){
    inputList[i].value = inputValue[i];
};

for (let i = 0; i < textAreaList.length; i++){
    textAreaList[i].value = textAreaValue[i];
};

// User Input Board
const userInputBoardInput = document.querySelectorAll('.mainRight input');
const userInputBoardTextArea = document.querySelectorAll(".mainRight textarea");

let inputValues = ["FSJS 2.0","fsjs@ineuron.ai"];
let textAreaValues = ["hello world"];
let inputLists = [];
let textAreaLists = [];

userInputBoardInput.forEach((input) => {
    inputLists.push(input);
});

userInputBoardTextArea.forEach((textarea) => {
    textAreaLists.push(textarea);
});

for (let i = 0; i < inputList.length; i++){
    inputLists[i].value = inputValues[i];
};

for (let i = 0; i < textAreaList.length; i++){
    textAreaLists[i].value = textAreaValues[i];
};
```
