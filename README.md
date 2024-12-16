# E-Commerce Website

A fully functional and modern E-Commerce Website built with ReactJS. This project showcases product listings, dynamic pages, a user-friendly interface, and responsiveness designed for online stores.

## 🚀 Features

- **Product Listings**: Display products with key details, including price, image, and description.
- **Dynamic Pages**: Modular components for easy scalability and maintenance.
- **Responsive Design**: Optimized for all devices, including mobile and desktop.
- **Cart Functionality**: Add and manage items in a shopping cart.
- **Navigation**: Smooth routing for seamless transitions.
- **ReactJS**: Built with modern development practices.

## 🛠️ Tech Stack

- **Frontend**: ReactJS (with Hooks)
- **Styling**: Vanilla CSS
- **Routing**: React Router
- **Backend**: Node.js, Express.js, MongoDB

## 📂 Folder Structure

```plaintext
Directory structure:
└── fudailzafar-E-Commerce-Website
    ├── backend
    │   ├── package.json
    │   ├── node_modules
    │   ├── package-lock.json
    │   └── index.js
    ├── frontend
    │   ├── index.html
    │   ├── .gitignore
    │   ├── eslint.config.js
    │   ├── public
    │   ├── package.json
    │   ├── vite.config.js
    │   ├── package-lock.json
    │   ├── README.md
    │   └── src
    │       ├── App.jsx
    │       ├── Components
    │       │   ├── CartItems
    │       │   │   ├── CartItems.css
    │       │   │   └── CartItems.jsx
    │       │   ├── Item
    │       │   │   ├── Item.css
    │       │   │   └── Item.jsx
    │       │   ├── RelatedProducts
    │       │   │   ├── RelatedProduct.jsx
    │       │   │   └── RelatedProducts.css
    │       │   ├── Offers
    │       │   │   ├── Offers.jsx
    │       │   │   └── Offers.css
    │       │   ├── Popular
    │       │   │   ├── Popular.css
    │       │   │   └── Popular.jsx
    │       │   ├── Navbar
    │       │   │   ├── Navbar.css
    │       │   │   └── Navbar.jsx
    │       │   ├── NewsLetter
    │       │   │   ├── NewsLetter.jsx
    │       │   │   └── NewsLetter.css
    │       │   ├── Breadcrums
    │       │   │   ├── Breadcrum.css
    │       │   │   └── Breadcrum.jsx
    │       │   ├── DescriptionBox
    │       │   │   ├── DescriptionBox.jsx
    │       │   │   └── DescriptionBox.css
    │       │   ├── Assets
    │       │   │   ├── drop-drop-icon.webp
    │       │   │   ├── all_product.js
    │       │   │   ├── data.js
    │       │   │   └── new_collections.js
    │       │   ├── Hero
    │       │   │   ├── Hero.css
    │       │   │   └── Hero.jsx
    │       │   ├── NewCollections
    │       │   │   ├── NewCollections.css
    │       │   │   └── NewCollections.jsx
    │       │   ├── Footer
    │       │   │   ├── Footer.jsx
    │       │   │   └── Footer.css
    │       │   └── ProductDisplay
    │       │       ├── ProductDisplay.css
    │       │       └── ProductDisplay.jsx
    │       ├── index.css
    │       ├── main.jsx
    │       ├── Pages
    │       │   ├── ShopCategory.jsx
    │       │   ├── CSS
    │       │   │   ├── LoginSignup.css
    │       │   │   └── ShopCategory.css
    │       │   ├── Shop.jsx
    │       │   ├── LoginSignup.jsx
    │       │   ├── Product.jsx
    │       │   └── Cart.jsx
    │       ├── App.css
    │       └── Context
    │           └── ShopContext.jsx
    └── README.md
```

## 💻 Getting Started

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v14 or later)
- **npm** (comes with Node.js) or **yarn**

### Installation

Clone this repository:

```bash
git clone https://github.com/fudailzafar/E-Commerce-Website.git
cd E-Commerce-Website
```

Install dependencies:

```bash
npm install
```

or

```bash
yarn
```

Start the development server:

```bash
npm start
```

or

```bash
yarn start
```

Open your browser and navigate to `http://localhost:3000`.

## 📦 Deployment

To build the project for production:

```bash
npm run build
```

This will create a `build/` folder with optimized static files. You can deploy these files to any web hosting service.
