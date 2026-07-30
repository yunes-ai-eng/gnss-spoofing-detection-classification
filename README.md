# 🛰️ AI-Based Detection & Classification of GNSS Spoofing Attacks on the NavIC System

An end-to-end Artificial Intelligence framework for detecting and classifying GNSS spoofing attacks using real-world NavIC signal data. This research combines Machine Learning, Deep Learning, advanced feature engineering, and signal analysis to improve navigation security for autonomous and safety-critical systems.

---

# 📌 Project Overview

Global Navigation Satellite Systems (GNSS) are widely used in autonomous vehicles, UAVs, aviation, maritime navigation, and timing-critical infrastructures. However, GNSS signals are vulnerable to spoofing attacks, where counterfeit satellite signals manipulate the receiver into calculating incorrect positioning or timing information.

This project proposes an AI-driven spoofing detection framework capable of distinguishing authentic and spoofed GNSS signals using real-world NavIC datasets.

The framework was designed and evaluated using multiple Machine Learning and Deep Learning models with a strong focus on reducing false-negative errors, the most dangerous type of failure in navigation security.

---

# 🎯 Objectives

- Detect GNSS spoofing attacks using AI.
- Classify authentic and spoofed GNSS signals.
- Engineer robust signal features from real GNSS observations.
- Compare multiple Machine Learning models.
- Reduce false-negative detection rates.
- Support future real-time deployment in navigation systems.

---

# 📡 Dataset

The project uses real-world NavIC GNSS signal measurements collected under realistic operating conditions.

Signal characteristics include:

- Carrier-to-Noise Density Ratio (C/N₀)
- Doppler Shift
- Pseudorange Error
- Position Stability
- Temporal Signal Statistics
- Environmental Noise
- Multipath Effects
- Receiver Variations

Unlike simulated datasets, the data reflects practical navigation environments.
Data link: https://drive.google.com/file/d/13nwSFXn7iAKG0YNwnLQsVygh2nHssirv/view?usp=drive_link
---

# ⚙️ Feature Engineering

The detection framework extracts informative features from GNSS signals, including:

- Signal Quality Indicators
- Motion Statistics
- Local Variation Features
- Signal Stability Metrics
- Doppler-based Features
- Pseudorange-based Features

These engineered features significantly improve spoofing detection performance.

---

# 🤖 AI Models

Several AI models were developed and compared:

- Deep Neural Network (DNN)
- Random Forest (RF)
- XGBoost

Performance comparison was conducted using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Special attention was given to minimizing False Negative predictions.

---

# 📊 Results

The developed framework achieved:

- Over **93% accuracy** across all evaluated models.
- **XGBoost** achieved the best overall performance.
- **95.5% classification accuracy** using real-world GNSS data.
- Significant reduction in False Negative detection.

The results demonstrate the effectiveness of AI-based spoofing detection in practical navigation environments.

---

# 🚀 Real-Time Deployment

The proposed framework is designed for future deployment in:

- UAV Navigation Systems
- Autonomous Vehicles
- Intelligent Transportation Systems
- Navigation Receivers
- Safety-Critical GNSS Applications

The framework supports real-time monitoring and automated spoofing mitigation strategies.

---

# 🛠 Technologies Used

- Python
- Scikit-learn
- TensorFlow
- XGBoost
- NumPy
- Pandas
- Matplotlib
- Signal Processing
- Feature Engineering

---

# 📂 Project Structure

```text
GNSS-Spoofing-Detection/
│
├── data/
├── notebooks/
├── models/
├── src/
├── results/
├── figures/
├── requirements.txt
└── README.md
```

---

# 📈 Future Improvements

- Real-time deployment on embedded GNSS receivers
- Edge AI optimization
- UAV integration
- Online spoofing detection
- Model compression
- Explainable AI for GNSS security

---

# 📖 Research Contribution

This project demonstrates how Artificial Intelligence can enhance GNSS security by providing a scalable, accurate, and practical spoofing detection framework trained on real-world signal data instead of simulated environments.

---

# 👨‍💻 Author

**Yunes Abdulghani Mohammed Ghaleb**

**alshameeri.ai.eng@gmail.com

AI & Machine Learning Engineer

---

⭐ If you found this project useful, consider giving it a star.
