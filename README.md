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
└── fudailzafar-e-commerce-website/
    ├── README.md
    ├── admin/
    │   ├── README.md
    │   ├── eslint.config.js
    │   ├── index.html
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── vite.config.js
    │   ├── .gitignore
    │   ├── public/
    │   └── src/
    │       ├── App.jsx
    │       ├── index.css
    │       ├── main.jsx
    │       ├── Components/
    │       │   ├── AddProduct/
    │       │   │   ├── AddProduct.css
    │       │   │   └── AddProduct.jsx
    │       │   ├── ListProduct/
    │       │   │   ├── ListProduct.css
    │       │   │   └── ListProduct.jsx
    │       │   ├── Navbar/
    │       │   │   ├── Navbar.css
    │       │   │   └── Navbar.jsx
    │       │   └── Sidebar/
    │       │       ├── Sidebar.css
    │       │       └── Sidebar.jsx
    │       ├── Pages/
    │       │   └── Admin/
    │       │       ├── Admin.css
    │       │       └── Admin.jsx
    │       └── assets/
    ├── backend/
    │   ├── index.js
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── node_modules/
    │   └── upload/
    │       └── images/
    └── frontend/
        ├── README.md
        ├── eslint.config.js
        ├── index.html
        ├── package-lock.json
        ├── package.json
        ├── vite.config.js
        ├── .gitignore
        ├── public/
        └── src/
            ├── App.css
            ├── App.jsx
            ├── index.css
            ├── main.jsx
            ├── Components/
            │   ├── Assets/
            │   │   ├── all_product.js
            │   │   ├── data.js
            │   │   ├── drop-drop-icon.webp
            │   │   └── new_collections.js
            │   ├── Breadcrums/
            │   │   ├── Breadcrum.css
            │   │   └── Breadcrum.jsx
            │   ├── CartItems/
            │   │   ├── CartItems.css
            │   │   └── CartItems.jsx
            │   ├── DescriptionBox/
            │   │   ├── DescriptionBox.css
            │   │   └── DescriptionBox.jsx
            │   ├── Footer/
            │   │   ├── Footer.css
            │   │   └── Footer.jsx
            │   ├── Hero/
            │   │   ├── Hero.css
            │   │   └── Hero.jsx
            │   ├── Item/
            │   │   ├── Item.css
            │   │   └── Item.jsx
            │   ├── Navbar/
            │   │   ├── Navbar.css
            │   │   └── Navbar.jsx
            │   ├── NewCollections/
            │   │   ├── NewCollections.css
            │   │   └── NewCollections.jsx
            │   ├── NewsLetter/
            │   │   ├── NewsLetter.css
            │   │   └── NewsLetter.jsx
            │   ├── Offers/
            │   │   ├── Offers.css
            │   │   └── Offers.jsx
            │   ├── Popular/
            │   │   ├── Popular.css
            │   │   └── Popular.jsx
            │   ├── ProductDisplay/
            │   │   ├── ProductDisplay.css
            │   │   └── ProductDisplay.jsx
            │   └── RelatedProducts/
            │       ├── RelatedProduct.jsx
            │       └── RelatedProducts.css
            ├── Context/
            │   └── ShopContext.jsx
            └── Pages/
                ├── Cart.jsx
                ├── LoginSignup.jsx
                ├── Product.jsx
                ├── Shop.jsx
                ├── ShopCategory.jsx
                └── CSS/
                    ├── LoginSignup.css
                    └── ShopCategory.css

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
