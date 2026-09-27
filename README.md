# DBM-VLM / DBM-65k

**DBM-65k** is a large-scale, multi-scale benchmark for data-centric bridge damage identification. This repository provides the public project entry point for the benchmark, including dataset links, pretrained-weight links, task configuration files, and the BridgeVLM project description.

The accompanying preprint is:

> **DBM-65k: A large-scale multi-scale dataset and benchmark for data-centric bridge damage identification**  
> DOI: [10.31224/7511](https://doi.org/10.31224/7511)

## Overview

DBM-65k is designed to support reproducible research on bridge damage detection and segmentation across multiple scales and bridge components. The benchmark contains more than 65,000 images and provides task-specific resources for detection and segmentation experiments.

This repository is actively maintained. Public datasets and pretrained weights are hosted on Kaggle because of their size, while task configuration files are versioned here on GitHub.

## Public Resources

| Resource | Purpose | Link |
| --- | --- | --- |
| DBM-Con | Detection task subset | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/dbm-con) |
| DBM-Stl | Detection task subset | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/dbm-stl) |
| DBM-Comp | Detection task subset | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/dbm-comp) |
| DBM-Conseg | Segmentation task subset | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/dbm-conseg) |
| DBM-Stlseg | Segmentation task subset | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/dbm-stlseg) |
| data_DBM | Consolidated detection resources | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/data-dbm) |
| data_DBMseg | Consolidated segmentation resources | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/data-dbmseg) |
| BridgeVLM | Vision-language resources | [Kaggle](https://www.kaggle.com/datasets/zjw1176380908/bridgevlm) |

## Repository Structure

```text
DBM-VLM/
├── README.md
├── VLM/
│   └── README.md
└── yaml/
    ├── DBM-Comp.yaml
    ├── DBM-Con.yaml
    ├── DBM-Conseg.yaml
    ├── DBM-Stl.yaml
    └── DBM-Stlseg.yaml

yaml/ contains task configuration files used by the public benchmark resources.
VLM/ contains the current BridgeVLM project description and resource entry point.
Large datasets and model weights are hosted externally on Kaggle.

Getting Started
1. Clone the repository
git clone https://github.com/BridgeVLM-Lab/DBM-VLM.git
cd DBM-VLM
2. Download the required dataset and pretrained weights
Choose the relevant task from the table above and download its resources from Kaggle.
3. Use the corresponding configuration file
For example:
yaml/DBM-Con.yaml
yaml/DBM-Comp.yaml
yaml/DBM-Conseg.yaml
4. Ultralytics-compatible workflows
The released resources are intended to support Ultralytics-style detection and segmentation workflows. Where a downloaded checkpoint is directly compatible with the installed Ultralytics version, a standard inference workflow can be used, for example:
pip install ultralytics
yolo predict model=/path/to/model.pt source=/path/to/images
Please use the configuration and checkpoint versions provided with each resource package when reproducing benchmark results.
BridgeVLM
BridgeVLM extends the project toward vision-language reasoning for bridge inspection, including defect-component semantic association, semi-supervised learning, standard-constrained report generation, and multimodal reasoning.
See [README.md](VLM/README.md) for the current project description and resource link.
Reproducibility and Maintenance
Our current maintenance priorities are:
- keeping public dataset, weight, and configuration links accessible;
- improving benchmark documentation and reproducibility;
- expanding training, evaluation, and inference instructions;
- reviewing external bug reports and contributions;
- improving automation for configuration validation, testing, and releases.
If you find a broken resource, configuration issue, or reproducibility problem, please open a GitHub issue with the task name, environment details, and reproduction steps.
Citation
If DBM-65k is useful in your research, please cite the accompanying preprint:
@article{zheng2026dbm65k,
  title   = {DBM-65k: A large-scale multi-scale dataset and benchmark for data-centric bridge damage identification},
  author  = {Zheng, Junwen and Feng, Hao and Zhang, Jinghuan and Zhang, Jian},
  year    = {2026},
  doi     = {10.31224/7511}
}
