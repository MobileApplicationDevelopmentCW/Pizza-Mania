
# Pizza Mania 🍕

Pizza Mania is a comprehensive mobile application designed for a pizza shop, built using **Android Studio (Java)** for the frontend and a **Node.js** backend for handling data and orders.

## 🚀 Features

* **User Authentication:** Secure login and registration for customers.
* **Product Catalog:** Browse a wide variety of pizzas with descriptions and prices.
* **Order Management:** Add items to the cart and place orders seamlessly.
* **Real-time Updates:** Backend integration for live menu and order tracking.
* **Modern UI:** Built with Android XML layouts for a smooth user experience.

---

## 🛠️ Project Structure

The repository is divided into two main parts:

* **`CW1/`**: The Android Studio project containing the Java source code, XML layouts, and application logic.
* **`pizza-mania-backend/`**: The Node.js server that handles API requests, database connectivity, and business logic.

---

## 💻 Getting Started

### Prerequisites

* **Frontend:** Android Studio (Bumblebee or newer recommended), JDK 11+.
* **Backend:** Node.js (v14+), npm or yarn.
* **Database:** (Specify your database here, e.g., MongoDB, MySQL, or Firebase).

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/MobileApplicationDevelopmentCW/Pizza-Mania.git
cd Pizza-Mania

```

#### 2. Backend Setup

```bash
cd pizza-mania-backend
npm install
# Configure your environment variables in a .env file
npm start

```

#### 3. Frontend Setup

1. Open **Android Studio**.
2. Select **Open an Existing Project** and navigate to the `CW1` folder.
3. Wait for Gradle to sync.
4. Update the `baseUrl` in your Java code (typically in a `Retrofit` or `Network` class) to point to your local backend IP or hosted server.
5. Click **Run** to launch the app on an emulator or physical device.

---

## 🛠️ Tech Stack

* **Frontend:** Java, Android SDK, XML
* **Backend:** Node.js, Express.js
* **Networking:** Retrofit / Volley (for API calls)

