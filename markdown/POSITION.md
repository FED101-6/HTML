- [Home](../README.md)
# Postition
The css `position` property is used to set the position of an element. There are 5 different values for the `position` property:  
```css
  position: static;
  position: relative;
  position: absolute;
  position: fixed;
  position: sticky;
```
`static`: This is the default value. Elements are rendered in the order they appear in the document.  
`relative`: The element is positioned relative to its normal position.  
`absolute`: The element is positioned relative to its first positioned ancestor.  
`fixed`: The element is positioned relative to the browser window.  
`sticky`: The element is positioned based on the user's scroll position. 

```html
<div style="position: static;">Static Position</div>
<div style="position: relative;">Relative Position</div>
<div style="position: absolute;">Absolute Position</div>
<div style="position: fixed;">Fixed Position</div>
<div style="position: sticky;">Sticky Position</div>
``` 

### Position Exercise
Create an HTML page with some divs. Try to be creative and show exemplary use cases for each of the 5 position values.
