# ShopEase — Responsive E-Commerce Product Gallery

A responsive product gallery created for **Web Engineering Laboratory 8** using HTML5 and CSS Grid.

## Features
- Responsive product cards using `repeat(auto-fit, minmax(250px, 1fr))`.
- No media query is used for the product-grid layout.
- Product cards include category, price, labels, and images.
- Hover animations on cards, images, and buttons.
- Separate HTML and CSS files.

## Files
- `index.html` — page structure and product content.
- `style.css` — styling, CSS Grid layout, and hover effects.

## Run locally
1. Download or clone this repository.
2. Open the folder in Visual Studio Code.
3. Open `index.html` in a browser (or use the Live Server extension).

## Git and GitHub upload
Replace the URL below with your own GitHub repository URL.

```bash
git init
git add .
git commit -m "Create responsive e-commerce product gallery"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

If the GitHub repository already contains a README created on GitHub, first run:

```bash
git pull origin main --allow-unrelated-histories
```

Then push:

```bash
git push -u origin main
```

## Required CSS Grid technique
```css
.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 26px 20px;
}
```
- `repeat()` repeats the column pattern.
- `auto-fit` fits as many columns as can fit in the available width.
- `minmax(250px, 1fr)` keeps each card at least 250px wide and lets it grow.
- `1fr` shares remaining space equally.
