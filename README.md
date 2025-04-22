# 📌 Project Name: E_Commerce_Follow_Along

## 🚀 Overview

This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.

## 📚 Table of Contents

- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Milestones](#-milestones)
  - [Milestone 1: Project Setup](#milestone-1-project-setup)
  - [Milestone 2: Frontend & Backend Initialization](#milestone-2-frontend--backend-initialization)
  - [Milestone 3: Backend Structure & Server Setup](#milestone-3-backend-structure--server-setup)
  - [Milestone 4: Creating User Model and Controller](#milestone-4-creating-user-model-and-controller)
  - [Milestone 5: Sign-Up Page & Form Validation](#milestone-5-sign-up-page--form-validation)
  - [Milestone 6: Secure User Registration](#milestone-6-secure-user-registration)
  - [Milestone 7: User Login & Authentication](#milestone-7-user-login--authentication)
  - [Milestone 8: Product Card Component & Homepage Layout](#milestone-8-product-card-component--homepage-layout)
  - [Milestone 9: Product Input Form](#milestone-9-product-input-form)
  - [Milestone 10: Product Schema & Endpoint Creation](#milestone-10-product-schema--endpoint-creation)
  - [Milestone 11: Dynamic Homepage with Product Data](#milestone-11-dynamic-homepage-with-product-data)
  - [Milestone 12: My Products Page - Filtering by User Email](#milestone-12-my-products-page---filtering-by-user-email)
- [How to Run the Project](#-how-to-run-the-project)

---

## 🛠 Tech Stack

- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- File Uploads: Multer
- Password Encryption: bcrypt
- Version Control: Git, GitHub

---

## 📌 Milestones

### Milestone 1: Project Setup

_✅ Goals:_

- Created and updated README.md file.
- Initialized GitHub repository for version control.

---

### Milestone 2: Frontend & Backend Initialization

_✅ Goals:_

1. _Project Folder Structure:_ Organized files into separate frontend and backend directories.
2. _React Frontend Setup:_ Initialized a React application for building the user interface.
3. _Node.js Backend Setup:_ Set up a simple Node.js server for API integration in future milestones.
4. _Tailwind CSS Configuration:_ Integrated and configured Tailwind CSS for modern, responsive styling.
5. _Login Page Development:_ Created a login page with functionality and styling.

---

### Milestone 3: Backend Structure & Server Setup

_✅ Goals:_

1. _Backend Folder Structure:_ Created a structured hierarchy for organizing routes, controllers, models, and middleware.
2. _Server Setup:_
   - Used Node.js and Express.js to create a backend server.
   - Configured the server to listen on a designated port.
3. _Database Connection:_
   - Integrated MongoDB for efficient data storage.
   - Confirmed the connection between the server and MongoDB.
4. _Error Handling:_
   - Provided clear error messages for better debugging and user feedback.

---

### Milestone 4: Creating User Model and Controller

_✅ Goals:_

1. _User Model:_ Defined the structure of user data with attributes like name, email, password, and profile picture.
2. _User Controller:_ Handled user-related actions such as registration and data retrieval.
3. _Multer Integration:_ Enabled file uploads for storing user profile pictures.
4. _API Routes:_ Created endpoints for user creation and fetching user details.
5. _README Update:_ Documented progress and updated repository.

---

### Milestone 5: Sign-Up Page & Form Validation

_✅ Goals:_

1. _Sign-Up Page UI:_ Designed a clean and user-friendly sign-up form with fields for name, email, and password.
2. _Form Validation:_
   - Ensured the email follows the correct format.
   - Implemented password security criteria (minimum length, special characters, etc.).
3. _User Registration Flow:_ Integrated frontend form submission with the backend API.
4. _Error Handling:_ Displayed validation errors to users in real-time.
5. _README Update:_ Documented progress and updated repository.

---

### Milestone 6: Secure User Registration

_✅ Goals:_

1. _Password Encryption:_
   - Used bcrypt to hash passwords before storing them in the database.
   - Ensured no plaintext passwords are stored.
2. _Secure Data Storage:_
   - Stored the user's encrypted password along with other necessary details in MongoDB.
3. _Updated API Endpoints:_
   - Modified the user registration endpoint to handle password hashing securely.
4. _Security Compliance:_
   - Followed best practices for protecting user credentials.
5. _README Update:_
   - Documented progress for Milestone 6 and updated the repository.

---

### Milestone 7: User Login & Authentication

_✅ Goals:_

1. _Login Endpoint:_ Created a backend endpoint for user login and verified user credentials.
2. _Password Validation:_ Utilized bcrypt for secure password comparison.
3. _Authentication Flow:_ Authenticated users based on matching hashed passwords.
4. _Security Considerations:_ Ensured secure handling of user credentials.
5. _README Update:_ Updated with details about the user login functionality.

---

### Milestone 8: Product Card Component & Homepage Layout

_✅ Goals:_

1. _Card Component Creation:_ Designed a reusable card component for displaying product details.
2. _Homepage Layout Design:_ Created a responsive grid layout for displaying multiple product cards.
3. _Dynamic Data Display:_ Implemented dynamic rendering of product cards using mapping.
4. _Consistency & Responsiveness:_ Ensured consistent styling and responsive design.
5. _README Update:_ Documented progress and learning outcomes for Milestone 8.

---

### Milestone 9: Product Input Form

_✅ Goals:_

1. _Product Form Creation:_
   - Designed a form for inputting product details such as name, description, price, and category.
   - Included fields for uploading multiple product images.
2. _Image Upload Functionality:_
   - Implemented file input to accept multiple images.
   - Configured frontend to preview selected images before submission.
3. _Form Validation & Error Handling:_
   - Ensured all required fields are filled out.
   - Displayed validation errors for incomplete or incorrect inputs.
4. _Integration with Backend:_
   - Connected the form to the backend API for product creation.
   - Stored product details and images in MongoDB.
5. _User Experience Enhancements:_
   - Provided a clean and user-friendly UI for the product input form.
   - Added real-time feedback for image uploads and form validation.
6. _README Update:_
   - Documented the progress and learning outcomes for Milestone 9.
   - Updated the repository with details about the product input form.

---

### Milestone 10: Product Schema & Endpoint Creation

_✅ Goals:_

1. _Product Schema Creation:_
   - Designed a Mongoose schema for product details including name, description, price, and image URL.
   - Ensured each field has proper validation (e.g., required fields, correct data types).
2. _Endpoint Creation:_
   - Built a POST endpoint to receive product data.
   - Validated and saved the product details to MongoDB.
3. _Why Validation?_
   - Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.
4. _Security Enhancements:_
   - Implemented additional validation and data integrity measures to ensure accurate and secure data storage.
5. _Next Steps (Optional):_
   - Experiment with adding features such as admin access control to allow only admins to upload products or creating user profiles with roles for managing the shop.

---

### Milestone 11: Dynamic Homepage with Product Data

✅ _Goals:_

#### ⿡ Backend - Fetch All Products

- Created an API endpoint to retrieve all product data stored in MongoDB.
- Used _Express.js_ and _Mongoose_ to fetch and send product details as JSON.

#### ⿢ Frontend - Fetch & Display Data Dynamically

- Created a function to _fetch product data_ from the backend.
- Passed the received data to the existing _Product Card Component_.
- Used .map() to dynamically _render each product_ on the homepage.

#### ⿣ Why This Matters?

- Enables _dynamic content loading_ from the database instead of hardcoded values.
- Improves _scalability and flexibility_ as new products are added.

#### ⿤ Submission Steps

- ✅ Pushed the updated code to the _GitHub repository_.
- ✅ Updated the _README.md_ file with Milestone 11 details.
- ✅ Shared the repository link for submission.

---

### Milestone 12: My Products Page - Filtering by User Email

✅ _Goals:_

#### 1️⃣ Backend - Fetch Products by User Email

- Created an API endpoint to _retrieve only the products_ added by the logged-in user.
- Used _Express.js_ and _Mongoose_ to _filter products based on the user's email_ stored in MongoDB.
- Ensured _secure and efficient querying_ to fetch only relevant data.

#### 2️⃣ Frontend - Fetch & Display User-Specific Products

- Created a function to _fetch products linked to the logged-in user's email_.
- Passed the received data to the existing _Product Card Component_.
- Used .map() to dynamically _render only the user's products_ on the _"My Products"_ page.

#### 3️⃣ Why This Matters?

- Enables _personalized product listings_ based on the logged-in user's email.
- Improves _data filtering skills_, ensuring only relevant data is sent to the client.
- Enhances user experience by displaying only their _added products_ instead of all products.

---

### Milestone 13: Complete Project Documentation & Code Refactoring

✅ Goals:

1. Code Refactoring:
   - Improved code structure, ensuring modular and maintainable components.
   - Removed unnecessary files and optimized logic.
2. Comprehensive README Update:
   - Documented all features and milestones clearly.
   - Added setup instructions and usage details for new contributors.
3. Bug Fixes:
   - Fixed known issues related to authentication and data fetching.
   - Enhanced error handling for better debugging.
4. Deployment Preparation (Optional):
   - Structured code for potential deployment on platforms like Vercel or Heroku.
5. Final Submission:
   - Pushed the updated code to GitHub.
   - Ensured project documentation is complete and easy to understand.

---

# Milestone 14 - Delete Product Functionality

## Overview

In this milestone, we implemented a delete functionality that allows users to remove a product from the database using its unique ID. This involved updating both the frontend and backend to support the delete operation.

## Learning Outcomes

By completing this milestone, we learned:

- How to create an API endpoint to delete a product from MongoDB using its ID.
- How to integrate the delete feature in the frontend.
- How to handle delete requests and update the UI accordingly.

## Steps Implemented

1. _Backend:_

   - Created an Express.js endpoint to handle DELETE requests.
   - Used MongoDB's delete operation to remove the product by its ID.

2. _Frontend:_
   - Added a delete button to each product card.
   - Implemented an event listener to send a delete request to the server when the button is clicked.
   - Updated the UI dynamically after a successful deletion.

## API Endpoint

_Method:_ DELETE  
_Endpoint:_ /api/products/:id  
_Description:_ Deletes a product from the database using the provided ID.

### Milestone 15: Navbar Component & Navigation

✅ **Goals:**

⿡ **Create a Navbar Component**

- Designed a **reusable** Navbar component.
- Included navigation links for:
  - **Home**
  - **My Products**
  - **Add Product**
  - **Cart**

⿢ **Make Navbar Responsive**

- Ensured the Navbar adapts to **all screen sizes** (desktop, tablet, mobile).
- Used **Tailwind CSS** for styling and responsiveness.

⿣ **Integrate Navbar Across Pages**

- Added the **Navbar component** to all screens.
- Ensured smooth navigation between pages.

⿤ **Improve User Experience**

- Implemented **active link highlighting** to indicate the current page.
- Used **React Router** for seamless routing.

✅ **Final Steps:**

- **Tested** the navigation flow.
- **Updated** the `README.md` with Milestone 15 details.
- **Pushed** changes to GitHub.

🚀 **Next Up:** Continue improving UI and adding more interactive features!

---

### Milestone 16: Product Info Page

✅ Goals:

#### ⿡ Creating the Product Info Page

- Designed a dedicated page to display detailed product information, including:
  - Product Name
  - Description
  - Price
  - Image(s)

#### ⿢ Adding Quantity Selection & "Add to Cart" Button

- Implemented a quantity selector to allow users to choose the desired quantity.
- Added an "Add to Cart" button to store selected items in the cart.

#### ⿣ Dynamic Routing for Product Details

- Utilized React Router to create dynamic routes for each product.
- Fetched product details based on the product ID from the URL.

#### ⿤ Enhancing User Experience

- Ensured mobile responsiveness for smooth browsing on all devices.
- Implemented loading indicators for better user experience.

### Milestone 17: Add to Cart Functionality

✅ Goals:

#### ⿡ Update User Schema for Cart Functionality

- Modified the user schema to include a cart field.
- Structured the cart field to store an array of product objects containing:
  - Product ID
  - Name
  - Price
  - Quantity

#### ⿢ Backend - Add to Cart Endpoint

- Created an endpoint to receive product details and store them in the user's cart.
- Ensured secure handling of requests and efficient database updates using MongoDB & Mongoose.

#### ⿣ Frontend - Add to Cart Integration

- Connected the "Add to Cart" button from the Product Info Page to the backend API.
- Stored cart data in the database and updated the UI dynamically.

---

### Milestone 18: Cart Page and Checkout Functionality

✅ Goals:

#### ⿡ Creating the Cart Page

- Designed a Cart Page to display:
  - List of added products
  - Product images, names, prices, and quantities
  - Total cart value
- Implemented a Remove from Cart button for each item.

#### ⿢ Backend - Fetch & Update Cart

- Created an endpoint to retrieve cart items from the database.
- Implemented an API to update product quantities in the cart.
- Ensured secure cart data management for logged-in users.

#### ⿣ Checkout Functionality

- Added a Checkout button that:
  - Confirms the order
  - Clears the cart after a successful purchase
  - Redirects users to an order confirmation page
- Integrated a payment gateway placeholder for future improvements.

#### ⿤ User Experience Enhancements

- Provided real-time cart updates when quantities change.
- Displayed subtotal and total price dynamically.
- Ensured a mobile-friendly UI for a seamless experience.

### Milestone 19: Cart Quantity Management

✅ Goals:

### ⿡ Frontend - Cart Page UI Enhancements

- Added + and - buttons next to each product to modify its quantity.

- Ensured real-time updates for accurate pricing adjustments.

### ⿢ Backend - Quantity Management Endpoint

- Created two API endpoints to increase and decrease product quantity in the cart.

- Integrated logic to prevent negative quantities and handle item removal automatically when reduced to zero.

### ⿣ Enhancing User Experience

- Ensured instant feedback when quantity adjustments are made.

- Maintained a clean UI design with clear quantity controls.

---

### Milestone 20: Profile Page

✅ Goals:

### ⿡ Backend - User Data Endpoint

- Created an API endpoint to send all user data including profile details and addresses.

- Ensured the endpoint is secure and accessible only to authenticated users.

### ⿢ Frontend - Profile Page UI

- Designed a Profile Page that displays:

  - Profile Photo

  - Name

  - Email

  - List of Addresses

- Added a clear "Add Address" button for adding new addresses.

- Displayed "No address found" when no addresses are available.

### ⿣ Enhancing User Experience

- Ensured the profile page design is clean and easy to navigate.

---

# Milestone 21: Address Form Page

✅ _Goals:_

### ⿡ Frontend - Address Form Page

- Created an address form page that collects the following details:

  - _Country_
  - _City_
  - _Address Line 1_
  - _Address Line 2_
  - _ZIP Code_
  - _Address Type_ (e.g., Home, Office, etc.)

- Implemented a state that stores the address input data for better management.

- Ensured that when users click the "Add Address" button on the Profile Page, they are navigated to this form page.

### ⿢ Enhancing User Experience

- Designed the address form to be user-friendly and intuitive.
- Ensured clear input labels and proper validation for required fields.

---

# Milestone 22: Address Storage Endpoint

✅ _Goals:_

### ⿡ Backend - Address Storage Endpoint

- Created an API endpoint that receives address data from the frontend address form.
- Added logic to store the received address inside the address array within the user's profile collection in the database.
- Ensured endpoint security by restricting access to authenticated users only.

### ⿢ Enhancing User Experience

- Ensured proper error handling to manage invalid data entries.
- Implemented success and error response messages for clear user feedback.

## ▶ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git
   cd E_Commerce_Follow_Along
   ```
2. Install dependencies for both frontend and backend:
   ```bash
   cd frontend && npm install
   cd ../backend && npm install
   ```
3. Run the backend server:
   ```bash
   npm start
   ```
4. Run the frontend application:
   ```bash
   cd frontend
   npm start
   ```
5. Open [http://localhost:3000/](http://localhost:3000/) in your browser.

---

### 📜 Milestone 23: Place Order Button and Select Address Page

✅ Tasks Completed:

- 🛒 Added a "Place Order" button on the Cart page that navigates to `/select-address`.
- 📝 Created a `SelectAddress.jsx` page to display all user addresses with radio button selection and a "Confirm" button.
- 🌐 Implemented a backend endpoint (`GET /api/v2/user/addresses`) to fetch all addresses for the logged-in user.
- 🛠️ Created an `Order` model in `backend/model/Order.js` to store order details (user, products, address, total amount, status).

---

### 📜 Milestone 24: Order Confirmation Page

✅ Tasks Completed:

- 📝 Created an `OrderConfirmation.jsx` page to display products being ordered, the selected delivery address, and the total cart value.
- 🛒 Displayed all products from the cart with their names, prices, quantities, and totals.
- 🏠 Showed the selected address passed from the Select Address page.
- 💰 Calculated and displayed the total cart value.
- 🚀 Added a "Place Order" button (placeholder for future backend integration).

---

### 📜 Milestone 25: Backend Endpoint for Placing Orders

✅ Tasks Completed:

- 🌐 Created a `POST /api/v2/order/place` endpoint in `routes/order.js` and `controller/order.js`.
- 🛠️ Implemented logic to retrieve user `_id` by email and create separate orders for each product with the same address.
- 📦 Used the `Order` schema to store order details in MongoDB.
- 🔗 Updated `server.js` to register the new order routes.
- 🚀 Modified `OrderConfirmation.jsx` to call the endpoint with cart, address, and user email data.

---

### 📜 Milestone 26: Backend Endpoint for Retrieving User Orders

✅ Tasks Completed:

- 🌐 Created a `POST /api/v2/order/orders` endpoint in `routes/order.js` and `controller/order.js`.
- 🛠️ Implemented logic to retrieve user `_id` by email and fetch all orders for that user.
- 📦 Used the `Order` schema to query orders from MongoDB, populating product details (name, price).
- 🔗 Added the endpoint to return all user orders in the response.

---

### 📜 Milestone 27: My Orders Frontend Page

✅ Tasks Completed:

- 📝 Created a `MyOrders.jsx` page to display all user orders.
- 🌐 Sent a POST request to `/api/v2/order/orders` with the user’s email to fetch orders.
- 🖥️ Displayed order details including products, address, status, and total amount.
- 🚀 Added a "My Orders" link to the navbar for navigation.

---

### 📜 Milestone 28: Cancel Order Functionality

✅ Tasks Completed:

- 📝 Added a "Cancel Order" button to each order in `MyOrders.jsx`, displayed only if the order isn’t "Cancelled".
- 🌐 Created a `PUT /api/v2/order/cancel/:orderId` endpoint in `routes/order.js` and `controller/order.js`.
- 🛠️ Implemented logic to update an order’s status to "Cancelled" using the order ID.
- 🔗 Updated the frontend to call the cancel endpoint and reflect the status change.

---

### 📜 Milestone 29: Payment Options with PayPal Setup
✅ Tasks Completed:
- 📝 Added payment options (COD and Online Payment) with radio buttons to `OrderConfirmation.jsx`.
- 🌐 Set up UI to display a PayPal placeholder when "Online Payment" is selected.
- 🛠️ Configured COD orders to use the `/place` endpoint; online payment logs a placeholder message.
- 🔗 Used existing PayPal sandbox accounts and obtained the Client ID for future integration.

---
### 📜 Milestone 30: PayPal Payment Integration
✅ Tasks Completed:
- 📝 Installed `react-paypal-js` and integrated `PayPalScriptProvider` and `PayPalButtons` in `OrderConfirmation.jsx`.
- 🌐 Used the PayPal Sandbox Client ID to enable online payments via PayPal API.
- 🛠️ Updated the `Order` schema and `placeOrder` endpoint to store `paymentMethod` and `paymentDetails`.
- 🔗 Handled COD and PayPal payments, redirecting to `/order-success` on completion.

---

### 📜 Milestone 31: Global State Management with Redux
✅ Tasks Completed:
- 📝 Installed `react-redux`, `redux`, and `@reduxjs/toolkit` in the frontend folder.
- 🌐 Created a `store` folder in `frontend/src/` with `store.js` and `userActions.js`.
- 🛠️ Configured a Redux store in `store.js` with a `userReducer` to manage the user’s email.
- 🔗 Defined a `setEmail` action in `userActions.js` to update the email state.
- 📦 Wrapped the `App` component in a `Provider` in `frontend/src/index.js` to connect the store to the app.

### 📜 Milestone 32: Accessing Global State (Email) Across Pages

✅ Tasks Completed:
- 📥 Used the `useDispatch()` hook in the **Login page** to store the email in Redux state.
- 🔄 Accessed the stored email in other pages using `useSelector()`.
- 📂 Continued use of `userSlice` for managing and updating the user’s email.
- 🧪 Verified that the email remains available across all routes, proving the efficiency of Redux for global state handling.


---
## 📌 Milestone 33: JWT Token Creation & Cookie Storage

### ✅ Tasks Completed:

- 📥 Installed the `jsonwebtoken` package using NPM.
- 🔐 Created a JWT token using the `sign` method with user's email and ID.
- ⏳ Set the expiration of the JWT token using the `maxAge` property.
- 🍪 Stored the generated JWT token inside a cookie and sent it with the HTTP response.
- 🌐 Verified the cookie was stored in the browser for authentication purposes.
### 📚 What I Learned:

- How to securely generate and sign a JWT token in Node.js.
- Best practices for storing JWT tokens using HTTP-only cookies.
- Using cookies to persist user authentication across multiple pages/routes.

---



### 🛠️ Tech Stack

# Frontend:
⚛️ React.js / Next.js
🎨 Tailwind CSS / Bootstrap
🛠️ Redux for state management

# Backend:
🖥️ Node.js / Express.js
🟢 MongoDB
🔑 JWT Authentication