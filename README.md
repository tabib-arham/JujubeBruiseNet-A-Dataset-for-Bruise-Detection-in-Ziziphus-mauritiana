
# JujubeBruiseNet Dataset

# Version: v1.0

* Last Updated: March 2025
* License: MIT License

# Overview

The **JujubeBruiseNet Dataset** is a high-resolution, expert-validated image dataset created for **bruise detection in Ziziphus mauritiana (jujube) fruits**. It provides two distinct classes: **Healthy** and **Bruised**, enabling research in agricultural automation, food quality control, and computer vision.

The dataset was captured under controlled conditions with expert validation to ensure accuracy and usability. With both original and augmented images, it is designed for training deep learning models such as CNNs, VGG16, and ResNet for bruise classification tasks.

# Metadata

| Attribute              | Description                                                                    |
| ---------------------- | ------------------------------------------------------------------------------ |
| **Dataset Name**       | JujubeBruiseNet                                                                |
| **Version**            | v1.0                                                                           |
| **Last Updated**       | March 2025                                                                     |
| **Fruit Included**     | Ziziphus mauritiana (Jujube)                                                   |
| **Categories**         | Healthy, Bruised                                                               |
| **Total Images**       | Original: 1,464 (732 per class) <br> Augmented: 5,856 <br> **Combined: 7,320** |
| **File Format**        | .jpg                                                                           |
| **Resolution**         | 512 × 512 pixels                                                               |
| **Color Mode**         | RGB                                                                            |
| **Capture Device**     | Samsung Galaxy Note 8, 12 MP, f/1.7 aperture, 2x optical zoom                  |
| **Capture Conditions** | Indoor setup, single 20W LED light, white A4 paper background                  |
| **Annotation**         | Manual, verified by agricultural domain experts                                |
| **Augmentation**       | Rotation (±30°), Flip, Brightness, Contrast, Gaussian Blur                     |
| **Preprocessing**      | Resizing to 512×512, noise reduction                                           |
| **Intended Use**       | Bruise detection, fruit quality assessment, post-harvest sorting               |

# Preprocessing and Augmentation

The dataset includes several augmentation techniques to improve model robustness:

1. **Horizontal Flip** – Random mirror flip.
2. **Brightness & Contrast Adjustment** – Random alpha scaling (0.7–1.3), beta shift (-50 to +50).
3. **Rotation** – Random angles within -30° to +30°.
4. **Gaussian Blur** – 5×5 kernel for smoothing.

Augmentations were applied using **Torchvision** and **PIL** in Python.

# Download Dataset

* Link: [JujubeBruiseNet – Mendeley Data](https://data.mendeley.com/datasets/3mtdhrwgfr/5)
* DOI: [10.17632/3mtdhrwgfr.5](https://doi.org/10.17632/3mtdhrwgfr.5)

# Citation

If you use this dataset, please cite:

**Md Arham Tabib, Sumyia Sabrin Liza, Md Mizanur Rahman (2025).**
*JujubeBruiseNet: A High-Resolution Image Dataset for Bruise Detection in Ziziphus mauritiana.*
Mendeley Data, V5, doi: 10.17632/3mtdhrwgfr.5

# Ethical Statement

The dataset was collected following ethical guidelines of **Daffodil International University (DIU)**. Jujube fruits were collected from local farmers and markets in Savar, Dhaka, with no harm caused to the environment. The dataset is strictly intended for **academic and research purposes**, not for commercial fruit handling or consumption decisions.

# Acknowledgement

We express our gratitude to the **Daffodil International University Ethical Committee** for granting approval to collect this dataset. Special thanks to local farmers and fruit sellers for their cooperation, and to domain experts for their assistance in dataset validation.

---

Would you like me to also create a **short “Usage Guide” section** (e.g., Python code snippet to load and preprocess the dataset) for the README so that other researchers can immediately apply it?
