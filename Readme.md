# YouTube Backend

This is the backend component of a YouTube-like application. It provides the necessary APIs and services to support video uploading, user authentication, and video management.

## Features

- User authentication: Users can create accounts, log in, and manage their profiles.
- Video uploading: Users can upload videos, including title, description, and tags.
- Video management: Users can view, edit, and delete their own videos.
- Search functionality: Users can search for videos based on title, description, or tags.
- User subscriptions: Users can subscribe to other users and receive notifications for new videos.

## Technologies Used

- Node.js: Backend runtime environment.
- Express.js: Web application framework.
- MongoDB: Database for storing user and video data.
- JWT: JSON Web Tokens for user authentication.
- AWS S3: Cloud storage for video uploads.
- Docker: Containerization for easy deployment.

## Getting Started

1. Clone the repository: `git clone https://github.com/mdtanvirahamedshanto/youtube-backend-nodejs.git`
2. Install dependencies: `npm install`
3. Set up environment variables: Create a `.env` file and configure the necessary variables (e.g., database connection string, AWS S3 credentials).
4. Start the server: `npm start`

## API Documentation

For detailed API documentation, please refer to the [API Documentation](./docs/api.md) file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](./LICENSE).
