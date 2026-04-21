# Hello World HTML Project

## Overview

This is a minimal HTML project that demonstrates the basic structure of a web page. It displays a simple **"Hello World"** message in the browser.

## File Structure

```
.
└── index.html
```

## Code Explanation

* `<!DOCTYPE html>`: Declares the document type and version of HTML.
* `<html>`: Root element of the HTML document.
* `<head>`: Contains metadata and the title of the page.

  * `<title>`: Sets the browser tab title to "Hello World".
  * `<meta>`: Intended to define responsive behavior (though the syntax should be corrected—see note below).
* `<body>`: Contains the visible content of the webpage.

  * `<h1>`: Displays the main heading "Hello World".

## How to Run

1. Save the file as `index.html`.
2. Open it in any web browser (Chrome, Firefox, Edge, etc.).
3. You should see "Hello World" displayed on the page.

## Note

The `<meta>` tag currently has incorrect syntax. For proper responsive design, update it to:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## License

This project is open-source and free to use for learning purposes.
