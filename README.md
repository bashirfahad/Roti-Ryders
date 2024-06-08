
---

# Restaurant App
---

### Overview
The Restaurant App is a web application developed using React for the frontend and Node.js (Express) for the backend. This project is designed to provide a comprehensive solution for managing a restaurant's operations.

### Project Structure
The project is structured into two main folders: `restaurant` for the frontend and `server` for the backend.

### Takeaways and Thoughts
- **Rigidity in Frontend Structure**: The frontend structure is quite rigid and non-modular, making it difficult to reuse components. This is something we will keep in mind for future projects and strive to write more modular code.
- **Functional Components**: Functional components are easier to read, understand, and maintain than class components.
- **Redux vs. Context API**: Redux could have been implemented instead of the Context API, considering the project's scalability and use cases.
- **Bootstrap vs. CSS Grid**: Bootstrap is a great tool for rapid design and its grid system, but it might have been better to use CSS grid tools for the layout instead of a more powerful tool for styling components like Styled Components or Ant Design.

### Main Technologies Used
- **React**
- **Node.js (Express)**
- **MySQL**
- **Socket.io**
- **React-Bootstrap**
- **Axios**
- **Mocha**

### Installation
To install dependencies, follow these steps:

1. **Install Frontend Dependencies**:
   ```bash
   cd restaurant
   npm install
   ```

2. **Install Backend Dependencies**:
   ```bash
   cd server
   npm install
   ```

### Environment Variables
Edit the `.env.example` file in the `server` directory:

1. **Remove the .example Extension**:
   ```bash
   rm .env.example
   ```

2. **Edit the File**:
   ```bash
   nano .env
   ```

   - Edit the file to match your database and PC settings.

### Setting Up the Database
This project requires MariaDB/MySQL to be running on your PC.

1. **Create the Database**:
   - Create the MariaDB/MySQL database for the app.

2. **Run Migrations and Seeds**:
   ```bash
   cd server
   npm run migrations
   npm run seeds
   ```

### Running the Project
To run the project, follow these steps:

1. **Run Frontend**:
   ```bash
   cd restaurant
   npm start
   ```

   - This will run the frontend on port 3000 of your PC.

2. **Run Backend**:
   ```bash
   cd server
   npm run devstart
   ```

   - This will run the backend on port 5000 of your PC (if you change the backend's port number, be sure to update the "proxy": "http://localhost:5000" line in the frontend's `package.json` file accordingly).

### Running Unitary Tests
To run unitary tests, follow these steps:

1. **Run Tests**:
   ```bash
   cd server
   npm run test
   ```

### Running Browser Tests
To run browser tests, follow these steps:

1. **Open Cypress**:
   ```bash
   cd server
   npx cypress open
   ```

2. **Run Tests**:
   ```bash
   npx cypress run
   ```

### Author
This project is maintained by Bashir Fahad. You can reach out to him at [bashirfahad](https://github.com/bashirfahad).

---
## Screenshots :

### HomePage
![82774294-0a6d0580-9e0a-11ea-8e0c-607083eaea10](https://github.com/bashirfahad/Roti-Ryders/assets/144224515/078b2dfd-5aa8-46f7-ada8-750d5ca0cc7b)
### Food Ordering Page
![82774302-0e99![82774304-0e992300-9e0a-11ea-996a-9cd9e77ec051](https://github.com/bashirfahad/Roti-Ryders/assets/144224515/c2f1c51b-362b-4756-b70d-b6b01361175a)
### Adding items to the cart
2300-9e0a-11ea-9b5e-2d3f4ca9323b](https://github.com/bashirfahad/Roti-Ryders/assets/144224515/522be4de-5537-4a3a-98eb-9c0f90f3937c)
### Admin Dashboard
![82774438-79e2f500-9e0a-11ea-8d56-c262f981487d](https://github.com/bashirfahad/Roti-Ryders/assets/144224515/d6cb06b5-b6f7-43ca-82e2-c2db345c3606)

