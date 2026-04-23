# Privacy-Preserving Deepfake Video Detection using Federated Spatial–Frequency Feature Learning and Class-Aware Optimization

Official implementation of our paper on privacy-preserving deepfake video detection using Federated Learning, spatial-frequency representations, and class-aware loss learning. The paper is under review at The Visual Computer.

---

## Overview

This repository contains code for:

- Dataset preprocessing (RGB + FFT fusion)
- Federated training using FedAvg
- Cross-dataset evaluation
- Video-level aggregation
- Testing on:
  - FF++
  - Celeb-DF-v1
  - Celeb-DF-v2
  - UADFV
  - DeepfakeTIMIT

---

## Installation

```bash
pip install -r requirements.txt
