# 🔐 Secrets

A simple web application built with **Node.js**, **Express.js**, **MongoDB**, **Passport.js**, and **EJS** where users can register, log in (using email/password or Google OAuth), and anonymously share secrets with others.

## Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* Passport.js
* EJS
* Bootstrap

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AnanyaParida07/Secrets.git
cd Secrets
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start MongoDB

Make sure MongoDB is running locally.

### 4. Configure Google OAuth (Optional)

Create a `.env` file in the project root:

```env
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
```

> If you don't configure Google OAuth, simply use the email/password registration and login instead.

### 5. Run the application

```bash
node app.js
```

Open your browser and visit:

```
http://localhost:3000
```
