# Mapping-speech-imagery-signal-to-Stiefel-manifold
# EEG on the Stiefel Manifold: Reading & Processing (`read_stiefel.ipynb`)

This repository provides a clean, reproducible walkthrough of **reading, validating, and processing EEG-derived matrices on the Stiefel manifold** (orthonormal column constraint), with practical utilities for:
- Orthonormalization and projection via **QR**,
- **Retraction** and **vector transport** for updates on Stiefel,
- **Riemannian gradient** handling,
- Computing a **Fréchet mean** as a geometric reference,
- **Log/Exp maps** for tangent–space embeddings,
- Preparing features for downstream ML/DL pipelines.

> **Use case**: imagined-speech EEG → trial-wise matrices with orthonormal columns.
---
Mapping "2020 Internatinal BCI competition" dataset to Stiefel manifold.
## 📂 Dataset

The experiments in this repository are based on the **Imagined Speech EEG dataset** available on OSF:

🔗 [Download from OSF (pq7vb)](https://osf.io/pq7vb/)

- Number of subjects: 15  
- Channels: 64 EEG electrodes (subset of channels also used in experiments)  
- Trials: 300 trials per subject, 5 classes (Hello, Help me, Stop, Thank you, Yes)  
- Sampling rate: 512 Hz  
- Format: `.mat` files (preprocessed EEG trials)




