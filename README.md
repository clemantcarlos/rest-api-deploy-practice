<div align="center">

🚀 REST API Deploy Practice — API Deployment Practice

A practice project for deploying REST APIs with MongoDB and MySQL support

[!JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[!Node.js](https://nodejs.org/)
[!Express](https://expressjs.com/)
[!MongoDB](https://www.mongodb.com/)
[!MySQL](https://www.mysql.com/)
[!Zod](https://zod.dev/)
[!License](LICENSE)

</div>

> 📚 Learning Project — This project was built to practice building and deploying REST APIs with multiple database backends.

***

## 📋 About the Project

REST API Deploy Practice is a comprehensive practice project for building and deploying REST APIs. It supports both MongoDB and MySQL backends, featuring a complete MVC-like structure with controllers, routes, models, middlewares, schemas (Zod), and utilities. Includes sample movie data for testing.

## ✨ Features

| Feature | Description |
|---------|-------------|
| Dual Database | MongoDB and MySQL support |
| MVC Architecture | Models, Views (routes), Controllers |
| Zod Validation | Request data validation |
| CORS Support | Configurable cross-origin resource sharing |
| HTTP Client File | API.http for testing endpoints |
| ES Modules | Modern JavaScript module system |
| Sample Data | movies.json for testing |

## 🏗️ Architecture

```
rest-api-deploy-practice/
├── app.js                  # Express app configuration
├── server-with-local.js    # MongoDB server entry point
├── server-with-mysql.js    # MySQL server entry point
├── utils.js                # Utility functions
├── controllers/            # Request handlers
├── middlewares/             # Custom middlewares (CORS, etc.)
├── models/                 # Data models
├── routes/                 # API routes
├── schemas/                # Zod validation schemas
├── movies.json             # Sample data
├── api.http                # HTTP client for testing
└── package.json
```

## 🛠️ Tech Stack

- **Runtime:** Node.js with ES Modules
- **Framework:** Express 4.18
- **Databases:** MongoDB 6 + MySQL (mysql2)
- **Validation:** Zod 3.22
- **CORS:** cors middleware
- **Linting:** Standard JS

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18
- MongoDB (for local mode)
- MySQL (for MySQL mode)

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/rest-api-deploy-practice.git
cd rest-api-deploy-practice

# Install dependencies
npm install
```

### Running the Application

```bash
# With MongoDB (local)
npm run start:local

# With MySQL
npm run start:mysql
```

## 📦 Available Commands

| Command | Description |
|---------|-------------|
| `npm run start:local` | Start with MongoDB |
| `npm run start:mysql` | Start with MySQL |

## 📄 License

This project is licensed under the MIT License. See LICENSE for more details.

***

## 👤 Author

**Carlos Clemant**

[!GitHub](https://github.com/your-username)
[!LinkedIn](https://linkedin.com/in/your-profile)

***
<div align="center">

If you found this project helpful, give it a ⭐!

</div>
