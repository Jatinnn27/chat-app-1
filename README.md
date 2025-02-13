# Chat App

# Overview

The Chat App is a real-time messaging application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The front-end, developed with React.js, provides a smooth and responsive user experience, while the back-end, powered by Node.js and Express, manages authentication and message routing. The app leverages Socket.io for real-time messaging and MongoDB for chat storage, ensuring a seamless communication experience. Key features include private and group chats, notifications, and online status tracking.

# Installation Guide

# Prerequisites

Ensure you have the following installed:

Node.js (v14+ recommended)

MongoDB (local or cloud instance)

npm or yarn

Socket.io for real-time communication

# Steps to Install

!) Clone the Repository

git clone https://github.com/Jatinnn27/chat-app-1.git
cd chat-app

2) Install Dependencies

cd server
npm install  # or yarn install
cd ../client
npm install  # or yarn install

3) Set Up Environment Variables, Create a .env file in the server directory and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4) Run the Server

cd server
npm start  # or yarn start

5) Run the Client

cd client
npm start  # or yarn start

The app will be available at http://localhost:3000/ or http://localhost:5000/ .

