### 📦 数据集、模型权重与配置文件下载

DBM-65k 数据集、预训练模型权重及相关配置文件统一托管于 **Kaggle 平台**。所有资源均公开提供，以支持模型复现、基准测试及后续研究。您可以通过以下链接下载对应任务的完整资源：

* **[DBM-Con](https://www.kaggle.com/datasets/zjw1176380908/dbm-con)**
* **[DBM-Stl](https://www.kaggle.com/datasets/zjw1176380908/dbm-stl)**
* **[DBM-Comp](https://www.kaggle.com/datasets/zjw1176380908/dbm-comp)**
* **[DBM-Conseg](https://www.kaggle.com/datasets/zjw1176380908/dbm-conseg)**
* **[DBM-Stlseg](https://www.kaggle.com/datasets/zjw1176380908/dbm-stlseg)**
* **[data_DBMseg](https://www.kaggle.com/datasets/zjw1176380908/data-dbmseg)**
* **[data_DBM](https://www.kaggle.com/datasets/zjw1176380908/data-dbm)**

💡 **兼容 Ultralytics 平台**

本项目提供的代码、配置文件和模型权重与 **Ultralytics** 平台兼容。用户可以使用标准 YOLO 推理流程直接加载预训练权重，在真实桥梁巡检图像上开展病害检测与分割测试。

此外，所提供的预训练权重可作为后续迁移学习和微调的初始化模型，并可结合对应配置文件用于自定义数据集训练，以提高训练效率并促进模型复现与扩展。

### 📦 Datasets, Model Weights, and Configuration Files

The DBM-65k datasets, pretrained model weights, and corresponding configuration files are publicly hosted on the **Kaggle platform**. These resources are provided to support reproducibility, benchmarking, and further research. The complete resources for each task can be accessed through the following links:

* **[DBM-Con](https://www.kaggle.com/datasets/zjw1176380908/dbm-con)**
* **[DBM-Stl](https://www.kaggle.com/datasets/zjw1176380908/dbm-stl)**
* **[DBM-Comp](https://www.kaggle.com/datasets/zjw1176380908/dbm-comp)**
* **[DBM-Conseg](https://www.kaggle.com/datasets/zjw1176380908/dbm-conseg)**
* **[DBM-Stlseg](https://www.kaggle.com/datasets/zjw1176380908/dbm-stlseg)**
* **[data_DBMseg](https://www.kaggle.com/datasets/zjw1176380908/data-dbmseg)**
* **[data_DBM](https://www.kaggle.com/datasets/zjw1176380908/data-dbm)**

💡 **Compatibility with Ultralytics**

The provided code, configuration files, and pretrained model weights are compatible with the **Ultralytics** framework. Users can directly load the pretrained weights using the standard YOLO inference pipeline for bridge damage detection and segmentation in real-world inspection images.

The pretrained weights can also serve as initialization models for transfer learning and fine-tuning on custom datasets. Together with the provided configuration files, they facilitate reproducible training, efficient model adaptation, and further extension of the DBM framework.

DBM-Con, DBM-Stl, DBM-Comp, DBM-Conseg, and DBM-Stlseg correspond to the five task subsets described in the paper, while data_DBM and data_DBMseg provide the consolidated resources used for detection and segmentation experiments, respectively.
