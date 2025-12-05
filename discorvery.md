## 🛠️ Ma Première Mini-Veille

### 1. Subject Chosen
**Subject:** `Kotlin Multiplatform (KMP)`

### 2. Sources
* **Primary Source:** [Official JetBrains KMP Documentation](https://www.jetbrains.com/kotlin-multiplatform/)
* **Secondary Source:** [Android Developers Blog: KMP at Google](https://android-developers.googleblog.com/)

### 3. Synthesis (Discovery Sheet)

> **What is it?**
> Kotlin Multiplatform (KMP) is a technology that allows developers to write the **business logic** of an application once (in Kotlin) and share it across multiple platforms (Android, iOS, Web, Desktop). Unlike Flutter, which shares the UI, KMP prefers to share the "brain" of the app while keeping the UI native for each platform.

> **Why is it useful for a developer?**
> * **Efficiency:** You don't have to write the same data processing code twice (once in Swift for iOS, once in Kotlin for Android).
> * **Native Performance:** It compiles down to native binaries, so it is faster than hybrid solutions like Ionic.
> * **Career Growth:** For an Android developer, it allows you to touch the iOS world without needing to learn Swift immediately.

> **Concrete Example**
> Imagine an app that fetches a list of tasks from a Laravel API.
> * **With KMP:** I write the networking code (Retrofit/Ktor) and the data models **once** in a `shared` module.
> * **Android App:** Uses the shared code + Jetpack Compose for UI.
> * **iOS App:** Uses the shared code + SwiftUI for UI.
> * **Result:** 50% less code to maintain.

---

