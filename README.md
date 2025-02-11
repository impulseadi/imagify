# Imagify - AI-Powered Text-to-Image Generator

## 🌟 Overview
Imagify is a **Full Stack AI SaaS Application** that allows users to generate AI-powered images from text prompts. It features a **credit-based system** for image generation and includes **user authentication** for secure access.

## 🛠 Tech Stack
- **Frontend**: React, Vite, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI API**: Clipdrop API
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Frontend on Netlify, Backend on Render

## 🎯 Features
- 🌐 **AI-Powered Image Generation**: Convert text prompts into AI-generated images.
- 🔐 **User Authentication**: Secure account creation and login.
- 💰 **Credit System**: Users need credits to generate images.
- 📦 **RESTful API**: Backend API built with Express.js.
- ⚡ **Fast UI**: Developed using React and TailwindCSS.
- 🚀 **Deployment**: Hosted on Netlify (frontend) and Render (backend).

## 📸 Screenshots
![Screenshot 2025-02-11 185017](https://github.com/user-attachments/assets/e083f3eb-83b9-4ca1-a847-6db646de49cb)


## 🚀 Getting Started
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/impulseadi/imagify.git
cd imagify
```
### 2️⃣ Install Dependencies
#### Backend
```sh
cd server
npm install
```
#### Frontend
```sh
cd client
npm install
```
### 3️⃣ Set Up Environment Variables
Create a `.env` file in the **server** directory and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIPDROP_API_KEY=your_api_key
```
### 4️⃣ Start the Application
#### Backend
```sh
cd server
npm start
```
#### Frontend
```sh
cd client
npm run dev
```

## 📡 Deployment
- **Frontend**: Deployed on Netlify -> [Live Link](your-netlify-link)
- **Backend**: Deployed on Render -> [Live Link](your-render-link)

## 💡 Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## 📜 License
This project is open-source and available under the MIT License.
