# E-Commerce Platform

A modern, full-featured E-Commerce Platform built with React (Vite) and Tailwind CSS. This platform demonstrates advanced state management using React Context API and component composition.

## Features

- 🛍️ **Product Catalog** - Browse products with filtering and sorting
- 🛒 **Shopping Cart** - Add, remove, and update quantities
- 🔐 **Authentication** - Login and registration system
- 💳 **Checkout Process** - Multi-step checkout with shipping and payment forms
- 📱 **Responsive Design** - Mobile-first design with Tailwind CSS
- 🎨 **Modern UI** - Clean, professional e-commerce interface

## Tech Stack

- **React 18** - Functional components with Hooks
- **Vite** - Fast build tool and dev server
- **React Router DOM** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **Context API** - Global state management for Cart and Authentication

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## Project Structure

```
src/
├── components/          # Reusable components
│   ├── Header.jsx      # Navigation header with cart icon
│   ├── Footer.jsx      # Footer with links
│   ├── ProductCard.jsx # Product display card
│   ├── CartItem.jsx    # Cart item with quantity controls
│   └── AuthForm.jsx    # Login/Register form
├── pages/              # Page components
│   ├── Home.jsx        # Landing page
│   ├── ProductCatalog.jsx  # Product listing with filters
│   ├── ProductDetail.jsx   # Individual product page
│   ├── Cart.jsx        # Shopping cart page
│   ├── Checkout.jsx    # Multi-step checkout
│   ├── Login.jsx       # Login page
│   └── Register.jsx    # Registration page
├── context/            # Context providers
│   ├── CartContext.jsx # Shopping cart state management
│   └── AuthContext.jsx # Authentication state management
├── mockData/           # Mock data
│   └── products.js     # Product data
├── App.jsx             # Main app component with routing
└── main.jsx            # Entry point
```

## Key Features Explained

### State Management

- **CartContext**: Manages shopping cart state (items, quantities, totals)
- **AuthContext**: Manages user authentication state (login status, user info)

### Routing

- `/` - Home page
- `/products` - Product catalog
- `/products/:id` - Product detail page
- `/cart` - Shopping cart
- `/checkout` - Checkout process
- `/login` - Login page
- `/register` - Registration page

### Mock Data

Products are stored in `src/mockData/products.js`. You can easily replace this with API calls to a backend service.

## Customization

### Colors

Edit `tailwind.config.js` to customize the color scheme. The primary color is currently set to blue.

### Products

Modify `src/mockData/products.js` to add or change products.

## License

This project is open source and available for personal and commercial use.

