# 📚 Book Notes

A simple and powerful web app that allows users to **add, update, and delete books**, storing the data in a **PostgreSQL** database. Book cover images are automatically fetched using the **Open Library API** based on the ISBN.


---

## 🌐 Live Demo

👉 [https://book-notes-main.onrender.com](https://book-notes-main.onrender.com)

---

## 🚀 Features

- ✅ Full **CRUD** operations (Create, Read, Update, Delete)
- ✅ **PostgreSQL** for robust data storage
- ✅ Integration with **Open Library API** for book covers
- ✅ Responsive front-end built using **EJS templates**
- ✅ Backend powered by **Node.js** and **Express.js**

---

## 📦 Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [PostgreSQL](https://www.postgresql.org/)
- Node packages:
  - `pg`
  - `express`
  - `body-parser`
  - `nodemon` (for development)

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Book-Notes.git
cd Book-Notes
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure PostgreSQL Database

- Ensure PostgreSQL is running.
- Create a new database (e.g., `booknotes`).
- Execute the SQL schema provided in [`queries.sql`](./queries.sql) to create the required tables.

### 4. Update DB Config

Edit the `dbConfig` object inside `index.js`:

```js
const dbConfig = {
  user: 'your_db_user',
  host: 'localhost',
  database: 'booknotes',
  password: 'your_db_password',
  port: 5432
};
```

---

## 💻 Usage

### Run the App

```bash
nodemon index.js
```

Then, open your browser and visit:

```
http://localhost:3000
```

You can now:
- 📘 Add books
- ✏️ Edit existing books
- ❌ Delete unwanted books

---

## 🧪 Development Workflow

1. **Fork** this repo to your GitHub account.
2. **Clone** your forked repo:
   ```bash
   git clone https://github.com/your-username/Book-Notes.git
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Make your changes.
5. Commit & push:
   ```bash
   git add .
   git commit -m "Your message"
   git push origin feature/your-feature-name
   ```
6. Create a **Pull Request** with a meaningful description.

---

## 📁 Folder Structure

```
Book-Notes/
├── public/
│   ├── css/
│   └── images/
├── views/
│   ├── index.ejs
│   └── ...
├── queries.sql
├── index.js
├── package.json
└── README.md
```

---


## 📬 Contact

Feel free to raise issues for feedback, improvements, or questions.

Thank you for checking out **Book Notes**! ✨
