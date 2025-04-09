# 🛢 E-commerce Project

Welcome to the **E-commerce Project**! This is a full-stack **E-commerce Website** built with modern frontend and backend technologies. The objective of this project is to create a seamless online shopping experience, featuring product listings, user authentication, shopping cart functionality, and secure payment processing.

## 🚀 Features
- 🏢 **Product Listings** – Browse a variety of products with detailed descriptions.
- 🔍 **Search & Filters** – Find products quickly using an intuitive search and filter system.
- 🛒 **Shopping Cart** – Add/remove products and manage your cart effortlessly.
- 🏦 **Secure Payments** – Integrated payment gateway for smooth transactions.
- 🔒 **User Authentication** – Sign up, log in, and manage user accounts securely.
- 🛢 **Order Tracking** – Monitor orders in real-time with status updates.

---

# 📌 Project Milestones

## 🏆 Milestone 1: Repository Initialization
- Created a **GitHub repository** for version control.
- Initialized the repository with a **README.md** file.
- Set up the basic project structure and committed initial files.
- Ensured that the repository follows best practices for maintainability.

## 🏆 Milestone 2: Project Setup and Login Page
- Utilized the **GitHub repository** created in Milestone 1.
- Developed the **Login Page** as part of the project setup.
- Configured **basic authentication mechanisms**.
- Updated the **README.md** file to track progress.
- Committed and pushed all changes to GitHub.
- Added error handling to the authentication system for better security.

## 🏆 Milestone 3: Backend Organization and Database Setup
- Structured backend code efficiently with dedicated **folders**.
- Initialized and configured a **Node.js server** to handle API requests.
- Connected the application to **MongoDB** for data storage.
- Implemented **error handling** for stable server operations.
- Updated the **README.md** file with progress updates.
- Ensured database connection is optimized for performance and scalability.

## 🏆 Milestone 4: User Model, Controller, and File Uploads
- Created a **User Model** to define how user data is stored.
- Developed a **User Controller** for handling user operations.
- Integrated **Multer** to enable file uploads (e.g., profile and product images).
- Updated the **README.md** file with progress details.
- Added validation to ensure proper data input and security.

## 🏆 Milestone 5: User Registration UI & Validation
- Designed the **frontend UI** for user registration.
- Implemented **form validation** to ensure accurate user input.
- Connected the **registration UI** to the backend API.
- Updated the **README.md** file with completed milestones.
- Ensured user-friendly error messages and feedback mechanisms.

## 🏆 Milestone 6: Secure Signup with Password Encryption
- Developed a **backend endpoint** for the signup page.
- Used **bcrypt** to hash user passwords before saving.
- Stored all user data securely in the database with encrypted passwords.
- Ensured compliance with security laws like **GDPR** and **PCI-DSS**.
- Protected user data against password theft and unauthorized access.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.

## 🏆 Milestone 7: Secure Login with Password Verification
- Developed a **backend endpoint** for user login.
- Implemented **user authentication** by validating credentials.
- Used **bcrypt** to compare hashed passwords securely.
- Ensured compliance with **security standards** like GDPR and PCI-DSS.
- Returned appropriate error messages for **invalid credentials**.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.

## 🏆 Milestone 8: Product Card Component and Homepage Design
- Designed a **reusable Product Card Component** to display product details.
- Implemented **props** to pass product information dynamically (e.g., name, price, image).
- Used **array mapping** to display multiple products efficiently.
- Designed a **structured homepage layout** with a clean and visually appealing UI.
- Ensured **responsiveness** using CSS Grid or Flexbox.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.

## 🏆 Milestone 9: Product Form Creation and Multiple Image Uploads
- Created a **Product Form** for adding products, including fields for name, description, price, and images.
- Integrated the form with the backend to **store product details** in the database.
- Enabled **multiple image uploads** using HTML's `<input type="file" multiple>` and Multer for handling uploads on the server.
- Experimented with additional features like **admin access**, allowing only authorized users to add products.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.

## 🏆 Milestone 10: Product Schema Creation and Endpoint for Storing Products
- Created a **Mongoose Schema** for products, defining the structure of the product data (e.g., name, description, price, image URL).
- Added **validation** to ensure proper data input (e.g., required fields, correct data types).
- Built a **POST endpoint** to receive product data, validate it, and store it in the MongoDB database.
- Ensured **data integrity** by validating input before saving the product details.
- Experimented with adding **admin access** for uploading products (admin-only access).
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.

## 🏆 Milestone 11: Dynamic Homepage with Product Data
- Developed a **backend endpoint** to fetch all product data stored in MongoDB.
- Configured the endpoint to send product data to the frontend efficiently.
- Created a **frontend function** to retrieve product data from the backend API.
- Dynamically displayed products on the homepage using the **Product Card Component** created in Milestone 8.
- Passed product data (e.g., name, price, image) as **props** to render multiple products seamlessly.
- Focused on understanding how to **send and receive data** between backend and frontend.
- Ensured the homepage is responsive and visually appealing.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.


## 🏆 Milestone 12: Shopping Cart Functionality
- Implemented **shopping cart functionality** for users to add and remove products.
- Stored cart data in **local storage** to persist items across sessions.
- Connected the cart with **Redux** for better state management.
- Displayed the cart items dynamically on the **Cart Page**.
- Implemented a **checkout button** to proceed to payment.
- Ensured smooth **frontend-backend integration** for cart operations.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.

## 🏆 Milestone 13: Edit Product Functionality

- Implemented an **Edit** button on each product card.
- Created a **backend endpoint** to update existing product data in MongoDB.
- Auto-filled the **Product Form** with existing data when editing.
- Allowed users to **modify product details** and save changes.
- Ensured **proper data validation** before updating.
- Updated the **README.md** file with progress details.
- Committed and pushed changes to the **GitHub repository**.


## 🏆 Milestone 14: Delete Product Functionality  

- Implemented a **Delete** button on each product card.  
- Created a **backend endpoint** to delete a product from MongoDB using its **ID**.  
- Ensured that clicking the **Delete** button sends the **product ID** to the server.  
- Successfully removed the product from the **database** upon confirmation.  
- Implemented **error handling** to prevent accidental deletions.  
- Updated the **README.md** file with progress details.  
- Committed and pushed changes to the **GitHub repository**.  


## 🏆 Milestone 15: Navbar Component and Navigation  
- Designed and implemented a **responsive Navbar Component** for seamless navigation.  
- Added essential navigation links:  
  - 🏠 **Home** – Browse products.  
  - 📦 **My Products** – View and manage listed products.  
  - ➕ **Add Product** – Add new products to the store.  
  - 🛒 **Cart** – View selected items before checkout.  
- Used **React Router** for dynamic navigation between pages.  
- Integrated **user authentication checks** to conditionally show login/logout options.  
- Ensured **mobile responsiveness** with a hamburger menu for smaller screens.  
- Implemented **active link highlighting** to improve user experience.  
- Committed and pushed all updates to the **GitHub repository**.  
- Updated the **README.md** file with progress details.  

## 🏆 Milestone 16: Product Info Page with Add to Cart  

### 🎯 Tasks Completed:
- Created a **dedicated product info page** to display detailed product information.  
- Dynamically fetched and displayed product details using **React Router parameters**.  
- Added a **quantity selector** to allow users to choose the number of items they want to buy.  
- Implemented an **"Add to Cart" button** that updates the shopping cart state.  
- Integrated the cart functionality with the global state (**Redux or Context API**) for persistent cart management.  
- Ensured **responsive design** for a smooth user experience on all devices.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**.  



## Milestone 17: Implementing Cart Functionality
In this milestone, we successfully implemented the cart functionality by:

 - Updating the User Schema to store cart products.
 - Creating a Cart Schema to store product details in the cart.
 - Writing a backend endpoint to receive product details and store them in the database.
 - Testing the API endpoint using Postman to ensure proper functionality.
 - Updating the **README.md** file with milestone progress.  
 - Committing and pushing changes to the **GitHub repository**. 

 ## Milestone 18: Fetching User Cart Data
In this milestone, we successfully implemented the backend endpoint for the cart page by:

- Creating an API endpoint to fetch all products inside a user's cart.
- Fetching cart details using the user's email.
- Writing backend logic to retrieve the cart data from the database.
- Testing the API endpoint using Postman to ensure it returns correct cart data.
- Updating the **README.md** file with milestone progress.  
- Committing and pushing changes to the **GitHub repository**. 



## 🏆 Milestone 19: Cart Page with Quantity Management  
- Created a **Cart Page** to display the products inside the cart using the **cart endpoint** built in Milestone 18.  
- Implemented **+ and - buttons** for each product to allow users to **increase or decrease quantity**.  
- Developed **backend endpoints** to update the product quantity dynamically.  
- Ensured that the cart updates in **real-time** when modifying quantities.  
- Improved **UI/UX for cart management** to enhance the shopping experience.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**.  


## 🏆 Milestone 20: Profile Page with User Data Display  
- Created a **backend endpoint** to send all user data, including email and addresses.  
- Developed a **frontend profile page** to display user details dynamically.  
- Displayed **profile photo, name, and email** in a dedicated section.  
- Added an **address section** with an **"Add Address"** button.  
- Displayed **"No address found"** when no address is available.  
- Ensured smooth UI/UX for an improved user experience.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**.  


## 🏆 Milestone 21: Address Form Implementation  
- Created a **frontend address form** to capture user address details.  
- Included fields for **country, city, address1, address2, zip code, and address type**.  
- Implemented **state management** to store input address data.  
- Enabled **navigation from the profile page** to the address form when clicking "Add Address."  
- Ensured a **user-friendly interface** for smooth address input.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**.  

## 🏆 Milestone 22: Storing User Address in Database  
- Implemented a **backend endpoint** to receive address data from the frontend form.  
- Stored the received address inside the **user's profile in the database**.  
- Address data is now **added to the address array** inside the user collection.  
- Ensured proper **request validation and error handling** for robustness.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**.  

## 🏆 Milestone 23: Implementing Place Order & Order Schema  

- **Added a "Place Order" button** inside the cart page.  
- **Created a "Select Address" page** where users can view and select their delivery address.  
- **Implemented a backend endpoint** to retrieve all saved addresses of the user.  
- **Designed Mongoose Schema for Orders** to store order details in the database.  
- Ensured **smooth navigation** from the cart page to the select address page.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**.  

🏆 **Milestone 24: Implementing Order Confirmation Page**  

- Created an **Order Confirmation** page to display order details.  
- Displayed **all products** in the order along with their quantity and price.  
- Showcased the **selected delivery address** for user confirmation.  
- Calculated and displayed the **total cart value** before placing the order.  
- Added a **"Place Order"** button at the bottom for order submission.  
- Ensured smooth **navigation** from the "Select Address" page to the "Order Confirmation" page.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**. 


🏆 **Milestone 25: Implementing Backend Endpoint for Placing Orders**  

- Created a **backend endpoint** to handle order placement.  
- Designed the API to receive **products, user details, and address details** from the frontend.  
- Extracted the **user's ID** using their email from the database.  
- Ensured each **product is stored as a separate order** with the same delivery address.  
- Used the previously created **Order Schema** to store order details in the MongoDB `orders` collection.  
- Successfully integrated the endpoint with the **frontend order confirmation flow**.  
- Updated the **README.md** file with milestone progress.  
- Committed and pushed changes to the **GitHub repository**. 🚀  

🏆 **Milestone 26: Implementing Backend Endpoint to Fetch User Orders**  

### **Achievements**  
 - Created a **backend endpoint** to retrieve all orders for a specific user.  
 - Designed the API to **receive the user's email** as input.  
-  Extracted the **user's ID** from the database using the provided email.  
-  Retrieved all **orders associated with the user** from the MongoDB `orders` collection.  
-  Sent the **user's order history** in the API response.  
-  Ensured smooth integration with the **frontend order history page**.  
-  Updated the **README.md** file with milestone progress.  
-  Committed and pushed changes to the **GitHub repository**. 🚀  

🏆 **Milestone 27: Creating My Orders Page (Frontend)**


- Created a dedicated **`My Orders` page** in the frontend.  
- Integrated the **GET request** to the `/my-orders` endpoint from the previous milestone.  
- Passed the **user’s email** in the request to fetch relevant order data.  
- Displayed all the **user’s orders** including products, address, and total value.  
- Added **navigation to "My Orders" page** from the Navbar for better UX.  
 Ensured smooth UI rendering for **order history**.  
- Updated the **README.md** file summarizing milestone progress.  
- Committed and pushed all changes to the **GitHub repository**. 🚀

🏆 **Milestone 28: Cancel Order Functionality**

### **Achievements**
- Added a **"Cancel Order" button** for each order in the `My Orders` page UI.  
- Ensured the **Cancel button is hidden** if the order is already marked as "Cancelled".  
- Created a **backend endpoint** to handle canceling orders via `order-id`.  
- Implemented logic to **fetch order by ID**, update its status to `"Cancelled"` and save it in the database.  
- Connected the frontend cancel button to the backend cancel order API.  
- Provided instant **UI feedback** after canceling an order.  
- Updated the **README.md** with Milestone 28 progress.  
- Committed and pushed all the changes to the **GitHub repository**. 


# 🤮 Why Encrypt Passwords?
- 🔒 **Protect User Data**: Ensures passwords are safe even if the database is compromised.
- ⚖️ **Privacy**: Prevents passwords from being visible to anyone.
- 💻 **Compliance**: Meets security standards like **GDPR** and **PCI-DSS**.
- 🔧 **Prevents Password Theft**: Hashed passwords are much harder to crack.

---

# 🤝 Tech Stack
### **Frontend:**
- ⚫ React.js / Next.js
- 🎨 Tailwind CSS / Bootstrap
- 🧑‍🌍 Redux (for state management)

### **Backend:**
- 🖥 Node.js / Express.js
- 🔷 MongoDB
- 🔑 JWT Authentication

### **Other Tools & Services:**
- ☁ Firebase / AWS S3 (for file storage)
- 💳 Stripe / Razorpay (for payment processing)
- 📝 RESTful APIs / GraphQL

---

# 🌟 Roadmap
- [ ] Add product reviews & ratings ⭐
- [ ] Implement wishlists ❤
- [ ] Introduce AI-powered recommendations 🤖
- [ ] Improve UI/UX with animations ✨
- [ ] Add multi-language support 🌍
- [ ] Implement an admin dashboard for product & order management 💼
- [ ] Enable social media authentication 👤
- [ ] Optimize website performance & SEO 🌐
- [ ] Introduce PWA support for a mobile-friendly experience 📱
