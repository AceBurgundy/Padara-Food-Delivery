# 🛵 Padara – Food Delivery at Your Fingertips

*Developed for Pixellebit Studios*

**Padara** is a full-featured food delivery mobile application designed for seamless, real-time ordering and delivery. Inspired by apps like FoodPanda and tailored for local use in the Philippines, Padara helps users browse nearby restaurants, place orders, track deliveries live, and manage everything through a beautifully built Flutter app backed by Firebase.

## 🍽️ Key Features

### 🍔 Restaurant Discovery

* Browse restaurants by category, popularity, or delivery radius
* See menus, images, pricing, and ratings

### 🛒 Streamlined Ordering

* Add items to cart with notes and modifiers
* Review and confirm orders before checkout

### 💳 Checkout & Payment

* Supports multiple payment methods (COD, e-wallets, etc.)
* Secure and fast order processing

### 🛵 Real-Time Tracking

* Firebase-powered live updates of order status
* Track driver location and delivery progress

### 👥 Account Management

* Register and log in with email
* Save delivery addresses and view order history

## 🛠️ Tech Stack

* **Frontend**: Flutter
* **Backend**: Firebase (Realtime Database, Auth, Storage)
* **Realtime Updates**: Firebase Realtime Database & Cloud Messaging
* **Platform**: Android (iOS support planned)

## 🚀 Getting Started

### 📌 Prerequisites

* Flutter SDK
* Dart
* Firebase project with:

  * Firebase Auth
  * Realtime Database
  * Firebase Storage
  * Cloud Messaging (optional)

### 🔧 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AceBurgundy/padara.git
   cd padara
   ```

2. Install packages:

   ```bash
   flutter pub get
   ```

3. Connect to Firebase:

   * Replace the default `google-services.json` (Android) or `GoogleService-Info.plist` (iOS)
   * Update Firebase settings in `lib/firebase_options.dart` or initialization logic

4. Run the app:

   ```bash
   flutter run
   ```

## 📱 PWA & Mobile Support

Padara is fully optimized for Android mobile devices, with plans for iOS and optional PWA compatibility.

## 📂 Project Structure

* `lib/` – Main Flutter source code

  * `screens/` – UI screens like Home, Cart, Profile, Tracking
  * `services/` – Firebase and app logic
  * `models/` – Data structures for users, orders, restaurants
  * `widgets/` – Reusable UI components
* `assets/` – Images and static files
* `firebase/` – Firebase configuration and setup files

## 🧭 Future Enhancements

* Rider dashboard and real-time dispatching
* Promo code and rewards system
* Push notifications via Firebase Cloud Messaging
* Restaurant-side order dashboard
* Admin panel for menu and user control

## 📛 Branding

Padara was developed for **Pixellebit Studios** as a fully branded, locally tailored food delivery solution aimed at the Philippine market.

## 📝 License

This app was developed specifically **for Pixellebit Studios** and is not open source. For customizations or licensing, contact the developer below.

## 📬 Contact

* **Developer**: Adrian Sam Sabalo
* **Email**: [samadriansabalo99@gmail.com](mailto:samadriansabalo99@gmail.com)
* **GitHub**: [AceBurgundy](https://github.com/AceBurgundy)
