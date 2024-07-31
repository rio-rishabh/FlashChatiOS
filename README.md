# FlashChatiOS
Flash Chat is a messaging application that combines traditional email/password authentication with Google Sign-In functionality. 

## Features

- User authentication (Email/Password and Google Sign-In)
- Real-time messaging
- User-friendly interface with dynamic text effects

## Technologies Used

- Swift 5.10.1
- UIKit
- Firebase (Authentication, Firestore)
- Google Sign-In
- CocoaPods
- SPM(Swift Package Manager)

## Prerequisites
- Xcode 12.0 or later
- iOS 13.0 or later
- CocoaPods
- Swift Package Manager


## Installation
1. Clone the repository
2. Install Cocoapods

## Configuration

### Firebase Setup
1. Create a new Firebase project
2. Add an iOS app to the Firebase project
3. Download the GoogleService-Info.plist and add it to the Xcode project
4. Enable Email/Password and Google Sign-In authentication methods in Firebase console

### Google Sign-In Setup
1. Configure your Google Sign-In credentials in the Google Cloud Console
2. Add the reversed client ID to your Xcode project's URL schemes


## Usage

1. Run the app in Xcode
2. On the welcome screen, choose to register or log in
3. Once authenticated, you can send and receive messages in real-time

## Project Structure

- `WelcomeViewController`: Handles the initial screen and Google Sign-In
- `LoginViewController`: Manages user login
- `RegisterViewController`: Handles new user registration
- `ChatViewController`: Main interface for sending and receiving messages

 ## Acknowledgments
- Angela Yu's iOS Development Course
- Firebase Documentation
- Google Sign-In Documentation

## Contact

Your Name - sharma.rishabh@northeastern.edu, rishabhsharma61996@gmail.com


