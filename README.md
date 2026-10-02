# DeepXTE: An Efficient Transformer-Xception Framework for Hyperspectral Image Classification
If you use the code or any part of this implementation in your research, we kindly request that you cite the following paper:

Janardan, S.K., Janghel, R.R. & Govil, H. Enhancing hyperspectral image classification: DeepXTE for efficient semantic feature extraction. Machine Vision and Applications 37, 39 (2026). https://doi.org/10.1007/s00138-026-01796-y

```
@article{janardan2026enhancing,
title={Enhancing hyperspectral image classification: DeepXTE for efficient semantic feature extraction:
Spectral spatial feature fusion via Xception augmented transformer encoder},
author={Janardan, Sushil Kumar and Janghel, Rekh Ram and Govil, Himanshu},
journal={Machine Vision and Applications},
volume={37},
number={2},
pages={39},
year={2026},
publisher={Springer}
}
```

# About DeepXTE
Hyperspectral image (HSI) classification is crucial for accurately identifying land-cover categories at the pixel level. Although convolutional neural networks (CNNs) have enhanced classification performance, deeper architectures often face computational overhead and challenges in capturing intricate semantic representations. To address these issues, we propose DeepXTE, an efficient and high-performing classification framework that integrates an enhanced Transformer architecture with the depthwise separable convolutional capabilities of an enhanced Xception module. DeepXTE employs a dual-branch design using 2D and 3D convolutions to extract rich spectral-spatial information. The Xception module refines these features before passing them to the Transformer encoder, enhancing the model’s ability to learn meaningful representations.
