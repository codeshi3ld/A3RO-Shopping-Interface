Below are the key interfaces of the application, presenting the complete e-commerce workflow.

### 🖥️ 1. Product Listing Page
Displays a collection of available products with images, pricing, ratings, and quantity selection. The layout is designed using a responsive grid system for better user experience across devices.

<img width="1580" height="1042" alt="home page" src="https://github.com/user-attachments/assets/f61143a9-dd3f-4523-9571-6dd6d50cd2da" />


### 🛒 2. Cart Management (Add to Cart)
Allows users to add products to the cart and manage selected items. Users can update quantities, remove items, and view the dynamically updated total cost.

<img width="1592" height="916" alt="add to cart" src="https://github.com/user-attachments/assets/c775a004-19b0-479e-a838-cf39d3ce37bf" />


### 💳 3. Checkout Page
Provides an order review interface where users can verify selected items, choose delivery options, and view a detailed payment summary before placing an order.

<img width="1592" height="916" alt="checkout without order" src="https://github.com/user-attachments/assets/6520df70-6528-41de-aa94-6e8c63ee791e" />

### 💳 4. Application Setup & Routing
This section shows the main application setup in App.jsx, where routing and cart state management are implemented.
It includes API integration using Axios to load cart data and uses React Hooks (useState, useEffect) to manage and initialize state, 
ensuring smooth data flow across pages like Home, Checkout, and Orders.

<img width="1593" height="855" alt="application setup   routing" src="https://github.com/user-attachments/assets/2b72de1a-61f7-4e4a-a181-09f91df6d452" />



## 🚀 Tech Stack

This project is built using modern web development technologies:

- **Frontend Framework:** React  
- **Language:** JavaScript (ES6+)  
- **Styling:** CSS / Custom Styling  
- **State Management:** React Hooks (e.g., useState, useContext)  
- **Architecture:** Component-based and modular design

- codeshield-ecommerce/
│
├── backend/
│   ├── src/
│   ├── server.js
│
├── frontend/
│   ├── src/
│   ├── App.js
│
├── README.md
└── .gitignore

## 🛒 Features

This application is a simplified e-commerce system focused on usability, performance, and clean UI design.

### 1. Product Listing
- Displays products with complete details (image, price, ratings)  
- Supports quantity selection per item  
- Responsive and user-friendly layout  

### 2. Cart Management
- Add items to cart with selected quantity  
- Update or remove items dynamically  
- Automatically calculates total price  

### 3. Checkout System
- Review selected items before placing an order  
- Displays shipping options and payment summary  
- Ensures a smooth checkout experience
  
### 4. Application Setup & Routing
- Defines the main application structure in App.jsx
- Implements page navigation using React Router
- Manages global cart state using React Hooks
- Integrates API calls with Axios for cart data synchronization


## 🧠 Project Overview

This application demonstrates core concepts of modern React development,
including component reusability, state management using hooks, and dynamic user interaction. 
It replicates a basic e-commerce workflow, from product browsing to order placement,
providing a practical example of front-end application design.
