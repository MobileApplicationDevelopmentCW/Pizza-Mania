

# Pizza Mania - Android Studio Code Base 📱

This directory contains the **Android Studio** project for the Pizza Mania mobile application. It is a native Android app developed in **Java**, serving as the user-facing interface for browsing and ordering pizzas.

## 📁 Folder Overview: `CW1/`

* **`app/src/main/java/`**: Contains the Java activity files and logic for navigation, cart management, and user authentication.
* **`app/src/main/res/`**: All UI resources, including XML layouts, drawables (images/icons), and string constants.
* **`app/build.gradle`**: Project dependencies (e.g., Retrofit for API calls, Glide for image loading).

---

## ✨ Features

* **Dynamic Menu:** Fetches the latest pizza offerings from the backend.
* **Cart System:** Add, remove, and adjust quantities of items before checkout.
* **User Profiles:** Sign-in and sign-up screens for a personalized experience.
* **Order Flow:** From selection to a summary screen of the final order.
* **Responsive Layouts:** Optimized for various Android screen sizes.

---

## 🛠️ Tech Stack

* **Language:** Java
* **UI Framework:** XML (Android Layout Editor)
* **Minimum SDK:** API 21+ (Android 5.0 Lollipop)
* **Networking:** Retrofit / Volley (integrated for communication with `pizza-mania-backend`)
* **Image Loading:** Glide or Picasso

---

## 🚀 Setup & Installation

To run this specific module:

1. **Open Android Studio.**
2. Go to `File > Open` and select the **`CW1`** folder specifically.
3. Ensure you have the latest **Android SDK** and **Build Tools** installed via the SDK Manager.
4. **Sync Gradle:** Allow the project to download required dependencies.
5. **Configure API URL:**
* Find the configuration file (usually a `Constants.java` or within your `RetrofitClient`) and update the `BASE_URL` to match your running backend IP (e.g., `http://10.0.2.2:5000` for the Android Emulator).


6. **Run:** Select your emulator or connected device and click the **Run** (green play) button.

---

## 📸 UI Components

The app utilizes standard Material Design components:

* `RecyclerView` for the pizza menu list.
* `CardView` for item displays.
* `Intent` for passing order data between activities.
* `SharedPreferences` for basic local session management.

---

## 🧪 Testing

* **Emulator:** Tested on Pixel 4 (API 30).
* **Networking:** Ensure the backend service in the root directory is running to see live data.
