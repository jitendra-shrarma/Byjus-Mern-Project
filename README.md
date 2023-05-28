# Byjus-Mern-Project

The Byjus-Mern-Project is a MERN (MongoDB, Express.js, React.js, Node.js) project that includes functionalities for managing users. It provides endpoints for creating, reading, updating, and deleting user data in a MongoDB database.

## Server

The server-side code handles the API requests and interacts with the database. Here are the main functionalities implemented:

### Create User

Endpoint: `POST /api/users`

Creates a new user with the provided data. The request body should include the user's name, email, address, and joining date.

### Find User by ID

Endpoint: `GET /api/users/:id`

Retrieves a user with the specified ID. The ID parameter should be included in the request URL.

### Update User by ID

Endpoint: `PUT /api/users/:id`

Updates a user with the specified ID. The request body should contain the updated user data.

### Delete User by ID

Endpoint: `DELETE /api/users/:id`

Deletes a user with the specified ID.

### Find All Users

Endpoint: `GET /api/users`

Retrieves all users. Optional query parameter `name` can be used to filter users by name.

### Delete All Users

Endpoint: `DELETE /api/users`

Deletes all users from the database.

## Client

The client-side code contains the user interface built with React.js. It interacts with the server-side API to perform CRUD operations on user data. The user interface provides forms for creating, updating, and deleting users, as well as a list of all users. The application uses socket.io for real-time communication.

To run the Byjus-Mern-Project on your system, follow these steps:

1. Clone the repository:

   ```shell
   git clone [repository_url]
   ```

2. Navigate to the project directory:

   ```shell
   cd Byjus-Mern-Project
   ```

3. Install dependencies for the server:

   ```shell
   cd server
   npm install
   ```

4. Start the server:

   ```shell
   npm start
   ```

   The server will run on port 5000.

5. Open another terminal and navigate to the client directory:

   ```shell
   cd ../client
   npm install
   ```

6. Start the client:

   ```shell
   npm start
   ```

   The client application will open in your default browser.

Please note that you need to have Node.js and MongoDB installed on your system to run the project.

Feel free to explore and modify the Byjus-Mern-Project according to your requirements. Enjoy managing user data with the MERN stack!