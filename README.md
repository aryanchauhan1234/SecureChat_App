# SecureChat

A modern real-time chat application built with React, Node.js, and Socket.IO. Features include real-time messaging, media sharing, online status, and more.

## Features

- Real-time messaging with Socket.IO
- User authentication and authorization
- Media sharing (images)
- Online/offline status indicators
- Message seen status
- Responsive design for all devices
- User profiles with customizable avatars and bio

## Tech Stack

- **Frontend:**
  - React
  - TailwindCSS
  - Socket.IO Client
  - Context API for state management

- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - Socket.IO
  - JWT Authentication

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd SecureChat_App
```

2. Install dependencies for frontend
```bash
cd SecureChat_App
npm install
```

3. Install dependencies for backend
```bash
cd ../server
npm install
```

4. Create a .env file in the server directory with the following variables:
```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

5. Start the development servers

For backend:
```bash
cd server
npm start
```

For frontend:
```bash
cd SecureChat_App
npm run dev
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
