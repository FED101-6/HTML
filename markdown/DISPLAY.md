- [Home](../README.md)    
# Display
The `display` property specifies if an element should be treated as a block element or an inline element.

```css
body {
  display: block;
  display: inline;
  display: inline-block;
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

You can set `visibility` to `hidden` to hide an element.  
```css
body {
  visibility: hidden;
}
```

Or set `visibility` to `none` to remove an element from the page.  
```css
body {
  display: none;
}
```
### Exercise
Create an HTML page with an inline list that can be used as a navigation menu.  
  
You can also try to add an element that changes its display value on hover.

