# 🏠 StayNest – Central Hub for Discovering Places to Stay

A user-friendly full-stack web application that allows users to explore, list, and review accommodation options. Built with the **Node.js + Express.js + MongoDB** stack and styled using **EJS**, StayNest enables intuitive interactions for travelers and hosts alike.

---

## 🚀 Motivation Behind the Idea

### 📌 The Need for Accommodation Listing Platforms
Modern travelers rely on platforms to discover and compare stay options before planning their trip.

### 📌 Inspired by Practical Platforms
Inspired by platforms that enable user-generated listings and reviews, StayNest aims to simplify the process of posting, browsing, and managing accommodations.

### 📌 Project Goals
- Provide a centralized and clean platform to **list and explore stays**  
- Enable users to **manage their own listings**  
- Allow logged-in users to **review listings**

### 🎯 Learning Experience
- Strengthened skills in backend development with **Node.js & Express.js**  
- Worked with **MongoDB** for data modeling and queries  
- Used **EJS templating** to build modular and responsive UIs  

---

## 🎓 Features

### 🔐 Authentication
- Secure sign-up and login system using sessions

### 🏘️ Listing Management
- Add new accommodation listings  
- Edit or delete your own listings  

### 📝 Review System
- Leave reviews on other users' listings  
- Delete your own reviews

### 🌍 Explore Listings
- Discover all available places to stay  
- Clean interface with logical routing

### ⚠️ Flash & Error Handling
- Flash messaging for actions like login, logout, create, and delete  
- Custom error pages for route exceptions

---

## 👥 User Roles

- **Guest**:
  - View listings and reviews.
    
- **Authenticated User**:
  - Create/Edit/Delete listings.
  - Write/Delete reviews on listings.

--- 


## 🌐 UI Preview

- 🔐 **Login/Signup Page**  
  Secure access to listing and review functionality
  
  <img width="1920" height="920" alt="image" src="https://github.com/user-attachments/assets/4bd3e899-c9ca-488f-9e90-915afb83eafb" />

  <img width="1919" height="918" alt="image" src="https://github.com/user-attachments/assets/c7422585-14db-47b9-b9e5-a6f095beb29c" />

- 🏘️ **Listing Pages**  
  Explore listings, view details, add your own

  <img width="1920" height="916" alt="image" src="https://github.com/user-attachments/assets/3c6af0bf-cbcd-4f05-ac01-4425ce65bd16" />
  
  <img width="1895" height="919" alt="image" src="https://github.com/user-attachments/assets/b9e469b6-70cc-4266-916e-9fef50def217" />

- 📝 **Review Section**  
  See what others say, and share your own thoughts

  <img width="1893" height="913" alt="image" src="https://github.com/user-attachments/assets/96857feb-6168-4577-abb3-61f7b6bb2a04" />

- ⚙️ **Edit/Delete Functionality**  
  Manage your own listings with ease

  <img width="1902" height="910" alt="image" src="https://github.com/user-attachments/assets/bf4dab0a-a55f-490a-a506-d3dfd5f59d41" />

- 📢 **Flash Messages**  
  Get immediate feedback on your actions

  <img width="1895" height="918" alt="image" src="https://github.com/user-attachments/assets/5a2a45ca-7736-4a29-8d50-5beb40ca4474" />

  <img width="1896" height="915" alt="image" src="https://github.com/user-attachments/assets/6ccd10c8-808a-40d0-8745-f82f825910d1" />

---

## 📊 Tech Stack

### 🔹 Frontend
- EJS (Embedded JavaScript Templates)  
- HTML, CSS, JavaScript  

### 🔹 Backend
- Node.js  
- Express.js  

### 🔹 Database
- MongoDB with Mongoose  

### 🔹 Other Tools
- **Passport** for authentication (using `passport-local` strategy)  
- **Express-session** for managing user sessions  
- **Joi** for request data validation  
- **Connect-flash** for flash messaging  
- **Cloudinary** for image storage and delivery  

<!-- 
---
## 📁 Project Structure

```
StayNest/
│
├── controllers/ # Route logic for listings, reviews, users
│ ├── listings.js
│ ├── reviews.js
│ └── users.js
│
├── init/ # Database seed data
│ └── data.js
│
├── models/ # Mongoose schemas
│ ├── listing.js
│ ├── review.js
│ └── user.js
│
├── public/ # Static assets
│ ├── css/
│ │ ├── style.css
│ │ └── rating.css
│ └── js/
│ └── script.js
│
├── routes/ # Express routes
│ ├── listing.js
│ ├── review.js
│ └── user.js
│
├── utils/ # Custom error handling and wrappers
│ ├── ExpressError.js
│ └── wrapAsync.js
│
├── views/ # EJS templates
│ ├── includes/ # Navbar, footer, flash messages
│ │ ├── flash.ejs
│ │ ├── footer.ejs
│ │ └── navbar.ejs
│ ├── layouts/
│ │ └── boilerplate.ejs
│ ├── listings/ # Views for listings
│ │ ├── index.ejs
│ │ ├── new.ejs
│ │ ├── edit.ejs
│ │ ├── show.ejs
│ │ └── search.ejs
│ └── users/ # Auth-related views
│ ├── login.ejs
│ ├── signup.ejs
│ └── error.ejs
│
├── .env # Environment variables
├── .gitignore
├── app.js # Entry point
├── cloudConfig.js # (Optional) Cloudinary config
├── middleware.js # Middleware for auth & validation
├── schema.js # Joi validation schemas
├── package.json
├── package-lock.json
└── README.md
```
-->
