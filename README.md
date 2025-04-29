# PerReg+: Towards Generalizable Trajectory Prediction using Dual-Level Representation Learning and Adaptive Prompting

Official codebase for the CVPR 2025 paper:  
**"Towards Generalizable Trajectory Prediction using Dual-Level Representation Learning and Adaptive Prompting"**  
by *Kaouther Messaoud, Matthieu Cord, and Alexandre Alahi*.

---

## Table of Contents
- [Overview](#overview)
- [Paper](#paper)
- [Highlights](#highlights)
- [Benchmarks](#benchmarks)
- [Coming Soon](#coming-soon)

---

## Overview

**PerReg+** is a novel transformer-based framework for **vehicle trajectory prediction**. It addresses key challenges in autonomous driving by:
- Generalizing across domains and datasets
- Enabling multimodal prediction without clustering or NMS
- Providing efficient domain adaptation via adaptive prompt tuning

### Key Innovations:
- **Dual-Level Representation Learning** using Self-Distillation (SD) and Masked Reconstruction (MR)
- **Register-based Queries** for efficient and structured multimodal output
- **Segment-Level Reconstruction** of trajectories and lanes
- **Adaptive Prompt Tuning** for scalable and fast fine-tuning

PerReg+ achieves **state-of-the-art** results on the [UniTraj Benchmark](https://github.com/vita-epfl/UniTraj) and shows strong cross-domain generalization.

---

## Paper

- 📄 [CVPR 2025 Paper (PDF)](link_to_paper) *(link will be added when available)*

---

## Highlights

- 📉 **6.8% reduction** in Brier-minFDE on small datasets through SSL pretraining
- 🔄 **11.8% improvement** in cross-domain generalization performance
- ⚡ **Prompt-based fine-tuning**: adapts with minimal overhead
- 🛠 **No clustering/NMS** required for multimodal prediction
- 🧠 **Richer scene understanding** through segment-level reconstruction and dual-level supervision

---

## Benchmarks

Evaluated on:
- [nuScenes](https://www.nuscenes.org/)
- [Argoverse 2](https://www.argoverse.org/av2.html)
- [Waymo Open Motion Dataset (WOMD)](https://waymo.com/open/data/motion/)

**Achievements:**
- Outperforms AutoBot, MTR, and Forecast-MAE baselines
- Best B-FDE and minFDE across single-dataset and multi-dataset training
- Strong generalization to unseen domains

---

## Coming Soon

- 📦 Full code release (training & evaluation)
- 🏆 Pretrained model checkpoints
- 📚 Detailed instructions and tutorials
