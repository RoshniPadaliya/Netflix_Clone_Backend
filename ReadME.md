# Netflix Clone

A Netflix clone application built with Node.js and MongoDB, providing users with functionalities to register, log in, and browse a variety of movies and shows.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Secure registration and login with JWT
- **Content Browsing**: View a list of movies and shows
- **Watchlist Management**: Save favorite movies for later
- **Password Security**: User passwords are hashed for safety
- **Environment Configuration**: Easy setup using environment variables

## Technologies

- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **HTTP Client**: Axios
- **Development Tools**: Nodemon for auto-reloading during development

## Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [MongoDB](https://www.mongodb.com/try/download/community) (with a running instance)

### Steps to Set Up

1. **Clone the repository**:

   ```bash
   git clone https://github.com/RoshniPadaliya/Netflix_Clone_Backend.git
   cd netflix-clone
Install dependencies:

bash
Copy code
npm install
Configure environment variables:

Create a .env file in the root directory with the following content:

plaintext
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the application:

Use the following command to run the server:

bash
Copy code
npm run dev
The server will be running on http://localhost:5000.