# The Single-Photon Real Dataset

## Overview

We present the Single-Photon Real Dataset, a comprehensive dataset containing 11 object categories designed for single-photon imaging research. Each category includes 400 npz files, providing rich depth information for computer vision applications. The dataset features diverse real-world scenarios with variations in lighting conditions, object scales, and viewpoints. Every npz file contains two key-value pairs:

`depth_ssp`: Single-photon estimated depth maps derived from time-of-flight measurements

`Z_true`: Ground-truth real depth maps with sub-millimeter precision

@misc{zhang2025labelefficient,
    title={Label-efficient Single Photon Images Classification via Active Learning},
    author={Zili Zhang and Ziting Wen and Yiheng Qiang and Hongzhou Dong and Wenle Dong and Xinyang Li and Xiaofan Wang and Xiaoqiang Ren},
    year={2025},
    eprint={2505.04376},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}

## Direct HTTP Download(Github)
[**Download Dataset**](https://github.com/shuinb/Singlephoton_realworld_dataset/blob/master/realworld.zip) (38.2 MB, contains all .npz files)


## Category List

The dataset includes the following 11 object categories, covering common urban and natural scene elements:

Building

Bike

Bin

Roadblock

Human

Ship

Firehydrant

Apple

Banana

Cap

Waterbottle

Each category contains 400 high-quality npz files with consistent naming conventions (e.g., `building_0001.npz`, `bike_0350.npz`) for easy data management.

## Dataset Statistics



| Attribute                | Value                          |
| ------------------------ | ------------------------------ |
| Number of Categories     | 11                             |
| Files per Category       | 400 npz files                  |
| Total Files              | 4,400 npz files                |
| File Format              | NPZ (compressed numpy archive) |
| Key-value Pairs          | `depth_ssp` (estimated depth)  |
|                          | `Z_true` (ground-truth depth)  |
| Depth Map Resolution     | 55x55 pixels (grayscale)     |


The dataset maintains a balanced distribution across all categories, with approximately equal representation of small (e.g., apple, banana), medium (e.g., bike, cap), and large (e.g., building, ship) objects.

## License

The Single-Photon Real Dataset is released under a **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)**. This allows use, sharing, adaptation, and distribution for both commercial and research purposes, provided that:

Appropriate credit is given to the original dataset authors.

Any modified versions are distributed under the same license.

Copyright for the raw sensor data remains with the contributing institutions. Users are responsible for adhering to privacy and ethical guidelines when using human-related data (Category 5: Human).
