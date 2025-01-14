
# Socket.IO Project

This repository contains a Socket.IO-based simple MERN application. The project is organized into client and server components to enable real-time, bidirectional communication between clients and the server through chat.

## Project Structure

```
socket.io-master/
├── .gitIgnore        # Files and folders ignored by Git
├── client/           # Contains client-side code
├── server/           # Contains server-side code
```

## Features

- Real-time communication using Socket.IO.
- Organized into separate client and server directories for scalability.

## Prerequisites

- **Node.js**: Ensure Node.js is installed on your machine.
- **npm**: Comes bundled with Node.js, used to install dependencies.

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
cd socket.io-master
```

### Install Dependencies

Navigate to both the `client` and `server` directories and install the necessary dependencies:

```bash
cd client
npm install

cd ../server
npm install
```

### Run the Application

1. Start the server:
   ```bash
   cd server
   npm start
   ```

2. Start the client:
   ```bash
   cd client
   npm start
   ```

3. Access the application in your browser at `http://localhost:3000` (or the specified port).

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Commit your changes: `git commit -m "Add some feature"`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License.

Krishchal Regmi
