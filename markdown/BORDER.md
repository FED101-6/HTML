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

