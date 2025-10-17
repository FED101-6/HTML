# Introduction to HTML

HTML is used to organize information and display it as a web page. It is the markup language of the web!  
  
The general format of an HTML document is as follows:  
  
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```  

## Lists
We discussed `<ul>` unordered lists, and `<ol>` ordered lists which can be used to stylize lists either with bullets or numbers.  
  
```html
<h2>Fruit</h2>
<ul>
  <li>apples</li>
  <li>oranges</li>
  <li>bananas</li>
</ul>

<h2>My Favorite Colors</h2>
<ol>
  <li>blue</li>
  <li>green</li>
  <li>red</li>
</ol>
```  


We also talked about `<dl>` definition lists which can be used to stylize lists with a term and a definition.  

```html
<dl>
  <dt>HTML</dt>
  <dd>Hyper Text Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
  <dt>JS</dt>
  <dd>JavaScript</dd>
</dl>
```  

## Tables
And of course, we discussed `<table>` tables, which can be used to stylize tables.  

```html
<table>
  <thead>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$80</td>
    </tr>
  </tbody>
</table>
```

## Div and Span

`<div>` and `<span>` are container elements. They are basically boxes that can hold information or things. The main difference is that a `<div>` is a block element and a `<span>` is an inline element.  
  
Just like our block of code:
```html
<div>
  <h1>My First Heading</h1>
  <p>My first paragraph.</p>
</div>
```  
or inline code: `<span>My first paragraph.</span>`.  
  
### Div & Span exercise 01. 
  
Create and HTML file with the following:
  1. A div with an image and a paragraph.
  - The image should have a size of 50px by 50px.
  - The image should also have alt text.
  2. A span with a paragraph and a link.

## Forms

Forms are used to collect information from users. They are used to create login pages, contact forms, and more.  

```html
<form method="post" action="/submit">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <input type="submit" value="Submit" />
</form>
```  

### Form Exercise 01

Create an HMTL page with a form that has 2 checkboxes and a submit button.  
  
It should be something like this:  
```html
<H1>Things I like</H1>
<form method="post" action="/submit">
  <input type="checkbox" id="item1" name="jeans" />
  <label for="name">jeans</label>
  <input type="checkbox" id="item2" name="t-shirts" />
  <label for="name">t-shirts</label>
  <input type="submit" value="Submit" />
</form>
```

## iFrame
An iFrame is an element that is useful for embeding another page within a page.  
```html
<iframe src="https://www.google.com"></iframe>
```  

## Video & Audio
Video and audio elements are used to embed videos and audio into a page.  
```html
<video>
   <src="https://www.youtube.com/watch?v=uh4gG7LbDPQ">
</video>
<audio>
  <source src="myaudiofile.mp3" type="audio/mpeg">
</audio>
```  

### Exercise 02: iFrames, Audio & Video
Create an HTML page with an iFrame, a video, and an audio element.  

## Colors

Colors can be set with hexadecimal values, RGB values, or color names.  

```css
body {
  color: #000000;
  color: rgb(0, 0, 0);
  color: black;
}
```

WHen you set the `color` style it is for text, if you want to set the color of the background, you can use `background-color`.  

```css
body {
  background-color: #FFFF00;
  background-color: rgb(255, 255, 0);
  background-color: yellow;
}
```  

## Background Images

Background images can be set with the `background-image` property.  

```css
body {
  background-image: url("your-image.jpg");
}
```
There are some properties you can set to have background images repeat on x or y axes, or not at all.  

```css
body {
  background-image: url("your-image.jpg");
  background-repeat: repeat-x;
}
```  

```css
body {
  background-image: url("your-image.jpg");
  background-repeat: no-repeat;
}
```
```css
body {
  background-image: url("your-image.jpg");
  background-repeat: repeat;
}
``` 

### Exercise 03: Background Images
Create an HTML page with a blue title and a background image that repeats itself on the y axis.

## Border

Borders can be set with the `border` property.  

```css
body {
  border: 1px solid black;
}
```  
We can also set each side of the border individually.  

```css
body {
  border-top: 1px solid black;
  border-right: 1px solid black;
  border-bottom: 1px solid black;
  border-left: 1px solid black;
}
```  
Or all in one line
```css
body {
  border: 1px 1px 1px 1px solid black;
}
```  

Likewise with `border-radius`:
```css
body {
  border-radius: 10px;
}
```  
Or individually:
```css
body {
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  border-bottom-left-radius: 10px;
}
```  
Or all in one line:
```css
body {
  border-radius: 10px 10px 10px 10px;
}
```  
### Exercise 04
Create a page with some borders:
  1. a div with a red 4px solid border
  2. a paragraph with a black dotted border with the following properties:  
    a. 2px width on the top  
    b. 4px on the right  
    c. 6px on the bottom  
    d. 15px on the left  
    
## Display Element

The `display` property is used to set the display of an element.  

```css
body {
  display: block;
}
```  

```html
<style>
  .my-div-display {
    border: 10px solid red;
    display: inline;
  }
</style>



<p>This is a paragraph <div class="my-div-display">with some text</div> in it.</p>
```

## Text
You can use the `text-decoration` property:
```css
p {
  text-decoration: line-through;
  text-decoration: overline;
  text-decoration: underline;
}
```  

The `text-transform` property is used to capitalize text. 
```css
p {
  text-transform: uppercase;
  text-transform: lowercase;
  text-transform: capitalize;
}
```  
Use `text-align` to align text.  
```css
p {
  text-align: left;
  text-align: right;
  text-align: center;
  text-align: justify;
}
```  
Use `direction` to set the direction of the text, from left-to-right or right-to-left.  
```css
p {
  direction: ltr;
  direction: rtl;
}
```  

Use `text-indent` to indent the first line of a paragraph.  
```css
p {
  text-indent: 50px;
}
```  
Use `letter-spacing` to set the space between letters.  
```css
p {
  letter-spacing: 3px;
}
```  
Use `line-height` to set the space between lines.  
```css
p {
  line-height: 1.5;
}
```  

`white-space` is used to set the white space of an element.  
```css
p {
  white-space: nowrap;
  white-space: pre;
  white-space: pre-line;
  white-space: pre-wrap;
}
```  

`word-spacing` is used to set the space between words.  
```css
p {
  word-spacing: 3px;
}
``` 
`text-shadow` is used to set the shadow of the text.  
```css
p {
  text-shadow: 2px 2px 5px red;
}
```  

### Exercise
Create a page with a:
  - blue title with an underline, capitalized and an orange shadow. Align the text to the center with a 3px letter spacing.
  - black paragraph with -3px line spacing between words, and 75px indentation.

## Height and Width

## Fonts

## Links

## Tables

## Lists

## Postition