# AIBuddy21

AIBuddy21 is a full-stack AI chat assistant web application powered by OpenAI.  
Built with **React**, **Node.js**, **Express**, and **MongoDB**.  
Features secure authentication (JWT, Google login), persistent chat history, and a friendly UI.

---

## ✨ Features

* Chat with AI (using OpenAI)
* Google login & signup
* Email/password login
* Forgot password option
* Save chat history
* Auto-save chat
* Delete account option
* Light & Dark modes
* Mobile responsive design

---

## 🛠️ Tech Stack

**Frontend:**

* Vite
* React.js
* SCSS
* Redux Toolkit

**Backend:**

* Node.js
* Express.js
* MongoDB
* JSON Web Token (JWT) for authentication

**Others:**

* OpenAI API
* Google Login
* JavaScript

---

## ✅ Prerequisites

Before you begin, make sure you have the following installed:

* [Node.js & npm](https://nodejs.org/)
* [MongoDB](https://www.mongodb.com/)
* [Git](https://git-scm.com/)
* An [OpenAI API key](https://openai.com/api/)

---

## 🔐 Environment Variables

### Backend (`/server/.env`)

Create a `.env` file inside the `server` folder with the following:

```
PORT=5000
MONGO_URL=your_mongodb_connection_string
SITE_URL=http://localhost:5173
JWT_PRIVATE_KEY=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
OPENAI_ORGANIZATION=your_openai_organization_id
MAIL_EMAIL=your_email@example.com
MAIL_SECRET=your_email_secret
```

### Frontend (`/client/.env.local`)

Create a `.env.local` file inside the `client` folder with:

```
VITE_CLIENT_ID=your_google_oauth_client_id
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone (https://github.com/soumyaarya/AIBuddy21)
```

---

### 2. Start the Backend

```bash
cd AIBuddy/server
npm install
npm start
```

---

### 3. Start the Frontend

```bash
cd AIBuddy/client
npm install
npm run dev
```

---

## 🌐 Access the App

Once both the frontend and backend are running, open your browser and go to:

```
http://localhost:5173
```

---

## 📌 Notes

* You need an OpenAI API key for the chat to work.
* Google login requires a valid OAuth Client ID (you can get it from the [Google Developer Console](https://console.cloud.google.com/)).
* For email features like "Forgot Password", you need to configure email credentials correctly.

---











