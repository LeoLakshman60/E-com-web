# Terra & Leaf — Beginner E-Commerce Demo

A single-file, beginner-friendly e-commerce website built with plain HTML, CSS, and JavaScript — no frameworks, no build tools, no server required.

## How to use
Just open `index.html` in any web browser.

## What's inside
- Product catalog with category filters (All / Indoor Plants / Accessories)
- Add to cart, quantity controls, remove items
- Live cart drawer with subtotal, shipping, and total
- Simulated checkout (no real payments are processed)
- Fully responsive and keyboard-accessible

## How it's organized (see comments inside index.html)
1. DATA   — the PRODUCTS array (the "database")
2. STATE  — the cart array + active filter, kept in memory
3. RENDER — functions that turn state into HTML
4. EVENTS — click handlers that update state and re-render

Note: the cart resets on page refresh since it's stored in memory only, not saved to a server or browser storage — a natural next step once you're ready to go further.
