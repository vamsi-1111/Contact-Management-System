# MERN Contact Management System

## Overview
A full-stack web application for managing contacts, built on the MERN technology stack. It allows users to securely register, authenticate, and manage their personal or professional contacts in an intuitive and responsive interface.

## Features
- **Secure User Authentication**: Users can create accounts, sign in, and securely sign out using JWT authentication.
- **Contact Listings**: View, add, update, and delete contacts with fields including name, email, phone number, and address.
- **User-Specific Contact Management**: Each user has a private contact list, fully isolated from others.
- **Responsive Layout**: Enjoy a seamless user experience across desktop, tablet, and mobile devices.
- **Toast Notifications**: Users receive instant feedback for actions like login, logout, or contact changes.
- **Protected API Routes**: Backend routes are secured, accessible only to authenticated users.

## Technologies Used
- **Frontend**: React.js, HTML, CSS, JavaScript, React Toastify, Bootswatch  
- **Backend**: Node.js, Express.js, Mongoose, Morgan, CORS  
- **Database**: MongoDB  
- **Authentication**: JSON Web Tokens (JWT), bcrypt  
- **Deployment**: Render

## Getting Started

1. Clone the repository:
   git clone https://github.com/yourusername/contact-management-system.git
   cd contact-management-system
3. Start the backend:
   cd server
   yarn install
   yarn run dev
4. Start the frontend:
   cd ../client
   yarn install
   yarn start
