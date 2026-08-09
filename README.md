# 👨‍🌾 Farming App - All-in-One Application for Farmers

An Android application designed to assist farmers by bringing multiple agricultural utilities, market insights, and community networking into a single unified platform.

## ✨ Key Features

- **🏛️ Government Yojna Awareness**: Information on agricultural schemes and government initiatives.
- **🛒 E-commerce Platform**: Buy and sell agricultural products, seeds, fertilizers, and equipment.
- **📊 Daily APMC Price Updates**: Real-time mandi prices and market rates across districts.
- **👥 Community Network**: Social feed for farmers to share knowledge, questions, and posts.
- **📚 Categorized Articles**: Knowledge base covering fruits, crops, diseases, and farming techniques.
- **🌤️ Weather Forecasting**: Accurate weather updates and forecasts tailored for farming decisions.

## 📱 Tech Stack & Architecture

- **Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI Components**: Android Jetpack, Material Design, ConstraintLayout, RecyclerView
- **Networking**: Retrofit 2, Gson
- **Async Operations**: Kotlin Coroutines
- **Backend & Database**: Firebase Authentication, Firestore, Storage, Realtime Database
- **Dependency Injection**: Kodein DI
- **Payment Integration**: Razorpay Checkout SDK
- **Local Persistence**: Android Room DB

## 🚀 Getting Started

### Prerequisites

- Android Studio Arctic Fox (or newer)
- JDK 1.8 / 11
- Android SDK (API Level 21 or higher)

### Setup

1. **Clone the Repository**:
   ```bash
   git clone <your-repository-url>
   cd Farming-App
   ```

2. **Firebase Setup**:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add your Android app package (`com.project.farmingapp`).
   - Download `google-services.json` and place it in the `app/` directory.

3. **Build & Run**:
   - Open the project in Android Studio.
   - Sync Gradle project files.
   - Run on an emulator or physical Android device.

## 📜 License

This project is open-source under the [MIT License](LICENSE).
