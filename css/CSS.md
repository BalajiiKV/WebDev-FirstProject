---
title: CSS

---

# CSS
CSS - means Cascading Style Sheets
Used to style a HTML document
CSS - layout of page, spacing between elements, color of text
## Changing Color of text to Orange
Done by three ways -
    1. Inline styles - not recommended
    2. Internal stylesheet - not recommended
    3. External stylesheet - recommended/common/easy
```
# Inline Style
<h1 style="color: orange">CSS Crash Course</h1>
```
## CSS rule Syntax
It has selector and style-declaration block. Each declaration has a property and value.

## Element Selectors
```
# Internal style sheet

<head>
    h1{
        color: orange;
    }
</head>

# External style sheet

h1{
    color: orange;
}

in the html page add this in head section

<head>
    <link rel="stylesheet" href="styles.css">
</head>
```
## Class Selectors
```
#html file

<head>
    <h1 class="error">red</h1>
    <h2 class="success">green</h2>
</head>

# css file

.error{
    color: red;
}
.success{
    color: green;
}
```
## Identity selectors
Used only during - targetting particular thing.
```
<head>
    <h1 id="test">king</h1>
</head>

# CSS file

#test{
    color: maroon;
}
```
## Background color 
```
<div class="orange">ORANGE BACKGROUND</div>
<span class="yellow">YELLOW BACKGROUND</span>

#css file
.orange{
    background-color: orange;
}
.yellow{
    background-color: yellow;
}
```
## Hex and opacity
```
h2{
    color: rgba(0,0,0,0.5); 
    #gives black and last denotes opacity
    
    color: #000000
    #6-0s:black, 6-f's-white  
}
```
## Font style and Allignment
```
<h2 class="font-styles">SAMPLE styling</h2>

#css file
.font-styles{
    background-color: brown;
    text-align: center;
    letter-spacing: 4px;
    word-spacing: 20px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-style: italic;
    font-weight: bold;
    text-decoration: underline;
    font-size: 40px;
}
```
## Lists
```
ul{
    list-style-type: none;
    margin: 0;
    padding: 0;
}
```
## CSS Box Model
Every element is a box model - margins, border, padding, content.
```
<div class=box-model>CSS BOX MODEL</div>

#CSS

.box-model{
    margin: 20px;
    padding: 20px;
    border: 1px;
    height: 50px;
    width: 300px;
    border: 1px solid red;
}
```