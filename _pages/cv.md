---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD in Mathematics and Computer Science**, Université Paris-Saclay, LISV Laboratory, 2024–2027 (expected)
  * **Available for a research internship of up to 6 months from January 2027; defense planned after the internship.**
  * CIFRE industrial doctorate with Alten Labs
  * Supervisors: Amar Ramdane-Chérif (LISV), Hassan Soubra (LyRIDS, ECE Paris), Zineb Noumir (Alten Labs)

* **Graduate coursework**, MVA Master's programme, ENS Paris-Saclay
  * Large language models; detection theory and industrial applications; convex optimization for machine learning; foundations of distributed and large-scale optimization

* **Double Master's degree MIDS, Mathematics, Computer Science and Data Science**, Université Paris Cité, 2021–2023
  * Average above 14/20

* **Bachelor's degree in Mathematics** (with honours), Université Paris-Est Créteil, 2018–2021

Publications
======
First author on all listed papers.

**Accepted**
* **Y. Bardes**, O. El Alaoui El Ismaili, H. Soubra, Z. Noumir, A. Ramdane-Chérif. *Hardware-Aware Detector Selection for Federated UAV Waste Monitoring.* [IEEE International Conference on Federated Learning Technologies and Applications (FLTA 2026)](https://flta-conference.org/flta-2026/index.php), Paris. Long paper, oral presentation.
* **Y. Bardes**, H. Soubra, Z. Noumir, A. Ramdane-Chérif. *From Waste Items to Cleanup Units: Harmonizing Instance Granularity with Geometry and Visual Context.* Workshop on Machine Vision for Earth Observation, Environmental Monitoring and Climate Change (MVEO), British Machine Vision Conference (BMVC 2026), Lancaster.

**Under review**
* **Y. Bardes**, H. Soubra, Z. Noumir, A. Ramdane-Chérif. *Autonomous UAV Perception with Federated Learning: A Survey on Collaborative Intelligence in Vehicle Environments.* IEEE Transactions on Intelligent Vehicles (T-IV). Earlier version on [TechRxiv](https://www.techrxiv.org/users/925495/articles/1300160-federated-learning-for-uav-perception-task-a-survey).
* **Y. Bardes**, A. Tounsi, H. Soubra, Z. Noumir, A. Ramdane-Chérif. *UAV-DiverseWaste: Harmonized Multisource Data and an Audited Benchmark for Aerial Waste Detection.* Neural Computing and Applications (NCA, Springer).

Research Experience
======
* **PhD Researcher**, LISV, Université Paris-Saclay & Alten Labs, since April 2024
  * Semi-supervised federated learning for object detection on UAVs, applied to real-time waste detection.
  * **Semi-supervised federated detection (main research problem):** a server holds a small labeled set and clients hold only unlabeled images; a teacher produces pseudo-labels on the clients. Studying which pseudo-labels to trust, where the teacher should run, and how to keep training reliable under non-IID data (YOLOv8-L, Grid'5000).
  * **Hardware-aware federated detection:** profiled 17 convolutional, Transformer and hybrid detectors on a Jetson Orin NX (gradient-computation time, peak VRAM, power), then adapted the selected architectures under altitude-induced non-IID federated learning on seven clients, comparing head-only, head-and-neck and LoRA adaptation. Showed that pre-FL embeddability does not predict post-FL adaptation utility and that adapting multi-scale feature fusion consistently beats head-only tuning.
  * **Aerial waste data:** built UAV-DiverseWaste, a 30,387-image resource consolidating 24 third-party datasets and an Unreal Engine 5 drone simulation, with D²EW, a 2,442-image audited benchmark. Pooling nearly doubled accuracy on an unseen test campaign.
  * **Annotation harmonization:** built reviewed relational annotations for 1,891 images from 15 ground, UAV and CCTV sources, and developed a geometry-first method with visual correction that turns waste-item boxes into cleanup units, raising detection mAP@0.5 from 0.434 to 0.563 (manual reference labels: 0.610).

Peer Review
======
* **Journals:** IEEE Transactions on Intelligent Vehicles (T-IV), IEEE Internet of Things Journal (IoT-J), Neural Computing and Applications (NCA, Springer)
* **Conferences:** IEEE FLTA 2026

Teaching
======
* **Lecturer**, ESIEE Paris, since September 2026
  * Big Data: final-year engineering students (ING5)
  * Full-stack data applications: engineering programme, master's level, international track, taught in English
* **Lecturer**, ECE Paris, since September 2025
  * Artificial Intelligence: engineering programme, master's level
  * MLOps: MSc in AI, master's level, international track, taught in English
  * Mathematics: preparatory cycle, first to third year
* **Mathematics Tutor**, Université Paris Cité, 2022–2023
  * Undergraduate mathematics tutoring, first to third year

Industry Experience
======
* **Data Core Team Member**, AtlasAI (remote), March 2024 – September 2025
  * Collected and prepared training data for language models in Moroccan Arabic, and trained an LLM for this dialect. Data and model available at [huggingface.co/atlasia](https://huggingface.co/atlasia).

* **Deep Learning Engineer**, Lincoln, Boulogne-Billancourt, October 2023 – April 2024
  * **Generative AI:** built a patented multi-modal RAG pipeline (LLM, embedding model, vector database, inference engine), generated synthetic question-answer data, developed a full-stack demonstrator and presented the platform to clients.
  * **Document structuring:** extracted document elements with OCR, structured text with regex and LLMs, and parallelized both pipelines.
  * **Deployment:** containerized the RAG, OCR and political-debate analysis projects with Docker, and set up CI/CD and monitoring on Azure DevOps.

Competitions and Projects
======
* **ASL video-to-text translation, Google Kaggle competition. Silver medal (top 4%).** Hand-motion detection with MediaPipe and a Conformer translation model.
* **NASDAQ closing-price prediction, Optiver Kaggle competition. Silver medal (top 4%).** Time-series forecasting model.
* **CV search platform.** Put a real-time semantic retrieval system into production.

See the [Portfolio](/portfolio/) page for code.

Skills
======
* **Programming:** Python, PySpark, Java, C, C++, R, TypeScript, JavaScript, LaTeX, Bash
* **Databases:** SQL, CQL, Neo4j, SPARQL, Faiss, Elasticsearch, Weaviate
* **ML and data:** PyTorch, TensorFlow, Keras, Ultralytics, Hugging Face, Scikit-Learn, FiftyOne, Spark, MLflow, LangChain, LlamaIndex, Ollama
* **Infrastructure:** Docker, Kubernetes, Linux, Grid'5000, Jetson Orin NX, MinIO, GitHub, Azure (cloud computing, DevOps, VM, Blob Storage)
* **Languages:** French (native), English (B2, teaches master's-level courses in English), Spanish (B1), Arabic (A2)
