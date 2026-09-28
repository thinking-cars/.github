# Thinking Cars GmbH – Qualifying the Future of Open-Source Automated Driving

[![Website](https://img.shields.io/badge/Website-thinking--cars.de-brightgreen?style=for-the-badge)](https://thinking-cars.de/)
[![Contact](https://img.shields.io/badge/Contact-info%40thinking--cars.de-yellow?style=for-the-badge)](mailto:info@thinking-cars.de)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Thinking%20Cars-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/company/thinking-cars/)

**Open. Transparent. Qualified.**
> We build the benchmark for transparent, trustworthy, and sovereign AD software.
> Making open-source driving stacks easier to evaluate, easier to trust, and easier to integrate.

---

## 🎯 What We Do

Open-source automated driving stacks are powerful, but without transparent benchmarking and qualification, industrial adoption remains slow and risky. 
**We close that gap.** Not with black-box claims, but with transparent benchmarks run on your data, structured qualification documentation, and evidence that holds up where it counts.

| | |
|---|---|
| ✅ **100 % Transparent & Open-Source** | Every evaluation process is fully documented and reproducible |
| 🔓 **0 % Vendor Lock-In** | Built on open ecosystems |
| ♾️ **Unlimited Integration Possibilities** | Modular approach supports any target stack or application |

---

## 🛠️ Our Services

### 🔍 Discover 
We identify the right open-source components for your target application and compliance requirements, and map them against your existing stack.

### 📊 Evaluate – *Prototype Available*
Automated evaluation and testing for open-source AD components. Transparent, reproducible metrics and report generation. Running on **your data** for **your auditable evidence**.

### 📋 Qualify – *Coming Soon*
Structured qualification documentation aligned with relevant standards. Ready for internal sign-off or external regulatory audit.

### 🔧 Integration & Long-Term Support – *Coming Soon*
Expert consulting to help OEM and autonomy teams select, adopt, and integrate open-source AD software into real delivery pipelines.

---
## 📦 Key Repositories

### 🏎️ Benchmarking (`thinking-cars`)

| Repository | Description | Teaser | Release |
| ---------- | ----------- | ------ | ------- |
| [autonomy_datasets](https://github.com/thinking-cars/autonomy_datasets) | Unified ROS 2 Interface for automated driving datasets. | <img src="teaser-datasets.gif" width="200"> | [![](https://img.shields.io/github/v/release/thinking-cars/autonomy_datasets)](https://github.com/thinking-cars/autonomy_datasets/releases/latest) |
| [autonomy_evaluation](https://github.com/thinking-cars/autonomy_evaluation) | Within the Autonomy.Benchmarks suite, Autonomy.Evaluation generates the metrics-based evidence for benchmarking automated driving deployments. | <img src="teaser-bot.gif" width="200"> | [![](https://img.shields.io/github/v/release/thinking-cars/autonomy_benchmarks)](https://github.com/thinking-cars/autonomy_benchmarks/releases/latest) |
| [autonomy_bot]() | Easily benchmark automated driving modules and full AD stacks as part of your CI/CD workflow. | <img src="teaser-bot.gif" width="200"> | 🚧 Under Construction |

### 🧩 OpenADS — Open Automated Driving Systems (`openads-project`)

Thinking Cars is an active contributor and maintainer in the OpenADS community — an ecosystem for building and benchmarking interoperable AD software. Developed as part of Germany's [Ecosystem Mobility 4.0](https://ecosystemmobility40.de/en/home/) initiative and aligned with the [European Connected and Autonomous Vehicle Alliance](https://digital-strategy.ec.europa.eu/en/policies/vehicle-alliance).

| Repository | Description | Release |
| ---------- | ----------- | ------- |
| [OpenADS](https://github.com/openads-project/) | [**Open Automated Driving Systems Ecosystem**](https://openads-project.github.io), including automated driving software stack, simulation and development toolchain. | [![](https://img.shields.io/badge/release-multiple-green)](#) |
| [OpenADStack](https://openads-project.github.io/openadstack/openadstack.html) | Baseline reference implementation for modular ROS 2 automated-driving stacks in OpenADS. | [![](https://img.shields.io/github/v/release/openads-project/openadstack)](https://github.com/openads-project/openadstack/releases/latest) |
| [OpenADSim](https://openads-project.github.io/openadsim/openadsim.html) | Simulation environment for testing the OpenADStack with CARLA or SUMO. | [![](https://img.shields.io/github/v/release/openads-project/openadsim)](https://github.com/openads-project/openadsim/releases/latest) |
| [OpenADSuite](https://openads-project.github.io/openadsuite/openadsuite.html) | Development tools that streamline developer workflows, such as module templates and ready-to-use development environments. | [![](https://img.shields.io/badge/release-multiple-green)](#) |
| [OpenADSafety 🚧](https://openads-project.github.io/openadsafety/openadsafety.html) | Documentation and tools for validation and verification of automated-driving modules and full stacks. | [![](https://img.shields.io/badge/release-wip-yellow)](#) |


#### OpenADS Module Integrations

| Repository | Description | Teaser | Release |
| ---------- | ----------- | ------ | ------- |
| [autoware_lidar_centerpoint](https://github.com/thinking-cars/autoware_lidar_centerpoint) | Modularized 3D lidar detection model from [Autoware Universe](https://github.com/autowarefoundation/autoware_universe). | <img src="https://github.com/thinking-cars/autoware_lidar_centerpoint/blob/main/assets/teaser-waymo.gif" width="200"> | [![](https://img.shields.io/github/v/release/thinking-cars/autoware_lidar_centerpoint)](https://github.com/thinking-cars/autoware_lidar_centerpoint/releases/latest) |
| [autoware_multi_object_tracker](https://github.com/thinking-cars/autoware_multi_object_tracker) | Modularized 3D multi-object tracker from [Autoware Universe](https://github.com/autowarefoundation/autoware_universe). | <img src="https://github.com/thinking-cars/autoware_multi_object_tracker/blob/main/assets/teaser-nuscenes.gif" width="200"> | [![](https://img.shields.io/github/v/release/thinking-cars/autoware_multi_object_tracker)](https://github.com/thinking-cars/autoware_multi_object_tracker/releases/latest) |
| [focalformer3d_detector](https://github.com/thinking-cars/focalformer3d_detector) | ROS 2 integration of the [NVlabs/FocalFormer3D](https://github.com/NVlabs/FocalFormer3D) lidar object detection model. | <img src="https://github.com/thinking-cars/focalformer3d_detector/raw/main/assets/teaser.gif" width="200"> | [![](https://img.shields.io/github/v/release/thinking-cars/focalformer3d_detector)](https://github.com/thinking-cars/focalformer3d_detector/releases/latest) |

---

## 🎓 Research & Events

| Event | Description | Status |
|---|---|---|
| [**IEEE ITSC 2026 Tutorial**](https://openads-project.github.io/tutorial-itsc-26/) | OpenADS tutorial at IEEE International Conference on Intelligent Transportation Systems, Naples, Italy | ✅ Active |

