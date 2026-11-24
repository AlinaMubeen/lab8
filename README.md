# ShopEase — Responsive E-Commerce Product Gallery

A responsive e-commerce product gallery developed for **Web Engineering Laboratory 8** using HTML5 and CSS Grid.

## Features

- Responsive product gallery using CSS Grid.
- Uses `auto-fit` and `minmax(250px, 1fr)` for automatic responsiveness.
- No media queries required for the product grid.
- Minimum product card width of 250px.
- Product cards with images, names, categories, and prices.
- Hover animations and image scaling effects.
- Responsive navigation bar.
- Separate HTML and CSS files.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Visual Studio Code
- Git and GitHub

## Project Structure

```text
ShopEase/
│
├── index.html
├── style.css
└── README.md
```

## How to Run

1. Download or clone the repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in your browser.
4. Alternatively, use the Live Server extension.

## CSS Grid Implementation

The following CSS makes the product gallery responsive:

```css
.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 26px 20px;
}
```

- `display: grid`: Activates CSS Grid.
- `repeat()`: Repeats the column pattern.
- `auto-fit`: Automatically fits available columns.
- `minmax(250px, 1fr)`: Maintains a minimum card width of 250px.
- `gap`: Adds spacing between product cards.


## Author

Developed as part of Web Engineering Laboratory 8.

**Project:** Responsive E-Commerce Product Gallery  
**University:** UET Taxila
