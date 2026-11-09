# II STUPID

A sleek, dark-themed storefront and landing page built with plain HTML, CSS, and JavaScript. The project presents a modern product showcase with navigation, featured products, a cart, FAQ, reviews, and a video modal.

## Overview

This repository contains a single-page web experience for a fictional product brand called “II STUPID.” It is designed as a premium landing page with:

- A hero section with bold branding
- Product cards and pricing
- An interactive mobile menu
- A cart panel with add and remove behavior
- An FAQ accordion
- A reviews section
- A showcase/video modal
- Smooth scrolling and reveal animations

## Project Structure

```text
.
├── index.html        # Main landing page structure
├── style.css         # Styling and responsive layout
├── script.js         # Interactive behavior and cart logic
└── README.md         # Project documentation
```

## Features

- Responsive layout for desktop and mobile screens
- Dark, modern visual design
- Product listings with prices and availability states
- Browser-based cart with item removal and total calculation
- FAQ toggling
- Video modal controls
- Smooth navigation and scroll-triggered reveal effects

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript

## Run Locally

This is a static website; no build tools or dependencies are required.

Open `index.html` in a browser, or start a local server from the project directory:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Notes

- Checkout is not connected to a payment service; the button currently displays a placeholder message.
- Cart contents are kept in memory and reset when the page is reloaded.
- The project does not include a backend or database.

## License

No license is specified in this repository. Check with the repository owner before reusing or distributing the project.
