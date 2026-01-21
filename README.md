

# Loop - Sustainable Luxury Fashion E-Commerce

**Loop** is a frontend e-commerce web application designed for a women's clothing brand. It bridges the gap between high-end fashion and everyday wearability, focusing on sustainable luxury. This project demonstrates a fully responsive, functional shopping interface built with core web technologies.

## 🚀 Features

* **Responsive Design:** A "mobile-first" approach ensuring the site looks great on desktops, tablets, and mobile devices (includes a custom hamburger menu).
* **Dynamic Product Catalog:** Products are rendered dynamically via JavaScript, featuring categories like Dresses, Tops, Bottoms, Outerwear, Shoes, and Accessories.
* **Functional Shopping Cart:**
* Add items to the cart from the shop or product detail pages.
* Remove items and view real-time total calculations.
* **Persistence:** Cart data is saved to `localStorage`, so users don't lose their items on refresh.


* **Product Details:** Dedicated product pages showing images, descriptions, pricing, and size selection.
* **Category Filtering:** Filter products on the Shop page to find specific items easily.
* **Checkout Simulation:** A simulated checkout process with form validation, order summary, and a success modal animation.
* **Interactive UI:** Smooth transitions, hover effects, and a glass-morphism inspired navigation bar.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure for all pages.
* **CSS3:** Custom styling without frameworks.
* Uses CSS Variables (`:root`) for consistent theming.
* Flexbox & CSS Grid for layouts.
* Media queries for responsiveness.


* **JavaScript (ES6):**
* DOM Manipulation for rendering products and UI updates.
* Event handling for user interactions.
* `localStorage` API for cart management.



## 📂 Project Structure

```text
Loop/
├── index.html       # Landing page with featured products and new arrivals
├── shop.html        # Full product catalog with sidebar category filters
├── product.html     # Dynamic product detail page (uses URL parameters)
├── about.html       # Brand story and mission statement
├── contact.html     # Contact form and location details
├── checkout.html    # Billing form and order summary
├── style.css        # Global styles, typography, and responsive rules
├── script.js        # Product data, cart logic, and page rendering functions
└── README.md        # Project documentation

```

## 📸 Screenshots & Highlights

* **Hero Section:** Features a cinematic background with a call to action.
* **Cart Sidebar:** A slide-out panel that allows users to manage their cart from any page.
* **Navigation:** Sticky navbar that changes opacity on scroll.

## 🔧 Setup & Usage

1. **Clone or Download** the repository.
2. **Open the Project:** Navigate to the project folder and open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. **Explore:**
* Browse the **Shop** to see the collection.
* Click on a product to view details.
* Add items to the **Cart** and proceed to **Checkout**.
* Fill in dummy details in the checkout form to see the success animation.

## 🔮 Future Enhancements

* **Backend Integration:** Connect to a Node.js/Python backend for real database management.
* **User Authentication:** Allow users to create accounts and save order history.
* **Payment Gateway:** Integrate Stripe or PayPal for real transactions.

---

*https://loop-pbl.netlify.app/*
