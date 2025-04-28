# MERN Stack snapCart E-Commerce Platform

An end-to-end **MERN Stack** based E-Commerce web application with Admin Panel, User Authentication, Cart Management, and Order Processing functionalities.

---

## ✨ Technologies and Tools Used

### Frontend
- React.js (Functional Components)
- Redux Toolkit
- Axios
- React Router DOM
- Tailwind CSS (or Bootstrap)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- bcryptjs (Password Hashing)
- dotenv (Environment Configuration)
- multer + cloudinary (for image uploads)
- cors (Cross-Origin Resource Sharing)

---

## 💡 Key Features

- User Registration and Login
- Authentication & Authorization using JWT
- Admin Dashboard (Manage Products, Users, Orders)
- Upload Product Images (via Cloudinary)
- Add to Cart / Remove from Cart
- Place Orders and Manage Order History
- API Security with Middlewares
- Fully Responsive UI

---

## 📦 Installation and Setup Instructions

```bash
# Clone the project
git clone https://github.com/yourusername/mernProjectEcommerce.git

# Navigate to backend folder and install dependencies
cd mernProjectEcommerce-master/backend
npm install

# Navigate to frontend folder and install dependencies
cd ../frontend
npm install
```

---

## 🌐 Environment Variables

Create a `.env` file inside the `/backend` directory and configure the following variables:

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PORT=5000
```

---

## ▶️ Running the App

### Development Mode

```bash
# Start Backend Server
cd backend
npm run dev

# Start Frontend Server
cd frontend
npm start
```

### Production Mode

```bash
# Build Frontend
cd frontend
npm run build

# Serve Frontend via Backend Server
cd ../backend
npm start
```

---

## 📂 Project Folder Structure

```bash
mernProjectEcommerce/
  ├── backend/
  │    ├── controllers/
  │    ├── middleware/
  │    ├── models/
  │    ├── routes/
  │    └── server.js
  └── frontend/
       ├── src/
            ├── components/
            ├── pages/
            ├── redux/
            └── App.js
```

---

## 📷 Screenshots
```markdown
![Home Page] Assets/Screenshot (560).png
![Product Details] https://drive.google.com/file/d/1_yzSlAnAif68Fjt0UboFVGXhGtx3CvmI/view?usp=sharing
![Admin Dashboard] https://drive.google.com/file/d/1otSxOvYvpv8lkiC21v8N2Nylts58RvlM/view?usp=sharing
```

---

## 📞 Contact

- **Author:** deepak kumar
- **GitHub:** https://github.com/deepakmehta7527/SnapCart-Ecommerce
- **LinkedIn:** https://www.linkedin.com/in/deepakkumar162/
