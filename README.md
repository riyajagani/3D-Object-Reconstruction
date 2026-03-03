# 3D Reconstruction from Single Image using Deformable Implicit Representation

This project implements a **single-image 3D reconstruction pipeline** using a deep implicit neural representation. Given an RGB image and object mask, the model predicts a continuous occupancy field and reconstructs a 3D mesh.

The implementation is built using **PyTorch** and follows an implicit occupancy-based learning approach.

---

## 🚀 Overview

The system performs:

- Image feature extraction using a pretrained CNN encoder
- Implicit occupancy prediction for 3D coordinates
- Mesh extraction via volumetric sampling
- Evaluation using IoU and Chamfer Distance

This approach enables high-resolution mesh reconstruction without explicit voxel grids.

---


