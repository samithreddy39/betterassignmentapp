# Better Assignment Mobile App

## Description
This is a mobile application designed to manage assignments efficiently. The app includes user authentication, sign-up, and login functionality. Users can securely sign up with a username and password, and the app stores user credentials using AsyncStorage for easy re-login.

## How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/samithreddy39/betterassignmentapp.git
Navigate to the project folder:

bash
Copy code
cd betterassignmentapp
Install the dependencies: If you are using npm:

bash
Copy code
npm install
Or if you are using yarn:

bash
Copy code
yarn install
Run the app: For iOS:

bash
Copy code
npx react-native run-ios
For Android:

bash
Copy code
npx react-native run-android
Make sure you have the appropriate emulator or a physical device connected.

Design Choices
State Management:

The app uses React's useState and useEffect hooks for handling states such as user login status, stored email, and sign-up forms.
AsyncStorage is used for storing user data locally, making it easier to manage authentication across app restarts.
Form Validation:

Username must be at least 3 characters long.
Email validation is done to ensure that the entered email is a valid Gmail address.
Password strength is checked using a basic password strength indicator.
User Interface:

The app uses react-native components for layout and interaction, including Text, Button, and TextInput components.
Custom checkboxes are implemented to allow users to opt for the "Remember Me" feature during login.
Security:

Basic password validation is implemented to ensure the password is sufficiently strong.
Credentials are stored securely in AsyncStorage with basic checks to ensure that users are able to log in again without needing to re-enter credentials.
Assumptions and Limitations
Assumptions:

The app assumes that the user has a valid Gmail account for the sign-up/login process.
The app doesn't handle advanced security features such as two-factor authentication (2FA) or encrypted password storage (this can be added for further security).
It is assumed that the app runs on both Android and iOS devices that support React Native.
Limitations:

The password strength indicator is basic and can be improved with more advanced rules.
No backend is implemented for user authentication. All user data is stored locally using AsyncStorage.
The app currently supports only Gmail email addresses. Support for other domains can be added.
The app does not yet support account recovery for forgotten passwords.
Video Demo
You can view the demo video of the app here:

[Insert your video link here]

License
This project is licensed under the MIT License - see the LICENSE file for details.

python
Copy code

### Instructions:
- Replace `[Insert your video link here]` with the actual URL where your video is hosted.

This markdown file includes all the required sections in a simple format. Let me know if you need anything else!






