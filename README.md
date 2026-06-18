# Imagify - AI Text to Image Generator

Imagify is a full-stack MERN application that converts text prompts into AI-generated images using the ClipDrop API. Users can generate images in seconds through a simple and responsive interface.

## Tech Stack

### Frontend

* React.js
* Vite
* Axios
* React Router
* CSS

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* ClipDrop API

## Features

* User Authentication (Signup/Login)
* AI Text-to-Image Generation
* Credit-Based Image Generation System
* Secure JWT Authentication
* Responsive User Interface
* MongoDB Database Integration

---

# How to Run the Project Locally

## Prerequisites

Make sure the following are installed:

* Node.js (v18 or later)
* MongoDB Atlas Account or Local MongoDB
* Git

## Step 1: Clone the Repository

```bash
git clone https://github.com/AkshadGiri/imagify.git
cd imagify
```

## Step 2: Install Dependencies

### Backend

```bash
cd server
npm install
```

### Frontend

```bash
cd ../client
npm install
```

## Step 3: Configure Environment Variables

Create a `.env` file inside the `server` folder.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIPDROP_API=your_clipdrop_api_key
```

Replace the values with your own credentials.

## Step 4: Start Backend Server

```bash
cd server
npm run server
```

or

```bash
npm start
```

The backend will run on:

```text
http://localhost:4000
```

## Step 5: Start Frontend

Open a new terminal:

```bash
cd client
npm run dev
```

The frontend will run on:

```text
http://localhost:5173
```

## Project Structure

```text
imagify/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── package.json
│   └── server.js
│
└── README.md
```

## Future Improvements

* Download Generated Images
* Image History
* Multiple AI Models
* Dark Mode
* Payment Gateway Integration

## Author

Akshad Giri

GitHub: https://github.com/AkshadGiri
