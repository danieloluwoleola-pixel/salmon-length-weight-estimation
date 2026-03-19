# 🐟 Atlantic Salmon Length & Weight Estimation using YOLOv8

A computer vision pipeline for precision aquaculture that:
- Detects Atlantic Salmon in images using YOLOv8
- Estimates fish length from bounding box dimensions
- Predicts weight using the allometric formula W = aL^b (Salmo salar)
- Generates population analytics across large image datasets

## Results
- 1,278 fish detected across 579 images
- Mean length: 28.5 cm
- Mean weight: 488g (0.49 kg)
- Total biomass estimate: 623.80 kg

## Models Used
- YOLOv8n (Ultralytics) — object detection
- CNN backbone — feature extraction
- Allometric regression — biological weight prediction

## Dataset
Salmon dataset via Roboflow — 579 images at 640×640

## Tech Stack
Python | YOLOv8 | OpenCV | Matplotlib | Pandas | Google Colab

## References
- Jonsson & Jonsson (2011) — Allometric constants for Salmo salar
- Ytrestøyl et al. (2020) — Feed cost in Atlantic salmon production
