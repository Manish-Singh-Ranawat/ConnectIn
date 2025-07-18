# ConnectIn

**`` ConnectIn ``** is a full-stack professional networking platform that empowers users to build meaningful connections, share updates, and engage with a vibrant professional community. Designed with performance and user experience in mind, it leverages the powerful  **`` MERN stack (MongoDB, Express, React, Node.js) ``**, styled using  **`` Tailwind CSS ``**, and powered by  **`` TanStack React Query ``** for data fetching and caching.

Deployed on  **`` Render ``** with a production-ready build that serves both backend API and frontend from a single Node.js server.

### 🌐 [*View Live*](https://connectin-sncw.onrender.com/)

---

## 🚀 `` Features ``

- 🔐 **User Authentication** : Secure sign-up, login, and logout powered by JWT

- 🧑‍🤝‍🧑 **Professional Connections** : Send, accept, decline, and manage connection requests

- 📰 **Activity Feed** : Post updates, like content, and comment on discussions

- 🔔 **Real-Time Notifications** : Stay informed with in-app alerts for relevant interactions

- 🧠 **Smart Suggestions** : Personalized suggestions to grow your professional network

- 🌐 **User Profiles** : Dynamic profile pages with editable personal and professional info

- 📸 **Media Uploads** : Seamlessly upload profile pictures and post images via Cloudinary


---

## 🧱 `` Tech Stack ``

### Backend
- **Node.js** with **Express.js**
- **MongoDB** + **Mongoose**
- **JWT** for authentication
- **Cloudinary** for image uploads
- **bcryptjs**, **cookie-parser**, **cors**, **dotenv**

### Frontend
- **React.js**
- **Tailwind CSS**
- **React Router DOM**
- **TanStack React Query**
- **Axios, React Hot Toast, Lucide React, date-fns**

---

## 🌍 `` Deployment ``

The entire application is deployed on **Render** using a single **Web Service**.

- 🔧 **Backend (Express + API)** and **Frontend (React)** are bundled together.
- React is built into static files and served by Express from the `/frontend/dist` folder in production.

