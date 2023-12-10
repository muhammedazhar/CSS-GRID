# Lecture 17: CSS Grid Alignment and Centering

Welcome to Lecture 17 of the CSS Grid Video Course by Wes Bos! This repository contains the code example and resources for aligning and centering items using CSS Grid. The HTML file for this lecture is located at `Lecture17/alignment-and-centering.html`.

## Contents

- [HTML Code](alignment-and-centering.html)
- [CSS Styles](alignment-and-centering.html#L26-L47)
- [Grid Configuration](alignment-and-centering.html#L28-L32)

## Overview

The HTML file creates a grid container with 10 items, each uniquely styled. The grid is configured to have 5 columns, each 130px wide, with a gap of 20px. The container has a fixed height of 500px and is bordered using a custom variable for color.

## Key CSS Properties

- `display: grid;`: Establishes a grid container.
- `grid-gap: 20px;`: Sets the gap between grid items.
- `grid-template-columns: repeat(5, 130px);`: Defines 5 columns, each 130px wide.
- `place-items: stretch stretch;`: Stretches items to fill their cells in both directions.
- `justify-content: space-between;`: Distributes items evenly with space between them along the main axis.
- `align-content: space-between;`: Distributes items evenly with space between them along the cross axis.
- `.itm5`: Custom styling for the 5th item, centered both horizontally and vertically.

## Running the Example

To run the example locally:

1. Clone the `CSS-GRID` repository.
2. Navigate to the `Lecture17` directory: `cd Lecture17`
3. Open `alignment-and-centering.html` in a web browser.

Feel free to explore and modify the code to deepen your understanding of CSS Grid alignment and centering.

## License

This project is licensed under the [MIT License](../LICENSE).

## Questions and Support

If you have any questions or need support, feel free to open an issue or reach out to [Muhammed Azhar](https://github.com/muhammedazhar).

For additional resources, check out my [Notion](https://muhammedazhar.notion.site/Lecture-17-CSS-Grid-Alignment-Centering-fbf725ebcdf34e96beca2bb8d08f89b7?pvs=4) page.

Happy coding!