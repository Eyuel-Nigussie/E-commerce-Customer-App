# 🛒 Flutter E-Commerce Pro

<p align="left">
  <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=Stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase" />
  <img src="https://img.shields.io/badge/GetX-800080?style=for-the-badge&logo=dart&logoColor=white" />
</p>

A high-performance, reactive E-commerce mobile application built with **Flutter** and **GetX**. This project is a full-stack showcase featuring secure payment processing, real-time communication, and a seamless shopping experience.

---

## 📲 Try It Out
Test the flow from product selection to checkout.

👉 [**Download Android APK (v1.0.0)**](https://github.com/Eyuel-Nigussie/E-commerce-Customer-App/releases/download/v1.0.0/EcomApp_v1.0.apk)

> **Note:** Since this is a portfolio project, you may need to "Allow from this source" when installing the APK.

---

## 📽️ App Demo

<p align="center">
  <img src="https://github.com/user-attachments/assets/67ac5752-a098-4d1f-ab92-398253e6fd6e" width="300" />
</p>

---

## 🚀 Key Features

* **💳 Secure Stripe Integration:** A fully functional payment gateway. I implemented the Stripe Android SDK to handle secure tokenization and credit card transactions.
* **💬 Real-time Customer Support:** Integrated an in-app chat system using **Firebase Cloud Firestore**. Users can get instant support, demonstrating real-time data streaming and UI synchronization.
* **🛒 Reactive Cart System:** High-speed quantity management and price calculations powered by **GetX (Obx)** for a "no-lag" user experience.
* **🔐 Robust Authentication:** Secure user onboarding via **Firebase Auth**, featuring Email/Password logic and Google Sign-In.
* **📦 Dynamic Catalog:** Real-time product fetching with categorized views and an optimized search algorithm.

---

## 🛠️ Tech Stack

### Frontend
* **Framework:** [Flutter](https://flutter.dev) (v3.x)
* **State Management:** [GetX](https://pub.dev/packages/get) (Reactive & Dependency Injection)
* **Local Storage:** [GetStorage](https://pub.dev/packages/get_storage) (for session persistence)

### Backend & Integration
* **Payments:** [Stripe API](https://stripe.com) 
* **Database & Auth:** [Firebase](https://firebase.google.com) (Firestore, Auth, Storage)
* **Support System:** Firebase Real-time data streams for the chat feature.

---

## 🏗️ Architecture
The project follows a **Controller-based MVC** (Model-View-Controller) pattern:
* **Models:** Clean data structures with JSON serialization.
* **Views:** Modular and reusable Flutter widgets.
* **Controllers:** Decoupled business logic and state management.

---

### 📚 Note de l'auteur (Author's Note)
*Pendant que je codais ce projet, j'ai aussi appris le français !* (While I was coding this project, I was also learning French!) 

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/Eyuel-Nigussie">Eyuel Nigussie</a>
</p>
