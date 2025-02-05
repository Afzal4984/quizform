# QuizForm Application

## Description
QuizForm is a Node.js-based web application that allows users to create, take, and manage quizzes. It uses Express.js for the backend, EJS for templating, and MongoDB for data-storage.

## Features
- User authentication (login and signup).
- Quiz creation and management.
- Dynamic form handling.
- Real-time quiz results.
- Session handling with Express-Session
- MongoDB database integration with Mongoose
- Flash messaging using Express-Flash

## Technologies Used
- Node.js
- Express.js
- MongoDB & Mongoose
- Passport.js (for authentication)
- EJS (templating engine)
- dotenv (for environment variables)
- Express-session (session management)

## Installation
1. Clone the repository:
   ```sh
   git clone <repo-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd quizform
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a `.env` file in the root directory and add:
   ```env
   SESSION_SECRET=your_secret_key
   MONGO_URI=your_mongodb_connection_string
   ```
5. Start the development server:
   ```sh
   npm run dev
   ```

## Usage
- Open a browser and navigate to `http://localhost:5000`.
- Register/Login to create or take quizzes.
- View quiz results in real-time.

## Project Structure
```
quizform/
│── public/              # Static files (CSS, JS, images)
│── server/
│   ├── config/          # Database configuration
│   ├── models/          # Mongoose schemas
│   ├── routes/          # Express routes
│   ├── views/           # EJS templates
│   ├── layouts/         # Layout templates
│── .env                 # Environment variables
│── app.js               # Main server file
│── package.json         # Project metadata
│── README.md            # Project documentation
```

## License
This project is licensed under the MIT License.
