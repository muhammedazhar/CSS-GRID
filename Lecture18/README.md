# Lecture 18: Re-ordering Grid Items

In this lecture, we explore the concept of re-ordering grid items using CSS Grid. The HTML file for this lecture is located at `Lecture18/order.html`. Here is my [Notion](https://muhammedazhar.notion.site/Lecture-18-Re-ordering-Grid-Items-ef904052264c489f97c8be7752d7533f?pvs=4) page about this lecture.

### Contents

- [HTML Code](Lecture18/order.html)
- [CSS Styles](Lecture18/order.html#L23-L39)
- [Grid Configuration](Lecture18/order.html#L24-L26)

### Overview

The HTML file demonstrates how to re-order grid items within a container using the `order` property in CSS Grid. Three items (`logo`, `nav`, and `content`) are placed in a grid, and their order is manipulated to achieve a specific layout.

### Key CSS Properties

- `display: grid;`: Establishes a grid container.
- `grid-gap: 20px;`: Sets the gap between grid items.
- `grid-template-columns: repeat(10, 1fr);`: Defines 10 equal-width columns.
- `.logo`: Spans across 3 columns and appears as the second item in the grid.
- `.nav`: Spans across 4 columns and appears as the first item in the grid.
- `.content`: Spans from the first column to the last column and appears as the third item in the grid.
- `order`: Specifies the order in which items are displayed within the grid.

### Running the Example

To run the example locally:

1. Clone this repository.
2. Open `Lecture18/order.html` in a web browser.

Feel free to explore and modify the code to deepen your understanding of re-ordering grid items in CSS Grid.

## License

This project is licensed under the [MIT License](LICENSE).

## Questions and Support

If you have any questions or need support, feel free to open an issue or reach out to [Muhammed Azhar](https://github.com/muhammedazhar).

Happy coding!