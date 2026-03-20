# Patch Instructions for Applying Bug Fixes to index.html

## Bug Fix 1: Correcting the Header Structure
### Change:
Replace the header in `index.html` from:
```html
<h1>Welcome</h1>
```
To:
```html
<h1>Welcome to Polytest</h1>
```

## Bug Fix 2: Fixing the Footer Links
### Change:
Update the footer links in `index.html` from:
```html
<a href="#">Home</a>
<a href="#">Contact</a>
```
To:
```html
<a href="/home">Home</a>
<a href="/contact">Contact Us</a>
```

## Bug Fix 3: Correcting Image Source Paths
### Change:
Change the image source in `index.html` from:
```html
<img src="images/logo.png" />
```
To:
```html
<img src="/assets/images/logo.png" />
```

## Bug Fix 4: Style Adjustments
### Change:
In the `style` section of `index.html`, modify the background color from:
```css
background-color: white;
```
To:
```css
background-color: #f0f0f0;
```

## Instructions
1. Open the `index.html` file in your code editor.
2. Follow the instructions for each bug fix listed above.
3. Save your changes and refresh your browser to see the updates.