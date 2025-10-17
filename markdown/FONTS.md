## Fonts
You can use the `font-family` property to set the font of an element.  
```css
p {
  font-family: Arial, Helvetica, sans-serif;
}
```  
You can also use the `font-size` property to set the size of the font.  
```css
p {
  font-size: 16px;
}
```  
You can use the `font-weight` property to set the weight of the font.  
```css
p {
  font-weight: bold;
}
```
We can use custom fonts by using the `@font-face` rule. [Google Fonts](https://fonts.google.com/) is a great resource for finding custom fonts, such as:  
```css
@import url('https://fonts.googleapis.com/css2?family=Archivo+Black&family=Lobster+Two:ital,wght@0,400;0,700;1,400;1,700&display=swap');

/* or */

@font-face {
  font-family: 'Lobster';
  src: url('lobster.woff2') format('woff2'),
       url('lobster.woff') format('woff');
}
```  
or
```html
<head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Lobster+Two:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
</head>
```
To use a custom font, you can use the `font-family` property.  
```css
p {
  font-family: 'Lobster', cursive;
  font-family: 'Archivo Black', sans-serif;
}
```

### Fonts Exercise
Create an HTML page using customer fonts. For example, try to use a different font for a title using a header element and a paragraph element. The two fonts should be different yet somehow complement each other.  
