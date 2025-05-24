# 🌊 Underwater Simulation and Dataset Index

This repository emerged from discussions at the AQ²UASIM workshop during ICRA 2025 in Atlanta, GA. The workshop highlighted a critical challenge in underwater robotics research: the need for accessible, high-fidelity simulation environments and comprehensive datasets to overcome the field's inherently high barriers to entry.

Underwater robotics presents unique challenges—expensive hardware, limited testing opportunities, and harsh operating environments all constrain innovation. Realistic simulation environments and well-curated datasets offer a compelling solution, providing researchers with cost-effective, risk-free platforms for algorithm development and validation before committing to real-world deployments.

Our objective is to maintain a comprehensive catalog of publicly available underwater simulations and datasets that support research across perception, state estimation, and sensor modeling domains. This resource aims to accelerate progress in underwater robotics by connecting researchers with the tools they need.

We welcome community contributions—if you're aware of valuable resources not currently listed, please submit a pull request or open an issue.

---

---

# 📋 Table of Simulations

## ⚙️ Simulators

| Name | Engine | Link | RGB Camera | Stereo Camera | Low-light Camera | Imaging Sonar | Forward-Looking Sonar | Side-scan Sonar | Multibeam Sonar | Contribution |
|------|--------|------|------------|---------------|------------------|---------------|----------------------|-----------------|-----------------|--------------|
| HoloOcean | Unreal Engine | [Link](https://byu-holoocean.github.io/holoocean-docs) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | High-fidelity underwater robotics simulator with support for common sensors and multi-agent missions. |
| OceanSim | NVIDIA Isaac Sim | [Link](https://github.com/umfieldrobotics/OceanSim/) | ✅ | ❌ | ❌ | ✅ | ✅ | ❌ | ✅ | Multibeam sonar simulator for bathymetry and acoustic modeling. |
| OysterSim | Blender | [Link](https://github.com/Field-Robotics-Lab/USU) | ✅ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ | Realistic underwater oyster farm simulator in Blender with support for synthetic data generation and navigation. |
| Stonefish | Custom | [Link](https://github.com/patrykcieslak/stonefish) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Open-source, ROS-compatible underwater simulator with advanced physics modeling and comprehensive sensor simulation. |
| DAVE | Unreal Engine 5 | [Link](https://github.com/Field-Robotics-Lab/dave) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Project DAVE offers high-detail rendering and physics simulation for underwater vehicles and environments. |
| UNav-Sim | Unreal Engine 5 | [Link](https://github.com/open-airlab/UNav-Sim) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Visually realistic simulator with autonomous vision-based navigation stack and synthetic data generation capabilities. |
| MARUS | Unity3D | [Link](https://github.com/MARUSimulator/marus-core) | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | Automatic annotation and dataset generation capabilites for vision tasks. |
| UUV Simulator | Gazebo | [Link](https://github.com/uuvsimulator/uuv_simulator) | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | Gazebo-based package for underwater intervention and multi-robot simulation with accurate hydrodynamics modeling. |
| UWSim | OpenSceneGraph | [Link](https://github.com/uji-ros-pkg/underwater_simulation) | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ❌ | UWSim-NET provides underwater simulation with network capabilities for distributed marine robotics. |
| BlueSim | Unreal Engine | [Link](https://github.com/BlueROV/BlueSim) | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | Simulator specifically designed for Blue Robotics vehicles with realistic underwater physics and sensor modeling. |
| Gemini | Unity3D | [Link](https://github.com/Gemini-team/Gemini) | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | Provides a foundation for electromagnetic radiation based sensors (RGB, Lidar, Radar) for use in autonomous appplications. |

## 🗂️ Datasets

| Name | Link | Size | Images | RGB Camera | Stereo Camera | Low-light Camera | Imaging Sonar | Forward-Looking Sonar | Side-scan Sonar | Multibeam Sonar | Contribution |
|------|------|------|--------|------------|---------------|------------------|---------------|----------------------|-----------------|-----------------|--------------|
| Sweet Corals | [Link](https://huggingface.co/datasets/wildflow/sweet-corals) | 352 GB | 90,289 | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | High-resolution underwater coral reef imagery from Indonesia, captured using GoPro cameras for 3D photogrammetry. The dataset includes raw images and some color-corrected versions, with plans to add camera poses, 3D point clouds, meshes, orthomosaics, annotations, and 3D Gaussian Splatting models. |
| Underwater Caves | [Link](https://cirs.udg.edu/caves-dataset/) | 3.7 GB | N/A | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | Data collected in underwater cave complexes using an AUV equipped with mechanically scanned imaging sonar and camera. Provides ground truth validation for underwater navigation and mapping. |
| MIT Marine Perception | [Link](https://seagrant.mit.edu/auvlab-datasets-marine-perception-1/) | N/A | N/A | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | Multi-modal sensor dataset for marine robotics research collected in Charles River and Boston Harbor. Includes data from 3D Lidar, radar, and multiple camera types for autonomous surface vessel development. |
| AURORA | [Link](https://nora.nerc.ac.uk/532651/) | N/A | N/A | ✅ | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | Multi-sensor dataset for robotic ocean exploration combining sidescan sonar, multibeam echosounder, and seafloor camera imagery with comprehensive metadata. |
| AQUALOC | [Link](https://www.lirmm.fr/aqualoc/) | 5.1 GB | 7,965 | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | Dataset dedicated to underwater localization of vehicles navigating close to the seabed, including camera images for SLAM and visual odometry development. |
| CADDY | [Link](http://www.caddian.eu/) | N/A | 10,000+ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | Underwater stereo-vision dataset for human-robot interaction in the context of diver activities, featuring diver sign language (CADDIAN) for communication with AUVs. |
| Common Objects Underwater (COU) | [Link](https://arxiv.org/html/2502.20651v1) | N/A | N/A | ✅ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | Instance-segmented image dataset of commonly found man-made objects in multiple aquatic and marine environments, designed for underwater object detection and segmentation tasks. |

## 📌 How to Contribute

Please format new entries using the existing table structure. Indicate sensor support with ✅ or ❌ as appropriate. For datasets without a simulation engine, use "N/A" in the Engine field.

Pull requests are reviewed monthly.

---
