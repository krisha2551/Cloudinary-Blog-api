# 📝 Blog API (Node.js + Express + MongoDB + Cloudinary)

A RESTful Blog API built using **Node.js**, **Express**, and **MongoDB**, with **Cloudinary** integration for image/video uploads.

---

## 🚀 Features

* Create Blog (with image/video upload)
* Get All Blogs
* Get Single Blog
* Update Blog
* Delete Blog
* Cloudinary media storage
* MongoDB integration

---

## 📁 Project Structure

```bash
BLOG PROJECT <br>
│ <br>
├── config/ <br>
│   ├── cloudinary.js <br>
│   └── db.js <br>
│ <br>
├── controllers/ <br>
│   └── blogController.js <br>
│ <br>
├── middleware/ <br>
│   ├── httpError.js <br>
│   └── upload.js <br>
│ <br>
├── model/ <br>
│   └── Blog.js <br>
│ <br>
├── routes/ <br>
│   └── blogRoutes.js <br>
│ <br>
├── .env <br>
├── app.js <br>
├── package.json <br>
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/blog-api.git
cd blog-api
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_uri

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## ▶️ Run Server

```bash
npm start
```

Server will run on:

```
http://localhost:5000
```

---

## 📡 API Endpoints

| Method | Endpoint            | Description     |
| ------ | ------------------- | --------------- |
| GET    | `/`                 | Check server    |
| POST   | `/blogs/add`        | Create blog     |
| GET    | `/blogs/allBlogs`   | Get all blogs   |
| GET    | `/blogs/:id`        | Get single blog |
| PATCH  | `/blogs/update/:id` | Update blog     |
| DELETE | `/blogs/delete/:id` | Delete blog     |

---

## 🧪 Testing

Use:

* Postman
* Thunder Client

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB (Mongoose)
* Cloudinary
* Multer

---


## 📸 Project Screenshots

### 🟢 Server Running

![Server Running](./screenshots/server.png)

<br>

### 🟡 Create Blog API

![Create Blog](./screenshots/create-blog.png)

<br>

### 🔵 Get All Blogs

![Get All Blogs](./screenshots/get-all-blogs.png)

<br>

### 🟣 Get Single Blog

![Get Single Blog](./screenshots/get-single-blog.png)

<br>

### 🟠 Update Blog

![Update Blog](./screenshots/update-blog.png)

<br>

### 🔴 Delete Blog

![Delete Blog](./screenshots/delete-blog.png)

<br>

### ☁️ Cloudinary Storage

![Cloudinary](./screenshots/cloudinary.png)

<br>

### 🗄️ MongoDB Database

![MongoDB](./screenshots/mongodb.png)




