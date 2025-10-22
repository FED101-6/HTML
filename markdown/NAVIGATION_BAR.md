## Navigation Bar

You can create a navigation bar using a list and some CSS properties.  
  
```html
<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>
```  
```css
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #eee;
  color: black;
}
```  

### Exercise (Rolling Execise CSS Part D)
Continued from the previous rolling exercise
  1. Create a cool navigation bar with:
    - Arial font
    - padding: 10px
  2. Add the following features to the header selector:
    - padding: 30px
    - text-align: center
    - background: rgb(122, 89, 156)
  3. All the h2 tags with be with color: rgb(122, 89, 156)
  4. All the h5 tags will be with color: rgb(122, 165, 226)
  5. The h1 in the header tag will have font-size: 50px
