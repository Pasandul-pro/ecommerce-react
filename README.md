# ShopHub - E-Commerce React Application

ShopHub is a modern, responsive single-page e-commerce web application built with React and Vite. It features a complete shopping experience, from browsing products to adding them to a cart, user authentication, and a checkout flow.

## 🚀 Features

- **Product Catalog:** Browse a grid of available products with images, prices, and descriptions.
- **Product Details:** View in-depth details about specific products.
- **Shopping Cart:** Add items to your cart, update quantities, and remove items. The cart automatically calculates the subtotal and total cost.
- **User Authentication:** 
  - Complete Login and Sign-up functionality.
  - Form validation handled seamlessly using `react-hook-form`.
  - User sessions and credentials are saved locally (using `localStorage`).
- **Global State Management:** Uses React Context API (`AuthContext` and `CartContext`) to manage user sessions and shopping cart data across the application without prop drilling.
- **Responsive Routing:** Client-side routing with `react-router-dom` for fast, seamless page transitions.

## 🛠️ Tech Stack

- **Framework:** [React 19](https://react.dev/)
- **Bundler:** [Vite](https://vitejs.dev/)
- **Routing:** [React Router v7](https://reactrouter.com/)
- **Form Management:** [React Hook Form](https://react-hook-form.com/)
- **Styling:** Vanilla CSS (`App.css`)

## 📦 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

- Node.js (v16.x or higher)
- npm (Node Package Manager)

### Installation

1. **Clone the repository** (if applicable) or navigate to the project directory:
   ```bash
   cd ecommerce-react
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open the app:**
   Open your browser and navigate to the URL provided in the terminal (usually `http://localhost:5173`).

## 📂 Project Structure

```
src/
├── assets/         # Static assets (images, svgs, etc.)
├── components/     # Reusable UI components (Navbar, ProductCard, etc.)
├── context/        # React Context providers (AuthContext, CartContext)
├── data/           # Mock data and utility functions for products
├── pages/          # Route components (Home, Auth, Checkout, ProductDetails)
├── App.jsx         # Main application component and routing setup
├── App.css         # Global styles
└── main.jsx        # Application entry point
```

## 🔐 Authentication Note
For demonstration purposes, this application uses the browser's `localStorage` to simulate a database for user accounts and sessions.

## 📄 License
This project is for educational and portfolio purposes.
