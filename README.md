# 🚀 Audio Noise Reduction using Spectral Gating

This project demonstrates how to remove background noise from audio recordings using **Spectral Gating**, implemented in Python. It is beginner-friendly and uses only free, open-source libraries.

---

## 📌 Project Overview

- 🎯 **Goal:** Remove steady background noise (e.g., air conditioning, chatter) while preserving speech.
- 🛠 **Techniques Used:** Spectral Gating with automatic noise estimation
- 🗣 **Application:** Can be used for cleaning up noisy voice recordings, teleconferences, or sound events.

---

## 🛠 Tools and Libraries

| Library        | Purpose                          |
|---------------|----------------------------------|
| `librosa`      | Audio loading and visualization |
| `noisereduce`  | Spectral Gating Noise Reduction |
| `soundfile`    | Saving cleaned audio            |
| `matplotlib`   | Plotting waveforms              |

---

## 🔗 Installation

1. Install Python 3.8 or newer.
2. Install required libraries:
   ```bash
   pip install noisereduce librosa matplotlib soundfile
