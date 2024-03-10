# Vanlife

Vanlife is a van rental website built using React and Firebase, designed to provide users with an easy and convenient platform to rent vans for their travel adventures.

## Features

- **User Authentication**: Secure user authentication and authorization using Firebase Authentication.
- **Van Listings**: Browse and search for available vans to rent, with detailed information and photos.
- **Booking System**: Book vans for specific dates, manage bookings, and view rental history.
- **Admin Dashboard**: Admin panel for managing van listings, user bookings, and site settings.

## Technologies Used

- React: Frontend development framework
- Firebase: Backend services for user authentication, database, and hosting
- HTML/CSS: Frontend markup and styling
- JavaScript: Programming language for frontend logic
- Bootstrap: CSS framework for responsive design

## Installation

To run the Vanlife project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/vanlife.git`
2. Navigate to the project directory: `cd vanlife`
3. Install dependencies: `npm install`
4. Set up Firebase project and obtain credentials (see below)
5. Create `.env` file in the root directory and add Firebase config details:

   ```plaintext
   REACT_APP_FIREBASE_API_KEY=your-api-key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
   REACT_APP_FIREBASE_PROJECT_ID=your-project-id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
   REACT_APP_FIREBASE_APP_ID=your-app-id
   ```

6. Run the development server: npm start
7. Open your browser and navigate to http://localhost:3000

## Firebase Setup

1. Create a new Firebase project on the Firebase Console.
2. Enable Firebase Authentication and Firestore database for your project.
3. Add web app to your project and obtain Firebase config details.
4. Update .env file in your project with Firebase config details.

## Contributing

Contributions to Vanlife are welcome! If you encounter any issues or have suggestions for improvements, please submit a pull request or open an issue on GitHub.
License

This project is licensed under the MIT License - see the LICENSE file for details.
Contact

For any inquiries or feedback, feel free to contact the project maintainer at osama.f.mabkhot@gmail.com
