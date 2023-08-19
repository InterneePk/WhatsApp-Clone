# Chat Application Project

This repository contains the source code for a chat application built using React for the client-side and Node.js for the server-side. The application enables users to engage in real-time conversations with each other.

## Features

- User authentication and login
- Real-time messaging with other users
- Conversations management
- Profile and account settings
- Responsive design for various devices

## Project Structure

The project is divided into two main components: the **client** and the **server**.

### Client

The `client` directory contains the frontend code of the application built using React. It includes the following main files and directories:

- `public`: Contains static assets like images, icons, and manifest files.
- `src`: Contains the main React components and logic of the application.
  - `App.js`: The root component of the application.
  - `components`: Contains subcomponents organized by functionality.
  - `context`: Contains context providers for managing user and account data.
  - `service`: Contains API interaction logic.
  - `utils`: Contains utility functions.
  - `index.js`: Entry point for the React app.

### Server

The `server` directory contains the backend code of the application built using Node.js. It includes the following main files and directories:

- `controller`: Contains controllers for handling different aspects of the application (conversations, messages, users, etc.).
- `database`: Contains the database configuration and models.
- `routes`: Contains API routes and endpoints.
- `utils`: Contains utility functions, e.g., for file uploads.
- `index.js`: Entry point for the Node.js server.

### Socket

The `socket` directory contains code related to real-time communication using WebSockets. It includes the following main files and directories:

- `index.js`: Entry point for socket communication.
- `package.json` and `package-lock.json`: Dependencies for socket-related functionality.

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the `client` directory: `cd client`
3. Install dependencies: `npm install`
4. Start the React app: `npm start`
5. Open another terminal window/tab
6. Navigate to the `server` directory: `cd ../server`
7. Install server dependencies: `npm install`
8. Start the Node.js server: `npm start`
9. Open another terminal window/tab
10. Navigate to the `socket` directory: `cd ../socket`
11. Install socket dependencies: `npm install`
12. Start the socket server: `npm start`

The application should now be running locally. Access it in your web browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
