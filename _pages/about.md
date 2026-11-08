---
permalink: /
title: "Yanis Bardes"
seo_title: "Yanis Bardes — PhD Researcher in AI, Semi-Supervised & Federated Learning"
description: "Yanis Bardes is a PhD researcher in AI at Université Paris-Saclay (LISV) and Alten Labs, working on semi-supervised and federated learning for object detection and computer vision on UAVs. Publications, talks, teaching and CV."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate in Artificial Intelligence at [Université Paris-Saclay](https://www.universite-paris-saclay.fr/) (LISV laboratory), in an industrial CIFRE doctorate with **Alten Labs**. My research is on **semi-supervised federated learning for object detection**: how to train detectors when labels are scarce and the data stays spread across devices. The application is real-time waste detection by drone.

**I am looking for a research internship of up to 6 months starting in February 2027** (PhD defense planned after the internship). Feel free to [contact me](mailto:yanis.bardes@gmail.com).

I am supervised by Amar Ramdane-Chérif (LISV), Hassan Soubra (LyRIDS, ECE Paris) and Zineb Noumir (Alten Labs). I also took graduate courses in the [MVA Master](https://www.master-mva.com/) at ENS Paris-Saclay.

Alongside my research, I teach at [ECE Paris](https://www.ece.fr/) (Artificial Intelligence, MLOps, Mathematics) and [ESIEE Paris](https://www.esiee.fr/) (Big Data, Full-Stack Data Applications), including master's-level courses taught in English.

## Research

Drones collect far more images than anyone can annotate, and these images often cannot be pooled on a central server. My PhD studies how to learn object detectors in this setting:

- **Semi-supervised federated detection.** A server holds a small labeled set, while clients hold only unlabeled images. A teacher model produces pseudo-labels on the clients, and the server aggregates the client updates. I study which pseudo-labels to trust, where the teacher should run, and how to keep the clients' training signal reliable when their data differ (non-IID).
- **Training on the device.** Which detectors can actually be trained on board a drone (Jetson Orin NX), and which parts of the model to adapt during federated learning ([IEEE FLTA 2026](/publication/2026-flta-hardware-aware-detector-selection)).
- **Data and labels.** Building and auditing aerial waste datasets, and harmonizing annotations that disagree across sources ([MVEO, BMVC 2026](/publication/2026-mveo-waste-items-to-cleanup-units)).

## News

- **November 2026:** our paper *From Waste Items to Cleanup Units* will be presented at the MVEO workshop of BMVC 2026, Lancaster (26 November).
- **28 October 2026:** oral presentation of *Hardware-Aware Detector Selection for Federated UAV Waste Monitoring* at IEEE FLTA 2026, Paris.

## Research Interests

- Semi-supervised learning (pseudo-labeling, teacher-student training, learning with few labels)
- Federated learning (semi-supervised federated learning, non-IID data, parameter-efficient adaptation)
- Object detection and computer vision for UAVs
- Efficient on-device training and inference (Jetson Orin NX)
- Datasets, annotation harmonization and benchmarks
- Large language models and RAG

## Publications

First author on all papers. See the [Publications](/publications/) page for details.

**Accepted**
- *Hardware-Aware Detector Selection for Federated UAV Waste Monitoring.* IEEE FLTA 2026, Paris. Long paper, oral presentation.
- *From Waste Items to Cleanup Units: Harmonizing Instance Granularity with Geometry and Visual Context.* MVEO Workshop, BMVC 2026, Lancaster.

**Under review**
- *Autonomous UAV Perception with Federated Learning: A Survey on Collaborative Intelligence in Vehicle Environments.* IEEE Transactions on Intelligent Vehicles (T-IV). Earlier version on [TechRxiv](https://www.techrxiv.org/users/925495/articles/1300160-federated-learning-for-uav-perception-task-a-survey).
- *UAV-DiverseWaste: Harmonized Multisource Data and an Audited Benchmark for Aerial Waste Detection.* Neural Computing and Applications (NCA).

## Service

Reviewer for IEEE Transactions on Intelligent Vehicles (T-IV), IEEE Internet of Things Journal (IoT-J), Neural Computing and Applications (NCA) and IEEE FLTA 2026.

## Background

Before my PhD, I was a **Deep Learning Engineer at Lincoln** (Boulogne-Billancourt), where I built a patented multi-modal retrieval-augmented generation (RAG) system, and a member of the **data core team at AtlasAI**, where I helped train an LLM for Moroccan Arabic. I won two Kaggle silver medals (top 4%).

I hold a **Double Master's degree in Mathematics, Computer Science and Data Science (MIDS)** from Université Paris Cité and a **Bachelor's degree in Mathematics** (with honours) from Université Paris-Est Créteil.
