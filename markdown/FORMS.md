
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