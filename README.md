# QuickBite — Food Ordering Website Concept

QuickBite is a responsive frontend food-ordering website concept built to demonstrate HTML, CSS, and JavaScript skills.

> **Status:** Frontend prototype only. It does not connect to restaurants, a backend, a payment gateway, or a delivery service. Checkout is a demo interaction.

## Features
- Responsive landing page and food menu
- Search meals by name, category, or description
- Filter by Burgers, Pizza, Bowls, and Drinks
- Add/remove cart items and change quantities
- Automatic subtotal and estimated total calculations
- Cart persistence using browser `localStorage`
- Demo checkout disclaimer
- Mobile navigation and keyboard `/` shortcut for search

## Technologies
- HTML5 — semantic structure
- CSS3 — layout, styling, responsive design
- Vanilla JavaScript — filtering, rendering, cart state and interactions
- `localStorage` — demo cart persistence

## Run locally
1. Download or clone this repository.
2. Open the folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the Live Server extension.

No package installation or build process is required. Internet access is needed for remote food photos and Google Fonts.

## Project structure
```text
quickbite-frontend/
├── index.html
├── style.css
├── script.js
├── README.md
└── .gitignore
```

## Publish to GitHub
Create an empty repository on GitHub, then run these commands in the project folder:

```bash
git init
git add .
git commit -m "Build QuickBite frontend food ordering concept"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/quickbite-frontend.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username and use the repository URL GitHub provides.

## Future improvements
- Connect a backend API for menu and order data
- Add user accounts and order history
- Integrate a secure payment provider through a backend
- Add automated tests and form validation
- Host image assets locally

## Academic note
Describe only features you understand, have tested, and can demonstrate. The checkout is not real order processing or payment functionality.

## Image credits
Food photography loads from Unsplash URLs.
