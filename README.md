# mystrapi
# Strapi Project

This project is built using Strapi, a headless CMS for building scalable and secure APIs.

---

## Prerequisites

Make sure the following are installed:

- Node.js (v18 LTS recommended)
- npm
- Git
- SQLite (default) or PostgreSQL / MySQL

---

## Clone the Repository

git clone https://github.com/chetan07k/REPO_NAME.git
cd REPO_NAME

---

## Environment Setup

Create a .env file in the root directory:

HOST=0.0.0.0
PORT=1337
APP_KEYS=key1,key2,key3,key4
API_TOKEN_SALT=your_api_token_salt
ADMIN_JWT_SECRET=your_admin_jwt_secret
JWT_SECRET=your_jwt_secret

Do not commit the .env file to GitHub.

---

## Setup on Linux

Update system packages:

sudo apt update

Install dependencies:

npm install

Run the project:

npm run develop

---

## Setup on Windows

Install Node.js from https://nodejs.org

Clone the repository using Git Bash or Command Prompt:

git clone https://github.com/chetan07k/REPO_NAME.git
cd REPO_NAME

Install dependencies:

npm install

Run the project:

npm run develop

---

## Access the Application

Admin Panel:
http://localhost:1337/admin

API Base URL:
http://localhost:1337/api

---

## Available Scripts

npm run develop  - Run Strapi in development mode  
npm run start    - Run Strapi in production mode  
npm run build    - Build the admin panel  

---

## Git Instructions

- Use your own GitHub account
- Create a branch with your name
- Raise a Pull Request to the main branch
- Do not push node_modules or .env file

---

## Author

Chetan Sonawane  
GitHub: https://github.com/chetan07k
