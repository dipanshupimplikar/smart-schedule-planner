# 📅 Smart Schedule Planner

A modern Android app for scheduling and visualizing time-based events with overlap detection — built using Jetpack Compose, Room, Paging 3, Hilt, and Clean Architecture in a multi-module setup.

---

## ✨ Features

- Add, update, and delete time-based events
- Visually aligned layout for overlapping events (like Google Calendar)
- Room Database with Paging 3 support
- Jetpack Compose UI using Material 3
- ViewModel-driven state management (MVVM)
- Hilt for Dependency Injection
- Multi-module Gradle setup using Kotlin DSL and Version Catalog

---

## 🛠 Tech Stack

- **Kotlin** 2.0.0
- **Jetpack Compose** (BOM-managed)
- **Room** 2.7.1 + **Paging 3**
- **Hilt** 2.56.1 for Dependency Injection
- **KSP** for Room annotation processing
- **MVVM + Clean Architecture**
- **Multi-module** (`app`, `data`, `domain`, `ui`)
- **Gradle Kotlin DSL** with `libs.versions.toml`

---

## 🧱 Project Structure
```text
:app       → Entry point, Hilt setup, navigation
:ui        → Compose UI components & ViewModels
:domain    → Business logic, entities, and use cases
:data      → Room DB, repository implementations, and paging source
```

---

## 📸 Screenshots

_Screenshots coming soon..._

---
## 🔄 Roadmap

- [x] Multi-module project setup with Kotlin DSL
- [ ] Add Room database with KSP
- [ ] Integrate Paging 3
- [ ] Implement event overlap layout logic
- [ ] Add drag-and-drop event rescheduling
- [ ] Add calendar view (day/week toggle)
- [ ] Sync events using Firebase (optional)
- [ ] Add tests and CI setup

---

## 🧪 Testing

- Unit Testing with JUnit
- UI Testing with Compose Testing APIs
- Instrumentation Testing setup via `androidx.test`

---
## 🧑‍💻 Author

**Dipanshu Pimplikar**  
[LinkedIn](https://www.linkedin.com/in/dipanshu-pimplikar) 

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
