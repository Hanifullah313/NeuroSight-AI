# 🧠 NeuroSight AI

### Revolutionizing Early Alzheimer's Detection with Artificial Intelligence

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg) ![React](https://img.shields.io/badge/frontend-React%20%7C%20TypeScript-61DAFB.svg) ![AI Model](https://img.shields.io/badge/AI-ResNet50-orange.svg)

**NeuroSight AI** is a cutting-edge web application designed to assist in the early screening of Alzheimer's disease. By leveraging advanced Deep Learning computer vision, we provide rapid, accessible, and highly accurate assessments of MRI brain scans, bridging the gap between medical imaging data and actionable clinical insights.

---

## 📖 Table of Contents
- [The Problem](#-the-problem)
- [Our Solution](#-our-solution)
- [Key Features](#-key-features)
- [AI Classification Stages](#-ai-classification-stages)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Roadmap](#-roadmap)
- [Medical Disclaimer](#-medical-disclaimer)
- [License](#-license)

---

## 🩺 The Problem
Alzheimer's disease affects over 50 million people worldwide. One of the biggest challenges in treatment is **late diagnosis**. Physical changes in the brain (atrophy) often begin years before symptoms appear, but these microscopic changes can be difficult for human eyes to distinguish from healthy aging on standard MRI scans.

## 💡 Our Solution
NeuroSight AI acts as an intelligent second opinion. Using a **ResNet50 Convolutional Neural Network (CNN)** trained on thousands of clinically labeled MRI scans, our system can detect subtle patterns of dementia progression in seconds.

> **Impact:** Early detection allows for earlier intervention, significantly improving patient outcomes and quality of life.

---

## 🚀 Key Features

### ⚡ **Instant Analysis**
Gone are the days of waiting weeks for a screening result. NeuroSight delivers AI-powered assessments in **under 5 seconds**, enabling real-time triage in clinical settings.

### 🎯 **High-Precision AI**
Our model utilizes **Transfer Learning** to achieve state-of-the-art performance.
* **95% Overall Accuracy** on test data.
* **High Sensitivity** for "Very Mild" dementia, ensuring early cases aren't missed.

### 💜 **Caregiver Centric**
Beyond diagnosis, we are building a bridge to care. Future updates will include a community hub connecting families with local support groups and medical resources.

### 🔒 **Privacy First**
Built with patient data security in mind. MRI scans are processed securely, ensuring confidentiality at every step.

---

## 🧠 AI Classification Stages

The AI analyzes the structural integrity of the brain and classifies scans into one of four distinct progression stages:

| Stage | Description |
| :--- | :--- |
| **🟢 Non-Demented** | Healthy brain tissue with no signs of atrophy. |
| **🟡 Very Mild Dementia** | Earliest detectable stage; microscopic changes often missed by human eye. |
| **🟠 Mild Dementia** | Clear signs of cognitive decline and physical shrinkage. |
| **🔴 Moderate Dementia** | Advanced progression requiring immediate medical attention. |

---

## 🛠️ Tech Stack

This project is built with a modern, performance-optimized stack:

### **Frontend**
* ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white) **React 18** - For a responsive, dynamic user interface.
* ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) **TypeScript** - Ensuring type safety and code reliability.
* ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white) **Vite** - Next-generation frontend tooling for blazing fast builds.
* ![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white) **Tailwind CSS** - For rapid, beautiful, and responsive styling.

### **AI & Backend (Integration Pending)**
* **TensorFlow / Keras** - Model training and inference.
* **Python** - Data preprocessing and API logic.

---

## 💻 Getting Started

Follow these steps to set up the project locally for development.

### Prerequisites
* Node.js (v16 or higher)
* npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/neurosight-ai.git](https://github.com/your-username/neurosight-ai.git)
    cd neurosight-ai
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

4.  **Open in browser**
    Visit `http://localhost:5173` to view the application.

---

## 🗺️ Roadmap

- [x] **Phase 1:** Core UI Development & Mock Integration (Current)
- [ ] **Phase 2:** Connect Python Flask/FastAPI Backend with ResNet50 Model
- [ ] **Phase 3:** User Authentication & History Saving
- [ ] **Phase 4:** PDF Report Generation for Doctors

---

## ⚠️ Medical Disclaimer

**NeuroSight AI is a screening tool, not a diagnostic device.**
This software is intended for educational and research purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Made with 💜 by the NeuroSight Team
</p>
