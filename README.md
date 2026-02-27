🚀 Project Overview

This project focuses on building a robust semantic segmentation model tailored for off-road autonomous navigation in desert environments. Using synthetically generated data, we trained an efficient transformer-based segmentation model to identify critical terrain elements relevant to UGV (Unmanned Ground Vehicle) perception.

We use SegFormer (a Vision Transformer based segmentation model) to handle complex textures and irregular object boundaries in varying desert conditions. Through careful preprocessing, augmentation, and training procedures, the model achieves accurate segmentation while keeping inference latency acceptable for real-time applications.

🧠 Problem Statement

Off-road autonomy requires dense pixel-level understanding of terrain. The synthetic dataset contains RGB images and corresponding segmentation masks for 10 classes, including navigational obstacles (Logs, Rocks), vegetation types, and background terrain.

Challenges addressed:

Severe class imbalance (Landscape & Sky dominate)

Overfitting to synthetic textures

Balancing segmentation accuracy with real-time inference requirements
