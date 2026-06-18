#  FastAPI Blog API

A Blog API built with FastAPI, PostgreSQL, SQLAlchemy, and JWT Authentication.

## 📸 Screenshots

### Swagger Documentation
<p align="center">
  <img src="https://github.com/user-attachments/assets/285e5324-f6db-4b4a-b388-e9ec6c3c39e8" width="800">
</p>

### JWT Authentication
<p align="center">
  <img src="https://github.com/user-attachments/assets/5bf387e6-621b-4c19-9edc-dd98b1628616" width="45%">
  <img src="https://github.com/user-attachments/assets/6b6693ae-3f90-45b8-935f-0eaf6bfdb3d9" width="45%">
</p>

### PostgreSQL Database
<p align="center">
  <img src="https://github.com/user-attachments/assets/bccd9b1c-5cae-4bf4-a207-02a509842d77" width="800">
</p>

## ✨ Features

* Create, Read, Update, and Delete Blogs (CRUD)
* JWT Authentication
* PostgreSQL Database Integration
* SQLAlchemy ORM
* Pagination Support
* Search Functionality
* Environment Variable Configuration
* Render Deployment

## 🛠️ Tech Stack

* FastAPI
* PostgreSQL
* SQLAlchemy
* Pydantic
* JWT (python-jose)
* Passlib (Password Hashing)
* Uvicorn

## 📂 Project Structure

```text
blog-api/
│
├── main.py
├── auth.py
├── database.py
├── models.py
├── schemas.py
├── requirements.txt
├── .env
└── .gitignore
```

## ⚙️ Installation

```bash
git clone <repository-url>
cd fastapi-blog-api

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt
```

## ▶️ Run Locally

```bash
uvicorn main:app --reload
```

Open:

```text
http://127.0.0.1:8000/docs
```

## 🔐 Authentication

This project uses JWT-based authentication to protect blog creation, update, and deletion endpoints.

## 🌐 Deployment

Deployed using Render with PostgreSQL.\

**Live Demo**

API Docs: https://fastapi-blog-api-xrp3.onrender.com/docs

## 📚 What I Learned

* Building REST APIs with FastAPI
* Database Integration using PostgreSQL
* SQLAlchemy ORM
* JWT Authentication
* Environment Variables (.env)
* Git & GitHub Workflow
* Cloud Deployment with Render

```
```
