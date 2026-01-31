# 🌍 Carbon Lens
> **Top 10 Finalist @ GDGC Winter Solstice Hackathon** 🏆

**Making the Invisible Impact Visible.**
An AI-powered environmental tracking application that uses computer vision to calculate the real-time carbon footprint of daily objects.

---

## 🔗 Live Demo
- **Web App:** [Launch Carbon Lens](https://carbon-shadow-tracker-db297.web.app)
- **Android APK:** [Download Build](https://drive.google.com/file/d/1Yz0Pz-dGCvTbC9nhHH8KxrR7d_vKnocr/view?usp=drive_link)

---

## 👨‍💻 My Contribution

While this was a collaborative effort by **Team Dev Crew**, my specific focus was on:
* Integrated the Gemini 2.5 Flash API to handle image recognition.
* Built the Firebase backend structure to store user scores in real-time.
* Optimized the Flutter UI for the "AR Lens" mode.

---

## 💡 The Problem
Climate change is abstract. Consumers buy products without seeing the **"Carbon Shadow"**—the hidden environmental cost attached to manufacturing and disposal. Carbon Lens acts as a real-time mirror to reveal this data.

## 🛠️ Tech Stack & Architecture

### Core Engine
| Tech | Usage |
| :--- | :--- |
| **Flutter** | Cross-platform mobile and web application (PWA). |
| **Google Gemini 2.5 Flash** | Multimodal AI for real-time object detection and carbon scoring. |
| **Google ML Kit** | **On-device** Object Detection for instant feedback and reduced latency. |

### Backend & Infrastructure
| Tech | Usage |
| :--- | :--- |
| **Firebase Auth** | Anonymous sessions and secure user login. |
| **Cloud Firestore** | NoSQL database for real-time leaderboards and logs. |
| **Firebase Hosting** | Scalable deployment for the web interface. |
| **Google Maps API** | Route tracking to verify eco-friendly transport modes. |

---

## 🚀 Key Features

### 1. 📷 Gemini-Powered Scanner
Using **Gemini 2.5 Flash**, the app analyzes photos of food, objects, or waste.
* **Input:** Real-time camera feed.
* **Process:** Identifies objects (e.g., "Plastic Bottle") and estimates Carbon Footprint score (0-100).
* **Output:** Suggests immediate eco-friendly alternatives.

### 2. 🕶️ AR "Lens" Mode
A Heads-Up Display (HUD) overlay that visualizes sustainability data onto the physical world.

### 3. 🎮 Gamification Engine
* **Planet Points:** Reward system for verified low-carbon choices (walking vs. driving).
* **Leaderboards:** Real-time social competition powered by Firestore.

---
