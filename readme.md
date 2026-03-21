<div align="center">



\# 🏠 RooMe



\### \*Dormitory Management System\*



A native Android application for streamlining dormitory operations — from resident management to room tracking — built with Kotlin and powered by Firebase.



<br />



!\[Kotlin](https://img.shields.io/badge/Kotlin-1.8-7F52FF?style=for-the-badge\&logo=kotlin\&logoColor=white)

!\[Android](https://img.shields.io/badge/Android-API%2021+-3DDC84?style=for-the-badge\&logo=android\&logoColor=white)

!\[Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge\&logo=firebase\&logoColor=black)

!\[Gradle](https://img.shields.io/badge/Gradle-7.4-02303A?style=for-the-badge\&logo=gradle\&logoColor=white)

!\[License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)





</div>



\---



\## 📖 About The Project



\*\*DormDynamo\*\* is a full-featured Android dormitory management app designed to simplify the administration of student housing. Built natively in Kotlin with Firebase as the backend, it provides administrators and residents with a centralised platform to manage rooms, occupants, and day-to-day dorm operations — all from a mobile device.



This project was developed to demonstrate practical Android development skills including real-time database integration, modern Kotlin patterns, and a clean user experience with AndroidX components.



\### Key Highlights



\- 🔥 \*\*Firebase backend\*\* for real-time data sync and cloud storage

\- 📱 \*\*Native Android\*\* experience built entirely in Kotlin

\- 🏘️ \*\*Room \& resident management\*\* in one unified interface

\- 🔐 \*\*Google Services integration\*\* for authentication and cloud features

\- ♻️ \*\*AndroidX\*\* components for modern, backward-compatible UI

\- 🧹 \*\*Clean code\*\* with official Kotlin code style enforced



\---



\## 🛠️ Built With



| Layer | Technology |

|---|---|

| Language | \[Kotlin 1.8](https://kotlinlang.org/) |

| Platform | \[Android SDK](https://developer.android.com/) |

| Backend \& Database | \[Firebase](https://firebase.google.com/) |

| UI Components | \[AndroidX](https://developer.android.com/jetpack/androidx) |

| Build System | \[Gradle 7.4](https://gradle.org/) |

| Dependency Source | \[JitPack](https://jitpack.io/) + Maven Central |



\---



\## 🚀 Getting Started



\### Prerequisites



\- \*\*Android Studio\*\* Flamingo or later

\- \*\*JDK 11\*\* or higher

\- A \*\*Firebase project\*\* with `google-services.json` configured



\### Installation



```bash

\# 1. Clone the repository

git clone https://github.com/tishoneyxdd/DormManagement.git



\# 2. Open the project in Android Studio

\#    File → Open → Select the DormManagement folder



\# 3. Add your Firebase config file

\#    Place google-services.json inside the /app directory



\# 4. Sync Gradle and run the app

\#    Click "Sync Now" when prompted, then Run → Run 'app'

```



\### Firebase Setup



1\. Go to \[Firebase Console](https://console.firebase.google.com/) and create a new project

2\. Register your Android app with the package name from the project

3\. Download `google-services.json` and place it in `/app/`

4\. Enable the Firebase services used by the app (Realtime Database / Firestore, Authentication, etc.)



\---



\## 📁 Project Structure



```

DormManagement/

├── app/                        # Main application module

│   ├── src/

│   │   └── main/

│   │       ├── java/           # Kotlin source files

│   │       ├── res/            # Layouts, drawables, strings

│   │       └── AndroidManifest.xml

│   └── build.gradle            # App-level Gradle config

├── gradle/

│   └── wrapper/                # Gradle wrapper files

├── .idea/                      # Android Studio project settings

├── build.gradle                # Project-level Gradle config

├── gradle.properties           # Gradle JVM and Android settings

├── settings.gradle             # Project name \& module includes

└── gradlew / gradlew.bat       # Gradle wrapper scripts

```



\---



\## ⚙️ Configuration



Key settings in `gradle.properties`:



```properties

android.useAndroidX=true          # AndroidX enabled

kotlin.code.style=official        # Official Kotlin style guide

android.nonTransitiveRClass=true  # Optimised R class generation

org.gradle.jvmargs=-Xmx2048m     # 2GB JVM heap for builds

```



<div align="center">



Made with ❤️ by \[tishoneyxdd](https://github.com/tishoneyxdd)



</div>

