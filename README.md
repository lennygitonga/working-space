# KWETU Fragrances Product Showcase

A responsive product showcase page for **KWETU Fragrances**, built with **HTML + CSS only**.  
Each product card includes an image, title, price, rating, and an **Add To Cart** button that opens a modal with product details — no JavaScript required.

---

## ✨ Features
- Responsive **grid layout** using CSS Grid.  
- **Product cards** with hover effects, consistent image sizing, and clean typography.  
- **CSS-only modals** using the checkbox hack:
  - Each product has its own hidden checkbox (`modal-toggle-X`).  
  - Clicking **Add To Cart** (a `<label>` linked to the checkbox) opens the modal.  
  - Clicking the **× close button** (another `<label>`) closes the modal.  
- **Mobile-friendly design** with media queries for tablets and phones.  
- Elegant styling with shadows, rounded corners, and transitions.

---

## 📂 Project Structure
### 1. Main HTML file with product cards + modals
### 2. Styles for grid, cards, buttons, and modals
### 3. Product images

Responsive Design
- Desktop: 4 columns.
- Tablet: 2–3 columns.
- Mobile: 1 column.
- Modals scale to fit smaller screens (max-width: 480px)
