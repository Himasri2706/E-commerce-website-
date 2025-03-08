# E-commerce-website-
A basic e-commerce store with product listings and a shopping cart built using HTML/CSS/JavaScript for the frontend and Express.js with MongoDB for the backend.
Features

Responsive frontend design
Product listings with search, filter, and sort functionality
Shopping cart with localStorage persistence
Checkout process
RESTful API for product and order management

Tech Stack
Frontend

HTML5
CSS3
JavaScript (Vanilla)

Backend

Node.js
Express.js
MongoDB with Mongoose

Project Structure
Copyecommerce-store/
├── frontend/
│   ├── index.html         # Homepage
│   ├── products.html      # Products listing page
│   ├── cart.html          # Shopping cart page
│   ├── css/
│   │   └── style.css      # Styles for all pages
│   └── js/
│       ├── main.js        # Main JavaScript for homepage
│       ├── products.js    # JavaScript for products page
│       └── cart.js        # JavaScript for cart page
├── backend/
│   ├── server.js          # Express server setup
│   ├── models/            # Mongoose models
│   │   ├── Product.js     # Product schema
│   │   └── Order.js       # Order schema
│   ├── routes/            # API routes
│   │   ├── products.js    # Product routes
│   │   └── orders.js      # Order routes
│   └── config/
│       └── db.js          # Database connection
├── package.json
└── README.md
Setup and Installation

Clone the repository
Copygit clone https://github.com/yourusername/ecommerce-store.git
cd ecommerce-store

Install dependencies
Copynpm install

Set up MongoDB

Make sure MongoDB is installed and running on your system
The application will connect to a local MongoDB instance by default


Start the development server
Copynpm run dev

Open in your browser
Copyhttp://localhost:8080


API Endpoints
Products

GET /api/products - Get all products
GET /api/products/:id - Get a specific product
POST /api/products - Create a new product

Orders

POST /api/orders - Create a new order
GET /api/orders/:id - Get a specific order

Future Enhancements

User authentication
Admin dashboard
Payment integration
Order history
Wishlist functionality
Product reviews and ratings

Submission for Code Alpha
This project demonstrates fundamental e-commerce functionality with a focus on clean code architecture and separation of concerns between frontend and backend.
License
MIT
