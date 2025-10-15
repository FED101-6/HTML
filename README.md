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
