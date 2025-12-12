# EcoShop – Sustainable Living Marketplace

EcoShop is a frontend-focused web application that demonstrates a sustainable e-commerce experience.  
The project combines product browsing, user accounts, community features, and interactive tools in a single-page layout.

This repository contains the **frontend implementation** built with raw HTML, CSS, and JavaScript, using Bootstrap for layout and styling.

---

## Features

- Responsive navigation bar with section-based scrolling
- Product gallery with search, category filtering, and sorting
- Shopping cart with add/remove functionality and checkout form
- User authentication UI (login, signup, logout)
- Sustainability calculator for estimating CO₂ savings
- Community forum UI for posting discussion topics
- Newsletter signup and contact form
- Analytics dashboard with chart visualization
- Modal-based interactions (login, signup, cart, checkout)

---

## Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript (ES6)
- Bootstrap 5
- Chart.js

**Backend (expected / optional)**
- REST API for authentication, products, orders, analytics, and forum posts  
- Any backend framework can be used (e.g., Express, Django, Flask)

---

## Project Structure

- `index.html` – Main application file
- Inline CSS for layout and styling
- Inline JavaScript for UI logic and API interaction
- No build tools or frameworks required

---

## Running the Project

### Option 1: Frontend only
Simply open `index.html` in your browser.

Some features (login, checkout, analytics) will show demo data if a backend is not connected.

### Option 2: With a backend
Update the API base URL in the JavaScript configuration:

```js
const API_BASE_URL = "http://localhost:5000/api";
