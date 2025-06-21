📚 Book Notes

A simple and powerful web app that allows users to add, update, and delete books, storing the data in a PostgreSQL database. Book cover images are automatically fetched using the Open Library API based on the ISBN.

🎥 Watch Demo on YouTube

🚀 Features

✅ Full CRUD operations (Create, Read, Update, Delete)

✅ PostgreSQL for robust data storage

✅ Integration with Open Library API for book covers

✅ Responsive front-end built using EJS templates

✅ Backend powered by Node.js and Express.js

📦 Prerequisites

Before running the project, ensure you have the following installed:

Node.js

PostgreSQL

Node packages:

pg

express

body-parser

nodemon (for development)

🛠️ Installation & Setup

1. Clone the Repository

git clone https://github.com/your-username/Book-Notes.git
cd Book-Notes

2. Install Dependencies

npm install

3. Configure PostgreSQL Database

Ensure PostgreSQL is running.

Create a new database (e.g., booknotes).

Execute the SQL schema provided in queries.sql to create the required tables.

4. Update DB Config

Edit the dbConfig object inside index.js:

const dbConfig = {
  user: 'your_db_user',
  host: 'localhost',
  database: 'booknotes',
  password: 'your_db_password',
  port: 5432
};

💻 Usage

Run the App

nodemon index.js

Then, open your browser and visit:

http://localhost:3000

You can now:

📘 Add books

✏️ Edit existing books

❌ Delete unwanted books

🧪 Development Workflow

Fork this repo to your GitHub account.

Clone your forked repo:

git clone https://github.com/your-username/Book-Notes.git

Create a new branch:

git checkout -b feature/your-feature-name

Make your changes.

Commit & push:

git add .
git commit -m "Your message"
git push origin feature/your-feature-name

Create a Pull Request with a meaningful description.

📁 Folder Structure

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

🤝 Contributing

We welcome contributions of all kinds!

Fork the repo and create a new branch.

Submit a well-described Pull Request (PR).

Wait for a review — we’ll get back to you ASAP!

📬 Contact

Feel free to raise issues for feedback, improvements, or questions.

Thank you for checking out Book Notes! ✨

