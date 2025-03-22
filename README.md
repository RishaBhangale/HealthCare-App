# HealthCare-App

---

# Healthcare Application

A simple and secure healthcare application with user authentication, registration, and data validation functionalities. This app provides a streamlined registration and login process with email and password validation, ensuring that only verified users can access the platform.

## Features

- **User Registration**: New users can create an account by providing a username, email, and password. The app validates the email format and enforces a strong password policy (minimum 6 characters, including uppercase letters and special characters).
  
- **User Login**: Registered users can log in using their credentials. If the entered credentials match those stored in the database, users are redirected to the Home screen.
  
- **Duplicate User Check**: The app prevents duplicate registrations by checking if a user already exists based on email and username.

- **Real-Time Database**: Firebase is integrated for real-time database functionality, securely storing user credentials and profile information.
  
- **Input Validation**:
    - **Email**: Ensures a valid email format (must contain `@`).
    - **Password**: Enforces a minimum length and complexity (6 characters, a special character, and an uppercase letter).
  
## Technologies Used

- **Android Studio**: IDE for Android application development.
- **Firebase Authentication**: Manages user registration and login.
- **Firebase Realtime Database**: Stores user data securely in the cloud.
- **Java**: Main programming language used in this project.
- **XML**: Used for designing user interfaces.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/healthcare-app.git
    ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Connect your Firebase project by adding the `google-services.json` file (downloaded from Firebase Console) to the `app` directory.
5. Build and run the app on an emulator or Android device.

## Usage

1. **Register New Users**:
    - Navigate to the registration screen and fill in the username, email, and password.
    - Submit the form to create a new account.
  
2. **Login**:
    - Enter registered email and password in the login screen.
    - Successfully authenticated users are redirected to the Home screen.

## Screens

- **Register Activity**: Collects user information for registration.
- **Login Activity**: Prompts users to log in with credentials.
- **Home Activity**: Accessible only after successful login.

## Future Enhancements

- **Password Recovery**: Add an option for users to recover/reset their passwords.
- **Enhanced Profile Management**: Allow users to edit their profile details.
- **Two-Factor Authentication**: Add extra security for sensitive data protection.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.

---
