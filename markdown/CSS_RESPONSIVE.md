- [Home](../README.md)
# CSS Responsive
  - [MDN Responsive Web Design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design)

Use the viewport meta tag to make your page responsive.  
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```  
Use media queries to apply CSS based on the width of the viewport.  
```css
@media (max-width: 600px) {
  body {
    color: #3300ff;
    text-shadow: 2px 2px 5px #00ffbb;
    background-image: gradient(to right, #ff0033, #3300ff);
  }
}

@media (min-width: 600px) {
  body {
    color: #ff0033;
    text-shadow: 2px 2px 5px #00ffbb;
    background-image: gradient(to right, #3300ff, #ff0033);
  }
}

```  
