Fullstack Chat App

A modern real-time chat application built with the **MERN stack** (MongoDB, Express, React, Node.js) and **Socket.io**.  
Users can sign up, log in, and chat instantly in a sleek, responsive interface.

Features
- User authentication (Signup & Login)
- Real-time messaging with Socket.io
- Profile pictures via Cloudinary
- Persistent chat history
- Fully responsive design
- Built with clean and modular architecture

Tech Stack

Frontend: React, Tailwind CSS, Zustand, Axios  
Backend: Node.js, Express.js, MongoDB, Mongoose  
Real-time: Socket.io  
Storage: Cloudinary (for profile pictures)  
Authentication:* JWT & bcrypt



Setup `.env` file (Backend):
In your `backend/` folder, create a `.env` file and add:

MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development


## Build & Start the App
From the project root (adjust commands if you separate frontend/backend):

# install dependencies for backend
cd backend
npm install

# start backend server
npm run dev  # or `npm start` depending on your setup

# install dependencies for frontend
cd ../frontend
npm install

# start frontend
npm run dev  # or `npm start`

