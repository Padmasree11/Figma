# Ex09 Event Registration Web Application
## Date:13/10/25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-12-at-20-09-16-f517e731-1.png" />
      <img class="img" src="img/whatsapp-image-2025-10-12-at-20-19-04-f526a6ac-1.png" />
      <div class="text-wrapper">sports day event</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="div">register</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">login</div>
    </div>
  </body>
</html>

style.css

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 587px;
  min-height: 1028px;
  position: relative;
}

.iphone .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 587px;
  height: 1013px;
  aspect-ratio: 0.69;
  object-fit: cover;
}

.iphone .img {
  position: absolute;
  top: 25px;
  left: 10px;
  width: 567px;
  height: 85px;
  aspect-ratio: 6.67;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 408px;
  left: 107px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #f01515;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 854px;
  left: 305px;
  width: 269px;
  height: 63px;
}

.iphone .rectangle {
  position: absolute;
  top: 637px;
  left: 170px;
  width: 269px;
  height: 66px;
  background-color: #f91818;
}

.iphone .div {
  position: absolute;
  top: 637px;
  left: 216px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 514px;
  left: 172px;
  width: 267px;
  height: 69px;
  background-color: #fb1313;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 514px;
  left: 251px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="box"><img class="iphone" src="img/iphone-16-1.svg" /></div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.box {
  width: 465px;
  height: 852px;
}

.box .iphone {
  position: fixed;
  top: 0;
  left: 0;
  width: 465px;
  height: 852px;
}

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-12-at-21-04-22-7b61a4c6-1.png" />
      <img class="rectangle" src="img/rectangle-3.svg" />
      <div class="text-wrapper">AGE :</div>
      <img class="img" src="img/rectangle-2.svg" />
      <div class="div">GENDER :</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper-2">EVENT REGISTRAION FORM</div>
      <img class="rectangle-2" src="img/rectangle-1.svg" />
      <img class="rectangle-3" src="img/rectangle-4.svg" />
      <div class="REGISTER-NUMBER">REGISTER NUMBER :</div>
      <div class="text-wrapper-3">FULL NAME :</div>
      <img class="text-on-a-path-2" src="img/image.svg" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">register</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 579px;
  min-height: 852px;
  position: relative;
}

.iphone .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 579px;
  height: 852px;
  aspect-ratio: 0.68;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 374px;
  left: 29px;
  width: 472px;
  height: 72px;
}

.iphone .text-wrapper {
  position: absolute;
  top: 376px;
  left: 29px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .img {
  position: absolute;
  top: 260px;
  left: 29px;
  width: 472px;
  height: 72px;
}

.iphone .div {
  position: absolute;
  top: 260px;
  left: 29px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 388px;
  left: 149px;
  width: 482px;
  height: 79px;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 29px;
  left: 44px;
  width: 526px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 29px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 146px;
  left: 29px;
  width: 485px;
  height: 72px;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 474px;
  left: 29px;
  width: 472px;
  height: 72px;
}

.iphone .REGISTER-NUMBER {
  position: absolute;
  top: 474px;
  left: 29px;
  width: 328px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 146px;
  left: 29px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-on-a-path-2 {
  position: absolute;
  top: 974px;
  left: 303px;
  width: 212px;
  height: 52px;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 641px;
  left: 211px;
  width: 212px;
  height: 59px;
  background-color: #ff3232;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 633px;
  left: 254px;
  width: 160px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 26px;
  letter-spacing: 0;
  line-height: normal;
}

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-17-at-18-32-37-fd838bf9-1.png" />
      <div class="text-wrapper">Thank you</div>
      <p class="we-all-are-eagerly">
        we all are eagerly <br />waiting for your <br />participation in the<br />sports even
      </p>
      <img class="img" src="img/whatsapp-image-2025-10-12-at-20-19-04-f526a6ac-1.png" />
      <div class="div">contact us</div>
      <p class="email-sportsevents">Email : sportsevents@gmail.com<br />contact no : 2345678901</p>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 0.55;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 108px;
  left: 99px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 35px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .we-all-are-eagerly {
  position: absolute;
  top: 198px;
  left: 86px;
  width: 613px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .img {
  position: absolute;
  top: 23px;
  left: 10px;
  width: 392px;
  height: 59px;
  aspect-ratio: 6.67;
  object-fit: cover;
}

.iphone-pro .div {
  position: absolute;
  top: 533px;
  left: 137px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #f81b1b;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .email-sportsevents {
  position: absolute;
  top: 595px;
  left: 26px;
  width: 457px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #1919ff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}




```

## OUTPUT:
![alt text](<WhatsApp Image 2025-10-17 at 18.53.52_226669ac.jpg>)
![alt text](<WhatsApp Image 2025-10-17 at 18.52.57_e4dbbad5.jpg>)
![alt text](<WhatsApp Image 2025-10-17 at 18.52.19_c6e9e7c3.jpg>)
![alt text](<WhatsApp Image 2025-10-17 at 18.51.36_cff73c74.jpg>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
