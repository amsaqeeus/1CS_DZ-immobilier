# 🏠 1CS DZ-Immobilier

A modern full-stack real estate management platform developed to simplify property listing, management, and client interactions. The application enables users to browse, publish, update, and manage real estate listings while providing administrators with tools to efficiently manage platform content.

The project was developed using **Node.js** and **Express.js** for the backend and follows a RESTful architecture to ensure scalability and maintainability.

---

# 📌 Features

### 🏘️ Property Management
- Create new property listings
- Update existing listings
- Delete properties
- View detailed property information
- Support for apartments, villas, houses, land, and commercial properties

### 🖼️ Image Upload
- Upload multiple property images
- Secure image storage
- Image serving through the backend

### 👤 User Authentication
- User registration and login
- Password encryption using **bcrypt**
- Secure authentication using **JWT**

### 📦 REST API
- RESTful API architecture
- JSON request/response handling
- Structured routing for properties, users, and authentication

### ⚙️ Backend Configuration
- Environment variable support
- Configurable server settings
- Easy deployment configuration

---

# 🛠️ Technology Stack

## Backend
- Node.js
- Express.js

## Database
- MongoDB *(or SQL depending on deployment configuration)*

## Authentication
- JWT (JSON Web Token)
- bcrypt

## File Upload
- Multer
- Busboy

## Configuration
- `.env`
- `_config.yml`

---

# 📂 Project Structure

```text
1CS_DZ-immobilier-main/
│
├── Backend/
│   ├── images/                # Uploaded property images
│   ├── node_modules/          # Project dependencies
│   ├── package.json
│   ├── package-lock.json
│   ├── _config.yml
│   └── ...
│
├── .codegpt
├── .gitignore
└── README.md
```

---

# 🚀 Getting Started

## Prerequisites

Before running the project, make sure you have installed:

- Node.js (v14 or later)
- npm

---

## Installation

Clone the repository:

```bash
git clone https://github.com/amsaqeeus/1CS_DZ-immobilier.git

cd 1CS_DZ-immobilier-main/Backend
```

Install dependencies:

```bash
npm install
```

Configure the application:

Create or update your configuration files:

- `.env`
- `_config.yml`

Configure:

- Database connection
- Server port
- JWT secret
- Other environment variables

---

# ▶️ Running the Application

## Development Mode

```bash
npm run dev
```

or

```bash
npx nodemon
```

---

## Production Mode

```bash
npm start
```

---

# 📸 Image Uploads

Property images are uploaded using multipart form-data and stored inside:

```text
Backend/images/
```

Supported image formats include:

- PNG
- JPG
- JPEG

---

# 📡 API Overview

The backend exposes RESTful endpoints for:

- Authentication
- User Management
- Property Listings
- Image Uploads

Typical operations include:

- `GET` — Retrieve properties
- `POST` — Create new listings
- `PUT` — Update existing listings
- `DELETE` — Remove listings

---

# 🔒 Security

The application implements several security practices, including:

- Password hashing with **bcrypt**
- JWT-based authentication
- Environment variable protection
- Input validation
- Secure image upload handling

---

# 📈 Future Improvements

- Advanced property search and filtering
- Favorites and wishlist
- Interactive maps integration
- Property booking system
- Email notifications
- Admin dashboard
- Analytics and reporting

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature/YourFeature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/YourFeature
```

5. Open a Pull Request

---

# 📄 License

This project was developed for educational purposes as part of a university coursework project.

---
