# 🐟 AquaTutor

> **A Practical Research Project for Semi-Supervised Underwater Fish Detection Using Modern Computer Vision**

![Status](https://img.shields.io/badge/Status-In%20Development-blue)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00)
![YOLOv8](https://img.shields.io/badge/YOLO-v8-green)
![License](https://img.shields.io/badge/License-MIT-success)

---

## Overview

AquaTutor is an open-source research project investigating **semi-supervised learning (SSL)** for underwater fish detection.

The project forms the foundation of my MSc in Artificial Intelligence at the University of Galway and explores how modern computer vision techniques can reduce the need for large manually labelled datasets.

The long-term objective is to design a **Teacher–Student learning framework** capable of producing accurate fish detection models using only a small quantity of labelled underwater images together with large collections of unlabelled marine imagery.

Rather than focusing solely on the final model, AquaTutor documents the complete research journey including:

- Dataset acquisition
- Data exploration
- Annotation
- Dataset quality improvement
- Supervised learning
- Semi-supervised learning
- Model evaluation
- Experiment tracking
- Research documentation

The repository is intended to be fully reproducible and publicly available.

---

# Research Objectives

The project aims to answer the following research questions.

### RQ1

Can a Teacher–Student semi-supervised learning framework achieve comparable fish detection performance using significantly fewer labelled images?

### RQ2

How do pseudo-label generation and weak/strong augmentation influence model performance?

### RQ3

Can semi-supervised learning improve generalisation to unseen underwater environments?

---

# Project Goals

- Learn the complete AI research workflow
- Build an end-to-end computer vision pipeline
- Develop a reproducible research project
- Explore semi-supervised object detection
- Create a public open-source AI project
- Produce the foundation for an MSc Capstone dissertation

---

# Technology Stack

| Area | Technology |
|-------|------------|
| Development | Google Colab |
| Programming | Python |
| Computer Vision | Ultralytics YOLO |
| Dataset Management | FiftyOne |
| Annotation | CVAT |
| Dataset Preparation | Roboflow |
| Version Control | GitHub |
| Documentation | Markdown |
| Experiment Tracking | MLflow / Weights & Biases (planned) |

---

# Repository Structure

```text
AquaTutor/
│
├── docs/
├── notebooks/
├── datasets/
├── models/
├── experiments/
├── figures/
├── reports/
├── scripts/
├── src/
├── presentations/
│
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
└── CITATION.cff
```

---

# Project Roadmap

## Phase 1

Project Foundation

- Repository setup
- Documentation
- Development environment

---

## Phase 2

Dataset Pipeline

- Acquire datasets
- Explore datasets
- Clean datasets
- Annotation

---

## Phase 3

Baseline Model

- Train YOLO
- Evaluate results
- Error analysis

---

## Phase 4

Semi-Supervised Learning

- Teacher model
- Pseudo-label generation
- Student model

---

## Phase 5

Experiments

- Label ratio experiments
- Confidence threshold tuning
- Augmentation studies
- Generalisation testing

---

## Phase 6

Research Outputs

- Technical report
- Dissertation
- Presentation
- Public release

---

# Current Status

| Sprint | Status |
|----------|--------|
| Sprint 1 – Project Foundation | 🟡 In Progress |
| Sprint 2 – Dataset Pipeline | ⬜ Planned |
| Sprint 3 – Dataset Exploration | ⬜ Planned |
| Sprint 4 – Baseline YOLO | ⬜ Planned |
| Sprint 5 – Teacher Model | ⬜ Planned |
| Sprint 6 – Student Model | ⬜ Planned |
| Sprint 7 – Experiments | ⬜ Planned |
| Sprint 8 – Documentation | ⬜ Planned |

---

# Research Philosophy

This project follows an incremental development methodology.

Every sprint will:

- Learn
- Build
- Evaluate
- Document
- Release

The emphasis is on reproducible AI research rather than simply producing a final model.

---

# Future Work

- Vision-Language Models (CLIP)
- Open Vocabulary Detection
- Active Learning
- Edge Deployment
- Marine Species Classification
- Real-Time Video Detection

---

# Acknowledgements

This project is being developed as part of the MSc in Artificial Intelligence at the University of Galway.

Special thanks to the open-source computer vision community and the developers of Ultralytics, FiftyOne, CVAT and Google Colab.

---

# License

This project will be released under the MIT License.

---

# Citation

Citation details will be added once the first public release is available.
