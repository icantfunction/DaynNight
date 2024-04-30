# Skyline Project

This project is a simple HTML and CSS project that creates a skyline view using different CSS properties and techniques.

## Files

The project consists of two main files:

1. `Skyline.html`: This is the main HTML file that contains the structure of the skyline. It includes divs for background and foreground buildings, each with their own unique classes for styling.

2. `style.css`: This CSS file contains the styles for the skyline. It uses CSS variables for colors, and it uses different properties such as `width`, `height`, `background`, `border`, and `position` to style the buildings. It also uses `linear-gradient` and `radial-gradient` for some of the building and sky backgrounds.

## Structure

The HTML structure consists of two main divs: `.background-buildings` and `.foreground-buildings`. Each of these divs contains several child divs that represent individual buildings. Each building div has a unique class (e.g., `.bb1`, `.bb2`, `.fb1`, `.fb2`) and some of them have additional child divs for more complex shapes or additional features like windows.

The CSS file defines styles for each of these classes. It uses CSS variables for the building and window colors, which makes it easy to change the color scheme of the skyline. It also uses media queries to change the color scheme for viewports less than `1000px` wide.

## Usage

To view the skyline, open the `Skyline.html` file in a web browser. The skyline should display as a series of colored blocks representing buildings against a gradient sky background.

## Customization

You can customize the skyline by modifying the `style.css` file. You can change the colors by modifying the CSS variables at the top of the file. You can also change the size, shape, or position of the buildings by modifying the properties of their corresponding classes.