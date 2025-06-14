# Driver Drowsiness Detection 🚗💤

This is the official repository for our **Driver Drowsiness Detection** system, developed as part of the **EPICS (Engineering Projects in Community Service)** initiative at **VIT Bhopal**.

## 📌 Project Overview

Driver drowsiness is a major cause of road accidents worldwide. This project aims to build a **real-time drowsiness detection system** that can alert drivers before their drowsiness turns into a risk.

Our solution uses **deep learning (transfer learning with MobileNet)** and **OpenCV** for accurate detection of eye closure in real time. Additionally, we implemented a **virtual hardware simulation** using **Proteus** to showcase future real-world applications of this technology.

## 🔧 Features

- ✅ Real-time face and eye detection using **Haarcascade** (OpenCV)
- ✅ **Transfer Learning (MobileNet)** for classifying eye state (open/closed)
- ✅ Real-time alert system (Buzzer & LED simulated)
- ✅ **Proteus** + **VSPE** integration for virtual testing of embedded prototype
- ✅ Comparison with other models (SVM, Random Forest, KNN)


## 🛠️ Tech Stack

- Python
- OpenCV
- TensorFlow / Keras (MobileNet)
- Proteus (for hardware simulation)
- VSPE (Virtual Serial Port Emulator)

## 📈 Results

| Model          | Accuracy | Reaction Time    |
|----------------|----------|------------------|
| TransferLearning (MobileNet) | 1.00     | 0.05–0.10 sec     |
| SVM            | 0.964    | ~1 sec           |
| Random Forest  | 0.98     | ~385 ms          |
| KNN            | 0.971    | ~2 ms            |

## 👨‍💻 Contributors

- **Harish L** (Team Lead) – Data Modeling, Programming, Virtual Simulation
- Dhananchezhiyan S
- Nitish K
- Tamilarasan V
- Akshaay
- Apoorv Pradhan
- Nikhil Kumar
- Tharun PMR

## 📑 Report

You can access the **full technical report** here: [LINK_TO_GOOGLE_DRIVE_OR_GITHUB_REPORT]

## 📬 Contact

For questions or collaboration:  
📧 [Your Email]  
📱 [LinkedIn profile link]

## ⭐ Acknowledgements

- Reference materials from **YouTube tutorials** and **ChatGPT** were used to guide certain implementation steps and troubleshoot issues.
- ## working for future development.
⚠️ Note on Demonstration Video:
This project was successfully demonstrated live in 2023 during the official EPICS project review at VIT Bhopal in front of faculty supervisors and evaluators.

At that time, we prioritized the live demonstration over recording, so currently, we do not have a saved video of the working prototype.

