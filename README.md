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
  - [Milestone 13: Edit Product Functionality](#milestone-13-edit-product-functionality)
  - [Milestone 14: Delete Product Functionality](#milestone-14-delete-product-functionality)
  - [Milestone 15: Navbar Component & Navigation](#milestone-15-navbar-component--navigation)
  - [Milestone 16: Product Info Page](#milestone-16-Product-Info-Page)
  - [Milestone 17: Add to Cart Functionality](#milestone-17-Add-to-Cart-Functionality)
  - [Milestone 18: Cart Page & Checkout Functionality](#milestone-18-Cart-Page-and-Checkout-Functionality)
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
✅ Goals:  
- Created and updated README.md file.  
- Initialized GitHub repository for version control.  

---

### Milestone 2: Frontend & Backend Initialization  
✅ Goals:  
1. Project Folder Structure: Organized files into separate frontend and backend directories.  
2. React Frontend Setup: Initialized a React application for building the user interface.  
3. Node.js Backend Setup: Set up a simple Node.js server for API integration in future milestones.  
4. Tailwind CSS Configuration: Integrated and configured Tailwind CSS for modern, responsive styling.  
5. Login Page Development: Created a login page with functionality and styling.  

---

### Milestone 3: Backend Structure & Server Setup  
✅ Goals:  
1. Backend Folder Structure: Created a structured hierarchy for organizing routes, controllers, models, and middleware.  
2. Server Setup:  
   - Used Node.js and Express.js to create a backend server.  
   - Configured the server to listen on a designated port.  
3. Database Connection:  
   - Integrated MongoDB for efficient data storage.  
   - Confirmed the connection between the server and MongoDB.  
4. Error Handling:  
   - Provided clear error messages for better debugging and user feedback.  

---

### Milestone 4: Creating User Model and Controller  
✅ Goals:  
1. User Model: Defined the structure of user data with attributes like name, email, password, and profile picture.  
2. User Controller: Handled user-related actions such as registration and data retrieval.  
3. Multer Integration: Enabled file uploads for storing user profile pictures.  
4. API Routes: Created endpoints for user creation and fetching user details.  
5. README Update: Documented progress and updated repository.  

---

### Milestone 5: Sign-Up Page & Form Validation  
✅ Goals:  
1. Sign-Up Page UI: Designed a clean and user-friendly sign-up form with fields for name, email, and password.  
2. Form Validation:  
   - Ensured the email follows the correct format.  
   - Implemented password security criteria (minimum length, special characters, etc.).  
3. User Registration Flow: Integrated frontend form submission with the backend API.  
4. Error Handling: Displayed validation errors to users in real-time.  
5. README Update: Documented progress and updated repository.  

---

### Milestone 6: Secure User Registration  
✅ Goals:  
1. Password Encryption:  
   - Used bcrypt to hash passwords before storing them in the database.  
   - Ensured no plaintext passwords are stored.  
2. Secure Data Storage:  
   - Stored the user's encrypted password along with other necessary details in MongoDB.  
3. Updated API Endpoints:  
   - Modified the user registration endpoint to handle password hashing securely.  
4. Security Compliance:  
   - Followed best practices for protecting user credentials.  
5. README Update:  
   - Documented progress for Milestone 6 and updated the repository.  

---

### Milestone 7: User Login & Authentication  
✅ Goals:  
1. Login Endpoint: Created a backend endpoint for user login and verified user credentials.  
2. Password Validation: Utilized bcrypt for secure password comparison.  
3. Authentication Flow: Authenticated users based on matching hashed passwords.  
4. Security Considerations: Ensured secure handling of user credentials.  
5. README Update: Updated with details about the user login functionality.  

---

### Milestone 8: Product Card Component & Homepage Layout  
✅ Goals:  
1. Card Component Creation: Designed a reusable card component for displaying product details.  
2. Homepage Layout Design: Created a responsive grid layout for displaying multiple product cards.  
3. Dynamic Data Display: Implemented dynamic rendering of product cards using mapping.  
4. Consistency & Responsiveness: Ensured consistent styling and responsive design.  
5. README Update: Documented progress and learning outcomes for Milestone 8.  

---

### Milestone 9: Product Input Form  
✅ Goals:  
1. Product Form Creation:  
   - Designed a form for inputting product details such as name, description, price, and category.  
   - Included fields for uploading multiple product images.  
2. Image Upload Functionality:  
   - Implemented file input to accept multiple images.  
   - Configured frontend to preview selected images before submission.  
3. Form Validation & Error Handling:  
   - Ensured all required fields are filled out.  
   - Displayed validation errors for incomplete or incorrect inputs.  
4. Integration with Backend:  
   - Connected the form to the backend API for product creation.  
   - Stored product details and images in MongoDB.  
5. User Experience Enhancements:  
   - Provided a clean and user-friendly UI for the product input form.  
   - Added real-time feedback for image uploads and form validation.  
6. README Update:  
   - Documented the progress and learning outcomes for Milestone 9.  
   - Updated the repository with details about the product input form.  

---

### Milestone 10: Product Schema & Endpoint Creation  
✅ Goals:  
1. Product Schema Creation:  
   - Designed a Mongoose schema for product details including name, description, price, and image URL.  
   - Ensured each field has proper validation (e.g., required fields, correct data types).  
2. Endpoint Creation:  
   - Built a POST endpoint to receive product data.  
   - Validated and saved the product details to MongoDB.  
3. Why Validation?  
   - Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.  
4. Security Enhancements:  
   - Implemented additional validation and data integrity measures to ensure accurate and secure data storage.  
5. Next Steps (Optional):  
   - Experiment with adding features such as admin access control to allow only admins to upload products or creating user profiles with roles for managing the shop.  

---
### Milestone 11: Dynamic Homepage with Product Data  

✅ Goals:  

#### 1️⃣ Backend - Fetch All Products  
- Created an API endpoint to retrieve all product data stored in MongoDB.  
- Used Express.js and Mongoose to fetch and send product details as JSON.  

#### 2️⃣ Frontend - Fetch & Display Data Dynamically  
- Created a function to fetch product data from the backend.  
- Passed the received data to the existing Product Card Component.  
- Used .map() to dynamically render each product on the homepage.  

#### 3️⃣ Why This Matters?  
- Enables dynamic content loading from the database instead of hardcoded values.  
- Improves scalability and flexibility as new products are added.  

#### 4️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 11 details.  
- ✅ Shared the repository link for submission.

---

### Milestone 12: My Products Page - Filtering by User Email  

✅ Goals:  

#### 1️⃣ Backend - Fetch Products by User Email  
- Created an API endpoint to retrieve only the products added by the logged-in user.  
- Used Express.js and Mongoose to filter products based on the user's email stored in MongoDB.  
- Ensured secure and efficient querying to fetch only relevant data.  

#### 2️⃣ Frontend - Fetch & Display User-Specific Products  
- Created a function to fetch products linked to the logged-in user's email.  
- Passed the received data to the existing Product Card Component.  
- Used .map() to dynamically render only the user's products on the "My Products" page.  

#### 3️⃣ Why This Matters?  
- Enables personalized product listings based on the logged-in user's email.  
- Improves data filtering skills, ensuring only relevant data is sent to the client.  
- Enhances user experience by displaying only their added products instead of all products.

---

### Milestone 13: Edit Product Functionality

✅ Goals:  

#### 1️⃣ Backend - Update Product Endpoint
- Write an endpoint that will receive new data and update the existing data inside MongoDB.
- Utilized Express.js and Mongoose to handle update operations securely and efficiently.

#### 2️⃣ Frontend - Edit Button & Auto-Filled Form
- Added an Edit button to each product card to enable product modification.
- On clicking Edit, the form auto-fills with the existing product data, allowing updates to name, description, price, and images.
- Implemented real-time form validation and preview of changes before submission.

#### 3️⃣ User Experience Enhancement
- Provided a smooth transition between the product list and the edit form.
- Ensured validation checks are in place to maintain data integrity during updates.

#### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 13 details.
- ✅ Shared the repository link for submission.

---
### Milestone 14: Delete Product Functionality

✅ Goals:

#### 1️⃣ Backend - Delete Product Endpoint
- Created an endpoint that allows deletion of a product using its specific ID.
- Utilized Express.js and Mongoose to handle delete operations securely and efficiently.

#### 2️⃣ Frontend - Delete Button Integration
- Added a Delete button to each product card.
- When clicked, the product ID is sent to the server endpoint to trigger the deletion.

#### 3️⃣ User Experience Enhancement
- Provided confirmation prompts to avoid accidental deletions.
- Implemented smooth transitions and updates to the UI when a product is deleted.

#### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 14 details.
- ✅ Shared the repository link for submission.

---

### Milestone 15: Navbar Component & Navigation

✅ Goals:

#### 1️⃣ Creating the Navbar Component
- Designed a responsive Navbar with navigation links for:
  - Home
  - My Products
  - Add Product
  - Cart
- Ensured consistency across all pages for a seamless experience.

#### 2️⃣ Implementing Reusability
- Used the Navbar across all screens to maintain a uniform layout.
- Optimized component structure for easy scalability.

#### 3️⃣ Enhancing Responsiveness
- Used CSS Flexbox/Grid & Tailwind CSS to make the Navbar adaptable to different screen sizes.
- Implemented hamburger menu for mobile users.

#### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 15 details.
- ✅ Shared the repository link for submission.

---

### Milestone 16: Product Info Page  

✅ Goals:  

#### 1️⃣ Creating the Product Info Page  
- Designed a dedicated page to display detailed product information, including:  
  - Product Name  
  - Description  
  - Price  
  - Image(s)  

#### 2️⃣ Adding Quantity Selection & "Add to Cart" Button  
- Implemented a quantity selector to allow users to choose the desired quantity.  
- Added an "Add to Cart" button to store selected items in the cart.  

#### 3️⃣ Dynamic Routing for Product Details  
- Utilized React Router to create dynamic routes for each product.  
- Fetched product details based on the product ID from the URL.  

#### 4️⃣ Enhancing User Experience  
- Ensured mobile responsiveness for smooth browsing on all devices.  
- Implemented loading indicators for better user experience.  

#### 5️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 16 details.  
- ✅ Shared the repository link for submission.  

---

### Milestone 17: Add to Cart Functionality  

✅ Goals:  

#### 1️⃣ Update User Schema for Cart Functionality  
- Modified the user schema to include a cart field.  
- Structured the cart field to store an array of product objects containing:  
  - Product ID  
  - Name  
  - Price  
  - Quantity  

#### 2️⃣ Backend - Add to Cart Endpoint  
- Created an endpoint to receive product details and store them in the user's cart.  
- Ensured secure handling of requests and efficient database updates using MongoDB & Mongoose.  

#### 3️⃣ Frontend - Add to Cart Integration  
- Connected the "Add to Cart" button from the Product Info Page to the backend API.  
- Stored cart data in the database and updated the UI dynamically.  

#### 4️⃣ User Experience Enhancements  
- Implemented a notification system to confirm when a product is added to the cart.  
- Ensured real-time cart updates without needing to refresh the page.  

#### 5️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 17 details.  
- ✅ Shared the repository link for submission.  

---
### Milestone 18: Cart Page and Checkout Functionality  

✅ Goals:  

#### 1️⃣ Creating the Cart Page  
- Designed a Cart Page to display:  
  - List of added products  
  - Product images, names, prices, and quantities  
  - Total cart value  
- Implemented a Remove from Cart button for each item.  

#### 2️⃣ Backend - Fetch & Update Cart  
- Created an endpoint to retrieve cart items from the database.  
- Implemented an API to update product quantities in the cart.  
- Ensured secure cart data management for logged-in users.  

#### 3️⃣ Checkout Functionality  
- Added a Checkout button that:  
  - Confirms the order  
  - Clears the cart after a successful purchase  
  - Redirects users to an order confirmation page  
- Integrated a payment gateway placeholder for future improvements.  

#### 4️⃣ User Experience Enhancements  
- Provided real-time cart updates when quantities change.  
- Displayed subtotal and total price dynamically.  
- Ensured a mobile-friendly UI for a seamless experience.  

#### 5️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 18 details.  
- ✅ Shared the repository link for submission.  

---

## ▶ How to Run the Project  
1. Clone the repository:  
   bash  
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git  
   cd E_Commerce_Follow_Along  
     
   
2. Install dependencies for both frontend and backend:  
   bash  
   cd frontend && npm install  
   cd ../backend && npm install  
     
   
3. Run the backend server:  
   bash  
   npm start  
     
   
4. Run the frontend application:  
   bash  
   cd frontend  
   npm start  
     
   
5. Open [http://localhost:3000/](http://localhost:3000/) in your browser.  

---