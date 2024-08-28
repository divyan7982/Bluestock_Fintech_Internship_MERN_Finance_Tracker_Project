# Expense Tracker

![image](https://github.com/user-attachments/assets/8fc23d83-fc46-4311-8471-f11269db5d89)

## Project Overview

The **Expense Tracker** is a full-stack application designed to help users manage their expenses efficiently. It provides a simple and user-friendly interface to track income and expenses, view transaction history, and manage financial records. The project is built using the MERN stack (MongoDB, Express, React, Node.js).

## Features

- **Expense Management**: Add, edit, delete, and view expenses.
- **Real-time Data**: All transactions are managed and displayed in real-time.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: React, Axios
- **Backend**: Node.js, Express, Mongoose
- **Database**: MongoDB
- **Dev Tools**: Nodemon, Concurrently
- **Additional Tools**: dotenv, morgan, colors

## Installation

### Prerequisites

- Node.js and npm installed on your local machine.
- MongoDB installed locally or a MongoDB Atlas account.

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-tracker.git
   cd expense-tracker

2. **Install Backend Dependencies**:
   ```bash
   npm install

3. **Install Frontend Dependencies**:
   ```bash
   cd client
   npm install

4. **Set up environment variables: Create a .env file in the root directory of the project and add your configuration values:**:
   ```bash
   MONGO_URI=your_mongodb_uri
   NODE_ENV=development

5. **Run the application**:
   ```bash
   npm run dev

## Usage
- **Access the app**: Open your browser and go to http://localhost:3000 to start using the application.
- **Manage expenses**: Add, edit, delete, and view expenses to keep track of your financial activities.

## Scripts
### Backend
- **npm start**: Start the backend server.
- **npm run server**: Start the backend server with Nodemon for development.

### Frontend
- **npm start**: Start the React development server.
- **npm run build**: Build the React app for production.
- **npm run test**: Run the React test suite.


