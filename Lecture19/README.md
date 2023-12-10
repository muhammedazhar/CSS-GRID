# Lecture 19: Nesting Grid with Album Layouts

Welcome to Lecture 19 of the CSS Grid Video Course by Wes Bos! This repository contains the code example and resources for nesting grids with album layouts using CSS Grid. The HTML file for this lecture is located at `Lecture19/albums.html`.

## Contents

- [HTML Code](albums.html)
- [CSS Styles](albums.html#L97-L118)

## Overview

The HTML file demonstrates how to create a grid layout for album items, each containing artwork and details. The grid is responsive and adjusts based on the available width, ensuring a consistent and visually appealing layout.

## Key CSS Properties

- `display: grid;`: Establishes a grid container.
- `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));`: Creates responsive columns, each with a minimum width of 300px and a maximum width of 1fr (fractional unit).
- `.albums`: Styles for the albums container, using grid and defining the gap between album items.
- `.album`: Styles for each album item, utilizing a grid layout with two columns (artwork and details), adding padding, background, box shadow, and aligning items vertically at the center.
- `.album__artwork`: Styles for album artwork, making it fill its container.

## Running the Example

To run the example locally:

1. Clone the `CSS-GRID` repository.
2. Navigate to the `Lecture19` directory: `cd Lecture19`
3. Open `albums.html` in a web browser.

Feel free to explore and modify the code to deepen your understanding of nesting grids with album layouts in CSS Grid.

## License

This project is licensed under the [MIT License](../LICENSE).

## Questions and Support

If you have any questions or need support, feel free to open an issue or reach out to [Muhammed Azhar](https://github.com/muhammedazhar).

For additional resources, check out my [Notion](https://muhammedazhar.notion.site/Lecture-19-Nesting-Grid-with-Album-Layouts-730e3e76616447739068ec7c9566856a?pvs=4) page.

Happy coding!