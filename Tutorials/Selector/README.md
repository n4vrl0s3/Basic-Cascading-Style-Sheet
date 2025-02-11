# CSS Selectors Tutorial

This tutorial demonstrates how to use various CSS selectors to style HTML elements.

## CSS File: `style.css`

```css
body {
  font-family: arial;
}

h1,
h2 {
  color: slategray;
}

ul li a,
ol li a {
  color: grey;
}

#p1 {
  color: saddlebrown;
}

.p2 {
  color: indianred;
}

.boldtext {
  font-weight: bold;
}

.p2.boldtext {
  font-size: large;
}
```

### Explanation of CSS Selectors

- **Type selectors**: These selectors target elements by their tag name. For example, `body`, `h1`, and `h2` are type selectors that apply styles to all `<body>`, `<h1>`, and `<h2>` elements respectively.
- **Descendant selectors**: These selectors target elements that are descendants of a specified element. For example, `ul li a` targets all `<a>` elements that are inside `<li>` elements, which are inside `<ul>` elements.
- **ID selectors**: These selectors target elements by their unique ID. For example, `#p1` targets the element with the ID `p1`.
- **Class selectors**: These selectors target elements by their class attribute. For example, `.p2` targets all elements with the class `p2`, and `.boldtext` targets all elements with the class `boldtext`.
- **Compound class selectors**: These selectors target elements that have multiple classes. For example, `.p2.boldtext` targets elements that have both `p2` and `boldtext` classes.

## HTML File: `index.html`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Selector</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hello World</h1>
    <ul>
      <li><a href="#">Link 1</a></li>
      <li><a href="#">Link 2</a></li>
    </ul>
    <ol>
      <li><a href="#">Link 3</a></li>
      <li><a href="#">Link 4</a></li>
    </ol>
    <a href="#">Guan</a>
    <h2>Article</h2>
    <p id="p1">Lorem ipsum dolor sit amet...</p>
    <p class="p2 boldtext">Lorem ipsum dolor sit amet...</p>
  </body>
</html>
```

This tutorial covers the following CSS selectors:

- Type selectors (e.g., `body`, `h1`, `h2`)
- Descendant selectors (e.g., `ul li a`, `ol li a`)
- ID selectors (e.g., `#p1`)
- Class selectors (e.g., `.p2`, `.boldtext`)
- Compound class selectors (e.g., `.p2.boldtext`)
