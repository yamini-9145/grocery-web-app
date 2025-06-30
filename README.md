# grocery-web-app
# 🛒 Grocery App - Full Stack Web Application

A full-featured grocery shopping web application using the MERN stack (MongoDB, Express.js, React.js, Node.js) with additional support for SQL-based analytics or relational modules.

## 📌 Features

- 🧾 User Authentication (Login / Signup)
- 🛍️ Browse & Search Grocery Products
- 🛒 Add to Cart & Checkout
- 🧑‍🍳 Admin Panel for Product Management
- 📊 Orders Dashboard (SQL or MongoDB-based)
- 📦 Order History
- 🔍 Product Filtering & Sorting

---

## 🧰 Tech Stack

### Frontend
- HTML5, CSS3, JavaScript (ES6+)
- React.js
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB (for products, users, and orders)
- SQL (optional, for analytics or legacy data)

---

## ⚙️ Folder Structure

/grocery-app/
├── client/ # React Frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── index.js
├── server/ # Node.js Backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── config/
│ ├── app.js
│ └── server.js
├── sql/ # SQL scripts (optional)
│ └── analytics.sql
├── .env
├── package.json
└── README.md

---

## 🚀 Installation

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/grocery-app.git
cd grocery-app
Set up Environment Variables

Create a .env file in the root directory and add:

ini
Copy
Edit
MONGO_URI=your_mongodb_uri
SQL_DB_URI=your_sql_database_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
Install Server Dependencies

bash
Copy
Edit
cd server
npm install
Install Client Dependencies

bash
Copy
Edit
cd ../client
npm install
🧪 Run the App Locally
Start the Server (Backend)
bash
Copy
Edit
cd server
npm run dev
Start the Client (Frontend)
bash
Copy
Edit
cd client
npm start
Access the app at: http://localhost:3000

🧑‍💻 Admin Credentials
Use the following test credentials to access the admin dashboard:

makefile
Copy
Edit
Email: admin@grocery.com
Password: admin123
🗃️ Database
MongoDB: Stores products, users, carts, and orders.

SQL (MySQL/PostgreSQL): Optional — used for reporting, analytics, or relational datasets (joins, aggregate queries).

📦 Deployment
You can deploy this app using:

Frontend: Vercel, Netlify

Backend: Render, Railway, Heroku

Database: MongoDB Atlas, ElephantSQL

