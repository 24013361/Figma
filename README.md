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
  LAYER 1:
  HTML:
  ```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-14-plus-1-1">
<img src="images/red-glow-1-2.png" class="red-glow-1-2" alt="red-glow-1" />
<div class="node-3" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-4"></div>
<div class="glass-effect-5"></div>
</div>
<img src="images/image-1-6.png" class="image-1-6" alt="image-1" />
<img src="images/rectangle-1-7.svg" class="rectangle-1-7" alt="rectangle-1" />
<p class="text-8"><span class="text-white">LOGIN</span></p>
<p class="text-9"><span class="text-black">Saveetha Engineering College</span></p>
<p class="text-10"><span class="text-black">Username:</span></p>
<p class="text-11"><span class="text-black">Password:</span></p>
<p class="text-12"><span class="text-black">Forget Password</span></p>
<p class="text-13"><span class="text-black">Create Account</span></p>
<div class="node-14">
<div class="fill-shadow-15"></div>
<div class="glass-effect-16"></div>
</div>
<div class="node-17">
<div class="fill-shadow-18"></div>
<div class="glass-effect-19"></div>
</div>
</div>

</body>
</html>

```
   CSS:
   ```
/* Add font files for SF Pro */
@font-face {
  font-family: 'SF Pro';
  src: url('fonts/sf-pro.woff2') format('woff2'),
       url('fonts/sf-pro.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-sf-pro: 'SF Pro', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-white {
  color: var(--text-white);
}

.text-black {
  color: var(--text-black);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.red-glow-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 360px;
  width: 100%;
  height: auto;
}

.fill-shadow-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  width: 36.915887850467286%;
}

.image-1-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 104px;
  width: 100%;
  height: auto;
}

.rectangle-1-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 30px;
  fill: rgba(0, 157, 255, 1);
  border: none;
  outline: none;
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.fill-shadow-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.fill-shadow-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.iphone-14-plus-1-1 {
@media (max-width: 1440px) {
  .iphone-14-plus-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-14-plus-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(188, 251, 0, 1);
}

```
LAYER 2:
  HTML:
  ```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-14-plus-2-1">
<img src="images/red-glow-1-2.png" class="red-glow-1-2" alt="red-glow-1" />
<div class="node-3" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-4"></div>
<div class="glass-effect-5"></div>
</div>
<div class="node-6" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-7"></div>
<div class="glass-effect-8"></div>
</div>
<p class="text-9"><span class="text-black">Tech Treasure Hunt</span></p>
<div class="node-10" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-11"></div>
<div class="glass-effect-12"></div>
</div>
<p class="text-13"><span class="text-black">Tech Treasure Hunt</span></p>
<div class="node-14" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-15"></div>
<div class="glass-effect-16"></div>
</div>
<p class="text-17"><span class="text-black">Tech Treasure Hunt</span></p>
<img src="images/image-1-18.png" class="image-1-18" alt="image-1" />
<p class="text-19"><span class="text-black">Saveetha Engineering College</span></p>
<p class="text-20"><span class="text-rgb-43-0-255">EVENTS</span></p>
</div>

</body>
</html>

```
   CSS:
   ```
/* Add font files for SF Pro */
@font-face {
  font-family: 'SF Pro';
  src: url('fonts/sf-pro.woff2') format('woff2'),
       url('fonts/sf-pro.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Racing Sans One */
@font-face {
  font-family: 'Racing Sans One';
  src: url('fonts/racing-sans-one.woff2') format('woff2'),
       url('fonts/racing-sans-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-sf-pro: 'SF Pro', sans-serif;
  --font-family-racing-sans-one: 'Racing Sans One', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-43-0-255: rgba(43, 0, 255, 1);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-43-0-255 {
  color: var(--text-rgb-43-0-255);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.red-glow-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 360px;
  width: 100%;
  height: auto;
}

.fill-shadow-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  width: 36.915887850467286%;
}

.fill-shadow-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 700;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.fill-shadow-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 700;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.fill-shadow-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 700;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.image-1-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 104px;
  width: 100%;
  height: auto;
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-racing-sans-one);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-43-0-255);
}

.iphone-14-plus-2-1 {
@media (max-width: 1440px) {
  .iphone-14-plus-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-14-plus-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(191, 255, 0, 1);
}

```
LAYER 3:
  HTML:
  ```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-14-plus-3-1">
<img src="images/red-glow-1-2.png" class="red-glow-1-2" alt="red-glow-1" />
<div class="node-3" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-4"></div>
<div class="glass-effect-5"></div>
</div>
<img src="images/image-1-6.png" class="image-1-6" alt="image-1" />
<p class="text-7"><span class="text-black">Saveetha Engineering College</span></p>
<p class="text-8"><span class="text-rgb-43-0-255">Tech Tresure  Hunt</span></p>
<div class="node-9" style="box-shadow: 0px 4px 5px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-10"></div>
<div class="glass-effect-11"></div>
</div>
<p class="text-12"><span class="text-black">A Tech Treasure Hunt is an exciting event where participants solve technical clues related to programming, technology, or engineering concepts to find the next location or hint. Each solved challenge leads them closer to the final treasure. It encourages teamwork, logical thinking, and technical knowledge while making learning fun and interactive.</span></p>
<img src="images/rectangle-1-13.svg" class="rectangle-1-13" alt="rectangle-1" />
<p class="text-14"><span class="text-white">REGISTER</span></p>
<p class="text-15"></p>
</div>

</body>
</html>

```
   CSS:
   ```
/* Add font files for SF Pro */
@font-face {
  font-family: 'SF Pro';
  src: url('fonts/sf-pro.woff2') format('woff2'),
       url('fonts/sf-pro.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Racing Sans One */
@font-face {
  font-family: 'Racing Sans One';
  src: url('fonts/racing-sans-one.woff2') format('woff2'),
       url('fonts/racing-sans-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-sf-pro: 'SF Pro', sans-serif;
  --font-family-racing-sans-one: 'Racing Sans One', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-43-0-255: rgba(43, 0, 255, 1);
  --text-white: rgba(255, 255, 255, 1);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-43-0-255 {
  color: var(--text-rgb-43-0-255);
}

.text-white {
  color: var(--text-white);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.red-glow-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 360px;
  width: 100%;
  height: auto;
}

.fill-shadow-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  width: 36.915887850467286%;
}

.image-1-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 104px;
  width: 100%;
  height: auto;
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-racing-sans-one);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-43-0-255);
}

.fill-shadow-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 30px;
  fill: rgba(0, 157, 255, 1);
  border: none;
  outline: none;
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
}

.iphone-14-plus-3-1 {
@media (max-width: 1440px) {
  .iphone-14-plus-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-14-plus-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(191, 255, 0, 1);
}

```
LAYER 4:
  HTML:
  ```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-14-plus-4-1">
<img src="images/red-glow-1-2.png" class="red-glow-1-2" alt="red-glow-1" />
<div class="node-3" style="box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)">
<div class="fill-shadow-4"></div>
<div class="glass-effect-5"></div>
</div>
<img src="images/image-1-6.png" class="image-1-6" alt="image-1" />
<p class="text-7"><span class="text-black">Saveetha Engineering College</span></p>
<p class="text-8"><span class="text-rgb-217-0-255">THANKS FOR REGISTERING</span></p>
<img src="images/rectangle-2-9.svg" class="rectangle-2-9" alt="rectangle-2" />
<p class="text-10"><span class="text-white">LOGIN</span></p>
<p class="text-11"><span class="text-white">←HOME</span></p>
</div>

</body>
</html>

```
   CSS:
   ```
/* Add font files for SF Pro */
@font-face {
  font-family: 'SF Pro';
  src: url('fonts/sf-pro.woff2') format('woff2'),
       url('fonts/sf-pro.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Racing Sans One */
@font-face {
  font-family: 'Racing Sans One';
  src: url('fonts/racing-sans-one.woff2') format('woff2'),
       url('fonts/racing-sans-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-sf-pro: 'SF Pro', sans-serif;
  --font-family-racing-sans-one: 'Racing Sans One', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-217-0-255: rgba(217, 0, 255, 1);
  --text-white: rgba(255, 255, 255, 1);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-217-0-255 {
  color: var(--text-rgb-217-0-255);
}

.text-white {
  color: var(--text-white);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.red-glow-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 360px;
  width: 100%;
  height: auto;
}

.fill-shadow-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(38, 38, 38, 1);
  border-radius: 34px;
}

.glass-effect-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 34px;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  width: 36.915887850467286%;
}

.image-1-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 104px;
  width: 100%;
  height: auto;
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-racing-sans-one);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-217-0-255);
}

.rectangle-2-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 30px;
  fill: rgba(0, 157, 255, 1);
  border: none;
  outline: none;
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-14-plus-4-1 {
@media (max-width: 1440px) {
  .iphone-14-plus-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-14-plus-4-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(191, 255, 0, 1);
}

```
  
  
## OUTPUT:






## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
