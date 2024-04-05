# svg-logos

## Overview

`svg-logos` is a lightweight npm package designed to simplify the process of adding SVG icons to your web projects. It provides a straightforward way to incorporate SVG icons into your HTML using classes, making it easy to manage and customize icons across your website or web application.

## Installation

You can install `svg-logos` via npm by running:

```bash
npm install svg-logos
```

## Usage

### 1. Adding SVG Icons

To use `svg-logos`, follow these steps:

1. Add the `svg-logos` script to your HTML file:

```html
<script src="node_modules/svg-logos/svg.js"></script>
```

2. Add a `<div>` element with a specific class name wherever you want to display an SVG icon:

```html
<div class="svg-instagram"></div>
<div class="svg-discord"></div>
<!-- Add more divs with different class names for different icons -->
```

3. Call the `addSvg()` function to insert the SVG icons into the corresponding `<div>` elements:

```html
<script>
    addSvg();
</script>
```

### 2. Customization

You can customize the SVG icons by modifying the SVG markup within the `addSvg()` function in the `svg.js` file.

```javascript
var svg = `<svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg"></svg>`;
```

You can adjust attributes like `width`, `height`, `viewBox`, `fill`, and other attributes to customize the appearance of the SVG icons.

## Example

Here's an example of how to use `svg-logos` in an HTML file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SVG Example</title>
</head>
<body>
    <div class="svg-instagram"></div>
    <div class="svg-discord"></div>
    <!-- Add more divs with different class names for different icons -->
    
    <script src="node_modules/svg-logos/svg.js"></script>
    <script>
        addSvg();
    </script>
</body>
</html>
```

## Contributing

Contributions to `svg-logos` are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the GitHub repository: [svg-logos GitHub Repository](https://github.com/Harshrb2424/svg-logos).

## License

This project is licensed under the ISC License. 

```
ISC License

Copyright (c)
Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.
THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

For inquiries or support, please contact Harsh RB via [https://harshrb2424.github.io/profile/](https://harshrb2424.github.io/profile/).

This license statement reflects the updated information regarding the license and provides a direct link to your contact page for support inquiries.

## Acknowledgments

- This package was inspired by the need for a simple solution to add SVG icons to web projects.
- Special thanks to all contributors who have helped improve this package.