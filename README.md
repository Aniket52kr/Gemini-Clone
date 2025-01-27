# Gemini Clone

This project is a clone of Gemini using the MERN stack (MongoDB, Express.js, React.js, Node.js) with TypeScript integration in both the frontend and backend.

## Features

- **Frontend**: React.js with Redux for state management, written in TypeScript.
- **Backend**: Node.js with Express.js for API endpoints, written in TypeScript.
- **Database**: MongoDB Atlas for data storage.
- **Authentication**: Firebase authentication.

## Environment Variables

In the frontend, the following environment variables are used:

- `VITE_API_KEY`: Google Gemini API key.
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

1. Clone the repository: `https://github.com/Aniket52kr/Gemini-Clone.git`
2. Navigate to the project directory: `cd Gemini-Clone`
3. Install dependencies:
   - Backend: `cd backend && npm install`
   - Frontend: `cd frontend && npm install`
4. Set up environment variables:
   - Create a `.env` file in the root of the backend directory.
   - Add your environment variables to the `.env` file (refer to the provided variables above).
5. Build the TypeScript code:
   - Backend: Run `npm run build` to compile TypeScript into JavaScript.
   - Frontend: Ensure TypeScript is properly configured and build as needed.
6. Start the backend server: `npm run start` in the backend directory (ensure `dist/app.js` is correctly built).
7. Start the frontend development server: `npm start` in the frontend directory.

## Screenshots

![Screenshot (211)](https://github.com/user-attachments/assets/a8981c30-c4bd-4051-945c-712115bfffe0)
![Screenshot (212)](https://github.com/user-attachments/assets/6dbe8326-6e63-45a2-9cde-b86ca4db474b)
![Screenshot (213)](https://github.com/user-attachments/assets/fe1fc6a3-14a0-45f5-b3ca-5beb24a43903)
![Screenshot (214)](https://github.com/user-attachments/assets/32ca679d-9c01-4a80-ab50-75eabe95dd71)
![Screenshot (215)](https://github.com/user-attachments/assets/ae28ea72-2193-4b61-b739-0cc31a9f4467)
![Screenshot (216)](https://github.com/user-attachments/assets/01aa4895-ddec-42fd-90bc-7d122d175b8a)
![Screenshot (217)](https://github.com/user-attachments/assets/92c1f1ed-40f0-450b-90cf-4a67de7356ab)

