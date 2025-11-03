# 🧠 Advanced Emotion Recognition from EEG Data: A Hybrid Approach Using Autoencoders and LSTM

## 📘 Overview

This project presents a **novel hybrid deep learning architecture** for EEG-based emotion recognition that combines **Stacked Autoencoders (SAE)**, **Long Short-Term Memory (LSTM)** networks, and **temporal sequence learning**.
Built upon the **DEAP dataset** from **Queen Mary University, London**, this approach integrates spatial and temporal EEG feature representations for robust affective state prediction.

## 🧩 Key Highlights

* **Hybrid Architecture** — Fusion of Autoencoders for spatial feature compression and LSTMs for temporal sequence modeling.
* **EEG Preprocessing** — Implemented using **MNE** and **SciPy**, covering filtering, artifact removal, and normalization.
* **Superior Accuracy** — Achieved **89% accuracy** in Valence–Arousal prediction under **10-fold cross-validation**, outperforming baseline SVM and standalone LSTM models.
* **Optimized Performance** — Balanced computational efficiency and accuracy for real-time affective computing applications.

## 🧠 Methodology

1. **Data Preprocessing**

   * Imported raw EEG signals from the DEAP dataset.
   * Used MNE for channel referencing and bandpass filtering.
   * Applied feature extraction (PSD, DE, and statistical features).

2. **Model Architecture**

   * **Stacked Autoencoders (SAE):** Dimensionality reduction and hierarchical feature extraction.
   * **LSTM Layer:** Captures temporal dependencies across EEG sequences.
   * **Dense Output Layer:** Predicts emotion states (Valence–Arousal).

## 📄 Reference

**Dataset:** DEAP (Queen Mary University, London)
**Publication:** *To be submitted for peer review (2025)*

## 🧰 Future Work

* Integration of **attention mechanisms** for emotion-context mapping.
* Exploration of transfer learning with multimodal **EEG–fNIRS datasets**.
* Real-time edge deployment on **NVIDIA Jetson** or **Raspberry Pi 5** platforms.

## 🏅 Acknowledgements

Special thanks to **Queen Mary University, London**, for providing the DEAP dataset and the open-source EEG research community for foundational tools and frameworks.

## 📬 Contact

**Author:** Aaron Mano Cherian
**LinkedIn:** [linkedin.com/in/aaronmanocherian](https://www.linkedin.com/in/aaron-cherian/)
**Email:** [aaron.m.cherian@example.com](mailto:aaron.cherian@columbia.edu)

⭐ If you found this project insightful, consider giving it a star!
