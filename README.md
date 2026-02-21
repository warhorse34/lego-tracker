🧙 Lego Collection Tracker

A Harry Potter-themed personal Lego set tracker, built as a single-page web app. Track your collection status, browse all Harry Potter sets, and search for any Lego set to add to your list.

🔗 Live app: warhorse34.github.io/lego-tracker

What It Does

Harry Potter tab — Automatically loads every Harry Potter Lego set via the Rebrickable API, so your list stays current as new sets are released

Other Sets tab — Search for any Lego set by name and add it to a personal collection

Status tracking — Mark each set as Owned (Complete), Owned (Not Complete), Wishlist, or Not Owned

Set detail lightbox — Click any set to see pieces, year, minifigure count, theme, and a Rebrickable link

Sorting & filtering — Sort by year, name, piece count, or set number; filter by ownership status

Sorting Hat — A Harry Potter-themed house sorting experience on first visit, with a matching colour theme applied throughout the app

Persistent storage — All statuses and custom sets are saved in your browser's local storage, so your collection is remembered between visits

Tech Stack

Vanilla HTML, CSS, and JavaScript — no frameworks, no build tools

Rebrickable API for set data, images, and minifigure details

Bootstrap 5 for layout utilities

Google Fonts (Cinzel, IM Fell English, Lato)

Browser localStorage for data persistence

Hosted on GitHub Pages

Running Locally

No build step required. Just open index.html in a browser.

git clone https://github.com/warhorse34/lego-tracker.git cd lego-tracker open index.html 

API Key

This project uses the Rebrickable API. The API key is embedded in index.html. This is a low-risk public API key — Rebrickable does not charge for usage and the key only provides read access to public Lego set data.

For a production app, the recommended approach would be to proxy API requests through a backend server so the key is never exposed in client-side code.

Project Status

This is a personal learning project, built to explore HTML/CSS/JavaScript fundamentals, API integration, and GitHub Pages deployment.

Potential future directions:

GitHub Desktop workflow for smoother local development

Backend server to secure the API key

Progressive Web App (PWA) for mobile installation

React or similar framework as the project grows in complexity

Acknowledgements

Set data, images, and minifigure information provided by Rebrickable. Harry Potter is a trademark of Warner Bros. Entertainment Inc.

