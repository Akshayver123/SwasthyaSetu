# SwasthyaSetu - Healthcare Companion App 🏥

A comprehensive Android healthcare application designed to provide users with immediate medical assistance, health monitoring, and emergency services at their fingertips.

## 📱 Features

### 🚨 Emergency Services
- **Emergency Contacts**: Quick access to ambulance, police, and emergency helplines
- **Hospital Locator**: Find nearby hospitals with real-time navigation
- **First Aid Guide**: Step-by-step first aid instructions for common emergencies

### 🤖 AI Health Assistant
- **Symptom Checker**: AI-powered symptom analysis and potential diagnosis
- **Health Chat**: Interactive chatbot for health-related queries
- **Medicine Information**: Detailed information about medications and usage

### 📋 Health Management
- **Appointment Booking**: Schedule appointments with doctors and hospitals
- **Medication Reminders**: Set reminders for medications and refills
- **Health History**: Track your medical history and appointments
- **Vaccination Records**: Maintain vaccination schedules and records

### 🏥 Medical Services
- **Hospital Finder**: Locate hospitals, clinics, and pharmacies nearby
- **Doctor Consultation**: Book online and offline consultations
- **Lab Results**: View and manage medical test results
- **Health Tips**: Daily health and wellness tips

### 🌐 Multi-Language Support
- **English & Hindi**: Full bilingual support for better accessibility
- **Regional Language Support**: Easy switching between languages

## 🛠️ Technical Stack

- **Platform**: Android
- **Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI Framework**: Android Jetpack Compose
- **Backend Integration**: Firebase
- **Maps**: Google Maps API
- **AI/ML**: TensorFlow Lite for on-device processing

## 📦 Dependencies

- **Android Jetpack**: Navigation, ViewModel, LiveData
- **Networking**: Retrofit2, OkHttp
- **Image Loading**: Glide
- **Maps**: Google Maps SDK
- **Authentication**: Firebase Auth
- **Database**: Room Database
- **AI Integration**: OpenAI API for health chat

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK 30 or higher
- Kotlin 1.5.0 or higher
- Google Maps API Key
- Firebase project configuration

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Akshayver123/SwasthyaSetu.git
   cd SwasthyaSetu/Application
   ```

2. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Download `google-services.json` and place it in `app/` directory
   - Enable Authentication, Firestore, and Cloud Messaging

3. **Set up Google Maps API**
   - Get API key from [Google Cloud Console](https://console.cloud.google.com/)
   - Add the key to `local.properties`:
     ```properties
     MAPS_API_KEY=your_api_key_here
     ```

4. **Build and Run**
   ```bash
   ./gradlew build
   ./gradlew installDebug
   ```

## 📱 App Screens

| Home Screen | Emergency Services | AI Health Chat |
|-------------|-------------------|----------------|
| ![Home](screenshots/home.png) | ![Emergency](screenshots/emergency.png) | ![Chat](screenshots/chat.png) |

| Hospital Finder | Profile | Appointments |
|-----------------|---------|---------------|
| ![Hospitals](screenshots/hospitals.png) | ![Profile](screenshots/profile.png) | ![Appointments](screenshots/appointments.png) |

## 🔧 Configuration

### Environment Variables
Create a `local.properties` file in the root directory:

```properties
MAPS_API_KEY=your_google_maps_api_key
OPENAI_API_KEY=your_openai_api_key
FIREBASE_PROJECT_ID=your_firebase_project_id
```

### Firebase Setup
1. Enable Firebase Authentication
2. Set up Firestore Database
3. Configure Cloud Messaging for notifications
4. Enable Firebase Crashlytics

## 📊 Project Structure

```
Application/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/swasthyasetu/
│   │   │   ├── ui/          # UI components and activities
│   │   │   ├── data/        # Data models and repositories
│   │   │   ├── network/     # API interfaces and networking
│   │   │   ├── utils/       # Utility classes
│   │   │   └── viewmodel/   # ViewModels for MVVM
│   │   ├── res/             # Resources (layouts, drawables, strings)
│   │   └── AndroidManifest.xml
│   ├── build.gradle.kts     # App-level build configuration
│   └── google-services.json # Firebase configuration
├── gradle/                  # Gradle wrapper
├── build.gradle.kts         # Project-level build configuration
└── README.md               # This file
```

## 🤝 Contributing

We welcome contributions to make SwasthyaSetu better! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Code Style
- Follow Kotlin coding conventions
- Use meaningful variable and function names
- Add comments for complex logic
- Ensure code is properly formatted

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reporting

If you find a bug, please report it by creating an issue on GitHub with:
- Detailed description of the bug
- Steps to reproduce
- Expected vs actual behavior
- Device and Android version information

## 📞 Contact

- **Developer**: Akshay Verma
- **Email**: akshayver@example.com
- **GitHub**: [@Akshayver123](https://github.com/Akshayver123)

## 🙏 Acknowledgments

- Google Maps API for location services
- Firebase for backend services
- OpenAI for AI health assistant
- Medical professionals for health content validation
- Open-source community for various libraries

## 📈 Roadmap

### Upcoming Features
- [ ] Integration with wearable devices
- [ ] Video consultation with doctors
- [ ] Health insurance integration
- [ ] Mental health support features
- [ ] Diet and nutrition tracking
- [ ] Exercise and fitness tracking
- [ ] Multi-city hospital networks
- [ ] Emergency ambulance booking

### Version History
- **v1.0.0** - Initial release with core features
- **v1.1.0** - Added AI health chat and vaccination tracking
- **v1.2.0** - Enhanced UI/UX and performance improvements

---

**⚠️ Disclaimer**: This app is for informational purposes only and should not replace professional medical advice. Always consult with qualified healthcare professionals for medical concerns.

**Made with ❤️ for better healthcare accessibility in India**
