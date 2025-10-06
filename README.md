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



