# NCT Lite - Mobile Application

**NCT Lite** is a native Android mobile application built with **Kotlin**, simulating the core functionalities of the NhacCuaTui music app. It offers a smooth user experience and a friendly interface. This project demonstrates the application of modern Android architectures and Jetpack libraries.

## 📱 Product Demo (Screenshots)

This section showcases the actual interface of the application.

| Home Screen | Player Screen | Playlist Screen | Search Screen |
|:---:|:---:|:---:|:---:|
| <img src="./assets/home_screen.png" alt="Home Screen" width="200"/> | <img src="./assets/player_screen.png" alt="Player Screen" width="200"/> | <img src="./assets/playlist_screen.png" alt="Playlist Screen" width="200"/> | <img src="./assets/search_screen.png" alt="Search Screen" width="200"/> |

> *Note: Please replace the `./assets/...` paths with your actual product screenshots.*

## ✨ Key Features

*   **Online Music Streaming:** Connects to APIs to fetch songs, albums, and artist data.
*   **Offline Storage:** Utilizes **Room Database** to store favorite songs and local playlists.
*   **Modern Interface:** Designed with Material Design standards, leveraging ConstraintLayout and ViewBinding.
*   **Image Processing:** Smooth loading and display of album covers using **Picasso**.
*   **MVVM Architecture:** Clear separation between UI and Business Logic, ensuring code maintainability and scalability.

## 🛠 Tech Stack

This project leverages top-tier technologies and libraries in modern Android development:

*   **Language:** [Kotlin](https://kotlinlang.org/)
*   **Architecture:** MVVM (Model-View-ViewModel)
*   **UI:** XML Layouts, ViewBinding, Material Components
*   **Networking:**
    *   [Retrofit2](https://square.github.io/retrofit/): API Request handling.
    *   [Gson](https://github.com/google/gson): JSON Parsing.
    *   [OkHttp3 Logging Interceptor](https://github.com/square/okhttp/tree/master/okhttp-logging-interceptor): API Debugging.
*   **Local Database:** [Room Database](https://developer.android.com/training/data-storage/room) (SQLite abstraction).
*   **Image Loading:** [Picasso](https://square.github.io/picasso/).
*   **Concurrency:** Kotlin Coroutines & LiveData.
*   **Build Tool:** Gradle (Kotlin DSL).

## 🚀 Installation & Setup

To run this project on your local machine, follow these steps:

### Prerequisites
*   Android Studio (Latest version recommended).
*   JDK 11 or newer.

### Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/username/NCT-Lite-MobileApp.git
    cd NCT-Lite-MobileApp
    ```

2.  **Open in Android Studio:**
    *   Launch Android Studio.
    *   Select **Open** and navigate to the `NCT-Lite-MobileApp` directory.

3.  **Sync Gradle:**
    *   Wait for Android Studio to download dependencies and index the project.

4.  **Configure Device:**
    *   Connect a physical Android device or start an Android Emulator.

5.  **Build & Run:**
    *   Click the **Run (▶)** button on the toolbar or press `Shift + F10`.

## 📂 Project Structure

```text
NCT-Lite-MobileApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/nct_lite/
│   │   │   │   ├── data/          # Data handling (Room, Retrofit)
│   │   │   │   ├── ui/            # UI components (Activities, Fragments, ViewModels)
│   │   │   │   ├── model/         # Data models
│   │   │   │   └── utils/         # Utility classes
│   │   │   └── res/               # Resources (Layouts, Drawables, Values)
│   └── build.gradle.kts           # App-level build configuration
├── build.gradle.kts               # Project-level build configuration
└── README.md
```

## 👤 Author

*   **Your Name**
*   Email: email@example.com
*   LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com)
*   GitHub: [github.com/username](https://github.com)

---
*This project is for educational purposes and to demonstrate Android development skills.*
