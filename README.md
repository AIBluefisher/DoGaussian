# <img src="./assets/imgs/dog_icon.png" style="width:50px;height:auto"> DoGaussian

<b>DoGaussian</b>: Distributed-Oriented Gaussian Splatting for Large-Scale 3D Reconstruction Via Gaussian Consensus 

[[Project Page](https://aibluefisher.github.io/DoGaussian) | [arXiv](https://arxiv.org/abs/2405.13943)] (**NeurIPS 2024**)

## 1. Introduction

Our method accelerates the training of 3DGS by 6+ times when evaluated on large-scale scenes while concurrently achieving state-of-the-art rendering quality.

<img src="./assets/imgs/dogaussian_pcl.gif" style="width:480px;height:auto" />
<img src="./assets/imgs/dogaussian.gif" style="width:480px;height:auto" />

## 2. TODO & Roadmap

- [ ] Release evaluation code
- [ ] Release pre-trained models on `Mill19`, `UrbanScene3D`, and `MatrixCity`
- [ ] Release web-viewer.
- [ ] Release training code
- [ ] Test on street-view scenes
- [ ] Support distributed training of `Scaffold-GS` and `Octree-GS`

## Cite

If you find this project useful for your research, please consider citing our paper:
```bibtex
@inproceedings{yuchen2024dogaussian,
    title={DoGaussian: Distributed-Oriented Gaussian Splatting for Large-Scale 3D Reconstruction Via Gaussian Consensus},
    author={Yu Chen, Gim Hee Lee},
    booktitle={arXiv},
    year={2024},
}
```
