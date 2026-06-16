# 🏡 Wanderlust

An Airbnb-inspired full-stack web application that allows users to discover, create, manage, and review accommodation listings. Wanderlust provides a seamless booking-style experience with secure authentication, listing management, image uploads, and a modern responsive user interface.

🌐 **Live Demo:** https://wanderlust-web-site-2.onrender.com

---

## ✨ Features

### 🔐 Authentication & Authorization

* User Registration (Sign Up)
* User Login & Logout
* Secure Session Management
* Password Authentication using Passport.js
* Protected Routes
* Authorization for Listing Owners
* Authorization for Review Authors

### 🏠 Listing Management

* Create New Listings
* Edit Existing Listings
* Delete Listings
* View Listing Details
* Upload Property Images

### ⭐ Reviews & Ratings

* Add Reviews
* Delete Reviews
* Rating System
* User Feedback Management

### ☁️ Cloud Image Storage

* Cloudinary Integration
* Image Upload & Management
* Optimized Media Storage

### 📱 Responsive Design

* Mobile-Friendly Interface
* Clean and Modern UI
* Bootstrap-Based Components

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript
* EJS

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

### Authentication & Security

* Passport.js
* Passport Local Strategy
* Express Session
* Connect Flash

### Cloud Services

* Cloudinary
* Multer
* Multer-Storage-Cloudinary

### Validation & Utilities

* Joi
* Method Override
* Dotenv

---

## 📸 Screenshots

### 🏠 Home Page

Airbnb-inspired homepage featuring destination search, category filters, and responsive navigation.

---

### 👤 Sign Up Page

Users can create an account securely through the registration form.

---

### 🔐 Login Page

Registered users can securely log in and access platform features.

log in page---

## 📂 Project Structure

```bash
wanderlust/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── middleware/
├── utils/
├── cloudConfig.js
├── schema.js
├── app.js
├── package.json
└── README.md

🗄️ Database Models
```

### User Model

```javascript
{
  username: String,
  email: String,
  password: String
}
```

### Listing Model

```javascript
{
  title: String,
  description: String,
  image: Object,
  price: Number,
  location: String,
  country: String,
  owner: ObjectId
}
```

### Review Model

```javascript
{
  comment: String,
  rating: Number,
  author: ObjectId
}
```

---

## 🔒 Security Features

* Passport.js Authentication
* Session-Based Authentication
* Route Protection
* Authorization Middleware
* Server-Side Validation using Joi
* Error Handling Middleware
* Flash Messages for User Feedback

---

## 🚀 Future Enhancements

* Booking Functionality
* Interactive Maps Integration
* Search & Filtering System
* Wishlist Feature
* User Profile Dashboard
* Payment Gateway Integration
* Real-Time Notifications
* Email Verification
* Password Reset Functionality

---

## 📚 Learning Outcomes

This project helped me gain practical experience in:

* Full-Stack Web Development
* RESTful APIs
* MVC Architecture
* Authentication & Authorization
* MongoDB Database Design
* Cloudinary Integration
* Express Middleware
* Session Management
* Error Handling
* Git & GitHub Workflow
* Deployment using Render

---

## 🚀 Deployment

### Live Application

https://wanderlust-web-site-2.onrender.com

### Deployment Platform

* Render (Application Hosting)
* MongoDB Atlas (Database)
* Cloudinary (Image Storage)

GitHub: https://github.com/your-github-username

---

## 🙏 Acknowledgements

* Inspired by Airbnb
* MongoDB Documentation
* Express.js Documentation
* Passport.js Documentation
* Cloudinary Documentation
* Bootstrap Documentation

---

⭐ If you found this project helpful, please consider giving it a star on GitHub!
