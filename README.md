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