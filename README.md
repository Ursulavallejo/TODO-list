#### Mars 2022

**Project Summary**

This project involved creating a full-stack TODO application as part of the Web Server Programming 1 course. The backend was built with Node.js, Express, and essential middleware (Helmet, CORS, Morgan), offering CRUD endpoints for managing users and their to-do items. Automated testing was implemented using Mocha, Chai, and Chai-HTTP to ensure API correctness. On the frontend side, two React versions were developed: a simple version covering core functionality and a more advanced version featuring user login, dynamic to-do management (add, update, delete), and animated UI elements inspired by CodePen resources. Throughout development, project tasks were organized in Trello, and typography and color choices were intentionally kept minimal for clarity. The result is a responsive, single-page application where users can authenticate, view, and manage their to-do lists, with all changes immediately reflected via API calls. Continuous integration between frontend and backend highlighted key learning around React hooks (useEffect), state management, and context to synchronize UI updates without full page reloads.

> On the repository are two version : one with login function and the other is a simple version.

https://user-images.githubusercontent.com/89070768/207939206-5d5d975a-8e34-4e0a-971e-6e4fed8e452b.mp4

### 🛠️ Technologies Used

#### Frontend Implementation :

- **React** for building dynamic user interfaces
- **JavaScript** for application logic and state management
- **CSS** for responsive styling and layout

#### Backend Implementation :

- **Express** for creating RESTful API endpoints
- **CORS** for handling cross-origin requests
- **dotenv** for environment variable management
- **Helmet** for securing HTTP headers
- **Morgan** for HTTP request logging

#### Testing :

- **Mocha** for test running
- **Chai** for assertions
- **Chai-HTTP** for HTTP integration testing

### 🚀 How to Run the Project Locally

1. **Clone or download** the project folder

   ```bash
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. **Backend Setup**

   ```bash
   cd backend
   npm install
   ```

   - Create a `.env` file in `backend/` (based on `.env.example` if provided), for example:

     ```
     PORT=3002
     ```

   - **Start the server** in development mode (using nodemon): 'npx nodemon src/server.js'

     ```bash
     npm start
     ```

   - **Run backend tests**:

     ```bash
     npm test
     ```

3. **Frontend Setup**

   - If you want the simple version:

     ```bash
     cd ../frontend-simple
     npm install
     npm start
     ```

   - If you want the login-enabled version:

     ```bash
     cd ../frontend-LogIn
     npm install
     npm start
     ```

   - Both commands above will launch the React app at [http://localhost:3000](http://localhost:3000).

4. **Run Frontend Tests**

   ```bash
   npm test
   ```

   (Run this from within the same frontend directory where you executed `npm install` and `npm start`.)

5. **Access the App**

   - Open [http://localhost:3000](http://localhost:3000) in your browser to view the frontend.
   - The React app will communicate with the backend API at [http://localhost:3002](http://localhost:3002).

Now you should have both backend and frontend running locally, along with the ability to execute all test suites.

---

### 📄 [Detailed Information of the Project](Detail_Info.md)
