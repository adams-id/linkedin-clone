# ✨ LinkedIn Clone

A full-stack social networking platform inspired by LinkedIn. Built with modern technologies like React, Node.js, and MongoDB — this clone offers rich user features like authentication, posts, profile management, payments, and real-time social interactions.

![Demo Screenshot](/frontend/public/screenshot-for-readme.png)

---

## 🚀 Project Overview

This LinkedIn Clone replicates key features of a professional networking site, including user profiles, post creation, likes and comments, connection requests, payment integration, and a personalized news feed. It's designed for scalability, responsiveness, and a smooth user experience.

## 📌 Live Demo

🔗 View the live app here [here](https://linkedin-clone-gylh.onrender.com)

> **Note:** The app may take up to a minute to load on first visit.  
> This is due to hosting on free Render services, which spin down inactive instances.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS, DaisyUI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Auth & Security:** JWT, bcrypt, secure cookies
- **Email Service:** Mailtrap
- **Cloud Storage:** Cloudinary

---

## ✨ Core Features

- 🔐 Secure JWT Authentication
- 💬 Create and Share Posts with Images
- 🖼️ Upload Profile Pictures
- 🤝 Send, Accept, and Reject Connection Requests
- 👍 Like and Comment on Posts
- 👥 Discover Suggested Users
- 📰 Smart News Feed Algorithm
- 📩 Welcome Emails on Signup
- 🛡️ Strong Data Validation and Protection
- 🎨 Responsive Design with Tailwind and DaisyUI

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/adams-id/netflix-clone.git
cd netflix-clone
```

### 2. Install Dependencies

In the root directory, run

```bash
npm install
```

Then install frontend dependencies

```bash
cd frontend
npm install
cd ..
```

## ⚙️ Environment Configuration

Create a `.env` file in the project root and add:

```bash
PORT=5000
MONGO_URI=<your_mongo_uri>

JWT_SECRET=<yourverystrongsecret>

NODE_ENV=development

MAILTRAP_TOKEN=<your_mailtrap_token>
EMAIL_FROM=mailtrap@demomailtrap.com
EMAIL_FROM_NAME=<Your_Name>

CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>

CLIENT_URL=http://localhost:5173
```

---

## 🚀 Running the App

### 1. Build the Frontend

If you’re serving the frontend through your Node server:

```bash
cd frontend
npm run build
cd ..
```

This builds the static frontend files for production.

### 2. Start the Backend Server

From the project root:

```bash
npm start
```

The backend app will be live at http://localhost:5000

---

### 🧠 Future Improvements

- Real-time messaging and chat
- User analytics and activity tracking
- Infinite scroll and pagination
- Admin dashboard for managing users and content
- Improved accessibility and performance optimizations
- Multi-language support

---

### 🙌 Acknowledgements

- **[Mailtrap](https://mailtrap.io/)** — for email testing and delivery sandbox.
- **[Cloudinary](https://cloudinary.com/)** — for secure and scalable media hosting.
- **LinkedIn** — for UI/UX inspiration and feature reference.
