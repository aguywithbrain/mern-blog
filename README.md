# 🚀 MERN Blog - Full Stack Web App with Admin Dashboard

<div align="center">
  <img src="https://your-blog-logo-url.png" alt="Blog Logo" width="200">
</div>

## Overview

Welcome to our stylish MERN Blog - a full-stack web application that combines the power of MongoDB, Express.js, React, and Node.js. Elevating the user experience, we've integrated Redux for state management and adorned the interface with Tailwind CSS and the elegant Flowbite UI library. The crown jewel of our offering is the seamlessly integrated admin dashboard, empowering you to effortlessly manage blog posts and user activity.

## Features

- **User Authentication:** 🔒 Securely register, log in, and log out.
- **Blog Posts:** ✍️ Create, read, update, and delete blog posts.
- **Comment System:** 💬 Engage with users through a robust commenting system.
- **Admin Dashboard:**
  - Intuitive management of blog posts.
  - Moderation of user comments with finesse.
- **Responsive Design:** 📱 Ensures a delightful experience across devices.

## Technologies Used

- **Frontend:**
  - React
  - Redux
  - Tailwind CSS
  - Flowbite UI library

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose

## Getting Started

### Prerequisites

- Node.js installed on your machine
- MongoDB installed and running locally or a MongoDB Atlas account

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/mern-blog.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd mern-blog
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Define the following variables:

     ```env
     MONGO_URI=your_mongo_connection_string
     JWT_SECRET=your_jwt_secret
     ```

5. **Start the application:**

   ```bash
   npm start
   ```

6. **Open your browser and go to** `http://localhost:3000` **to view the application.**

## Admin Dashboard

To access the admin dashboard, log in with admin credentials.

- **Admin Credentials:**
  - Username: admin
  - Password: admin123

## Folder Structure

- **client:** Contains the React frontend code.
- **server:** Houses the Express.js backend code.
- **models:** MongoDB schema models using Mongoose.
- **routes:** Express.js route handlers.
- **config:** Configuration files for the server.

## Contributing

Contributions are welcome! Please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the creators of the MERN stack, Tailwind CSS, and Flowbite UI library.
- Inspiration from various blog platforms for feature ideas.
