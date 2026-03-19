---
title: "ASL to Text Video Translation"
excerpt: "Kaggle competition by Google — top 4%. Sign language video transcription to text."
collection: portfolio
---

Kaggle competition by Google — **top 4%**.

Model to transcribe American Sign Language (ASL) from video to text. Hand position detection followed by text translation.

**Approach:** Image processing and data augmentation, MediaPipe for hand movement detection, then a Conformer model (convolution + attention mechanism).

**Stack:** TensorFlow, TFLite, OpenCV, MediaPipe, Transformers, Conformers, CNN, CTCLoss, AdamW

[View on GitHub](https://github.com/sinaayyy/ASL2TEXT)
