# Ezecha Store

Ezecha Store is a responsive single-page storefront built with HTML, Tailwind CSS (CDN), and a small amount of vanilla JavaScript.  
It showcases featured products in aligned cards, includes a responsive navigation menu, and uses local image assets for branding and products.

Live Laravel link: [ezecha-store.vercel.app](https://ezecha-store.vercel.app)

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Custom CSS
- Vanilla JavaScript

## Features

- Fixed top navigation bar.
- Responsive desktop/mobile menu with toggle button.
- Hero section with call-to-action.
- Product grid with equal-height cards and aligned buttons.
- About section with project/store description.
- Contact section with a styled form (name, email, message).
- Product image hover animation.
- Footer with social links placeholders.

## Project Structure

```text
ezecha/
|-- index.html
|-- README.md
|-- css/
|   |-- style.css
|-- images/
|   |-- logo.png
|   |-- product1.jpg
|   |-- product2.jpg
|   |-- product3.jpg
|   |-- product4.jpg
|-- .vscode/
|   |-- settings.json
```

## File-by-File Description

- `index.html`: Main page structure and content. Contains header/nav, hero section, product cards, about section, contact form section, footer, and JavaScript for mobile menu and front-end form behavior.
- `css/style.css`: Custom styles for smooth scrolling and product image hover animation.
- `images/logo.png`: Brand logo displayed in the navbar.
- `images/product1.jpg`: Product card image for Wireless Headphones.
- `images/product2.jpg`: Product card image for Smartwatch.
- `images/product3.jpg`: Product card image for Stylish Backpack.
- `images/product4.jpg`: Product card image for Designer Sunglasses.
- `.vscode/settings.json`: Workspace editor setting (Live Server runs on port `5502`).
- `README.md`: Project documentation and setup information (this file).

## Run Locally

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Start a local server (for example, with Live Server).
4. Open `index.html` in your browser through the local server.

## Notes

- The navigation menu links to `#home`, `#products`, `#about`, and `#contact`, and all sections are now implemented in `index.html`.
- The contact form currently uses front-end handling only (no backend/API submission yet).
