# 🌐 Social Media API - Node.js

A modern and scalable RESTful Social Media API built with **Node.js**, **Express.js**, and **MongoDB**.  
This backend project provides core social media functionalities including authentication, posts, comments, likes, follow systems, and user management.

---

# 🚀 Features

- 🔐 JWT Authentication & Authorization
- 👤 User Registration & Login
- 📝 Create, Update, and Delete Posts
- ❤️ Like & Unlike Posts
- 💬 Comment System
- 👥 Follow & Unfollow Users
- 🖼 User Profile Management
- 📸 Media Upload Support
- 🔎 Search Users & Posts
- 🛡 Role-Based Access Control
- ⚡ RESTful API Architecture
- 📁 Clean Folder Structure
- 🔒 Secure Password Hashing
- 🌍 Environment Variables Support
- 🚨 Error Handling Middleware

---

# 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- dotenv

Modern social media APIs commonly use REST architecture with JWT authentication for scalable backend systems. :contentReference[oaicite:0]{index=0}

---

# 📂 Project Structure

```bash
Social-Media-API-Nodejs/
│
├── controllers/
├── routes/
├── models/
├── middlewares/
├── utils/
├── config/
├── uploads/
├── app.js
├── package.json
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the repository

```bash
git clone https://github.com/MErfanPld/Social-Media-API-Nodejs.git
```

## 2. Navigate to the project directory

```bash
cd Social-Media-API-Nodejs
```

## 3. Install dependencies

```bash
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

# ▶️ Run the Project

```bash
npm run dev
```

---

# 🔐 Authentication

This API uses **JWT Authentication**.

Include your token in request headers:

```http
Authorization: Bearer your_token
```

JWT-based authentication is widely used in REST APIs for secure access control. :contentReference[oaicite:1]{index=1}

---

# 📌 API Endpoints

## Auth

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login user |
| GET | /api/auth/profile | Get user profile |

---

## Users

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/users | Get all users |
| GET | /api/users/:id | Get single user |
| PUT | /api/users/:id | Update profile |
| DELETE | /api/users/:id | Delete account |

---

## Posts

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/posts | Get all posts |
| POST | /api/posts | Create post |
| PUT | /api/posts/:id | Update post |
| DELETE | /api/posts/:id | Delete post |

---

## Comments

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/comments | Add comment |
| DELETE | /api/comments/:id | Delete comment |

---

## Likes

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/posts/:id/like | Like post |
| POST | /api/posts/:id/unlike | Unlike post |

---

## Follow System

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/users/:id/follow | Follow user |
| POST | /api/users/:id/unfollow | Unfollow user |

---

# 🧪 Example Request

## Register User

```http
POST /api/auth/register
```

```json
{
  "username": "erfan",
  "email": "erfan@example.com",
  "password": "123456"
}
```

---

# 📸 Future Improvements

- Real-time Chat System
- WebSocket Support
- Notifications System
- Story Feature
- Reels / Short Videos
- AI Content Moderation
- Redis Caching
- Docker Support
- Swagger Documentation
- Unit & Integration Testing
- CI/CD Pipeline

Real-time chat and notification systems are common upcoming features in modern social media platforms. :contentReference[oaicite:2]{index=2}

---

# 🌐 Deployment

You can deploy this project using:

- Render
- Railway
- VPS
- Docker

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed by [MErfanPld](https://github.com/MErfanPld)

If you like this project, give it a ⭐ on GitHub.
