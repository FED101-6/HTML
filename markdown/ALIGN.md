- [Home](../README.md)
# Align
You can use some CSS properties to align elements or text.  
  
For example, we can align a div with a word in the center of another div using the `margin-inline` property.

```css
.container {
  width: 30%;
  border: 1px solid pink;
}

.centered {
  width: 30%;
  border: 1px dotted blue;
  margin-inline: auto;
  text-align: center;
}
```  
```html
<div class="container">
  <div class="centered">Centered Text!</div>
</div>
```  

Inline elements can be aligned using the `text-align` property. We can also use `line-height` and `vertical-align` to vertically align inline elements.  

```css
.container2 {
  width: 10%;
  border: solid green;
}

.me2 {
  line-height: 1.5;
  display: inline-block;
  vertical-align: middle;
}

.me3 {
  line-height: 200px;
  height: 200px;
  text-align: center;
}
```  
```html
<div class="container2">
  <p class="me2">I love CSS! I really think it is great.</p>
</div>
```   

### Exercise
Create an HTML page with a centered title and a centered paragraph.  
  - The title should be in a different color than the paragraph.  
  - The paragraph should be in a different font than the title.  
  - The title should be aligned to the left and the paragraph to the right.  
  - The title should be in a different font size than the paragraph.    