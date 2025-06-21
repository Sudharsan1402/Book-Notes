from pathlib import Path

# Markdown content from the previously created README
readme_content = """
# 📚 Book Notes

A simple and powerful web app that allows users to **add, update, and delete books**, storing the data in a **PostgreSQL** database. Book cover images are automatically fetched using the **Open Library API** based on the ISBN.

🎥 [Watch Demo on YouTube](https://www.youtube.com/watch?v=cqHv4No8WMg)

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
