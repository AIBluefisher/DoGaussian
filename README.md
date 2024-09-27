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

## 3. Train & Test

### Visualize scene splitting

Please check and compile [my modification of COLMAP](https://github.com/AIBluefisher/colmap). After installation, launch COLMAP's GUI. I extended the original model files of COLMAP with an additional `cluster.txt` file, where each line of the file follows the format: [image_id, cluster_id]. When COLMAP's GUI find this file, it will render each image with its color corresponds to its cluster ID. Below are some examples of scene splitting:

![sci-art_blocks_2x4_cameras](https://github.com/user-attachments/assets/218ff44e-0f9a-43ab-bb72-99421f5702a4)

![campus_blocks_2x4_cameras](https://github.com/user-attachments/assets/dea576c7-a480-4c12-886e-46113e08465b)


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
