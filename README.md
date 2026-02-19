# 👮‍♂️ Focus Guardian | AI-Powered Focus Assistant

> ⚠️ **Note:** The source code for this project is kept **Private** to protect intellectual property and custom detection algorithms. This repository serves as a technical showcase and portfolio piece.

🔗 **[Live Demo: Try Focus Guardian Here](https://focus-guardian-zeta.vercel.app)**

## 📌 Overview
Focus Guardian is a web-based, real-time focus tracking application designed to help users maintain deep work sessions. It utilizes in-browser Artificial Intelligence (Computer Vision) to monitor user presence and ensure a distraction-free environment. 

By leveraging TensorFlow.js, the application processes the webcam feed entirely offline. **Zero images or data are transmitted to any server**, ensuring absolute user privacy.

## ✨ Core Features
* **Real-time AI Detection:** Continuously monitors the webcam feed to verify if the user is present at their workstation.
* **Smart Distraction Recognition:** Actively detects if the user is holding a mobile phone (`cell phone` detection) and instantly triggers an alert to break the distraction.
* **Mathematical Bounding-Box Logic:** Calculates the overlap between the "Person" and "Phone" bounding boxes to differentiate between a phone lying safely on the desk versus a phone being actively held.
* **100% Privacy-First:** Local processing guarantees that camera data never leaves the user's device.
* **Multi-Language Support (i18n):** Fully localized interface supporting English, Persian (RTL), and Turkish.

## 🛠️ Tech Stack
* **Frontend:** React.js, Vite
* **AI & Machine Learning:** TensorFlow.js (`@tensorflow-models/coco-ssd`)
* **Hardware Integration:** `react-webcam` (for hidden, background video processing)
* **Deployment:** Vercel

## 📸 Preview
*(Add your GIF or Screenshot here)*
![Focus Guardian Preview](./assets/demo.gif)

---
👨‍💻 **Developed by:** [Your Name]
📧 **Contact:** [Your LinkedIn or Email]
