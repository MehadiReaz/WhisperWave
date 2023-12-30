# WhisperWave

WhisperWave is a chat application that aims to provide a seamless and secure messaging experience. This README provides an overview of the application, its features, and how to get started.

[![Flutter](https://img.shields.io/badge/Flutter-3.13.7-blue?logo=flutter)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-3.1.3-blue?logo=dart)](https://dart.dev/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Table of Contents

- [Features](#features)
- [Used Packages](#used-packages)
- [Getting Started](#getting-started)
- [Screenshots](#screenshots)
- [Contribution](#contribution)
- [License](#license)

## Features

1. **Add User:**
   - Ability to add new users to your contact list.

2. **Search User:**
   - Convenient search functionality to find users within the application.

3. **Update Profile:**
   - Users can update their profiles, including changing their name, about, and profile photo.

4. **Login with Google:**
   - Seamless authentication process using Google sign-in.

5. **User Activity:**
   - Display whether a user is currently active or not.

6. **Last Seen:**
   - Keep track of when a user was last seen.

7. **Unread Messages:**
   - Highlight unread messages for quick visibility.

8. **Push Notification:**
   - Implement push notifications to keep users informed about new messages.

9. **Message Read Status:**
   - Indicate whether a sent message has been seen by the recipient.

10. **Delete Message:**
    - Allow users to delete messages for better control over their chat history.

11. **Send Text or Image:**
    - Support for sending both text and image messages.

## Used Packages

WhisperWave integrates the following packages to enhance functionality:

```yaml
dependencies:
  # For using Google fonts
  google_fonts: 

  # For using cupertino icons
  cupertino_icons: ^1.0.2
  
  # For integrating firebase
  firebase_core: ^2.2.0

  # For handling firebase authentication
  firebase_auth: ^4.1.3

  # For handling google sign in
  google_sign_in: ^5.4.2

  # For accessing cloud firestore database
  cloud_firestore: ^4.1.0

  # For showing network images
  cached_network_image: ^3.2.3

  # For picking images
  image_picker: ^0.8.6

  # For accessing Firebase Storage (for uploading files)
  firebase_storage: ^11.0.6

  # For showing Emojis
  emoji_picker_flutter: ^1.5.1

  # For accessing firebase messaging (Push Notification)
  firebase_messaging: ^14.2.0

  # For calling RestAPIs
  http: ^0.13.5

  # For creating notification channel
  flutter_notification_channel: ^2.0.0

  # For storing images into gallery
  gallery_saver: ^2.3.2
