📦 E-Commerce Website — Full-Stack MERN Project
Overview
This E-Commerce Website is a robust, full-stack application simulating a real-world online store. The frontend is built using React.js, HTML, CSS, Bootstrap, and JavaScript, offering a clean, responsive user interface. The backend is powered by Node.js, Express.js, and MongoDB, delivering a scalable and secure environment for managing users, products, and orders.

The platform allows customers to browse products, manage their shopping carts, securely register/login, and place orders, while admin users can manage inventory via a protected dashboard.

🔑 Key Features
User Authentication: JWT-based secure login/register system

Product Catalog: Fully dynamic product listings with images, price, and categories

Shopping Cart: Real-time cart updates with add/remove options

Search & Filter: Search bar and category-wise product filtering

Admin Dashboard: Role-based product management and CRUD operations

Responsive Design: Mobile-first layout using Bootstrap and React

REST APIs: Robust API layer using Express and MongoDB

Order Management: Checkout functionality with order summaries

🛠️ Technology Stack
Frontend

HTML5, CSS3

JavaScript (ES6)

React.js (via Create React App)

Bootstrap

Backend

Node.js

Express.js

MongoDB (Mongoose)

Others

JWT for Authentication

Bcrypt.js for password hashing

Git & GitHub for version control

Postman for API testing

⚙️ Installation Instructions
🔹 Getting Started with Create React App
This project was bootstrapped with Create React App.

✅ Available Scripts
In the project directory, you can run:

🔸 Frontend Setup
bash
Copy
Edit
cd client
npm install
Then start the React development server:

bash
Copy
Edit
npm start
Opens http://localhost:3000 in your browser.
The page will reload on save. Lint errors will appear in the console.

🔸 Backend Setup
bash
Copy
Edit
cd server
npm install
Create a .env file in the server directory:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Then run:

bash
Copy
Edit
npm run dev
Starts the backend server at http://localhost:5000

🧪 npm test
Launches the test runner in watch mode. See Running Tests

🚀 npm run build
Builds the frontend React app for production to the build folder.

⚙️ npm run eject
Removes Create React App abstraction for advanced customization. Irreversible!

👨‍💻 Usage Instructions
Register or Login as a user or admin.

Browse or search for products.

Add items to cart and proceed to checkout.

Admins can create/edit/delete products via the dashboard.

