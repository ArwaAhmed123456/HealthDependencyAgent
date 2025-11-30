# Project Setup and Running Instructions

## Backend

1. Navigate to the backend directory:
   ```
   cd health-dependency-agent/backend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the backend server:
   ```
   npm run dev
   ```
   The server will run on port 4000 by default.

## Frontend

1. Navigate to the frontend directory:
   ```
   cd health-dependency-agent/frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the frontend development server:
   ```
   npm start
   ```
   The React app will run on port 3000 by default.

## Notes

- Backend server expects requests on port 4000.
- Ensure that both frontend and backend servers are running simultaneously to test the full application.
- The frontend upload of project directory works by selecting multiple files manually (due to React limitation with directory uploads). Alternatively, upload individual files (.json or .txt).
- Use the Analyze Dependencies button to send data from frontend to backend for dependency analysis.
- The results and health scores will be displayed on the dashboard, with an option to export as CSV.

## Running Tests

- Backend tests use Jest and Supertest.
- Run backend tests with:
  ```
  npm test
  ```
  in the backend directory.
