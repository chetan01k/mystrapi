<<<<<<< HEAD
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

git clone https://github.com/chetan01k/mystrapi.git
cd mystrapi

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
=======
# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project including [Strapi Cloud](https://cloud.strapi.io). Browse the [deployment section of the documentation](https://docs.strapi.io/dev-docs/deployment) to find the best solution for your use case.

```
yarn strapi deploy
```

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
>>>>>>> 508de90 (Initial Strapi setup)
