# SWIM: An Efficient Framework to Train Neural Networks
This project analyzes the **Sampling Where It Matters (SWIM)** framework [2], an innovative approach for training fully-connected neural networks that avoids iterative, gradient-based optimization by directly sampling weights from the available data.

## Abstract
The project explores the efficiency and versatility of the SWIM algorithm. The main objective is to overcome the computational bottlenecks of traditional backpropagation through a non-iterative, data-driven sampling strategy [2]. The analysis is structured into two main phases:

1. **Multi-Fidelity Regression**: Application of SWIM to multi-fidelity problems, where the framework is used to approximate the benchmark Forrester function.
2. **Physics-Informed Modeling (SWIM-PDE)**: By incorporating physical constraints directly into the network architecture, SWIM-PDE [1] provides a fast alternative to traditional Physics-Informed Neural Networks (PINNs). Within this framework, the performance of SWIM-PDE is evaluated and compared to PINNs specifically for the reconstruction of heartbeat propagation via the Eikonal equation.

## References
* [1] C. Datar et al. "Solving partial differential equations with sampled neural networks", arXiv:2405.20836, 2024.
* [2] E. Bolager et al. "Sampling weights of deep neural networks", NeurIPS 2023; arXiv:2306.16830.

## License and Usage Policy

This repository adopts a dual-licensing approach to distinguish between the software components and the scientific documentation:

### 1. Software & Code (MIT License)
The source code and scripts in this repository are licensed under the **[MIT License](LICENSE)**. Since this implementation builds upon existing frameworks and external libraries, you are free to use, modify, and distribute the code, provided that the original license and copyright notice are included.

### 2. Scientific Report & Results (Non-Manipulable)
The project report (`SWIM_Scientific_Report.pdf`) and the visual results are protected. All rights are reserved to the authors: **Arianna Cagali, Mattia Gastoldi, and Roberto Gastoldi**.

* **Non-Manipulable**: You are **not allowed to modify, alter, or build upon** the report text or the visual results for further distribution.
* **Non-Commercial**: The use of the report, findings, or posters for profit is strictly prohibited.
* **Attribution**: You are free to download and share the report for personal or academic purposes, provided that appropriate credit is given to the original authors.

## Contact
For questions, clarifications, or further information about the project, feel free to contact me at **mattia.gastoldi@mail.polimi.it** or **roberto.gastoldi@mail.polimi.it**. Upon request, further details can be provided.
