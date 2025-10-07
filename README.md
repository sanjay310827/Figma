# Ex09 Event Registration Web Application
## Date:

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
slide 1

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
    <div class="android-medium">
      <img class="d" src="img/d2-1.png" />
      <img class="saveetha" src="img/saveetha-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">sports day event</div>
      <div class="div"></div>
      <div class="text-wrapper-2">login</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Register</div>
      <div class="text-wrapper-4">designed by: SANJAY(25016505)</div>
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
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .d {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.android-medium .saveetha {
  position: absolute;
  top: 77px;
  left: 13px;
  width: 674px;
  height: 140px;
  aspect-ratio: 4.81;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 286px;
  left: 142px;
  width: 446px;
  height: 96px;
  background-color: #fef5f53d;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 300px;
  left: 162px;
  width: 435px;
  font-family: "Fredoka One-Regular", Helvetica;
  font-weight: 400;
  color: #161f27;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 494px;
  left: 54px;
  width: 215px;
  height: 81px;
  background-color: #254c73a6;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 498px;
  left: 99px;
  font-family: "Kaisei HarunoUmi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 489px;
  left: 360px;
  width: 270px;
  height: 86px;
  background-color: #1e4165b0;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 494px;
  left: 399px;
  width: 217px;
  font-family: "Kaisei HarunoUmi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 777px;
  left: 67px;
  width: 618px;
  font-family: "Libre Caslon Text-Bold", Helvetica;
  font-weight: 700;
  color: #e31616;
  font-size: 36px;
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
    <div class="android-medium">
      <img class="d" src="img/d4-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">sports day event</div>
      <img class="star" src="img/star-1.svg" />
      <div class="div">cricket</div>
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <img class="star-5" src="img/star-7.svg" />
      <img class="star-6" src="img/star-8.svg" />
      <img class="star-7" src="img/star-6.svg" />
      <div class="text-wrapper-2">football</div>
      <div class="text-wrapper-3">hockey</div>
      <div class="text-wrapper-4">badmitton</div>
      <div class="text-wrapper-5">table tennis</div>
      <div class="text-wrapper-6">basket ball</div>
    </div>
  </body>
</html>

global.css
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
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .d {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 71px;
  left: 97px;
  width: 506px;
  height: 105px;
  background-color: #0000008c;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 85px;
  left: 103px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star {
  position: absolute;
  top: 259px;
  left: 48px;
  width: 25px;
  height: 23px;
}

.android-medium .div {
  position: absolute;
  top: 245px;
  left: 111px;
  font-family: "Marko One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 357px;
  left: 48px;
  width: 25px;
  height: 23px;
}

.android-medium .star-2 {
  position: absolute;
  top: 465px;
  left: 17px;
  width: 56px;
  height: 63px;
}

.android-medium .star-3 {
  position: absolute;
  top: 407px;
  left: 50px;
  width: 33px;
  height: 30px;
}

.android-medium .star-4 {
  position: absolute;
  top: 457px;
  left: 49px;
  width: 24px;
  height: 24px;
}

.android-medium .star-5 {
  position: absolute;
  top: 658px;
  left: 50px;
  width: 24px;
  height: 24px;
}

.android-medium .star-6 {
  position: absolute;
  top: 757px;
  left: 51px;
  width: 24px;
  height: 24px;
}

.android-medium .star-7 {
  position: absolute;
  top: 557px;
  left: 50px;
  width: 24px;
  height: 24px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 342px;
  left: 111px;
  font-family: "Marko One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 441px;
  left: 111px;
  font-family: "Marko One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 544px;
  left: 108px;
  font-family: "Marko One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 644px;
  left: 108px;
  width: 243px;
  font-family: "Marko One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 743px;
  left: 111px;
  font-family: "Marko One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
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
    <div class="android-medium">
      <img class="d" src="img/d1-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Event Registration Form</div>
      <img class="img" src="img/rectangle-2.svg" />
      <div class="div">fill the details</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Full Name</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-3">Registration No.</div>
      <div class="text-wrapper-4">Gender</div>
      <div class="text-wrapper-5">Age</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">Department</div>
      <div class="ellipse"></div>
      <div class="text-wrapper-7">Register</div>
    </div>
  </body>
</html>

global.css
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
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .d {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 0.71;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 35px;
  left: 61px;
  width: 586px;
  height: 92px;
  background-color: #84848412;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 11px;
  left: 90px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #d6090d;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 146px;
  left: 60px;
  width: 162px;
  height: 63px;
}

.android-medium .div {
  position: absolute;
  top: 127px;
  left: 90px;
  font-family: "Inria Sans-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 177px;
  left: 66px;
  width: 310px;
  height: 77px;
  background-color: #36618c;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 190px;
  left: 96px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 280px;
  left: 66px;
  width: 310px;
  height: 73px;
  background-color: #36618c;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 383px;
  left: 66px;
  width: 310px;
  height: 73px;
  background-color: #37618cb8;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 492px;
  left: 66px;
  width: 310px;
  height: 73px;
  background-color: #37618ccf;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 510px;
  left: 82px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 295px;
  left: 96px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 392px;
  left: 90px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 601px;
  left: 66px;
  width: 310px;
  height: 73px;
  background-color: #37618ccf;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 622px;
  left: 90px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .ellipse {
  position: absolute;
  top: 723px;
  left: 436px;
  width: 248px;
  height: 95px;
  background-color: #0b051d;
  border-radius: 124px / 47.5px;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 749px;
  left: 493px;
  font-family: "Instrument Sans-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-10-07 220102.png>)

![alt text](<Screenshot 2025-10-07 220004.png>) 

![alt text](<Screenshot 2025-10-07 214945.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
