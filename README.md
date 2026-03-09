# AiVena — AI-Powered Healthcare Companion

**AiVena** is a modern Android healthcare application designed to provide a **calm, intuitive, and user-centric digital healthcare experience**. The application focuses on simplifying doctor discovery, consultation booking, and patient–doctor communication through a thoughtfully designed interface and scalable mobile architecture.

The project was built to address common usability issues in healthcare applications such as **complex onboarding flows, cluttered interfaces, and limited emotional guidance**, which often reduce user engagement and trust during initial interactions.

AiVena combines **clean UI design, smooth motion interactions, and Firebase-powered backend services** to deliver a seamless healthcare companion experience.

---

# Key Features

### Doctor Discovery

* Search doctors by **name or specialization**
* Filter doctors by **availability, ratings, and consultation fee**
* View detailed doctor profiles including **experience, ratings, and availability**

### Appointment Booking

* Book **video consultations** with healthcare professionals
* Real-time doctor availability indicators
* Simple and intuitive booking flow

### Asynchronous Care Messaging

* Secure messaging between **patients and doctors**
* Enables consultation without scheduling a full appointment

### Authentication & Security

* Email and password authentication
* Phone number OTP verification
* Google Sign-In integration
* Secure user management using Firebase Authentication

### Profile Management

* Dedicated **patient and doctor profiles**
* Editable user information and profile images
* Health-related personal details management

### Modern UI Experience

* Built entirely with **Jetpack Compose**
* Smooth animations and subtle motion design
* Clean, accessible, and responsive user interface

---

# Architecture

AiVena follows a **scalable MVVM (Model-View-ViewModel) architecture** to maintain clear separation of concerns and improve maintainability.

```text
UI Layer (Jetpack Compose)
        ↓
ViewModel (State Management)
        ↓
Repository Layer
        ↓
Firebase Services
```

### Architectural Highlights

* State-driven UI with Compose
* Modular and reusable UI components
* Repository pattern for data abstraction
* Scalable navigation architecture using Navigation Compose

---

# Technology Stack

**Programming Language**

* Kotlin

**UI Framework**

* Jetpack Compose
* Material 3

**Backend Services**

* Firebase Authentication
* Firebase Firestore

**Navigation**

* Navigation Compose

**Architecture**

* MVVM
* Repository Pattern

**Design Principles**

* Component-driven UI architecture
* Motion and animation design
* Responsive and adaptive layouts

---

# Application Screens

The application currently includes the following core modules:

* Onboarding Experience
* Login and Signup
* OTP Authentication
* Home Dashboard
* Doctor Discovery
* Doctor Profile
* Appointment Booking
* Async Messaging
* Notifications
* Profile Management

---

# Project Structure

```text
app
│
├── core
│   ├── firebase
│   └── navigation
│
├── domain
│   └── model
│
├── ui
│   ├── auth
│   ├── home
│   ├── doctors
│   ├── profile
│   ├── notifications
│   └── async
│
└── MainActivity.kt
```

---

# How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/aivena.git
```

### 2. Open the project in Android Studio

```
File → Open → Select the project folder
```

### 3. Configure Firebase

1. Create a Firebase project
2. Add an Android application
3. Download the `google-services.json` file
4. Place the file inside:

```
app/google-services.json
```

### 4. Run the application

```
Run → app
```

---

# Future Enhancements

* AI-powered symptom analysis
* Video consultation integration
* Doctor rating and feedback system
* Health records and prescription management
* Smart health notifications
* Integration with wearable health devices

---

# Author

**Praveen Ray**
Android Developer | UI/UX Enthusiast

Passionate about building **scalable, user-focused mobile applications that combine strong engineering practices with thoughtful design**.

---

# Acknowledgement

This project was developed as part of a personal initiative to explore **modern Android development using Jetpack Compose, Firebase services, and scalable application architecture**.

---

If you find this project useful, please consider giving it a ⭐ on GitHub.
