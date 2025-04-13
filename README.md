# 🛒 Full Stack E-Commerce Website



A complete e-commerce platform built with the MERN (MongoDB, Express, React, Node.js) stack. This application allows users to sign up, log in, browse products, and add items to the cart. Admins have access to a dedicated dashboard where they can manage products, orders, and users.

## 🚀 Features

- 🔐 User Authentication & Authorization (JWT)
- 🛒 Cart & Checkout System
- 📦 Order Management
- 📱 **Responsive Design** – Fully functional across devices and screen sizes.
- ⚡ **Fast and Smooth UI** – User-friendly interface for a seamless experience.

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Redux Toolkit
- Axios
- Bootstrap 

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT)

## 📸 Screenshots

### 🔐 Login Page
![SignUp Page](https://res.cloudinary.com/dfacldueh/image/upload/v1744533474/Screenshot_2025-04-13_140528_dg20dp.png)

### 🏠 Home Page
![Shopping Page](https://res.cloudinary.com/dfacldueh/image/upload/v1744533505/Screenshot_2025-04-13_140448_nkogco.png)


## 💼 Jobs Page
![Cart Page](https://res.cloudinary.com/dfacldueh/image/upload/v1744533546/Screenshot_2025-04-13_140547_gs2h9n.png)

## Installation & Setup
### Prerequisites:
- Node.js installed
- MongoDB (if using a local database)

### Clone the Repository
```bash
git clone https://github.com/KashishMahajan1203/full-stack-e-commerce-website.git
cd frontend
cd backend
```

### Backend Setup
```bash
cd backend
npm install
```
#### Configure Environment Variables
Create a `.env` file in the backend directory and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8080
```

#### Start Backend Server
```bash
npm start
```

### Frontend Setup
```bash
cd frontend
npm install
```

#### Start Frontend Server
```bash
npm start
```

## Usage
1. Open `http://localhost:8080` in your browser.
2. 2. Log in with registered credentials.

## API Routes
### Auth Routes:
- `POST /auth/login` - Authenticate user & return JWT
- `POST /auth/signup` - new user & return JWT
- 

### Deploying Backend on Render / Heroku
1. **Push Code to GitHub**
2. **Connect Repository to Hosting Service**
3. **Set Up Environment Variables in Hosting Dashboard**
4. **Deploy & Monitor Logs**


## 📞 Contact
For any queries, reach out via:
- **Email:** [kashishmahajan878@gmail.com]
- **LinkedIn:** [https://www.linkedin.com/in/kashish-mahajan-0591ba2b4/]
- **GitHub Issues:** [https://github.com/KashishMahajan1203]

---
_Developed with ❤️ by Kashish Mahajan


