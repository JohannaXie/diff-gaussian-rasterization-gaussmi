# Differential Gaussian Rasterization with GauSS-MI

This software is used as the rasterization engine for the paper ["GauSS-MI: Gaussian Splatting Shannon Mutual Information for Active 3D Reconstruction"](https://www.roboticsproceedings.org/rss21/p030.pdf), including:

* Computes the log odds of inverse sensor model for each Gaussians from image loss. (Eq. 10)
* Computes GauSS-MI from information gain function. (Eq. 20)

The code is built based on the [Differential Gaussian Rasterization with Camera Pose Jacobians](https://github.com/rmurai0610/diff-gaussian-rasterization-w-pose) in "Gaussian Splatting SLAM" and [Differential Gaussian Rasterization](https://github.com/graphdeco-inria/diff-gaussian-rasterization) in "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields".

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
