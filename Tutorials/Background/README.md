# Background Tutorial

This tutorial demonstrates how to set background properties in CSS, including background color and background image.

## Files

### style.css

This file contains the CSS rules for setting the background properties of the `body` element.

```css
/* Set the background color of the body to a light gray */
body {
  background-color: #999999;
  /* Set the background image of the body to bg1.png located in the image folder */
  background-image: url(image/bg1.png);
}
```

### index.html

This file contains the HTML structure of the document and links to the external CSS file.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Metadata about the document -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Background</title>
    <!-- Link to the external CSS file -->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Main content of the document -->
    <h1>Hello World</h1>
  </body>
</html>
```

## How to Use

1. Ensure that the `style.css` file is in the same directory as `index.html`.
2. Make sure the `bg1.png` image is located in the `image` folder within the same directory.
3. Open `index.html` in a web browser to see the background color and image applied to the body of the document.
