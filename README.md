# Paradise Nursery

Paradise Nursery is a responsive plant shopping experience built for browsing beautiful houseplants, outdoor growers, and succulents. It includes a welcoming landing page, curated product catalog, and a fully interactive shopping cart powered by Redux Toolkit.

## Features

- Responsive nature-inspired landing page with hero imagery and Get Started navigation
- About Us page with company story, mission, vision, services, and reasons to choose Paradise Nursery
- 18 unique plants across Indoor Plants, Outdoor Plants, and Succulents
- Product cards with thumbnail, description, price, and Add to Cart controls
- Duplicate-safe Add to Cart behavior with Added to Cart state
- Dynamic navbar cart icon and item count
- Cart quantity controls, item totals, delete controls, and dynamic overall total
- Coming Soon checkout message
- Continue Shopping navigation
- React Router routes for Home, About, Plants, and Cart
- Redux Toolkit state management with a beginner-friendly project structure
- Responsive CSS with hover, transition, shadow, rounded card, and image zoom effects

## Technologies

- React and JSX
- Vite
- JavaScript
- Redux Toolkit and React Redux
- React Router DOM
- Normal CSS

## Project Structure

```text
src/
  components/
    AboutUs.jsx
    CartItem.jsx
    Navbar.jsx
    ProductList.jsx
  data/
    plants.js
  redux/
    CartSlice.jsx
    store.js
  App.jsx
  App.css
  index.css
  main.jsx
README.md
```

## Installation

```bash
npm install
```

## Run The App

```bash
npm run dev
```

For a production build:

```bash
npm run build
```

## Images

The catalog and landing page use stable remote Unsplash image URLs so the project works immediately without manual asset setup. Product image paths are centralized in `src/data/plants.js`, making them easy to replace with local files in `public/images/` later.

## Author

- Name: Add your name here
- GitHub: Add your GitHub username here

## Assignment Checklist

1. Landing page, company introduction, background image, and functional Get Started button: complete.
2. About Us content covering introduction, mission, vision, products/services, and reasons to choose: complete.
3. At least 18 products in 3 categories with 6 products per category: complete.
4. Product browsing, thumbnails, descriptions, prices, Add to Cart, disabled Added state, and dynamic count: complete.
5. Responsive navbar with logo, Home, Plants, and Cart routes: complete.
6. Redux Toolkit cart actions for add, remove, increase, decrease, and clear: complete.
7. Cart page with quantity management, delete, totals, checkout message, and Continue Shopping: complete.
