# Pseudo Class Tutorial

This tutorial demonstrates the use of various CSS pseudo-classes to style HTML elements. Pseudo-classes are keywords added to selectors that specify a special state of the selected elements.

## CSS (style.css)

The `style.css` file contains styles for different pseudo-classes applied to links and list items.

```css
/* Style for unvisited links with class 'hello' */
.hello:link {
  color: red;
}

/* Style for hovered links with class 'hello' */
.hello:hover {
  font-family: arial;
  font-size: 20px;
  color: brown;
}

/* Style for active links with class 'hello' */
.hello:active {
  font-style: italic;
  color: green;
}

/* Style for visited links with class 'hello' */
.hello:visited {
  color: blue;
}

/* Style for the first child list item link */
li:first-child a {
  color: green;
}

/* Style for the last child list item link */
li:last-child a {
  color: red;
}

/* Style for the fifth child list item link */
li:nth-child(5) a {
  color: orange;
}

/* Style for every second child list item link */
li:nth-child(2n) a {
  color: black;
}

/* Style for even child list item links */
li:nth-child(even) a {
  color: yellowgreen;
}

/* Style for hovered even child list item links */
li:nth-child(even) a:hover {
  color: yellow;
}

/* Style for the first paragraph */
p:first-of-type {
  color: green;
}

/* Style for the last paragraph */
p:last-of-type {
  color: grey;
```

## HTML (index.html)

The `index.html` file contains the structure of the webpage, including links and paragraphs to demonstrate the pseudo-classes.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Pseudo Class</title>

    <!-- Link to the external CSS stylesheet -->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Heading with a link that uses the 'hello' class -->
    <h1><a href="#" class="hello">Hello World</a></h1>

    <!-- Unordered list with multiple list items and links -->
    <ul>
      <li><a href="#">Link 1</a></li>
      <li><a href="#">Link 2</a></li>
      <li><a href="#">Link 3</a></li>
      <li><a href="#">Link 4</a></li>
      <li><a href="#">Link 5</a></li>
      <li><a href="#">Link 6</a></li>
      <li><a href="#">Link 7</a></li>
      <li><a href="#">Link 8</a></li>
      <li><a href="#">Link 9</a></li>
      <li><a href="#">Link 10</a></li>
      <li><a href="#">Link 11</a></li>
    </ul>

    <!-- Paragraphs to demonstrate first-of-type and last-of-type pseudo-classes -->
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio laborum
      facilis officia provident fugit placeat illo id reprehenderit libero
      impedit culpa fuga tenetur repellat quis laudantium enim, sint eligendi.
      Corrupti?
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum similique
      error placeat facere obcaecati officiis esse nam porro harum cumque.
      Soluta provident temporibus molestiae qui repudiandae nobis praesentium ex
      sapiente.
    </p>
  </body>
</html>
```

### Explanation

- **`:link`**: Targets unvisited links. In this example, links with the class `hello` are styled with red color.
- **`:hover`**: Targets elements when the user designates (hovers over) them. Here, hovered links with the class `hello` change their font to Arial, size to 20px, and color to brown.
- **`:active`**: Targets elements that are being activated (e.g., clicked). Active links with the class `hello` are styled with italic font and green color.
- **`:visited`**: Targets visited links. Visited links with the class `hello` are styled with blue color.
- **`:first-child`**: Targets the first child element of its parent. The first list item link is styled with green color.
- **`:last-child`**: Targets the last child element of its parent. The last list item link is styled with red color.
- **`:nth-child(n)`**: Targets the nth child element of its parent. For example, the fifth list item link is styled with orange color, and every second list item link is styled with black color.
- **`:nth-child(even)`**: Targets even child elements. Even list item links are styled with yellowgreen color, and when hovered, they change to yellow.
- **`:first-of-type`**: Targets the first element of its type among siblings. The first paragraph is styled with green color.
- **`:last-of-type`**: Targets the last element of its type among siblings. The last paragraph is styled with grey color.
