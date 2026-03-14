# 🌌 Digit Predictor AI

A high-performance, modern web application for handwritten digit recognition, powered by **Convolutional Neural Networks (CNN)** and **TensorFlow.js**.

![UI Mockup](/C:/Users/LENOVO/.gemini/antigravity/brain/1b9d18bd-dc37-4928-9568-0ecd522ec0fc/modern_hype_ai_ui_mockup_1773480963236.png)

## 🚀 Overview

Digit Predictor AI brings machine learning directly to the browser. Users can draw digits on an interactive canvas, and the AI will predict the number in real-time with high confidence levels. The application features a cutting-edge **Glassmorphism** aesthetic with a dark cosmic theme, providing a premium user experience.

## ✨ Key Features

- **Real-time Recognition**: Powered by a pre-trained CNN model optimized for the browser.
- **Glassmorphic UI**: High-end visual design with backdrop blurring and neon accents.
- **Mobile Responsive**: Fully adaptive layout for tablets and smartphones.
- **Micro-interactions**: Smooth transitions and glow effects for a "hype" tech feel.
- **Offline Capable**: All processing happens client-side using TensorFlow.js.

## 🛠️ Tech Stack

- **Framework**: [TensorFlow.js](https://www.tensorflow.org/js) for browser-based deep learning.
- **Structure**: Semantic HTML5.
- **Styling**: Vanilla CSS with Modern Design Tokens & Glassmorphism.
- **Logic**: Vanilla JavaScript (ES6+).
- **Architecture**: Convolutional Neural Network (CNN) trained on the MNIST dataset.

## 📁 Project Structure

```text
├── modul/
│   ├── model.json       # Pre-trained CNN model architecture
│   ├── group*-shard*    # Model weight shards
│   └── model.py         # Original Keras training script
├── index.html           # Main application entry point
├── style.css            # Modern glassmorphic design system
├── script.js            # Drawing logic & AI inference bridge
└── README.md            # You are here!
```

## 🏃 How to Run

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   ```
2. **Serve the project**:
   Since it uses ES modules and loads local JSON models, you need a local server. You can use:
   - **VS Code Live Server**: Right-click `index.html` -> "Open with Live Server"
   - **Python**: `python -m http.server 8000`
   - **Node.js**: `npx serve`
3. **Open in Browser**: Navigate to `http://localhost:8000`.

## 👥 Meet the Team (Kelompok 4)

- **MOH ROFIQI** (2021300046)
- **ALFAINI WAHID** (2021300046)
- **BADRUS SHOLEH** (2021300046)
- **LUKMAN HAKIM** (2021300046)
- **FERI IRAWAN** (2021300046)
- **FAYAKUN** (2021300046)
- **FIKRI** (2021300046)

---
*Built with ❤️ for AI research and modern web development.*
