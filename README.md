# Gemini Clone

This project is a clone of Gemini using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- **Frontend**: React.js with Redux for state management.
- **Backend**: Node.js with Express.js for API endpoints.
- **Database**: MongoDB for data storage.
- **Authentication**: Firebase authentication.

## Environment Variables

In the frontend, the following environment variables are used:

- `VITE_API_KEY`: Google Maps API key.
- `VITE_FIREBASE_KEY`: Firebase API key.
- `VITE_FIREBASE_DOMAIN`: Firebase authentication domain.
- `VITE_FIREBASE_DATABASE`: Firebase database URL.
- `VITE_FIREBASE_PROJECT`: Firebase project ID.
- `VITE_FIREBASE_STORAGE`: Firebase storage bucket.
- `VITE_FIREBASE_MESSAGING`: Firebase messaging sender ID.
- `VITE_FIREBASE_APP_ID`: Firebase app ID.
- `VITE_DATABASE_URL`: MongoDB database connection URL.

## Backend APIs

### Result Routes

- `POST /api-v1/result/new`: Sets data.
- `GET /api-v1/result/all/:user`: Gets all data for a specific user.
- `GET /api-v1/result/:id`: Gets a single data entry by ID.

### User Routes

- `POST /api-v1/user/new`: Creates a new user.
- `POST /api-v1/user/login`: Logs in a user.
- `POST /api-v1/user/isuser`: Checks if a user exists.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `https://github.com/Aniket52kr/GeminiClone.git`
2. Navigate to the project directory: `cd GeminiClone`
3. Install dependencies:
   - Backend: `cd backend && npm install`
   - Frontend: `cd frontend && npm install`
4. Set up environment variables:
   - Create a `.env` file in the root of the backend directory.
   - Add your environment variables to the `.env` file (refer to the provided variables above).
5. Start the backend server: `nodemon dist/app.js`  for development mode.
6. Start the frontend development server: `npm start` in the frontend directory.

![Screenshot (211)](https://github.com/user-attachments/assets/e26847a8-616a-492d-a3b2-b8b3db399026)
![Screenshot (212)](https://github.com/user-attachments/assets/0b219161-5bf6-4e08-928a-d4d9ddcc7f68)
![Screenshot (213)](https://github.com/user-attachments/assets/6c87b825-7dcb-4588-9074-89ec24f37bab)
![Screenshot (214)](https://github.com/user-attachments/assets/38b70cb6-5a8e-45ca-99e0-c355c1cc32d7)
![Screenshot (215)](https://github.com/user-attachments/assets/b8d68dc7-741e-48c5-8100-617a4470ec16)
![Screenshot (216)](https://github.com/user-attachments/assets/468ab4d8-e9d9-4dbb-ae68-d3f9c623faf5)
![Screenshot (217)](https://github.com/user-attachments/assets/5d894a7c-78fa-413e-b498-82f8ebe9161b)



