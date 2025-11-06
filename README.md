# Ex09 Event Registration Web Application
## Date: 4-11-2025
# NAME: JAGAN JP
# REG.NO: 212224230099
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
# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="home-page-1">
<img src="images/node-2.png" class="node-2" alt="idc2cismwr_1762004317717-1" />
<img src="images/home-page-1-3.png" class="home-page-1-3" alt="home-page-1" />
<p class="text-4"><span class="text-white">World Of Imagination</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for Ribeye Marrow */
@font-face {
  font-family: 'Ribeye Marrow';
  src: url('fonts/ribeye-marrow.woff2') format('woff2'),
       url('fonts/ribeye-marrow.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-ribeye-marrow: 'Ribeye Marrow', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
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

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.home-page-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-ribeye-marrow);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.home-page-1 {
@media (max-width: 1440px) {
  .home-page-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .home-page-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(140, 71, 206, 1);
}
```

# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="events-page-1">
<img src="images/events-1-1-2.png" class="events-1-1-2" alt="events-1-1" />
<p class="text-3"><span class="text-white">E-SPORTS 
EVENTS</span></p>
<p class="text-4"><span class="text-white">FREE FIRE

PUBG

CALL OF DUTY

CLASH OF CLANS

LEAGUE OF LEGENDS

DOTA

WORLD OF WARCRAFT</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for Ribeye Marrow */
@font-face {
  font-family: 'Ribeye Marrow';
  src: url('fonts/ribeye-marrow.woff2') format('woff2'),
       url('fonts/ribeye-marrow.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-ribeye-marrow: 'Ribeye Marrow', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
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

.events-1-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-ribeye-marrow);
  font-weight: normal;
  font-size: 135px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-ribeye-marrow);
  font-weight: normal;
  font-size: 96px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.events-page-1 {
@media (max-width: 1440px) {
  .events-page-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .events-page-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```

# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="event-registration-1">
<img src="images/events-2-1-2.png" class="events-2-1-2" alt="events-2-1" />
<p class="text-3"><span class="text-white">Event Registration
      Fill The Details</span></p>
<div class="rectangle-1-4"></div>
<div class="rectangle-2-5"></div>
<div class="rectangle-3-6"></div>
<div class="rectangle-4-7"></div>
<p class="text-8"><span class="text-black">Year</span></p>
<div class="rectangle-5-9"></div>
<p class="text-10"><span class="text-black">Phone Number</span></p>
<div class="rectangle-6-11"></div>
<p class="text-12"><span class="text-black">Name</span></p>
<p class="text-13"><span class="text-black">Register Number</span></p>
<p class="text-14"><span class="text-black">Department</span></p>
<p class="text-15"><span class="text-black">Email ID</span></p>
<div class="rectangle-7-16"></div>
<p class="text-17"><span class="text-white">REGISTER</span></p>
<div class="rectangle-8-18"></div>
<p class="text-19"><span class="text-black">Events To Register</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for Revalia */
@font-face {
  font-family: 'Revalia';
  src: url('fonts/revalia.woff2') format('woff2'),
       url('fonts/revalia.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-revalia: 'Revalia', sans-serif;
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

.events-2-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 96px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-1-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-2-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 247, 247, 1);
}

.rectangle-3-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-4-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 249, 249, 1);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-5-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-6-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-7-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-8-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 251, 251, 1);
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-revalia);
  font-weight: normal;
  font-size: 130px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.event-registration-1 {
@media (max-width: 1440px) {
  .event-registration-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .event-registration-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```

# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="contact-page-1">
<img src="images/node-2.png" class="node-2" alt="idc2cismwr_1762004317717-2" />
<img src="images/home-page-2-1-3.png" class="home-page-2-1-3" alt="home-page-2-1" />
<p class="text-4"><span class="text-white">        Contact Us:
      Email Address:
secesports@gmail.com

     Phone Number:
       9182736450
</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for Irish Grover */
@font-face {
  font-family: 'Irish Grover';
  src: url('fonts/irish-grover.woff2') format('woff2'),
       url('fonts/irish-grover.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-irish-grover: 'Irish Grover', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
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

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.home-page-2-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-irish-grover);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.contact-page-1 {
@media (max-width: 1440px) {
  .contact-page-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .contact-page-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(132, 85, 241, 1);
}
```
## OUTPUT:

<img width="1304" height="648" alt="Screenshot 2025-11-06 103218" src="https://github.com/user-attachments/assets/cc5e7bba-197e-4c69-b19d-45835866546d" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
