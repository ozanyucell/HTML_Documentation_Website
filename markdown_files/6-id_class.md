# HTML class Attribute
* The HTML class attribute is used to specify a class for an HTML element. Multiple HTML elements can share the same class.
* The class attribute is often used to point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.

```
<!DOCTYPE html>
<html>
<head>
<style>
.student {
  background-color: orange;
  color: white;
  border: 2px;
  margin: 15px;
  padding: 15px;
}
</style>
</head>
<body>

<div class="student">
  <h2>Ceren</h2>
  <p>Ceren is student of Dietitian and Nutrition.</p>
</div>

<div class="student">
  <h2>Ozan</h2>
  <p>Ozan is student of Computer Engineering.</p>
</div>

<div class="city">
  <h2>Agata</h2>
  <p>Agata is student of Medicine.</p>
</div>

</body>
</html> 
```
  
# HTML id Attribute
* The HTML id attribute is used to specify a unique id for an HTML element. The value of the id attribute must be unique within the HTML document. You cannot have more than one element with the same id in an HTML document.
* The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.
```
<!DOCTYPE html>
<html>

<head>
<style>
#Header {
  background-color: blue;
  color: gray;
  padding: 20px;
  text-align: center;
}
</style>
</head>

<body>
<h1 id="Header">My Header</h1>
</body>

</html> 
```
#
* See you on the next document!