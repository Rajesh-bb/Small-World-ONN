# Project Supervision
This project was conducted under the guidance of Prof. Rajesh M. Hegde at IIT Kanpur.
----
### Project Verification  
[Click here to view the Project Verification File (PVF)](https://github.com/kaushalmehra23/Small-World-Inspired-Optical-Neural-Network/blob/eb0c6607380ef28cd5033820758625adb0a798f5/Small-World-Inspired%20Optical%20Neural%20Network_PVF.pdf)
# Small-World-Inspired-Optical-Neural-Network
This repository contains some of the code we used to train our optical neural network models. The models are inspired by small-world connectivity and simulate light propagation using techniques like the Angular Spectrum Method.
Files with the prefix "BEST" are models that achieved the highest accuracy in our experiments.
-----
# Model Overview
Designed a grayscale ONN based on a Multi-Lens Array (MLA) with small-world inter-layer
connections to capture local and global spatial features; a cross-layer connections based multi-lane
small-world model was also developed
Implemented saturable absorber to introduce non-linearity, significantly enhancing model
optimization and learning capability
Extended the model for RGB inputs by constructing three parallel small-world ONN subnetworks
for the R, G, and B channels, each independently capturing color-specific features and merging them
through a final feature-fusion stage
An ensemble of small-world ONN variants was also constructed to enhance robustness and
generalization performance.
---
# Result
Achieved 98% on MNIST, 82.78% on EMNIST, and 87.88% on Fashion-MNIST; for CIFAR-10, reached
55.87%
Performance gains stem from integration of MLA, saturable absorber, and small-world
connectivity, enabling efficient and compact ONN design
----
