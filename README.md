# Leyzo Project

Leyzo is a modern web application designed to provide a seamless shopping experience with a dark theme and smooth animations. The application features a pre-release countdown page, an access code system, user authentication, a shop for purchasing products, and a user account dashboard.

## Features

- **Pre-release Countdown**: A dedicated page displaying a countdown timer until the official launch of the Leyzo platform.
- **Access Code System**: Users can enter an access code to gain early access to the platform.
- **User Authentication**: Secure login and registration functionality for users to manage their accounts.
- **Shop**: A fully functional shop where users can browse and purchase products.
- **Account Dashboard**: A personalized dashboard for users to view their profile and order history.

## Technologies Used

- **Frontend**: React, TypeScript, CSS
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB (or any other database as per your choice)
- **State Management**: Context API or any state management library
- **Animations**: CSS animations for smooth transitions

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MongoDB (if using MongoDB as the database)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd leyzo
   ```

2. Install dependencies for the client:
   ```
   cd client
   npm install
   ```

3. Install dependencies for the server:
   ```
   cd ../server
   npm install
   ```

4. Set up environment variables:
   - Copy `.env.example` to `.env` and fill in the required values.

5. Run the application:
   - Start the server:
     ```
     cd server
     npm start
     ```
   - Start the client:
     ```
     cd ../client
     npm start
     ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.