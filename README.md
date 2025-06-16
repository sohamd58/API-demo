
# 🔗 Full-Stack Product API Demo (MERN + Vite + Zustand)

A clean and minimal full-stack product catalog application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js), **Vite** for blazing-fast frontend performance, and **Zustand** for lightweight state management. Perfect for demonstrating REST API integration, CRUD operations, and a modern development workflow.

---

## 📌 Project Highlights

- 🔗 **Full-Stack MERN**: Seamless backend and frontend integration
- 📦 **CRUD Functionality**: Create, read, update, delete products
- ⚡ **Vite-Powered UI**: Ultra-fast dev experience with React + Vite
- 📊 **State Management**: Zustand store for predictable state flow
- 🧱 **RESTful API**: Modular backend with route/controller separation
- 💅 **Modern Design**: Clean, responsive UI with component-based architecture
- 🎯 **Beginner-Friendly**: Great reference for understanding API consumption

---

## 📁 Folder Structure

```text
API-demo-main/
├── backend/                  # Node/Express backend
│   ├── config/               # MongoDB connection config
│   │   └── db.js
│   ├── controllers/          # Controller logic for product routes
│   │   └── product.controller.js
│   ├── models/               # Mongoose product schema
│   │   └── product.model.js
│   ├── routes/               # Product API routes
│   │   └── product.route.js
│   └── server.js             # Main server entry
│
├── frontend/                 # Vite + React frontend
│   ├── public/               # Static files and assets
│   │   ├── vite.svg
│   │   └── screenshot-for-readme.png
│   ├── src/
│   │   ├── components/       # Navbar and ProductCard components
│   │   ├── pages/            # HomePage and CreatePage
│   │   ├── store/            # Zustand store for product state
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
├── README.md
├── package.json
├── package-lock.json
````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sohamd58/API-demo.git
cd API-demo
```

### 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3. Environment Variables

Create a `.env` file inside `backend/` and add:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4. Run the Application

Use two terminals to start backend and frontend:

```bash
# Terminal 1: Backend
cd backend
npm run dev
```

```bash
# Terminal 2: Frontend
cd frontend
npm run dev
```

---

## 🧩 Tech Stack

* **Frontend**: React, Vite, Zustand
* **Backend**: Node.js, Express.js, MongoDB, Mongoose
* **API Pattern**: RESTful, MVC structured
* **Dev Tools**: dotenv, nodemon, axios

---

## 📣 Contributing

Feel free to fork the repo, open issues, or submit pull requests. Contributions are highly appreciated!

---

:mortar_board: Built with help from [Codesistency](https://www.youtube.com/@codesistency) 
⭐ **Star this repo** if it helped you!
📫 **Connect** on [LinkedIn](https://www.linkedin.com/in/soham-d1758) or GitHub!

---

