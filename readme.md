# 🌊 Underwater Simulation and Dataset Index
This repository was initiated following the AQ²UASIM workshop at [ICRA 2025](https://sites.google.com/view/aq2uasim/), held on May 23, 2025, in Atlanta, GA. The workshop emphasized the critical role of realistic, open-source simulation environments in overcoming the high entry barriers of underwater robotics research. By providing cost-effective, risk-free platforms for testing and development, these tools aim to accelerate innovation in the field.

Our goal is to curate a comprehensive list of publicly available underwater **simulations** and **datasets** that support research in **perception**, **state estimation**, and **sensor modeling**.

If you know of a valuable resource not listed here, please open a pull request or issue to contribute.

---

---

## 📋 Table of Simulations

## ⚙️ Simulation Environments

| Name        | Engine  | Link                                                                                   | Perception | State Estimation | Sensors | Contribution                                                                 |
|-------------|---------|----------------------------------------------------------------------------------------|------------|------------------|---------|------------------------------------------------------------------------------|
| HoloOcean   | Unreal Engine  | [Link](https://byu-holoocean.github.io/holoocean-docs/v1.0.0/index.html)               | ✅         | ✅               | ✅      | High-fidelity underwater robotics simulator with support for common sensors and multi-agent missions. |
| OceanSim    | NVIDIA IssacSim  | [Link](https://github.com/umfieldrobotics/OceanSim/)                                              | ✅         | ✅               | ✅      | Multibeam sonar simulator for bathymetry and acoustic modeling.             |
| OysterSim   | Blender | [Link](https://github.com/prgumd/Oystersim)                                      | ✅         | ✅               | ✅      | Realistic underwater oyster farm simulator in Blender with support for synthetic data generation and navigation. |
| MARUS   | Unity3D | [Link](https://github.com/MARUSimulator/marus-core)                                      | ✅         | ✅               | ✅      | Automatic annotation and dataset generation capabilities, used to support vision model training |


## 🗂️ Datasets

| Name           | Link                                                                 | Size   | Images | Contribution                                                                 |
|----------------|----------------------------------------------------------------------|--------|--------|------------------------------------------------------------------------------|
| Sweet Corals   | [Link](https://huggingface.co/datasets/wildflow/sweet-corals)       | 352 GB | 90,289 | High-resolution underwater coral reef imagery from Indonesia, captured using GoPro cameras for 3D photogrammetry. The dataset includes raw images and some color-corrected versions, with plans to add camera poses, 3D point clouds, meshes, orthomosaics, annotations, and 3D Gaussian Splatting models. |

---

## 📌 How to Contribute

Please format new entries using the existing table. Indicate applicability to perception, state estimation, and/or sensors with ✅ or ❌. Use “N/A” for datasets without a simulation engine.
I will try to handle the pulls monthly. 
---
