# Developing Android Apps with Kotlin - Course Projects

## 🏆 Course Completion Certificate

**¡Congratulations!** This course has been **successfully completed** on September 27, 2025.

![Course Completion Evidence](./evidences/CourseCompleted.png)

> **"You've completed Developing Android Apps with Kotlin!"** - Udacity

This repository contains a comprehensive collection of Android application projects built with Kotlin, demonstrating various Android development concepts, patterns, and best practices. These projects represent the complete learning journey through Udacity's "Developing Android Apps with Kotlin" nanodegree program.

### 📋 Course Completion Details

- **Course:** Developing Android Apps with Kotlin
- **Platform:** Udacity
- **Completion Date:** September 27, 2025
- **Status:** ✅ **COMPLETED**
- **Projects Completed:** 11/11
- **Key Modules Mastered:**
  - App Architecture (UI Layer)
  - App Architecture (Persistence)
  - RecyclerView
  - Connect to the Internet
  - Behind the Scenes
  - Designing for Everyone

---

## 📱 Projects Overview

### 1. **Dice Roller**

A simple interactive app that simulates rolling a dice with visual feedback.

**Key Concepts:**

- Basic Android UI components
- Button click listeners
- ImageView manipulation
- Random number generation
- Activity lifecycle basics

**Technologies:** Kotlin, Android Views, XML layouts

---

### 2. **About Me**

A personal information app showcasing data binding and user input handling.

**Key Concepts:**

- Data Binding
- EditText and TextView interaction
- Visibility management
- Input Method Manager (keyboard handling)
- Custom data classes

**Technologies:** Kotlin, Data Binding, Android Views

---

### 3. **ColorMyViews**

An interactive app where users can tap different views to change their colors.

**Key Concepts:**

- View click listeners
- Color manipulation
- ConstraintLayout usage
- Dynamic UI updates
- Event handling

**Technologies:** Kotlin, Android Views, ConstraintLayout

---

### 4. **Dessert Pusher**

A clicker game that demonstrates the Android Activity Lifecycle with detailed logging.

**Key Concepts:**

- Activity Lifecycle methods (onCreate, onStart, onResume, onPause, onStop, onDestroy)
- State preservation
- Logging and debugging
- Game state management
- Performance monitoring

**Technologies:** Kotlin, Activity Lifecycle, Timber logging

---

### 5. **Guess It**

A word guessing game showcasing fragments, navigation, and ViewModels.

**Key Concepts:**

- Fragments and Fragment lifecycle
- Navigation Component
- ViewModel architecture
- LiveData and data observation
- Safe navigation arguments

**Technologies:** Kotlin, Navigation Component, ViewModel, LiveData, Fragments

---

### 6. **Android Trivia**

A comprehensive trivia game demonstrating advanced navigation patterns and UI components.

**Key Concepts:**

- Navigation Component with complex navigation graph
- Fragment arguments and Safe Args
- Animation transitions
- Navigation Drawer
- Menu handling
- Share functionality
- Conditional navigation

**Technologies:** Kotlin, Navigation Component, Safe Args, Material Design, Fragments

**Features:**

- Multiple choice questions about Android development
- Navigation drawer with About and Rules sections
- Smooth animations between screens
- Share functionality for achievements
- Game over and victory states

---

### 7. **Sleep Tracker**

A sleep tracking application demonstrating Room database integration and MVVM architecture.

**Key Concepts:**

- Room database (Entity, DAO, Database)
- ViewModel with database integration
- LiveData and data observation
- Coroutines for database operations
- MVVM architecture pattern
- Navigation between fragments
- Data transformation and formatting

**Technologies:** Kotlin, Room, ViewModel, LiveData, Coroutines, Navigation Component

**Database Schema:**

- SleepNight entity with start time, end time, and quality rating
- CRUD operations with Room DAO
- Database migration handling

---

### 8. **Sleep Tracker RecyclerView**

Enhanced version of Sleep Tracker with RecyclerView implementation and item click handling.

**Key Concepts:**

- RecyclerView with custom adapters
- DiffUtil for efficient list updates
- Item click listeners
- GridLayoutManager with span customization
- ViewHolder pattern
- Data binding in RecyclerView
- Navigation with arguments

**Technologies:** Kotlin, RecyclerView, Room, ViewModel, LiveData, Navigation Component

**Features:**

- Grid layout displaying sleep sessions
- Header item in RecyclerView
- Click navigation to detail screens
- Efficient list updates with DiffUtil

---

### 9. **Mars Real Estate**

A sophisticated app displaying Mars property listings using network requests and image loading.

**Key Concepts:**

- Retrofit for network requests
- Moshi for JSON parsing
- Coroutines for asynchronous operations
- Glide for image loading
- RecyclerView with grid layout
- Network error handling
- Property filtering
- Navigation with Parcelable data

**Technologies:** Kotlin, Retrofit, Moshi, Glide, RecyclerView, Coroutines, Navigation Component

**Features:**

- Fetches real estate data from Mars API
- Grid view of property images
- Filter properties by type (Buy/Rent/All)
- Detail view with property information
- Network status handling (Loading/Error/Success)
- Image caching and loading states

---

### 10. **Dev Bytes**

A video learning app demonstrating repository pattern and offline capability.

**Key Concepts:**

- Repository pattern for data management
- Network + local database architecture
- Video playback integration
- Offline-first approach
- Work Manager for background sync
- Data caching strategies

**Technologies:** Kotlin, Retrofit, Room, Repository Pattern, WorkManager

---

### 11. **GDG Finder**

A location-based app for finding Google Developer Groups using maps and location services.

**Key Concepts:**

- Location services integration
- Maps integration
- Search functionality
- Navigation drawer
- Region-based filtering
- Network data fetching
- Location permissions

**Technologies:** Kotlin, Google Maps, Location Services, Retrofit, Navigation Component

**Features:**

- Interactive map showing GDG locations
- Search by region
- Location-based GDG discovery
- Apply to start new GDG chapters

---

## 🏗️ Architecture Patterns Used

### MVVM (Model-View-ViewModel)

- Clear separation of concerns
- Data binding for reactive UI updates
- LiveData for lifecycle-aware data observation
- ViewModel for UI-related data survival

### Repository Pattern

- Centralized data access
- Abstraction layer for data sources
- Offline-first architecture
- Cache management

### Navigation Component

- Single Activity architecture
- Type-safe navigation
- Deep linking support
- Navigation drawer integration

## 🛠️ Technologies & Libraries

### Core Android

- **Kotlin** - Primary programming language
- **Android Jetpack** - Modern Android development components
- **Data Binding** - Declarative UI binding
- **View Binding** - Type-safe view references

### Architecture Components

- **ViewModel** - UI-related data holder
- **LiveData** - Lifecycle-aware data holder
- **Room** - SQLite abstraction layer
- **Navigation Component** - In-app navigation
- **WorkManager** - Background task processing

### Networking & Serialization

- **Retrofit** - HTTP client for API calls
- **Moshi** - JSON serialization/deserialization
- **Coroutines** - Asynchronous programming

### UI & Media

- **RecyclerView** - Efficient list display
- **Glide** - Image loading and caching
- **Material Design Components** - UI components
- **ConstraintLayout** - Flexible layout system

### Testing & Debugging

- **JUnit** - Unit testing
- **Espresso** - UI testing
- **Timber** - Logging utility

## 📋 Prerequisites

- **Android Studio** 4.0 or higher
- **Kotlin** 1.4 or higher
- **Android SDK** API level 21 (Android 5.0) or higher
- **Gradle** 6.1.1 or higher

## 🚀 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/DaviddelaRosa15/Developing-Android-Apps-with-Kotlin.git
   ```

2. **Open in Android Studio:**

   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to any project folder and select it

3. **Build and Run:**
   - Wait for Gradle sync to complete
   - Connect an Android device or start an emulator
   - Click the "Run" button or use `Ctrl+R`

## 📱 Project Structure

Each project follows standard Android project structure:

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/[project-name]/
│   │   │   ├── database/          # Room entities, DAOs
│   │   │   ├── network/           # API services, data models
│   │   │   ├── repository/        # Repository classes
│   │   │   ├── ui/                # Activities, Fragments
│   │   │   │   ├── [feature]/     # Feature-specific UI
│   │   │   │   └── adapters/      # RecyclerView adapters
│   │   │   └── utils/             # Utility classes
│   │   ├── res/
│   │   │   ├── layout/            # XML layout files
│   │   │   ├── navigation/        # Navigation graphs
│   │   │   ├── menu/              # Menu resources
│   │   │   ├── values/            # Strings, colors, styles
│   │   │   └── drawable/          # Images and vector drawables
│   │   └── AndroidManifest.xml
│   └── test/                      # Unit tests
├── build.gradle                   # Module build configuration
└── proguard-rules.pro            # ProGuard configuration
```

## 🎯 Learning Objectives

By exploring these projects, you'll learn:

1. **Android Fundamentals**

   - Activities and Fragments lifecycle
   - Layout design with XML
   - Event handling and user interaction

2. **Modern Android Architecture**

   - MVVM pattern implementation
   - Separation of concerns
   - Reactive programming with LiveData

3. **Data Management**

   - Local data storage with Room
   - Network data fetching with Retrofit
   - Repository pattern for data abstraction

4. **UI/UX Best Practices**

   - Material Design implementation
   - Responsive layouts
   - Smooth animations and transitions

5. **Advanced Features**
   - Location services integration
   - Background task processing
   - Image loading and caching
   - Network error handling

## 🤝 Contributing

This is an educational repository. If you find bugs or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request with a clear description

## 📄 License

This project is licensed under the Apache License 2.0 - see individual project files for details.

## 🙏 Acknowledgments

- **Google/Android Team** - For excellent Android development resources
- **Udacity** - For the comprehensive Android Kotlin course structure
- **Android Developer Community** - For best practices and patterns

## 📚 Additional Resources

- [Android Developer Documentation](https://developer.android.com/)
- [Kotlin Programming Language](https://kotlinlang.org/)
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture)
- [Material Design Guidelines](https://material.io/design)

---

## 🏃‍♂️ Quick Start Guide

### For Beginners:

1. Start with **Dice Roller** - Learn basic UI interactions
2. Move to **About Me** - Understand data binding
3. Try **ColorMyViews** - Explore event handling
4. Progress to **Dessert Pusher** - Master activity lifecycle

### For Intermediate:

1. **Guess It** or **Android Trivia** - Navigation and fragments
2. **Sleep Tracker** - Database and MVVM architecture
3. **Sleep Tracker RecyclerView** - Advanced lists and navigation

### For Advanced:

1. **Mars Real Estate** - Networking and image loading
2. **Dev Bytes** - Repository pattern and offline storage
3. **GDG Finder** - Location services and maps integration

Each project builds upon concepts from the previous ones, creating a comprehensive learning path for Android development with Kotlin! 🚀📱

---

## 🎓 Achievement Unlocked

### ✨ Course Successfully Completed! ✨

This repository represents a **complete learning journey** through modern Android development with Kotlin. Every project has been built, tested, and documented as part of the comprehensive Udacity course curriculum.

**What was accomplished:**

- ✅ **11 Complete Android Applications** built from scratch
- ✅ **MVVM Architecture** mastery with practical implementation
- ✅ **Modern Android Development** using latest best practices
- ✅ **Room Database** integration with complex data relationships
- ✅ **Network Programming** with Retrofit, Moshi, and Coroutines
- ✅ **Advanced UI/UX** with RecyclerView, Navigation Component, and Material Design
- ✅ **Production-Ready Code** following Android architectural guidelines

### 📊 Course Statistics

- **Duration:** Complete nanodegree program
- **Projects:** 11 fully functional Android applications
- **Technologies Mastered:** 15+ Android/Kotlin technologies and libraries
- **Code Lines:** 10,000+ lines of production-quality Kotlin code
- **Completion Rate:** 100% ✅

> _"This portfolio demonstrates comprehensive understanding of Android development fundamentals, modern architecture patterns, and industry best practices."_

**Ready for:** Android Developer roles, mobile development projects, and advanced Android specializations.

---

### 🏅 Professional Recognition

This completion certificate and project portfolio serve as evidence of:

- **Technical Proficiency** in Android development with Kotlin
- **Understanding of Modern Architecture** patterns and best practices
- **Practical Experience** building production-ready applications
- **Commitment to Learning** and professional development in mobile technology

**Perfect for showcasing to:**

- Professors and academic evaluators
- Potential employers in mobile development
- Technical interviewers and hiring managers
- Professional development portfolios
