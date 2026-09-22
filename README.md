# 🔎 FixLens AI

### See the Problem. Understand the Risk. Fix It Smarter.

FixLens AI is an **AI-powered visual troubleshooting web application** that helps users understand everyday problems by simply uploading or scanning an image.

Instead of depending on a fixed set of predefined problems, FixLens uses **AI vision analysis** to identify and explain different types of visible issues and provide practical next-step guidance.

---

## 🚀 Features

* 📷 **Scan or Upload Images**
  Capture a new image or upload an existing image of a problem.

* 🤖 **AI-Powered Visual Analysis**
  Uses Gemini Vision AI to analyze uploaded images and identify visible problems.

* 🔍 **Problem Detection**
  Detects and describes possible issues across different categories.

* ⚠️ **Risk Assessment**
  Provides an estimated risk level such as Low, Medium, or High.

* 🧠 **Possible Causes**
  Explains potential reasons behind the detected problem.

* 🛠️ **Step-by-Step Guidance**
  Provides practical recovery or troubleshooting steps.

* 💬 **AI Assistant**
  Users can ask questions about the detected problem and receive AI-powered guidance.

* 🔄 **Scan Again & Verify**
  Users can upload another image to check whether the visible condition has improved.

* 📚 **Scan History**
  Keeps track of previous analyses in the application.

* 🌙 **Dark / Light Mode**
  Provides a modern interface with theme switching.

* 📱 **Responsive Design**
  Works across desktop, tablet, and mobile screens.

---

## 💡 How It Works

```text
        📷 Capture / Upload Image
                  ↓
          🔍 Visual AI Analysis
                  ↓
          🧠 Detect Visible Issue
                  ↓
           ⚠️ Assess Risk Level
                  ↓
          🔎 Explain Possible Causes
                  ↓
        🛠️ Generate Next Steps
                  ↓
           💬 Ask AI Assistant
                  ↓
          🔄 Scan Again & Verify
```

---

## 🧩 Supported Problem Types

FixLens is designed to work with **different types of visible problems**, rather than being restricted to one specific issue.

Examples include:

* ⚡ Electrical problems
* 💧 Plumbing issues
* 🚲 Bicycle problems
* 🧱 Wall and structural issues
* 🏠 Household problems
* 🔌 Appliance issues
* 🚗 Vehicle-related visible issues
* 🪑 Furniture damage
* 🔧 Tools and equipment
* 📦 Other visible problems

The AI determines the relevant category based on the uploaded image.

---

## 🛠️ Technology Stack

| Technology       | Purpose                               |
| ---------------- | ------------------------------------- |
| HTML5            | Application structure                 |
| CSS3             | Styling and animations                |
| JavaScript       | Application logic                     |
| React.js         | User interface                        |
| Tailwind CSS     | Responsive UI design                  |
| Gemini Vision AI | Image analysis and AI responses       |
| Local Storage    | Local preferences and API-key storage |
| FileReader API   | Image upload and preview              |

---

## 🖥️ Application Flow

### 1. Welcome

Users start from the FixLens landing page and can begin scanning immediately.

### 2. Upload / Scan

Users can:

* Capture an image
* Upload an image
* Use a sample image for demonstration

### 3. AI Analysis

The uploaded image is processed by the AI vision model.

The system analyzes the visible information and generates:

* Detected problem
* Category
* Explanation
* Confidence
* Risk level
* Risk factors
* Possible causes
* Safety warning
* Recovery recommendations

### 4. AI Assistant

Users can ask additional questions about the detected issue and receive contextual AI guidance.

### 5. Verification

Users can scan the same problem again after taking action and compare the new result with the previous scan.

---

## 🔐 API Key Setup

FixLens uses Gemini AI for visual analysis.

For local testing:

1. Open **FixLens AI**.
2. Go to **Settings**.
3. Open **AI Preferences**.
4. Enter your Gemini API key.
5. Save the settings.
6. Start scanning.

### ⚠️ Security Note

Do **not** commit a real API key directly into the source code or public GitHub repository.

The prototype stores the API key locally in the browser rather than hard-coding it into the project.

For a production application, the API request should be moved to a secure backend so the API key is never exposed to users.

---

## 📂 Project Structure

```text
FixLens/
│
├── FixLens_Universal_AI.html
└── README.md
```

The current prototype can run as a standalone HTML application.

---

## 🎯 Problem Statement

Many everyday problems are noticed only after they become serious. Users may not immediately understand:

* What the visible problem is
* How risky it may be
* What could have caused it
* What action should be taken next

Traditional troubleshooting often requires searching through multiple websites or contacting a professional before understanding the basic issue.

---

## 💡 Our Solution

**FixLens AI** provides a simple visual troubleshooting experience:

> **Upload an image → Let AI understand the problem → Understand the risk → Get guidance → Verify the result**

The goal is to make initial troubleshooting **faster, simpler, and more accessible**.

---

## 🌟 What Makes FixLens Different?

### 🔹 Universal Visual Troubleshooting

Instead of supporting only one predefined problem, FixLens is designed to analyze **different visible everyday problems** using AI vision.

### 🔹 Explainable Results

The system does not only provide a detected issue. It also presents:

**Problem → Risk → Causes → Safety → Recommended Actions**

### 🔹 Continuous Verification

Users can scan again after taking action and compare the condition with the previous result.

### 🔹 AI Conversation

The integrated AI Assistant allows users to ask follow-up questions instead of relying only on a single analysis.

---

## ⚠️ Disclaimer

FixLens provides **AI-powered visual guidance based on visible information**.

It does not replace professional inspection, diagnosis, electrical work, structural assessment, medical advice, or professional repair services.

For high-risk problems, users should contact an appropriately qualified professional.

---

## 🔮 Future Enhancements

* 🎥 Video-based problem detection
* 📱 Native Android / iOS application
* 📊 Advanced scan history and analytics
* 🧠 Fine-tuned computer vision models
* ☁️ Secure backend architecture
* 👨‍🔧 Professional service-provider integration
* 📍 Location-based repair assistance
* 🔔 Maintenance and follow-up reminders
* 🏆 Problem severity tracking over time

---

## 👩‍💻 Project

**FixLens AI — AI-Powered Visual Troubleshooting**

Built as an AI-based prototype demonstrating how computer vision and conversational AI can simplify everyday problem identification and troubleshooting.

### Tagline

> **See the Problem. Understand the Risk. Fix It Smarter.**
