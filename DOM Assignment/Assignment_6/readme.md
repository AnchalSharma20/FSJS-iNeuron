## Before Update :

![image](https://user-images.githubusercontent.com/113786234/236130173-5c3842a3-992d-4a34-b051-a3d531780855.png)

## Task 1
**The user has to remove the equalizer text and add iNeuron Image.**
### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/93f664a6-682b-4ce5-97b3-637ddd24189b)

**Solution :**

**Create script.js file**

```Javascript
var companyLogo = document.getElementsByClassName('logo')[0];
companyLogo.setAttribute('src', './assets/ineuron-logo.png');
```

## Task 2
**The user has to change the price value and a linkedin social media icon in the footer.**

### After Update :
![image](https://github.com/AnchalSharma20/FSJS-iNeuron/assets/113786234/12f00610-d6cb-4d13-932f-20c8c10b0df9)


**Solution :**

**Create script.js file**

```Javascript
// Task 2
// Price change
let price = document.querySelector(".app_price span")
price.innerText = "$10"

//Social Media Icon
let socials = document.querySelector(".footer_social")
console.log(socials)

let linkedin = document.createElement("div")
linkedin.className = "footer_social_ico"
socials.appendChild(linkedin)

let icon = document.createElement("i")
icon.className = "fa-brands fa-linkedin"
linkedin.appendChild(icon)

/*
var priceSpan = document.getElementsByClassName('app_price')[0].children[0];
priceSpan.innerHTML='$10'

// social media
var footer_social = document.querySelector(".footer_social");

var footer_social_ico = document.createElement("div");
footer_social.appendChild(footer_social_ico);
footer_social_ico.setAttribute('class','footer_social_ico');
footer_social_ico.innerHTML='<i class="fa-brands fa-linkedin"></i>';
*/
```
