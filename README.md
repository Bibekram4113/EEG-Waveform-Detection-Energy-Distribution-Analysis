# 🧠 EEG Waveform Detection & Energy Distribution Analysis

This repository contains a **MATLAB-based signal processing project** that analyzes EEG signals from the **DEAP dataset** to detect different brainwave frequency bands (**delta, theta, alpha, beta, gamma**) and compute their **energy distribution using Power Spectral Density (PSD)**.  

The project demonstrates applications in **cognitive load monitoring**, **neurological disorder analysis**, and **brain-computer interface (BCI) systems**.  

---
---
**
## 🚀 Project Overview**
- EEG signals are analyzed to **detect dominant brainwave activity**.  
- **Fast Fourier Transform (FFT)** and **Power Spectral Density (PSD)** are used to study frequency distribution.  
- Band-specific power is extracted for **delta, theta, alpha, beta, gamma**.  
- Results provide insights into **cognitive states**, **focus/relaxation levels**, and **neurological conditions**.  

---

**## 📊 Dataset**
- **Dataset:** [DEAP (Database for Emotion Analysis using Physiological Signals)](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/)  
- EEG collected from **32 participants** while watching **40 one-minute music videos**.  
- Each participant: **32-channel EEG, 128 Hz sampling rate**.  
- Preprocessed dataset is already provided (downsampled, artifact removal applied).  

---

**## 🧠 Brainwave Frequency Bands**

| Band   | Frequency Range | Associated Cognitive State |
|--------|----------------|----------------------------|
| **Delta**  | 0.5 – 4 Hz     | Deep sleep, unconscious processes |
| **Theta**  | 4 – 8 Hz       | Drowsiness, meditation, creative states |
| **Alpha**  | 8 – 13 Hz      | Relaxed but alert, calm awareness |
| **Beta**   | 13 – 30 Hz     | Active thinking, focus, problem-solving |
| **Gamma**  | 30 – 50+ Hz    | High-level processing, memory, learning |

---

**## 🧩 Methodology**
1. **Load EEG signals** from the DEAP dataset (MATLAB `.mat` files).  
2. **Preprocess signals**: band-pass filtering, noise removal.  
3. **Apply FFT & Welch’s method** to compute Power Spectral Density (PSD).  
4. **Extract band-specific energy** by integrating PSD over frequency ranges.  
5. **Normalize energy values** across all frequency bands.  
6. **Visualize**: EEG waveform, PSD spectrum, and relative energy per band.  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/EEG-Waveform-Detection.git
   cd EEG-Waveform-Detection
