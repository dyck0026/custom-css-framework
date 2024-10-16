# Facilis CSS Framework
Facilis is a lightweight and customizable CSS framework designed to provide a solid foundation for web projects. It offers a custom theme for standard HTML elements and utility classes for common styling needs.

## Installation
To use Facilis in your project, follow these steps:
1. Download the `facilis-framework.css` file in this repository.
2. Include the CSS file in your HTML:
`<link rel="stylesheet" href="path/to/facilis-framework.css">`

Alternatively, you can use a CDN link (if you have set one up):
`<link rel="stylesheet" href="https://raw.githubusercontent.com/dyck0026/facilis/main/dist/facilis-framework.css">`

## Usage
Facilis provides styled HTML elements and utility classes. Here's a comprehensive guide on how to use them:

## Typography
Facilis includes styles for headings (h1 to h6) and paragraph text. Simply use the standard HTML tags:
```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<p>This is a paragraph with <strong>bold</strong> and <em>italic</em> text.</p>
<a href="#">This is a link</a>
```
## Buttons
Facilis provides several button styles:
```
<button>Default Button</button>
<button class="btn-primary">Primary Button</button>
<button class="btn-secondary">Secondary Button</button>
<button class="btn-accent">Accent Button</button>
<button class="btn-outline">Outline Button</button>
```
## Forms
Form elements are styled by default. Use standard HTML form tags:
```
<form>
    <div>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
    </div>
    <div>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
    </div>
    <div>
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
    </div>
    <button type="submit">Submit</button>
</form>
```
## Lists
Both unordered and ordered lists are styled:
```
<h3>Unordered Lists</h3>
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

<h3>Ordered Lists</h3>
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```
## Tables
Tables are styled for better readability:
```
<table>
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
            <th>Header 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
            <td>Row 1, Cell 3</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
            <td>Row 2, Cell 3</td>
        </tr>
    </tbody>
</table>
```
## Utility Classes
Facilis provides a range of utility classes for quick styling:
### Text Alignment

- `text-left`: Align text to the left
- `text-right`: Align text to the right
- `text-center`: Center align text

### Background Colors

- `bg_primary`: Primary background color
- `bg_secondary`: Secondary background color
- `bg_info`: Info background color
- `bg_danger`: Danger background color
- `bg_warning`: Warning background color
- `bg_light`: Light background color
- `bg_dark`: Dark background color

### Text Colors

- `text_primary`: Primary text color
- `text_secondary`: Secondary text color
- `text_info`: Info text color
- `text_danger`: Danger text color
- `text_warning`: Warning text color
- `text_light`: Light text color
- `text_dark`: Dark text color

### Border Colors

- `border_primary`: Primary border color
- `border_secondary`: Secondary border color
- `border_info`: Info border color
- `border_danger`: Danger border color
- `border_warning`: Warning border color
- `border_light`: Light border color
- `border_dark`: Dark border color

### Widths

- `sm-width`: Small width (25%)
- `md-width`: Medium width (50%)
- `lg-width`: Large width (75%)
- `full-width`: Full width (100%)

### Opacity

- `bg-opacity-50-primary`: 50% opacity primary background color

### Example usage:
```
<div class="bg_primary text_light text-center">
    This is a centered text with primary background and light text color.
</div>
<div class="border_secondary md-width">
    This is a div with secondary border color and medium width.
</div>
```
## Customization
To customize Facilis, you can modify the variables in the _variables.scss file. Key variables include:
```
scssCopy$primary-color: #577590;
$secondary-color: #f08a4b;
$font-family-base: 'Open Sans, sans-serif';
$font-size-base: 16px;
```
After modifying the variables, you'll need to recompile the SCSS files to CSS.
## Contributing
Contributions to Facilis are welcome! Please submit a pull request or open an issue to discuss proposed changes.
## Copyright and license
Code and documentation copyright 2024 the Facilis Authors. Code released under the [MIT License](./LICENSE).