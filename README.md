# 🎵 NCT Lite - Mobile Application

**NCT Lite** is a native Android mobile application built with **Kotlin**, simulating the core functionalities of the NhacCuaTui music app. It offers a smooth user experience and a friendly interface.

---

## 📱 Product Demo (Screenshots)

| Home Screen | Player Screen | Playlist Screen | Search Screen |
|:---:|:---:|:---:|:---:|
| <img width="180" src="https://github.com/user-attachments/assets/b4cf199a-6030-423d-8b4c-1512dceac9ac" /> | <img width="180" src="https://github.com/user-attachments/assets/302a2659-6e95-428a-99f1-3d2b523ec79e" /> | <img width="180" src="https://github.com/user-attachments/assets/cdf7d447-8b2f-4089-a75b-0be48eb059c0" /> | <img width="180" src="https://github.com/user-attachments/assets/0f512c6e-04f3-4a74-9b87-d0e98b649a61" /> |

---

## ⚡ Quick Overview

| ✨ Key Features | 🛠 Tech Stack |
| :--- | :--- |
| 🎶 **Online Streaming:** Fetch songs/albums via API. | 🌐 **Networking:** Retrofit2, Gson, OkHttp3. |
| 💾 **Offline Storage:** Local DB with Room Database. | 🗄️ **Database:** Room (SQLite abstraction). |
| 🎨 **Modern UI:** Material Design & ViewBinding. | 🖼️ **Images:** Picasso for smooth loading. |
| 🏗️ **Architecture:** Clean MVVM pattern. | ⚙️ **Core:** Kotlin Coroutines & LiveData. |
| 🔍 **Smart Search:** Find any tracks instantly. | 🚀 **Build Tool:** Gradle (Kotlin DSL). |

---

## 🛠 Detailed Technology Breakdown

| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat&logo=kotlin&logoColor=white) |
| **UI Framework** | XML Layouts, ConstraintLayout, Material Components |
| **Architecture** | MVVM (Model-View-ViewModel) |
| **Concurrency** | Kotlin Coroutines, LiveData |
| **API Debugging** | OkHttp Logging Interceptor |

---

## 🚀 Installation & Setup

### 📋 Prerequisites
* Android Studio (Latest version) | JDK 11+ | Android Device/Emulator

### 🛠 Steps
1. **Clone:** `git clone https://github.com/username/NCT-Lite-MobileApp.git`
2. **Open:** Launch Android Studio and open the project folder.
3. **Sync:** Let Gradle download dependencies.
4. **Run:** Press `Shift + F10` to build and launch.

---

## 📂 Project Structure

```text
NCT-Lite-MobileApp/
├── 📦 data/          # Room Database, Retrofit API Services
├── 🎨 ui/            # Activities, Fragments, ViewModels
├── 📑 model/         # Data Models (POJO)
└── 🛠 utils/         # Helpers & Extensions
