# Project Title

Experiments for European Study Group with Industry (ESGI 187).

---

## About
The proejct is to detect whether a generative diffusion model has been fine-tuned to produce unsafe material, without generating unsafe material using said model. Our proposed approach is to implement a classifier on diffusion trajectories.

Using CIFAR-10 dataset of cats and dogs to train SVM and CNN classifiers, we test the robustness of these classifiers on noisy images along the diffusion trajectories.
