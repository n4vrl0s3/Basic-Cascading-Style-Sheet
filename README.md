# Basic Cascading Style Sheets (CSS)

This repository contains the source code for a basic CSS project demonstrating the fundamental concepts and usage of CSS. This project is designed to help beginners understand how to style web pages using CSS.

<hr><br>

## Purpose of This Repository

To provide a foundational understanding of CSS and demonstrate how to style web pages with various CSS properties and techniques.

<hr><br>

## Demonstration

Below is a demonstration of a simple CSS styling:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Basic CSS Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
      }
      header {
        background-color: #333;
        color: #fff;
        padding: 1rem;
        text-align: center;
      }
      nav ul {
        list-style: none;
        padding: 0;
      }
      nav ul li {
        display: inline;
        margin-right: 1rem;
      }
      nav ul li a {
        color: #333;
        text-decoration: none;
      }
      main {
        padding: 1rem;
      }
      footer {
        background-color: #333;
        color: #fff;
        text-align: center;
        padding: 1rem;
        position: fixed;
        width: 100%;
        bottom: 0;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Welcome to My Styled Website</h1>
    </header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <main>
      <section id="home">
        <h2>Home</h2>
        <p>This is the home section.</p>
      </section>
      <section id="about">
        <h2>About</h2>
        <p>This is the about section.</p>
      </section>
      <section id="contact">
        <h2>Contact</h2>
        <p>This is the contact section.</p>
      </section>
    </main>
    <footer>
      <p>&copy; 2023 My Styled Website</p>
    </footer>
  </body>
</html>
```

<hr><br>

## Features

- Basic CSS styling
- Header, navigation, main content, and footer sections
- Simple navigation links
- Responsive design with meta viewport tag

<hr><br>

## Technologies Used

- HTML5
- CSS3

<hr><br>

## Project Setup

1. **Clone this Repository**

```bash
git clone https://github.com/n4vrl0s3/Basic-Cascading-Style-Sheet.git
```

2. **Open the project in your preferred code editor**

<hr><br>

## Steps to Run

1. **Open the project in your preferred code editor**
2. **Open the `index.html` file in a web browser to view the styled web page**

<hr><br>

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<hr><br>

<div align="center">
  <a href="https://www.x.com/n4vrl0s3/">
    <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=100:49108B,20:F3F8FF&section=footer&reversal=false&textBg=false&fontAlignY=50&descAlign=48&descAlignY=59"/>
  </a>

</div>
