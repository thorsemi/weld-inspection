# AI-Enhanced Visual Inspection of Pharmaceutical Pipe Welds

Computer vision solution for automating the visual qualification of pharmaceutical pipe welds.

## Overview

- **End-to-End Ownership:** Directed the complete development lifecycle of a computer vision solution to automate the visual qualification of pharmaceutical pipe welds.

- **System Architecture:** Architected a multi-head deep learning pipeline utilizing self-supervised Vision Transformers for precise segmentation and unsupervised anomaly detection.

- **Hardware Integration:** Engineered and deployed a portable edge computing prototype using NVIDIA Jetson Orin NX, enabling real-time weld classification directly on the factory floor.

- **Regulatory Compliance:** Bridged the gap between AI and strict pharmaceutical regulations (GMP) by integrating Explainable AI (XAI) features like Grad-CAM and attention maps for full decision traceability.

## Performance

- **Validation:** Achieved a high mean Average Precision (mAP), significantly outperforming traditional CNN baselines and establishing a new standard for objective quality assurance.

## System Architecture

![Multi-head pipeline architecture](architecture.png)

## Edge Prototype

![Portable edge computing prototype](prototype.png)

## Explainability (XAI)

![Class-wise heatmaps overlaid on borescope images](xai.png)
