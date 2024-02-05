
An HTML document is composed of several main parts that structure and organize its content.

### HTML

The `<html>` tag is the root element of an HTML document. It encapsulates all the content on the page.

```html
<!DOCTYPE html>
<html lang="en">
  <!-- Content goes here -->
</html>
```

#### Head

The `<head>` tag contains meta-information about the HTML document, such as its title, character encoding, and links to external resources like stylesheets and scripts.

```html
<head>
  <title>Document Title</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles.css">
  <script src="script.js"></script>
</head>
```

#### Body

The `<body>` tag contains the main content of the HTML document, including text, images, links, and other elements visible to the user.

```html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is the main content of the webpage.</p>
  <img src="image.jpg" alt="Description">
  <a href="page2.html">Go to Page 2</a>
</body>
```

##### Header, Main, Footer

Within the `<body>` tag, additional structural elements like `<header>`, `<main>`, and `<footer>` can be used to further organize and delineate different sections of the webpage.

```html
<body>
  <header>
    <h1>Website Header</h1>
    <!-- Navigation menu, logo, etc. -->
  </header>

  <main>
    <h2>Main Content Area</h2>
    <!-- Main content of the webpage -->
  </main>

  <footer>
    <p>&copy; 2024 My Website. All rights reserved.</p>
    <!-- Footer content, links, etc. -->
  </footer>
</body>
```

Understanding the main parts of an HTML document is crucial for creating well-structured and semantically meaningful web pages.

---

