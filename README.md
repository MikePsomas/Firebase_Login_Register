# Firebase Login & Registration App

This Android application demonstrates a fully functional user authentication system using **Firebase Authentication**. The app includes three key activities: **Login**, **Register**, and a **Main Screen** that welcomes the user. It uses Firebase services to handle secure login, registration, and session management.

---

## 📋 Features

- **User Registration**:
  - Allows new users to register with an email and password.
  - Includes a password visibility toggle.
  - Redirects to the login screen upon successful registration.

- **User Login**:
  - Enables existing users to log in with their registered credentials.
  - Handles errors such as empty fields or invalid authentication.
  - Automatically redirects logged-in users to the main screen.

- **Session Management**:
  - Ensures logged-in users stay authenticated until they explicitly log out.
  - Redirects unauthenticated users to the login screen.

- **Logout Functionality**:
  - Allows users to log out and clears the session.

- **UI Enhancements**:
  - Implements user-friendly UI with a password visibility toggle and progress indicators for loading states.

---

## 📂 Project Structure

### 1️⃣ **MainActivity**
- Displays a welcome message with the user's email after successful login.
- Includes a logout button to end the session and redirect the user to the login screen.

### 2️⃣ **Login**
- Manages user login functionality.
- Handles errors for empty fields or failed authentication.
- Includes a link to navigate to the registration screen.
- Features a password visibility toggle.

### 3️⃣ **Register**
- Handles new user registration.
- Ensures email and password validation.
- Displays progress indicators during the registration process.
- Redirects users to the login screen upon successful account creation.
- Features a password visibility toggle.

---

## 🛠️ Technologies Used

- **Kotlin**: Programming language for Android development.
- **Firebase Authentication**: Secure backend service for handling user login and registration.
- **Material Design Components**: UI elements like `TextInputEditText`, `ProgressBar`, and `Button`.

---

## 🚀 How to Run the App

### Prerequisites
1. Install **Android Studio**.
2. Set up a Firebase project and integrate it with your Android application. Follow the [Firebase Setup Instructions](https://firebase.google.com/docs/android/setup).
3. Add the `google-services.json` file to your project’s `app/` directory.

### Steps
1. Clone this repository or copy the provided source code.
2. Open the project in **Android Studio**.
3. Sync the project with Gradle to ensure all dependencies are installed.
4. Build and run the application on an Android emulator or a physical device.

---

## 📜 Usage Instructions

### Registration
1. Launch the app.
2. Click on **"Register Now"**.
3. Enter your email and password.
4. Click **"Register"** to create an account.

### Login
1. Return to the **Login** screen after registration.
2. Enter the registered email and password.
3. Click **"Login"** to access the app.

### Logout
1. On the **Main Screen**, click the **"Logout"** button to end the session.

---

## 📑 Code Highlights

### MainActivity
 Redirects unauthenticated users to the login screen:
  
![carbon](https://github.com/user-attachments/assets/2a45b0d8-ccc1-4c8f-8ecf-ef9016ea2226)

### Login
Authenticates the user and handles invalid credentials:
![carbon (1)](https://github.com/user-attachments/assets/37fcf3d2-ac65-4e56-b114-1394465e3d75)



### Registers a new user with Firebase Authentication:
![carbon (2)](https://github.com/user-attachments/assets/90436c27-86cc-4f3a-9b4b-e64151b36d37)

