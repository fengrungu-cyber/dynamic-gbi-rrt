# Real-Time Adaptive Navigation for Mobile Robots in Dynamic Environments

## Overview
This repository presents an adaptive navigation framework for autonomous mobile robots in dynamic environments. The proposed approach integrates LRBPF-SLAM-based localization, online map updating, uncertainty-aware obstacle prediction, and Dynamic GBI-RRT path planning.

## Key Features
- **Localization:** LRBPF-SLAM-based robot pose estimation.
- **Adaptive Mapping:** Selective updates of dynamically affected map regions.
- **Obstacle Prediction:** Motion forecasting using an adaptive Motion Confidence Index (MCI).
- **Dynamic Path Planning:** Predictive Dynamic GBI-RRT with uncertainty-aware collision-risk assessment.
- **Event-Triggered Replanning:** Adaptive replanning in response to changing environmental conditions.
- **Performance Evaluation:** Comparison with GBI-RRT, RRT*, D* Lite, and Timed Elastic Band (TEB).

## Reported Results
The proposed framework achieves the following results in the experiments reported in the associated manuscript:

- Navigation success rate: 94%
- Collision rate: 3.9%
- Average planning time: 21.4 ms
- Real-time execution rate: 0.90

These results correspond to the experimental conditions described in the manuscript.

## Experimental Scenarios
The framework is evaluated in simulated indoor environments, including warehouse environments, hospital corridors, and general corridor scenarios.

## Repository Structure
The repository is intended to include the implementation, experimental configurations, evaluation scripts, and supplementary documentation associated with the proposed framework.

## Reproducibility
Details regarding software dependencies, experimental parameters, baseline configurations, and execution instructions should be provided alongside the corresponding source files.

## Code Availability
Source code and supplementary resources are provided in this repository to support research transparency and reproducibility.

## Citation
Please cite the associated research article when using this implementation in academic work. Bibliographic information will be added when available.

## Limitations
Reported performance is based on the experimental scenarios described in the manuscript. Further real-world testing is needed to assess deployment performance under practical operating conditions.
