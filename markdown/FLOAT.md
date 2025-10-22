## Float
The css `float` property is used to position an element to the left or right of its container.  

example:  
```css
img {
  float: left;
}
```  
```html
<img src="your-image.jpg" alt="your-image">
```  
The `clear` property is used to specify what should happen with the elements after the floating element.  
```css
p {
  clear: left;
}
```  
```html
<p>Your paragraph here.</p>
```  
There is something called the "clearfix hack" which is used to clear the float.  
```css
.container::after {
  content: "";
  clear: both;
  display: table;
}
```  
```html
<div class="container">
  <img src="your-image.jpg" alt="your-image">
  <p>Your paragraph here.</p>
</div>
```  
### Exercise (Rolling Exercise CSS Part C)
Continuing from the previous rolling exercise:
Divide the page into two parts
  a. Left Part - 75% left-column
  b. Right Part - 25% right-column with background color #f1f1f1 and padding-left
