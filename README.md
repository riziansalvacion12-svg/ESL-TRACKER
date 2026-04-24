# ESL Tracker

## Setup Instructions

1. **Clone the Repository**  
   To get started, clone the repository using:
   ```bash
   git clone https://github.com/<your-username>/ESL-TRACKER.git
   cd ESL-TRACKER
   ```

2. **Install Dependencies**  
   Make sure you have [Node.js](https://nodejs.org/) installed. Run the following command to install dependencies:
   ```bash
   npm install
   ```

3. **Setup Environment Variables**  
   Create a `.env` file in the root directory and specify the following variables:
   ```
   FIREBASE_API_KEY=your_firebase_api_key
   FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   FIREBASE_DATABASE_URL=your_firebase_database_url
   FIREBASE_PROJECT_ID=your_firebase_project_id
   FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   FIREBASE_APP_ID=your_firebase_app_id
   ```

## Usage Guide

1. **Start the Application**  
   After the setup is complete, you can start the application by running:
   ```bash
   npm start
   ```
   This will start the server and you will be able to access the application on your browser at `http://localhost:3000`.

2. **Using the Application**  
   - Follow the on-screen instructions for tracking ESL activities.
   - Use the dashboard to manage entries and review statistics.

## Troubleshooting

- **Common Issues**  
  - If you encounter any issues while starting the application, make sure your Node.js version is compatible (preferably Node.js v14 or above).
  - Check the console for any error messages that might suggest what needs to be fixed.
  
- **Firebase Configuration Issues**  
  - Ensure that your Firebase configuration in the `.env` file is correct.
  - Verify that your Firebase project is correctly set up in the Firebase console.

## Firebase Configuration Steps

1. **Create a Firebase Project**  
   Go to [Firebase Console](https://console.firebase.google.com/) and create a new project.

2. **Register your App**  
   In the project overview, click on 'Add app' to register your application.

3. **Get Configuration Settings**  
   After registering your app, Firebase will provide you with the configuration settings needed to be added to your `.env` file.

4. **Enable Firestore**  
   In the Firebase console, go to Develop > Firestore Database and create a database.

5. **Enable Authentication**  
   Go to Develop > Authentication > Get Started and enable the sign-in methods you want to use (Email/Password, Google, etc.).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.