---
title: "Hardware-Aware Detector Selection for Federated UAV Waste Monitoring"
collection: publications
category: conferences
permalink: /publication/2026-flta-hardware-aware-detector-selection
excerpt: 'We profile 17 convolutional, Transformer and hybrid detectors on a Jetson Orin NX, then adapt the selected ones under altitude-induced non-IID federated learning. Pre-FL embeddability does not predict post-FL adaptation utility, and adapting multi-scale feature fusion consistently beats head-only tuning. Long paper, oral presentation.'
date: 2026-10-27
venue: 'IEEE International Conference on Federated Learning Technologies and Applications (FLTA 2026), Paris'
citation: 'Y. Bardes, O. El Alaoui El Ismaili, H. Soubra, Z. Noumir, A. Ramdane-Chérif. &quot;Hardware-Aware Detector Selection for Federated UAV Waste Monitoring.&quot; <i>IEEE FLTA 2026</i>, Paris.'
---

**Authors:** Y. Bardes, O. El Alaoui El Ismaili, H. Soubra, Z. Noumir, A. Ramdane-Chérif.

Drones that detect waste must run, train and learn together across very different flight altitudes. We measure the on-device training cost of 17 detectors on a Jetson Orin NX (gradient-computation time, peak VRAM, power), then adapt the selected architectures under altitude-induced non-IID federated learning on seven clients, comparing head-only, head-and-neck and LoRA adaptation.

Main findings: rankings do not carry over from one stage to the next, and adapting the neck (multi-scale feature fusion) consistently beats head-only tuning. LoRA sends far less data, at some cost in accuracy.

Long paper, oral presentation. [Conference website](https://flta-conference.org/flta-2026/index.php).
