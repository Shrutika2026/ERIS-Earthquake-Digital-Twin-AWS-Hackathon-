# 🧠 ERIS: Earthquake Risk Intelligence System
### **Digital Twin for Seismic Risk & Precursor Intelligence**
**BSc-IT National Award-Winning Research | Mumbai Digital Twin Implementation**

`ERIS` (Earthquake Risk Intelligence System) is a high-performance Digital Twin designed for the **AWS Hackathon**. It bridges the gap between raw environmental sensor data and actionable seismic risk intelligence. By monitoring unconventional precursors like Radon gas and animal behavior anomalies, ERIS provides a multi-layered approach to earthquake early warning systems.

---

## 🛰️ Project Vision
VisionTrac AI was about seeing; **ERIS is about sensing.** Developed for the 2026 Solution Challenge and AWS Hackathon, this system simulates a Digital Twin of Mumbai to track seismic noise, radon levels, and EMF disturbances in real-time. It transforms complex environmental datasets into a simplified "Risk Meter" for mission-critical decision-making.

---

## 🧠 Core Intelligence (The Brain)
To ensure high-precision risk assessment, ERIS utilizes a specialized Random Forest architecture:
*   **Predictive Backbone:** Powered by a `Random Forest Classifier` trained on specific innovation logic:
    *   *High Risk ($Risk=1$)* is triggered when **Radon** and **Animal Anomalies** exceed a 70% threshold, or **Seismic Noise** crosses 85%.
*   **Explainable AI (XAI):** Uses feature importance mapping to tell the user *why* the risk is high (e.g., "60% of current risk is due to Radon spikes").
*   **Visual Seismograph:** An innovative Computer Vision engine that uses **Frame Differencing** to detect physical tremors in uploaded video footage.

---

## 🎨 Visual Identity & UI
The interface follows a **"Strategic Monitoring"** aesthetic designed for emergency response centers:
*   **Glassmorphism UI:** Semi-transparent containers with blurred backdrops for a sleek, mission-critical look.
*   **Interactive Gauge:** A Plotly-powered real-time risk meter with dynamic color-coding (Green/Gold/Crimson).
*   **Mumbai Digital Twin Map:** A live vulnerability map displaying simulated sensor nodes across Mumbai.
*   **Custom CSS Branding:** High-impact tab navigation and a red-accented theme for high-alert scenarios.

---

## 🛠️ Technical Stack
*   **Language:** Python 3.10+
*   **Machine Learning:** Scikit-Learn (Random Forest)
*   **Frontend:** Streamlit (with Custom CSS Injection)
*   **Data Visualization:** Plotly & Pandas
*   **Computer Vision:** OpenCV (OpenCV-Python-Headless)
*   **Deployment:** AWS Cloud / Streamlit Community Cloud

---

## 📂 Project Structure
```text
📂 ERIS-Earthquake-Digital-Twin
├── 📄 app.py                # Main Digital Twin Dashboard & UI Logic
├── 📄 train_model.py        # Innovation Logic & Model Training Script
├── 📄 earthquake_model.pkl  # Trained Neural Brain (Pickle File)
├── 📄 requirements.txt      # Project Dependencies (OpenCV, Sklearn, etc.)
└── 📄 README.md             # Technical Documentation
