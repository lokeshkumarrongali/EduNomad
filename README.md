# EduNomad - Mobile Learning Platform

A comprehensive Android application for on-the-go learning, providing access to educational courses, interactive content, and personalized learning experiences.

## 📱 Overview

EduNomad is a modern mobile learning platform built with Kotlin and Android Jetpack components. The app offers a seamless learning experience with features like course browsing, video lectures, PDF materials, interactive quizzes, and user progress tracking.

## ✨ Features

### 🎓 Learning Management
- **Course Catalog**: Browse and discover courses across various categories
- **Course Categories**: Organized content for easy navigation
- **Search Functionality**: Find courses and content quickly
- **Course Details**: Comprehensive information about each course
- **Enrollment System**: Easy course enrollment and management

### 📚 Content Delivery
- **Video Player**: Integrated video streaming for lectures
- **PDF Viewer**: Access to course materials and documents
- **Interactive Quizzes**: Assess knowledge with engaging quizzes
- **Progress Tracking**: Monitor learning progress and achievements

### 👤 User Experience
- **User Authentication**: Secure sign-in and sign-up with Firebase
- **Personalized Dashboard**: Customized home screen with enrolled courses
- **Profile Management**: Edit user information and preferences
- **Settings**: Customizable app preferences
- **Dark/Light Theme**: Material Design theme support

### 🤝 Interactive Features
- **Ask Me Anything**: Q&A section for course-related questions
- **Chat System**: Real-time messaging for course discussions
- **My Courses**: Personal collection of enrolled courses
- **Enrolled Courses**: Track active learning sessions

## 🛠 Technical Stack

### Core Technologies
- **Language**: Kotlin
- **Platform**: Android (API 24+)
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI Framework**: Material Design Components
- **View Binding**: Type-safe view references

### Dependencies & Libraries
- **Firebase**: Authentication, Firestore, Storage
- **Navigation Component**: Fragment navigation
- **ViewPager2**: Tabbed interfaces and sliders
- **RecyclerView**: Efficient list rendering
- **Glide**: Image loading and caching
- **ExoPlayer**: Video playback
- **OkHttp**: HTTP client for API calls
- **Lifecycle Components**: ViewModel and LiveData

### Build Configuration
- **Gradle**: Kotlin DSL
- **Compile SDK**: 35
- **Target SDK**: 34
- **Min SDK**: 24 (Android 7.0)
- **Java Version**: 1.8

## 📁 Project Structure

```
app/src/main/java/com/example/edunomad/
├── Activities/
│   ├── MainActivity.kt              # Main app screen
│   ├── SignInActivity.kt            # User authentication
│   ├── SignUpActivity.kt            # User registration
│   ├── CourseDetailsActivity.kt     # Course information
│   ├── VideoPlayerActivity.kt       # Video playback
│   ├── PdfViewerActivity.kt         # PDF viewing
│   ├── QuizActivity.kt              # Interactive quizzes
│   └── ...                          # Other feature activities
├── Adapters/
│   ├── CourseAdapter.kt             # Course list adapter
│   ├── CategoryAdapter.kt           # Category list adapter
│   ├── QuizListAdapter.kt           # Quiz list adapter
│   └── ...                          # Other adapters
├── Models/
│   ├── Course.kt                    # Course data model
│   ├── Category.kt                  # Category data model
│   ├── QuizModel.kt                 # Quiz data model
│   └── ...                          # Other data models
└── Fragments/
    ├── HomeFragment.kt              # Home screen fragment
    ├── ProfileFragment.kt           # User profile fragment
    └── SearchFragment.kt            # Search functionality
```

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK (API 24+)
- Firebase project configuration
- Google Play Services

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd EduNomad
   ```

2. **Firebase Setup**
   - Create a new Firebase project
   - Download `google-services.json`
   - Place it in `app/google-services.json`

3. **Configure Firebase Services**
   - Enable Authentication (Email/Password)
   - Set up Firestore Database
   - Configure Firebase Storage

4. **Build and Run**
   - Open the project in Android Studio
   - Sync Gradle dependencies
   - Run the app on an emulator or device

### Configuration

Update the following files as needed:
- `app/google-services.json` - Firebase configuration
- `app/build.gradle.kts` - Dependencies and build settings
- `local.properties` - Local configuration (SDK path, API keys)

## 🔧 Key Components

### Authentication System
- Firebase Authentication integration
- Email/password sign-in and sign-up
- Session management with Firebase Auth

### Course Management
- Firestore database for course data
- Firebase Storage for media files
- Real-time data synchronization

### Media Handling
- ExoPlayer for video streaming
- Custom PDF viewer implementation
- Glide for image loading and caching

### User Interface
- Material Design Components
- Responsive layouts for various screen sizes
- Navigation drawer and bottom navigation
- Custom themes and styles

## 📱 App Screens

1. **Authentication Flow**
   - Sign In / Sign Up screens
   - Password recovery functionality

2. **Main Dashboard**
   - Featured courses carousel
   - Category navigation
   - Quick access to enrolled courses

3. **Course Discovery**
   - All courses listing
   - Category-based browsing
   - Search functionality

4. **Learning Experience**
   - Course details and syllabus
   - Video player for lectures
   - PDF viewer for materials
   - Interactive quizzes

5. **User Management**
   - Profile editing
   - Settings and preferences
   - Enrolled courses tracking

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Issues & Support

If you encounter any issues or have suggestions:
- Check existing issues on GitHub
- Create a new issue with detailed description
- Include steps to reproduce the problem

## 🔄 Version History

- **v1.0.0** - Initial release
  - Basic course browsing
  - User authentication
  - Video and PDF content support
  - Quiz functionality

## 🔮 Future Enhancements

- Offline mode support
- Push notifications for course updates
- Social learning features
- Certificate generation
- Multi-language support
- Advanced analytics dashboard

## 📞 Contact

For questions or support, please reach out through:
- GitHub Issues
- Project maintainers

---

**Built with ❤️ for the modern learner**
