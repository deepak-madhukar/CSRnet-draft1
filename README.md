# Crowd Monitoring

This is the repo for devloping a pytho  software to cout or estimate the density of crowd in a image.

## Datasets
ShanghaiTech Dataset: [Google Drive](https://drive.google.com/open?id=16dhJn7k4FWVwByRsQAEpl9lwjuV03jVI)

## Prerequisites
You can either run this codebase on your loacal machine if you have atleast 8gb video memory or you can use any online gpu providing services.

### for Local machine setup you  ust have
Python:3.7 or later
PyTorch: 0.4.0
CUDA: 9.2

### For online GPU providing services
All needed sofware will be already available on remote machine.

Just Run all the codeblocks in Part A and Part B python notebook

## Results
Shanghai A MAE: 39.2
-
Shanghai B MAE: 8.32

## References

This repo is based on following research paper

```
@inproceedings{li2018csrnet,
  title={CSRNet: Dilated convolutional neural networks for understanding the highly congested scenes},
  author={Li, Yuhong and Zhang, Xiaofan and Chen, Deming},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={1091--1100},
  year={2018}
}

