# GridSync Messenger

**GridSync Messenger** is a real-time messaging application built to understand backend architecture end-to-end. It features seamless communication, efficient file sharing, 
and optimized storage for low-latency chat retrieval, built using Node.js, Express, MongoDB, Socket.io, and other essential technologies. This project includes user authentication, secure file sharing, and dynamic password recovery functionalities.

 Features

1. **Real-time Communication**: 
   - Implemented using **Socket.io** for instant message updates and notifications.
   - WebSocket ensures low-latency communication between users.

2. **File Sharing**: 
   - Files are split into chunks, stored, and shared as links using **S3**, similar to popular social platforms.
   - Provides efficient storage and retrieval of large files, maintaining data integrity with **GridFS**.

3. **Optimized Chat Storage**:
   - Utilizes **MongoDB** for fast and reliable chat data retrieval, which is highly efficient for read-heavy applications, improving latency and user experience.

4. **User Authentication**:
   - Integrated **Google Authentication** using **Passport.js**.
   - Supports **JWT-based middleware** for secure, authenticated API requests.
   
5. **Password Recovery**:
   - Implements a **forgot-password feature** using dynamic links to reset passwords securely.

## Technologies Used

- **Node.js** and **Express.js**: Backend server and API development.
- **Socket.io**: Real-time communication for low-latency messaging.
- **MongoDB**: Database management, optimized for high read efficiency.
- **GridFS**: File storage and retrieval for efficient handling of large files.
- **AWS S3**: Used for file chunking and storage.
- **Passport.js**: Google OAuth authentication.
- **JWT (JSON Web Tokens)**: Secure middleware for user authentication.

## Installation and Setup

1. Clone the repository:
   git clone https://github.com/yourusername/gridsync-messenger.git
   cd gridsync-messenger


2. Install dependencies: npm install


3. Set up environment variables:
     

4. Run the application: npm start
  

5. Access the app:
   - The server should be running on `http://localhost:5000`.

## Usage

1. **Real-time Chat**:
   - Users can exchange messages in real-time with low latency.
   
2. **File Sharing**:
   - Files are uploaded, chunked, stored, and a link is generated for the receiver.

3. **User Authentication**:
   - Users can sign in using Google and are authenticated for secure messaging.

4. **Password Recovery**:
   - If users forget their passwords, they can reset them through an emailed dynamic link.

## Project Structure

- /models - Contains MongoDB schema models for users and messages.
- /routes - API endpoints for handling user authentication, messaging, and file uploads.
- /controllers - Core logic for handling real-time communication, user authentication, and file sharing.
- /middleware - Authentication middleware using JWT for secure route access.

## Future Enhancements

- Group Chat: Support for group messaging and file sharing.
- Advanced File Types: Enhanced support for various file types beyond basic documents and images.
- Message Reactions: Add reactions or emojis to enhance user interaction.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

**Naveen Kumar**  
- GitHub: [Naveen1745](https://github.com/Naveen1745)  
- LinkedIn: [Naveen1745](https://linkedin.com/in/naveen1745)

---

Thank you for checking out **GridSync Messenger**! If you have any questions or feedback, feel free to reach out.
