# Lumina - AI-powered Calendar Assistant

Lumina is a modern calendar application that uses AI to help you manage your schedule more effectively. Built with React Native and Expo for the frontend, and Node.js/Express for the backend.

## Features

- AI-powered scheduling assistance
- Cross-platform support (iOS, Android, Web)
- Smart event management
- Intuitive user interface
- Real-time notifications
- Calendar integrations

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB
- Expo CLI (`npm install -g expo-cli`)

## Project Structure

```
lumina/
├── backend/         # Express server
├── frontend/        # React Native/Expo app
│   └── lumina-app/
```

## Getting Started

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Update the `.env` file with your credentials

5. Start the development server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend app directory:
   ```bash
   cd frontend/lumina-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Expo development server:
   ```bash
   npx expo start
   ```

## Development

- Backend runs on `http://localhost:5000`
- Frontend development server runs through Expo

## Environment Variables

### Backend
- `PORT`: Server port (default: 5000)
- `MONGODB_URI`: MongoDB connection string
- `JWT_SECRET`: Secret key for JWT tokens
- `NODE_ENV`: Environment (development/production)
- `AI_API_KEY`: API key for AI services

### Frontend
- Environment configuration is handled through Expo's configuration system

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with React Native and Expo
- Powered by Node.js and Express
- Uses MongoDB for data storage
- AI capabilities provided by advanced language models