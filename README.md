# Echoon---A-introvert-Social-Media-app
Echoon is the social media Android based app specially designed for the introverts with respect to their requirements.

🌿 Echoon – A Social Media App for Introverts
“Connect Quietly, Express Freely.”
🧠 Overview

Echoon is a minimal and calm social media application designed especially for introverts — people who prefer subtle, text-and-photo-based interaction rather than noisy and overwhelming engagement.

This app provides a safe and comfortable digital space for self-expression, sharing thoughts, and connecting through meaningful posts — without video content or social pressure.

✨ Key Features

🏠 Home Feed:
View posts shared by users in a simple, card-based layout.

🔍 Search Tab:
Explore users, trending hashtags, and suggestions.

➕ Add Post:
Upload photos with captions or share thoughts through text-only posts.

❤️ Like & Comment System:
Interact in a light, non-intrusive way — perfect for introverts.

👤 Profile Page:
View user profiles and their uploaded posts.

🧘 Soft & Calm UI:
Built using a white theme and Material 3 design for a peaceful experience.

⚙️ Technology Stack
Component	Technology
Language	Kotlin
UI Layouts	XML (Material 3 Components)
Database	SQLite (Local)
IDE	Android Studio
Architecture	MVVM (Model–View–ViewModel)
Target SDK	Android 14 (API 34)
💾 Local Database – EchoonDatabaseHelper.kt

The app uses SQLite for local data persistence.
This database manages:

Users: Registration, bio, profile image

Posts: Captions, images, timestamps

Comments & Likes: Interactions on posts

Key tables:

users

posts

comments

It supports CRUD operations and foreign key relationships for better data management.

🏗️ App Structure
com.example.echoon/
├── ui/
│   ├── HomeFragment.kt
│   ├── AddPostFragment.kt
│   ├── SearchFragment.kt
│   ├── ProfileFragment.kt
│   └── adapters/
│       ├── FeedAdapter.kt
│       └── SuggestedUserAdapter.kt
│
├── data/
│   ├── FeedModel.kt
│   ├── SuggestedUserModel.kt
│   └── PostRepository.kt
│
├── database/
│   └── EchoonDatabaseHelper.kt
│
└── MainPage.kt

🧩 How to Run

Clone the repository:

git clone https://github.com/yourusername/Echoon-App.git


Open the project in Android Studio.

Sync Gradle and let dependencies download.

Run the app on an emulator or physical device.

Explore features: Add posts → View feed → Visit profile → Search users.

🎨 Design Philosophy

Echoon is built on the idea that introverts prefer depth over display.
The UI avoids unnecessary noise:

No videos, reels, or flashy animations.

Gentle transitions, minimal colors, and clean layouts.

Encourages personal expression and emotional comfort.

🚀 Future Enhancements

🔐 User authentication and login system.

☁️ Cloud synchronization with Firebase or backend API.

💬 Direct messaging between users.

🌓 Dark and custom themes.

🧠 Smart content recommendations.
