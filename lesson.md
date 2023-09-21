## Brief

### Lesson Overview

The learners will be learning how to create simple webpages using HTML. This lesson will explore the different HTML tags as well as attributes.

---

## Part 1 - Introduction

All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```.

The HTML document itself begins with ```<html>``` and ends with ```</html>```.

The visible part of the HTML document is between ```<body>``` and ```</body>```.

```html
<!-- index.html -->
<!DOCTYPE html>
<html>
    <head>
        <title>My first webpage</title>
    </head>
    <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
    </body>
</html>
```

Save the file as `index.html`.

### Viewing HTML code in web browsers
The Chrome developer's tool can be accessed by doing either of the following:

1. Right-click on the screen and choose "Inspect"
2. Pressing F12 or Ctrl+Shift+I in the keyboard

### HTML tags
Demonstration to the learners the following HTML elements:
```
<h1>...<h6>
<p>
<img>
<ul><li>
<a>
```
Code:
```html
<!-- index.html -->
<h3>John Doe</h3>
<img class="avatar" src="https://m.media-amazon.com/images/I/71qokUI2ypL._AC_SX679_.jpg" height="200px" width="200px"/>
<p>My name is John. I am a software developer. I am proficient in:</p>
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>React</li>
</ul>
<p>Check out my full profile at <a href="https://w3schools.com">W3Schools!</a></p>
```
### HTML Attributes
All HTML elements can have attributes. They provide additional information about elements.

Attributes are always specified in the start tag and usually come in name/value pairs like: name="value".

Here are some of the commonly used attributes:
1. href - used in anchor tags (```<a>```), specifies the URL of the page the link goes to.
2. src - when used in image tags, it specifies the path to the image to be displayed.
3. alt - when used in image tags, it specifies an alternate text for an image, if the image for some reason cannot be displayed.
4. style - used to add inline style to an element, such as color, font, size, and more.
5. id - denotes the id of the element
6. class - denotes a class for a group of elements

---

## Part 2 - HTML Tables

HTML tables allow web developers to arrange data into rows and columns.

```html
<!-- index.html -->
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

The ```<table>``` tag denotes that there is a table
The ```<tr>``` tag denotes a table row
The ```<th>``` tag denotes that it is a header for a column
The ```<td>``` tag denotes a single cell in the table

HTML tables can have cells that span over multiple rows and/or columns by using the rowspan and colspan attributes. The values of the attributes represent the number of rows/columns to span.

---

## Part 3 - HTML Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing.

```html
<!-- index.html -->
<h3>Sample Form</h3>
<form>
    <label for="fname">First Name:</label>
    <input type="text" name="fname" placeholder="Enter Name"/>
    <br/>
    <label for="age">Age:</label>
    <input type="number" name="age" placeholder="Enter Age"/>
    <br/>
    <textarea>Enter Comment</textarea>
    <br/>
    <input type="submit">
</form>
```

The HTML ```<form>``` element is used to create an HTML form for user input:`
The HTML ```<input>``` element is the most used form element.

An ```<input>``` element can be displayed in many ways, depending on the type attribute.

Here are some examples:

```<input type="text">``` - Displays a single-line text input field
```<input type="number">``` - Displays a single-line number input field
```<input type="radio">``` - Displays a radio button (for selecting one of many choices)
```<input type="checkbox">``` - Displays a checkbox (for selecting zero or more of many choices)
```<input type="submit">``` - Displays a submit button (for submitting the form)
```<input type="button">``` - Displays a clickable button

The ```<label>``` tag defines a label for many form elements.
