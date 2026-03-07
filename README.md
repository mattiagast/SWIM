# SWIM: An Efficient Framework to Train Neural Networks
This project analyzes the **Sampling Where It Matters (SWIM)** framework [2], an innovative approach for training fully-connected neural networks that avoids iterative, gradient-based optimization by directly sampling weights from the available data.

## Abstract
The project explores the efficiency and versatility of the SWIM algorithm. The main objective is to overcome the computational bottlenecks of traditional backpropagation through a non-iterative, data-driven sampling strategy [2]. The analysis is structured into two main phases:

1. **Multi-Fidelity Regression**: Application of SWIM to multi-fidelity problems, where the framework is used to approximate the benchmark Forrester function.
2. **Physics-Informed Modeling (SWIM-PDE)**: By incorporating physical constraints directly into the network architecture, SWIM-PDE [1] provides a fast alternative to traditional Physics-Informed Neural Networks (PINNs). Within this framework, the performance of SWIM-PDE is evaluated and compared to PINNs specifically for the reconstruction of heartbeat propagation via the Eikonal equation.

## References
* [1] C. Datar et al. "Solving partial differential equations with sampled neural networks", arXiv:2405.20836, 2024.
* [2] E. Bolager et al. "Sampling weights of deep neural networks", NeurIPS 2023; arXiv:2306.16830.

## License
The scientific report included in this repository is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)**. You are free to share and redistribute the material in any medium or format, provided that appropriate credit is given.

## Contact
For questions, clarifications, or further information about the project, feel free to contact me at **mattia.gastoldi@mail.polimi.it** or **roberto.gastoldi@mail.polimi.it**. Upon request, further details can be provided.
