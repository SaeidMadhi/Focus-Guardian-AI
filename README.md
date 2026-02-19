# 🛡️ Focus Guardian | AI-Powered Productivity Assistant

> ⚠️ **Portfolio Showcase:** The source code for this repository is kept **Private** to protect custom detection algorithms and intellectual property. This repository serves as a technical portfolio piece demonstrating the project's architecture, features, and user interface.

🔗 **[Live Demo: Try Focus Guardian Here](https://focus-guardian-zeta.vercel.app/)**

## 📖 About The Project
Focus Guardian is a real-time, browser-based focus tracking application designed to enhance deep work sessions. It acts as a strict digital guardian, utilizing Computer Vision to monitor user presence and actively discourage distractions, such as picking up a smartphone during focus time.

## 💻 Languages & Tech Stack
This project was built entirely from scratch using modern web technologies and client-side machine learning:

**Core Languages:**
* **JavaScript (ES6+):** The primary language handling the application's core logic, asynchronous AI model loading, and real-time state management.
* **CSS3:** Used for a modern, glass-morphism UI design, responsive layouts, and dynamic RTL/LTR direction rendering.
* **HTML5 / JSX:** Semantic structuring of the application interface.

**Frameworks & Libraries:**
* **React.js:** Component-based UI architecture heavily relying on React Hooks (`useState`, `useEffect`, `useRef`, `useCallback`) for efficient rendering and state lifecycle management.
* **TensorFlow.js (`@tensorflow/tfjs`):** The core engine running machine learning models directly inside the browser.
* **COCO-SSD Model:** A pre-trained object detection model used to classify and track specific entities (e.g., `person`, `cell phone`).
* **React-Webcam:** For secure, background access to the device's media stream without displaying it to the user.

**Build Tools & Deployment:**
* **Vite:** Blazing fast frontend build tool and development server.
* **Vercel:** Deployed on Vercel's edge network for optimal performance.

## ✨ Core Features
* **100% Client-Side Privacy:** All camera feed processing happens locally in the browser memory. Zero images or user data are ever saved or transmitted to any external server.
* **Multi-Language & RTL Support (i18n):** Fully localized interface supporting English, Turkish, and Persian, including dynamic Right-to-Left (RTL) layout switching.
* **Smart Distraction Recognition:** It doesn't just look for people; it actively penalizes phone usage during focus sessions.

## 🧠 Under the Hood: The Detection Algorithm
Since the code is private, here is a brief overview of the custom logic driving the AI:
1.  **Continuous Scanning:** The app runs a background interval loop that processes webcam frames through the TensorFlow model.
2.  **Collision Detection Logic:** To differentiate between a phone lying harmlessly on a desk and a phone actively being held, the app calculates the Bounding Box coordinates (X, Y, Width, Height) of both the `person` and the `cell phone`. It then applies a mathematical collision detection algorithm. If the boxes overlap, it triggers a "distraction alert".

## 📸 Interface Preview
*(Add a GIF or Screenshot of the app here, showing the Police reacting!)*
![Focus Guardian Preview](./assets/demo.gif)

---
👨‍💻 **Developed by:** [Saeid Madhilaleh]
📧 [saeedmadhitabriz@gmail.com]
