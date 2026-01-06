# BulletDrone

**BulletDrone** is a Kotlin-based mobile application designed for a shooting range to record shooters’ training or competition sessions. It integrates with **Parrot SDK** for drone control and **Firebase** (Firestore and Storage) for user data management and cloud storage.

## My Role & Contributions
- Developed core Android application logic using Kotlin
- Integrated Parrot SDK for drone control, live video feed, and recording
- Implemented Firebase Firestore integration to fetch shooter profiles dynamically
- Designed and implemented Firebase Storage upload flow for large video files
- Created structured file-naming and directory logic for cloud storage
- Worked with asynchronous data flows and SDK callbacks in a real-time environment

This project gave me hands-on experience with hardware SDKs, real-time video handling, and cloud-based data management in a production-like setting.

---

## Features

### Main Page
- **Fly View**: Control the drone and start recording videos.
- **Gallery**: Manage videos/photos, including downloading, deleting, and uploading to Firebase Storage.

![Main Page](Screenshot_20241217_165436_BulletDrone.jpg)

---

### Fly View
- Start and stop drone video recording.
- Monitor the battery status of both the drone and remote.
- Control all drone flight functionalities.

![Fly View](Screenshot_20241217_165507_BulletDrone.jpg)

---

### Gallery
- Browse through recorded videos and photos stored on the drone's SD card.
- Download videos/photos to your phone.
- Delete unnecessary files.

![Gallery](Screenshot_20241217_165516_BulletDrone.jpg)
  
- **Fetch user names from Firestore**: Select the shooter's name from a dropdown/list populated by Firestore.
- **Upload videos to Firebase Storage**:
  - Automatically creates a directory for each shooter in Firebase.
  - Organizes file naming (e.g., `ShooterName_(ActivityType)_YYYYMMDD_HHMMSS.MP4`).

![Uploading to Firebase](Screenshot_20241217_165527_BulletDrone.jpg)
![File naming logic](Sieppaa.PNG)

---

## Technologies Used
- **Kotlin**: Core development language  
- **Parrot SDK**: Drone control and video management  
- **Firebase Storage**: Cloud storage for video files  
- **Firestore**: User data management (fetching shooter names)  
- **Android Studio**: Integrated Development Environment (IDE) for Android  
