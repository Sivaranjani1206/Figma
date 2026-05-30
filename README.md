# Ex09 Event Registration Web Application
## Date: 30/05/2026

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
FRAME 1

HTML:
```
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<meta charset="utf-8" />
<link rel="stylesheet" href="globals.css">
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="iphone-pro-max" ><img class="logo" src="img/logo-1.png" />
<img class="BG" src="img/BG-2.png" />
<div class="text-wrapper" >THE GRAVITY GAMES EVENT</div>
<div class="rectangle" ></div>
<div class="LOGIN" > LOGIN</div>
<div class="div" >EMAIL:</div>
<div class="text-wrapper-2" >PASSWORD:</div>
<img class="img" src="img/rectangle-2.svg" />
<div class="rectangle-2" ></div>
<img class="sport" src="img/sport-1.png" /></div>
</body>
</html>
```

CSS:
```
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-Bold", "weight": "700", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-Bold";
  src: local("Inter-Bold");
}
/* @FONTWARNING[{"type": "restricted", "family": "Inter-BoldItalic", "weight": "700", "style": "italic", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-BoldItalic";
  src: local("Inter-BoldItalic");
}

style.css

.iphone-pro-max {
  background-color: #2c0943;
  width: 100%;
  min-width: 592px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .logo {
  position: absolute;
  top: 18px;
  left: 7px;
  width: 578px;
  height: 87px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.iphone-pro-max .BG {
  position: absolute;
  top: 113px;
  left: 0;
  width: 592px;
  height: 843px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 189px;
  left: 123px;
  width: 362px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #f2e5e5;
  font-size: 32px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 314px;
  left: 221px;
  width: 171px;
  height: 50px;
  background-color: #d9d9d9;
}

.iphone-pro-max .LOGIN {
  position: absolute;
  top: 319px;
  left: 216px;
  width: 176px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #220431;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 435px;
  left: 23px;
  width: 200px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 541px;
  left: 37px;
  width: 259px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .img {
  position: absolute;
  top: 427px;
  left: 216px;
  width: 326px;
  height: 51px;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 541px;
  left: 287px;
  width: 255px;
  height: 50px;
  background-color: #d9d9d9;
}

.iphone-pro-max .sport {
  position: absolute;
  top: 692px;
  left: 55px;
  width: 497px;
  height: 213px;
  aspect-ratio: 2.33;
  object-fit: cover;
}
```

FRAME 2
HTML:
```
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<meta charset="utf-8" />
<link rel="stylesheet" href="globals.css">
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="frame" ><img class="bg" src="img/bg2-1.png" />
<p class="text-wrapper" >HERE ARE THE LIST OF EVENTS TO WITNESS</p>
<img class="star" src="img/star-8.svg" />
<img class="polygon" src="img/polygon-1.svg" />
<div class="div" >KARATE</div>
<img class="img" src="img/star-7.svg" />
<div class="text-wrapper-2" >BASKETBALL</div>
<img class="star-2" src="img/star-6.svg" />
<div class="text-wrapper-3" >BADMINTON</div>
<img class="star-3" src="img/star-5.svg" />
<div class="text-wrapper-4" >KHO - KHO</div>
<img class="star-4" src="img/star-4.svg" />
<div class="text-wrapper-5" >THROW BALL</div>
<img class="star-5" src="img/star-3.svg" />
<div class="text-wrapper-6" >CRICKET</div>
<img class="star-6" src="img/star-2.svg" />
<div class="text-wrapper-7" >FOOTBALL</div>
<img class="star-7" src="img/star-1.svg" />
<div class="text-wrapper-8" >RUNNING RACE</div></div>
</body>
</html>
```
CSS:
```
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-Bold", "weight": "700", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-Bold";
  src: local("Inter-Bold");
}

style.css

.frame {
  background-color: #2c0a43;
  width: 100%;
  min-width: 592px;
  min-height: 956px;
  position: relative;
}

.frame .bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 592px;
  height: 956px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 39px;
  left: 14px;
  width: 513px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star {
  top: 181px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .polygon {
  position: absolute;
  top: 54px;
  left: 492px;
  width: 69px;
  height: 55px;
}

.frame .div {
  position: absolute;
  top: 181px;
  left: 81px;
  width: 215px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .img {
  top: 268px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 268px;
  left: 60px;
  width: 350px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star-2 {
  top: 371px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 371px;
  left: 102px;
  width: 245px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star-3 {
  top: 466px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 466px;
  left: 81px;
  width: 252px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star-4 {
  top: 567px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 567px;
  left: 92px;
  width: 271px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star-5 {
  top: 674px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 671px;
  left: 60px;
  width: 267px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star-6 {
  top: 770px;
  height: 39px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 770px;
  left: 92px;
  width: 250px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star-7 {
  top: 875px;
  height: 36px;
  position: absolute;
  left: 61px;
  width: 40px;
}

.frame .text-wrapper-8 {
  position: absolute;
  top: 870px;
  left: 81px;
  width: 338px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```

FRAME 3
HTML:
```

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<meta charset="utf-8" />
<link rel="stylesheet" href="globals.css">
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="iphone-pro-max" ><img class="bg" src="img/bg2-2.png" />
<div class="text-wrapper" >REGISTRATION FORM</div>
<div class="div" >NAME:</div>
<div class="text-wrapper-2" >REF NO:</div>
<div class="text-wrapper-3" >CONTACT:</div>
<div class="text-wrapper-4" >EMAIL:</div>
<div class="text-wrapper-5" >EVENT INTERESTED:</div>
<div class="text-wrapper-6" >MALE</div>
<div class="ellipse" ></div>
<div class="text-wrapper-7" >FEMALE</div>
<div class="ellipse-2" ></div>
<div class="ellipse-3" ></div>
<div class="text-wrapper-8" >REGISTER</div>
<div class="ellipse-4" ></div>
<div class="ellipse-5" ></div>
<div class="rectangle" ></div>
<div class="rectangle-2" ></div>
<div class="rectangle-3" ></div>
<div class="rectangle-4" ></div>
<div class="rectangle-5" ></div></div>
</body>
</html>
```

CSS:
```
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-Bold", "weight": "700", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-Bold";
  src: local("Inter-Bold");
}

style.css

.iphone-pro-max {
  background-color: #2c0a43;
  overflow: hidden;
  width: 100%;
  min-width: 592px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 592px;
  height: 956px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 45px;
  left: 30px;
  width: 532px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 137px;
  left: -16px;
  width: 228px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 230px;
  left: -9px;
  width: 233px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 328px;
  left: 35px;
  width: 189px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 425px;
  left: -16px;
  width: 221px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 514px;
  left: 35px;
  width: 302px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 640px;
  left: 35px;
  width: 241px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .ellipse {
  position: absolute;
  top: 648px;
  left: 164px;
  width: 29px;
  height: 27px;
  background-color: #fdfd0a;
  border-radius: 14.5px / 13.5px;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 640px;
  left: 268px;
  width: 220px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .ellipse-2 {
  position: absolute;
  top: 648px;
  left: 432px;
  width: 28px;
  height: 27px;
  background-color: #c3fb0d;
  border-radius: 14px / 13.5px;
}

.iphone-pro-max .ellipse-3 {
  position: absolute;
  top: 757px;
  left: 149px;
  width: 297px;
  height: 98px;
  background-color: #d9d9d9;
  border-radius: 148.5px / 49px;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 786px;
  left: 175px;
  width: 246px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .ellipse-4 {
  position: absolute;
  top: 786px;
  left: 62px;
  width: 46px;
  height: 42px;
  background-color: #d9d9d9;
  border-radius: 23px / 21px;
}

.iphone-pro-max .ellipse-5 {
  position: absolute;
  top: 786px;
  left: 488px;
  width: 43px;
  height: 40px;
  background-color: #d9d9d9;
  border-radius: 21.5px / 20px;
}

.iphone-pro-max .rectangle {
  top: 137px;
  left: 186px;
  width: 362px;
  height: 51px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-2 {
  top: 230px;
  left: 199px;
  width: 349px;
  height: 53px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-3 {
  top: 317px;
  left: 243px;
  width: 305px;
  height: 54px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-4 {
  top: 419px;
  left: 191px;
  width: 357px;
  height: 52px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-5 {
  top: 513px;
  left: 294px;
  width: 254px;
  height: 93px;
  position: absolute;
  background-color: #d9d9d9;
}
```

FRAME 4
HTML:
```
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<meta charset="utf-8" />
<link rel="stylesheet" href="globals.css">
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="iphone-pro-max" ><img class="logo" src="img/logo-2.png" />
<img class="BG" src="img/BG-1.png" />
<img class="SUCC" src="img/SUCC-1.png" />
<div class="text-wrapper" >REGISTRATION SUCCESSFUL</div>
<p class="THANK-YOU-SO-MUCH" >THANK YOU SO MUCH!<br/>MEET YOU ON THE VENUE!</p></div>
</body>
</html>
```

CSS:
```
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
/* @FONTWARNING[{"type": "restricted", "family": "Inter-Bold", "weight": "700", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Inter-Bold";
  src: local("Inter-Bold");
}

style.css

.iphone-pro-max {
  background-color: #2c0a43;
  overflow: hidden;
  width: 100%;
  min-width: 592px;
  min-height: 956px;
  position: relative;
}
.iphone-pro-max .logo {
  position: absolute;
  top: 7px;
  left: 4px;
  width: 587px;
  height: 88px;
  aspect-ratio: 6.65;
  object-fit: cover;
}
.iphone-pro-max .BG {
  position: absolute;
  top: 102px;
  left: 0;
  width: 592px;
  height: 956px;
  aspect-ratio: 1;
  object-fit: cover;
}
.iphone-pro-max .SUCC {
  position: absolute;
  top: 279px;
  left: 89px;
  width: 437px;
  height: 437px;
  aspect-ratio: 1;
  object-fit: cover;
}
.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 172px;
  left: 0;
  width: 603px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
.iphone-pro-max .THANK-YOU-SO-MUCH {
  position: absolute;
  top: 756px;
  left: 62px;
  width: 491px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```
## OUTPUT:
![alt text](<Screenshot 2026-05-30 210831.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
