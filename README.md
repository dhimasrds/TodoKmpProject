# TodoKmpProject 📝

A **Kotlin Multiplatform (KMP)** Todo App Project — built with **Compose Multiplatform** for Android & iOS.  
This repository serves as a learning project and template for developers exploring **KMP with MVVM architecture**.

---

## 🚀 Features
- ✅ Cross-platform (Android & iOS) with Kotlin Multiplatform
- ✅ UI built using **Jetpack Compose Multiplatform**
- ✅ Shared business logic in `commonMain`
- ✅ MVVM design pattern with Kotlin Coroutines + Flow
- ✅ Database setup with SQLDelight
- ✅ Example Todo CRUD implementation

---

## 📂 Project Structure

```
shared/
 ├─ src/commonMain/kotlin/com/todokmpproject/
 │   ├─ App.kt
 │   ├─ TodoRepository.kt
 │   ├─ db/
 │   │   ├─ AppDatabase.kt
 │   │   ├─ TodoDao.kt
 │   │   └─ TodoEntity.kt
 │   └─ features/todo/
 │       ├─ TodoViewModel.kt
 │       └─ mapper/ usecase/
```

---

## 🔧 Tech Stack
- **Kotlin Multiplatform (KMP)**
- **Compose Multiplatform** (UI)
- **SQLDelight** (Database)
- **Coroutines & Flow** (Async + Reactive)
- **Gradle Kotlin DSL**

---

## 📱 Platforms
- **Android** (Jetpack Compose)
- **iOS** (SwiftUI bridge / UIKit with ComposeView)

---

## 💡 How to Run
```bash
# Clone repo
git clone https://github.com/dhimasrds/TodoKmpProject.git

# Open in Android Studio (Arctic Fox+ with KMP plugin)
# Build and run for Android/iOS simulator
```

---

## 🌍 Why This Project?
This project is intended for:
- Developers learning **Kotlin Multiplatform**
- Exploring **Compose Multiplatform** for Android & iOS
- Understanding **MVVM pattern in KMP**
- Hands-on practice with **cross-platform shared logic**

---

## 🏷️ Topics
Make sure to add these **topics** in GitHub repo settings:
```
kotlin kotlin-multiplatform kmp compose-multiplatform
android ios cross-platform mvvm todolist
```

---

## 📣 Contribution
PRs are welcome! Feel free to fork, open issues, or submit feature requests.

---

## 📄 License
MIT License © 2025 [Dhimas Saputra](https://github.com/dhimasrds)
