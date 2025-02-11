# CSS Positioning Tutorials

This folder contains tutorials demonstrating different ways to apply CSS to HTML elements. The examples include Inline CSS, External CSS, and Embedded CSS.

## Inline CSS

Inline CSS is used to apply a unique style to a single HTML element. To use inline styles, add the `style` attribute directly to the HTML element.

Example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inline CSS</title>
  </head>
  <body>
    <h1 style="text-align: center; font-size: 60px; font-family: arial">
      Hello World
    </h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
  </body>
</html>
```

## External CSS

External CSS is used to apply styles to multiple HTML elements from an external file. To use external styles, link the CSS file in the `<head>` section of the HTML document.

Example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>External CSS</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hello World</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
  </body>
</html>
```

The `style.css` file:

```css
/* This CSS rule styles the h1 element with red color, 50px font size, centered text alignment, and Arial font family */
h1 {
  color: red;
  font-size: 50px;
  text-align: center;
  font-family: arial;
}
```

## Embedded CSS

Embedded CSS is used to apply styles within the `<style>` tag in the `<head>` section of the HTML document. This method is useful for applying styles to a single document.

Example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Embed CSS</title>
    <style>
      body {
        font-family: arial;
      }
      h1 {
        color: lightblue;
      }
      p {
        line-height: 1.6em;
        color: grey;
      }
    </style>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
  </body>
</html>
```
