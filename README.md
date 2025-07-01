<h1 align="center">📝 QuickBlog – AI-Powered Blogging Platform</h1>
<p align="center">
  <b>A full-stack blog application with AI-generated content, rich text editor, image support, and admin moderation</b>
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Database-MongoDB-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Gemini%20API-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Auth-JWT-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deployed%20With-Docker-blueviolet?style=for-the-badge" />
</p>

---

## 🚀 Overview

<div align="justify">

<b>QuickBlog</b> is a modern, full-stack blog platform where users can write and explore content-rich blogs. It features AI-generated blog posts using Gemini API, rich-text editing, image uploads via ImageKit, and secure JWT-based authentication. An admin dashboard allows blog and comment moderation with publish/unpublish functionality.

</div>

---

## 🛠 Tech Stack

<table>
  <tr>
    <td><b>Frontend</b></td>
    <td>React.js, Tailwind CSS</td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>Node.js, Express.js</td>
  </tr>
  <tr>
    <td><b>Authentication</b></td>
    <td>JWT (JSON Web Tokens)</td>
  </tr>
  <tr>
    <td><b>Database</b></td>
    <td>MongoDB</td>
  </tr>
  <tr>
    <td><b>AI Blog Generation</b></td>
    <td>Gemini API</td>
  </tr>
  <tr>
    <td><b>Image Uploads</b></td>
    <td>ImageKit</td>
  </tr>
  <tr>
    <td><b>Deployment</b></td>
    <td>Docker</td>
  </tr>
</table>

---

## 💡 Features

<ul>
  <li><b>🧠 AI-Powered Blogging:</b> Users can generate blog posts using Gemini AI with just a prompt.</li>
  <li><b>📝 Rich Text Editing:</b> Quill.js-based WYSIWYG editor for content formatting.</li>
  <li><b>🖼 Image Support:</b> Upload and embed images in blogs using ImageKit.</li>
  <li><b>👥 User Authentication:</b> Secure login and registration using JWT.</li>
  <li><b>🛠 Admin Controls:</b> Publish/unpublish blogs and moderate comments with full control.</li>
  <li><b>📦 Dockerized:</b> Easily deployable with Docker for local and cloud hosting.</li>
</ul>

---



---

## 🧪 Getting Started

### ✅ Prerequisites

- Node.js and npm
- Docker (optional for deployment)
- MongoDB connection string
- Gemini API key
- ImageKit account credentials

### 📦 Installation

bash
git clone https://github.com/your-username/quickblog.git
cd quickblog
npm install



## 🔑 Set Environment Variables
### Create a .env file in the root and configure:

MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_endpoint
GEMINI_API_KEY=your_key

## ▶ Run Locally

bash
npm run dev
