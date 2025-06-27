# Differential Gaussian Rasterization with GauSS-MI

This software is used as the rasterization engine for the paper ["GauSS-MI: Gaussian Splatting Shannon Mutual Information for Active 3D Reconstruction"](https://www.roboticsproceedings.org/rss21/p030.pdf), including:

* Computes the log odds of inverse sensor model for each Gaussian from image loss. (Equation 10 in paper)
* Computes GauSS-MI from the information gain function. (Equation 20 in paper)

The code is built based on the [Differential Gaussian Rasterization with Camera Pose Jacobians](https://github.com/rmurai0610/diff-gaussian-rasterization-w-pose) in "Gaussian Splatting SLAM" and [Differential Gaussian Rasterization](https://github.com/graphdeco-inria/diff-gaussian-rasterization) in "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields".

## Installation
#### Requirements
* Conda (recommended for easy setup)
* CUDA Toolkit 11.8
#### Clone the Repository
```bash
git clone https://github.com/JohannaXie/diff-gaussian-rasterization-gaussmi.git
cd diff-gaussian-rasterization-gaussmi
```
#### Install
```bash
conda activate GauSS-MI   # or your conda environment
pip install .
```

## Citation
If you find our code/work useful, please consider citing:
```
@article{xie2025gaussmi,
  title     = {GauSS-MI: Gaussian Splatting Shannon Mutual Information for Active 3D Reconstruction},
  author    = {Yuhan Xie, Yixi Cai, Yinqiang Zhang, Lei Yang, and Jia Pan},
  journal   = {arXiv preprint arXiv:2503.02881},
  year      = {2025}
}
```
