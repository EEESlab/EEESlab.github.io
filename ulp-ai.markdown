---
layout: default
title: Artificial Intelligence and Deep Neural Networks on ultra-low-power devices
permalink: /ulp-ai/
---

# Artificial Intelligence and Deep Neural Networks on ultra-low-power devices

Interest in applications of Artificial Intelligence (AI) has been growing exponentially in the last 5 years, particularly thanks to the rise of Deep Learning and Deep Neural Networks (DNNs).
AI and, in particular, DNNs are extremely effective at ``understanding'' information, but they typically require advanced compute capabilities guaranteed by powerful GPUs consuming hundreds of Watts of power.
At the EEES lab, one of the main research interests is bringing Deep Learning and DNNs on devices that consume 1000x less power than GPUs; an extremely challenging task that requires a combined an effort on the algorithm, software and hardware architecture level. Exciting applications of our work include tiny smart UAVs, wearable biomedical aids, and high efficiency sensors to improve the safety of buildings and industrial plants.

- **Fast Quantization Exploration for Deep Neural Networks**
One of the key techniques to squeeze Deep Neural Networks for ultra-low-power devices is *quantization*, i.e. computing with integer numbers with a low number of bits in place of 32-bit floating-points.
Understanding how many bits can be dedicated to each part of the DNN computation is not easy, and several techniques have been explored.
In this project, we aim at extending a in-house tool for DNN quantization, called NEMO, to determine which configurations of a neural network are more promising for quantization.

- **Optimal DNN Code Generation**
Execution of DNNs on ultra-low-power devices typically relies on libraries deeply optimized to achieve the best performance given a set of "hard" constraints. However, these libraries typically target a fixed data-flow, not the "best one" perfectly matching the current application. In this project, we aim at using a high-level model to extract the "best" data-flow for a given network and use it to generate the DNN source code.

- **You Only Look Once: Real-Time Object Detection on PULP**
Tiny DNN-based object detection algorithms such as YOLO-Nano ([https://arxiv.org/pdf/1910.01271.pdf]) have been proposed recently. This project aims at using tools developed within the EEES Lab to train a YOLO-Nano object detection network and run it on a GreenWaves Technologies GAPuino board, a commercial embodiment of the PULP Platform.

- **Hardware-Accelerated Deep NNs on PULP**
Several hardware accelerators for Deep NNs have been designed for the PULP platform. This project aims at integrating them with the current DNN design flows, making it possible to mix software-based execution (e.g. using PULP-NN [https://github.com/pulp-platform/pulp-nn]) with hardware-based acceleration.

- **Deep Learning Based Visual-Inertial Odometry in ULP Drones**
Visual-Inertial Odometry (VIO) is a key technique enabling small robots to acquire "awareness" of their position and orientation in an environment based only on information from cameras and accelerometers -- just like we do with our eyes and inner ears. Deep Neural Networks are emerging as one of the choice techniques to fuse visual and accelerometric data and perform VIO. In this project, we aim at reproducing this capability on top of an ultra-low-power nano-drone platform.

