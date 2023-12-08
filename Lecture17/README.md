## Lecture 17: Alignment and Centering

In this lecture, we explore techniques for aligning and centering items using CSS Grid. The HTML file for this lecture is located at `Lecture17/alignment-and-centering.html`. Here is my [<ins>**Notion**</ins>](https://muhammedazhar.notion.site/Lecture-17-CSS-Grid-Alignment-Centering-fbf725ebcdf34e96beca2bb8d08f89b7?pvs=4) page about this lecture.

### Contents

- [HTML Code](https://github.com/muhammedazhar/CSS-GRID/blob/master/Lecture17/alignment-and-centering.html)
- [CSS Styles](https://github.com/muhammedazhar/CSS-GRID/blob/master/Lecture17/alignment-and-centering.html#L21)
- [Grid Configuration](https://github.com/muhammedazhar/CSS-GRID/blob/master/Lecture17/alignment-and-centering.html#L21-L29)

### Overview

The HTML file creates a grid container with 40 items, each uniquely styled. The grid is configured to have 10 columns and 4 rows with a grid gap of 20px. The items are centered both horizontally and vertically using CSS Grid properties.

### Key CSS Properties

- `display: grid;`: Establishes a grid container.
- `grid-gap: 20px;`: Sets the gap between grid items.
- `grid-template-columns: repeat(10, 1fr);`: Defines 10 columns with equal width.
- `grid-template-rows: repeat(4, 100px);`: Defines 4 rows with a fixed height of 100px.
- `justify-items: center;`: Centers items along the horizontal axis.
- `align-items: center;`: Centers items along the vertical axis.
- `place-items: center center;`: Shorthand for both horizontal and vertical centering.

### Running the Example

To run the example locally:

1. Clone this repository.
2. Open `Lecture17/alignment-and-centering.html` in a web browser.

Feel free to explore and modify the code to deepen your understanding of CSS Grid alignment and centering.

## License

This project is licensed under the [MIT License](LICENSE).

## Questions and Support

If you have any questions or need support, feel free to open an issue or reach out to [Muhammed Azhar](https://github.com/muhammedazhar).

Happy coding!