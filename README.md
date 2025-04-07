🌿 Plant E-Commerce Website
Welcome to the Plant E-Commerce web application — a full-stack platform built for selling and managing plant products online. This site is ideal for a nursery business to showcase plant varieties, allow customers to order online, and manage orders efficiently.

📌 Features
🛒 User Side
🌱 View available plants with images, price, and details

🧾 Add plants to cart and checkout

👤 User Signup/Login with secure authentication

📦 Track order status and view order summary

💳 Place orders with delivery address and payment details

⚙️ Admin Side
🔐 Secure admin login (separate from user login)

➕ Add/Edit/Delete plant details

👥 View user details

📋 Manage and update orders

🧾 Track order history

🛠️ Tech Stack
🌐 Frontend
React.js (Vite)

Tailwind CSS for styling

🔙 Backend
Node.js with Express.js

🗃️ Database
MongoDB with Mongoose

📦 Installation & Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/plant-ecommerce.git
cd plant-ecommerce
Frontend Setup:

bash
Copy
Edit
cd client
npm install
npm run dev
Backend Setup:

bash
Copy
Edit
cd server
npm install
npm start
📁 Project Structure
bash
Copy
Edit
plant-ecommerce/
├── client/             # React frontend (Vite)
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── ...
├── server/             # Node.js + Express backend
│   ├── models/         # MongoDB models (User, Admin, Plant, Order)
│   ├── routes/         # API routes
│   ├── controllers/    # Request handling
│   └── server.js
└── README.md
🔐 User Authentication
User Signup: Name, email, mobile, address, password

User Login: Email, password

Admin Login: Email, password (with restricted access)

🧾 Order Flow
User adds plants to cart

Clicks "Checkout"

Enters order details: auto-generated order ID, quantity, total, address

Confirms order for home delivery

