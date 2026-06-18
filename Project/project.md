Shop Ville - React Ecommerce Website

Overview

Shop Ville is a responsive ecommerce web application built using React.js. The project demonstrates core frontend development concepts such as component-based architecture, state management, API integration, search functionality, cart management, and form validation.

The application fetches product data from FakeStoreAPI and allows users to browse products, search items, add/remove products from the cart, and access a registration form.

---

Features

- Product listing from FakeStoreAPI
- Search products by title
- Add products to cart
- Remove products from cart
- Dynamic cart counter
- Registration form with validation
- Responsive navigation bar
- Conditional rendering using React state
- Clean and modern UI

---

Technologies Used

- React.js
- JavaScript (ES6+)
- JSX
- CSS (Inline Styling)
- FakeStoreAPI
- Vite

---

Project Structure

src
│
├── components
│   ├── nav.jsx
│   ├── productcard.jsx
│   └── Register.jsx
│
├── App.jsx
└── main.jsx

---

Installation

1. Clone the repository

git clone <repository-url>

2. Navigate to the project folder

cd shop-ville

3. Install dependencies

npm install

4. Start development server

npm run dev

---

Build for Production

npm run build

---

Functionalities

Search

Users can search products by typing in the search bar. Product filtering is performed using JavaScript's "filter()" method.

Cart Management

Users can:

- Add products to cart
- View cart items
- Remove products from cart

Registration Form

The registration form validates:

- Name field
- Email field
- Email format
- Password field
- Minimum password length (8 characters)

---

React Concepts Demonstrated

- Functional Components
- Props
- useState Hook
- useEffect Hook
- Conditional Rendering
- Event Handling
- Controlled Components
- Array Mapping
- Array Filtering

---
Disclaimer

Product names, images, and product data used in this project are obtained from FakeStoreAPI and are used strictly for educational and learning purposes.

---

Author

Priyanshu
CSE DS-2

Built as a React learning project and frontend development practice.
