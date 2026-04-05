# 📚 StudyBuddy iOS App

## 👨‍💻 Project Overview

StudyBuddy is an iOS application designed to help students organize and manage their study subjects efficiently. Users can view subjects, explore details, and manage their study planning in a clean and user-friendly interface.

---

## 🎯 Features

* 📖 View list of subjects
* 🧠 Subject details screen
* 🖼️ Custom icons for each subject
* 💾 Local database using **SwiftData**
* 🎨 Smooth animations for better UI experience
* 📱 Clean and modern UI (SwiftUI)

---

## 🛠️ Technologies Used

* Swift
* SwiftUI
* SwiftData (Local Database)
* Xcode

---

## 🧱 Project Structure

### Models

* `Subject.swift`
  Represents each subject with:

  * name
  * description
  * image

### Views (Minimum 4)

* `ContentView` → Main screen (list of subjects)
* `SubjectCellView` → Each row UI
* `SubjectDetailView` → Detail screen
* `StudyBuddyApp` → Entry point

---

## 💾 Database

This app uses **SwiftData** as a local database to store and retrieve subject data.

Example:

```swift
@Query var subjects: [Subject]
```

---

🎬 Animations
.animation(.easeInOut) used for smooth transitions
UI updates dynamically when data changes

---

## 👨‍🎓 Author
Isharat Jahan

## 🎉 Conclusion

StudyBuddy is a simple yet powerful app to help students manage their studies effectively with a clean interface and smooth experience.
