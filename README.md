# Campus Collaborate

Campus Collaborate is a platform designed for students to collaborate, showcase their projects, and connect with like-minded peers. The application offers various features, including student profiles, project portfolios, multimedia support, a rating and feedback system, and more.

## Features

- **User Profiles**: Each user has a profile showcasing their projects, skills, and academic background.
- **Project Portfolios**: Users can create, manage, and showcase their projects, including details like project title, domain, description, duration, status, type, contributors, and multimedia uploads.
- **Collaboration**: Users can collaborate with others by adding contributors to their projects.
- **Rating and Feedback System**: Projects can be rated and reviewed by other users, providing valuable feedback.
- **Help Requests**: Users can request help from the community by creating help requests with detailed descriptions.
- **Search Functionality**: Users can search for projects based on various criteria like project name, domain, etc.
- **Notifications**: Stay updated with the latest activities related to your projects and collaborations.

## Tech Stack

- **Flutter**: The entire application is built using the Flutter framework for a seamless and intuitive user experience across multiple platforms.
- **Provider**: State management is handled using the Provider package, ensuring efficient and scalable state management across the app.
- **Custom Widgets**: The app utilizes custom widgets to maintain a consistent and reusable UI design.
- **Firebase**: Backend services are integrated with Firebase, providing real-time database capabilities, authentication, and storage.

## Project Structure
Campus-Collaborate/
└── lib/
    ├── chats/
        ├── models/
            ├── conversation.dart
            └── message.dart
        ├── providers/
            └── database_provider.dart
        └── screens/
            ├── chat_splash_screen.dart
            ├── dm_chat_screen.dart
            ├── dm_message_screen.dart
            ├── group_chat_screen.dart
            └── group_message_screen.dart
    ├── constants/
    ├── models/
    ├── screens/
        ├── bottom_nav_bar_screen.dart
        ├── create_project_screen.dart
        ├── home_screen.dart
        ├── login_screen.dart
        ├── new_course_review_screen.dart
        ├── new_help_request_screen.dart
        ├── other_user_profile_screen.dart
        ├── profile_screen.dart
        ├── project_screen.dart
        ├── splash_screen.dart
        └── test_screen.dart
    ├── services/
        ├── contributor_cross.dart
        ├── docs_and_images.dart
        ├── drop_down_services.dart
        ├── nav_bar_services.dart
        ├── navigation_services.dart
        ├── reset_providers.dart
        └── roll_number_decoder.dart
    ├── widgets/
        ├── commonWidgets/
        └── createProjectScreen/
            └── image_collage.dart
    ├── firebase_options.dart
    ├── locator.dart
    ├── main.dart
    ├── routes.dart
    └── sample_data.dart

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/campus-collaborate.git
   ```
2. Navigate to the project directory:
   ```bash
   cd campus-collaborate
   ```
3. Install dependencies:
   ```bash
    flutter pub get
   ```
4. Run the app:
  ```bash
    flutter run
  ```
