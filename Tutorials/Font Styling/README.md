# Font Styling Tutorial

This tutorial demonstrates how to style fonts using CSS. We will cover how to set font families, sizes, variants, styles, and weights for different HTML elements.

## CSS File

The CSS file (`style.css`) contains the styles for the `h1` and `p` elements.

### Example CSS

```css
/* Styling for h1 elements */
h1 {
  font-family: arial, verdana, sans-serif;
  font-size: 100px;
  font-variant: small-caps;
  font-style: italic;
}

/* Styling for p elements */
p {
  font-family: Georgia, serif;
  font-weight: bold;
  line-height: 50px;
}
```

## HTML File

The HTML file (`index.html`) includes the structure of the document and links to the external CSS file.

### Example HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Font Styling</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hello World</h1>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus
      praesentium qui molestias at blanditiis sequi, maiores non perspiciatis
      quisquam, itaque fugiat? Deleniti maxime labore numquam, perspiciatis
      accusamus eaque repellat possimus.
    </p>
  </body>
</html>
```

By following this tutorial, you will learn how to apply different font styles to your HTML elements using CSS.
