# Template-Kotlin-Android-CleanMVVM

A modular, scalable Android architecture template built with Kotlin, following **MVVM** and **Clean Architecture** principles.  
This template provides a clean, maintainable, and testable foundation for Android projects using modern tools like Coroutines, Flow, Hilt, Retrofit, and Room.

Ideal for developers who want a robust starting point to build production-ready apps with a well-organized codebase.

---

## ✨ Features

- Clean and modular folder structure
- Predefined base setup for MVVM and Clean Architecture
- Built with Kotlin DSL and best practices
- Separation of concerns between presentation, domain, and data layers
- Dependency injection with Hilt
- Reactive streams with Kotlin Flow
- Easily extendable for any new feature

---

## 🧱 Architecture

This template follows the principles of [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/The-Clean-Architecture.html) by Uncle Bob, ensuring a decoupled and testable structure. It uses the MVVM pattern at the presentation layer and separates concerns via modular layers.

### Layers

- **Presentation (`app`)**: UI, ViewModels, Hilt injection setup
- **Domain**: UseCases, business logic, entities (independent of Android SDK)
- **Data**: Repositories, mappers, data sources
- **Remote**: Handles API interaction via Retrofit
- **Cache**: Local database layer using Room

---

## 🛠️ Tech Stack

- **Kotlin** — Modern, concise language for Android development  
- **Kotlin Coroutines** — Simplifies asynchronous code  
- **Kotlin Flow** — Asynchronous stream processing  
- **Jetpack ViewModel** — Lifecycle-aware UI logic  
- **Hilt** — Dependency injection for Android  
- **Room** — SQLite abstraction for local persistence  
- **Retrofit** — Type-safe HTTP client  
- **OkHttp** — Networking layer  
- **Moshi** — JSON parsing  
- **Kotlin DSL** — Used for Gradle configuration  
- **JUnit & Mockito** — Testing framework and mocking

---


## 🚀 Getting Started

To use this template for your Android project:

1. Clone or fork this repository  
2. Customize the modules, package names, and dependencies as needed  
3. Start building features following the clean architecture pattern outlined  
4. Refer to the folder/module structure to keep your code organized and maintainable  

---

## 🤝 Contributing

Feel free to submit issues or pull requests to improve this template.  
Contributions should follow the existing architectural guidelines and coding style.

---

## 📌 Related Projects

This template is used as the foundation for the [Kotlin-MVVM-Clean-MovieApp](https://github.com/dharmik1992/Kotlin-MVVM-Clean-MovieApp) — a sample app demonstrating this architecture with real API integration.

---

## 👨‍💻 Author

Created and maintained by [Dharmik Kamdar](https://github.com/dharmik1992)

If you found this template helpful, consider giving it a ⭐️ on GitHub!

---
