Weld Defect Detection Datasets
📌 Dataset Overview

This repository provides two weld radiographic film digital image datasets collected from real industrial radiographic inspection scenarios.
The datasets are designed for weld defect detection, classification, and analysis, and contain a variety of typical welding defects encountered in practical nondestructive testing (NDT) applications.

Both datasets consist of digital X-ray radiographic images of weld seams, characterized by noise contamination, low contrast, complex background structures, blurred defect boundaries, and subtle defect patterns, which pose significant challenges to automatic inspection systems.
These characteristics make the datasets suitable for evaluating both traditional image processing techniques and machine learning / deep learning–based methods.

🔍 Defect Types

The datasets cover common weld defects observable in radiographic films, including but not limited to:

Incomplete penetration

Porosity

Slag inclusion

Incomplete fusion

Cracks

Other typical weld anomalies

⚠️ Note:
The occurrence frequency of different defect types is inherently unbalanced, and the exact defect categories, labeling conventions, and annotation formats (if applicable) should be interpreted according to the specific experimental setup adopted by the researcher.

📁 Dataset Description
Dataset 1: Weld Radiographic Defect Image Dataset

This dataset contains one group of weld seam radiographic digital images collected from industrial inspection scenarios.
The images exhibit diverse defect morphologies, including circular pores, elongated slag inclusions, linear lack-of-fusion indications, continuous dark penetration lines, and sharp-contoured crack features.

From visual inspection, the defect appearances vary significantly in shape, size, contrast, and continuity. Some defects present clear contours, while others are weakly contrasted or partially obscured by background noise, making them difficult to distinguish even by the naked eye.
The dataset reflects realistic inspection challenges such as blurred edges, small-scale defects, low-contrast unfused regions, and complex texture interference, which cannot be fully addressed by conventional image processing or standard machine learning methods alone.

This dataset is suitable for:

Weld defect detection and classification

Defect morphology analysis

Traditional image processing–based feature extraction

Deep learning model training and evaluation

Download link:
https://pan.baidu.com/s/1gZBmIyyV1NCvUP2NUUxMgQ?pwd=gyxi

Dataset 2: Cross-Condition Weld Radiographic Image Dataset

This dataset serves as a cross-dataset benchmark, consisting of weld radiographic images collected under different imaging conditions or weld configurations.

The dataset is designed to evaluate model robustness and generalization capability and includes images with rare, small-scale, subtle, or weakly visible defects, which are particularly challenging for automated detection systems.
Compared with Dataset 1, the defects in this dataset tend to exhibit lower contrast, less prominent boundaries, and stronger background interference, closely resembling real-world inspection scenarios.

The dataset can be effectively used for:

Cross-dataset validation

Robustness and generalization testing

Comparative experiments under varying inspection conditions

Practical performance evaluation in realistic NDT scenarios

Download link:
https://pan.baidu.com/s/1mf3gkusHvUvokVvlW_tKuA?pwd=2dut

🎯 Recommended Use Cases

Weld defect detection and segmentation

Defect feature extraction and enhancement

Deep learning model training and evaluation

Cross-dataset and robustness analysis

Industrial nondestructive testing (NDT) research

📜 License & Usage

The datasets are provided for academic research and non-commercial use only.
If you use these datasets in your research, publications, or projects, please cite this repository appropriately.
