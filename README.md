# Awesome Data Drift: A Curated List of Research Papers and Resources

Welcome to **Awesome Data Drift**! This repository is a curated collection of research papers, articles, and open-source tools focused on the detection, understanding, and mitigation of data drift in machine learning systems.

Data drift, also known as concept drift, occurs when the statistical properties of the target variable or the input features change over time, causing the model's performance to degrade. This list aims to provide a comprehensive overview of the cutting-edge research in this critical area of MLOps and trustworthy AI.

## Contents

- [Surveys & Reviews](https://github.com/PGSmall/data-drift#surveys-and-reviews)
- [Data Drift in Federated Learning](https://github.com/PGSmall/data-drift#data-drift-in-federated-learning)
- [Data Drift in Continual Learning](https://github.com/PGSmall/data-drift#data-drift-in-continual-learning)
- [System-Level Solutions (MLOps & Edge AI)](https://github.com/PGSmall/data-drift#system-level-solutions-mlops--edge-ai)
- [Unsupervised & Interpretable Detection](https://github.com/PGSmall/data-drift#unsupervised--interpretable-detection)
- [Data Drift & Fairness](https://github.com/PGSmall/data-drift#data-drift--fairness)
- [Toolkits & Libraries](https://github.com/PGSmall/data-drift#toolkits--libraries)

-----

### Surveys and Reviews

| Title | Publication | Paper |
| :--- | :--- | :--- |
| Learning under Concept Drift: A Review | TKDE 2019 | [Link](https://arxiv.org/abs/2004.05785) |

### Data Drift in Federated Learning

| Title | Publication | Paper | Code |
| :--- | :--- | :--- | :--- |
| Towards Unsupervised Sudden Data Drift Detection in Federated Learning with Fuzzy Clustering | FUZZ-IEEE 2024 | [Link](https://ieeexplore.ieee.org/document/10611883) | [Link](https://github.com/stallmo/fed_data_drift_detection) |
| Federated Learning under Distributed Concept Drift | AISTATS 2023 | [PMLR Link](https://proceedings.mlr.press/v206/jothimurugesan23a/jothimurugesan23a.pdf) | [Link](https://github.com/microsoft/FedDrift) |
| FedDC: Federated Learning With Non-IID Data via Local Drift Decoupling | CVPR 2022 | [Link](https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_FedDC_Federated_Learning_With_Non-IID_Data_via_Local_Drift_Decoupling_CVPR_2022_paper.pdf) | N/A |

### Data Drift in Continual Learning

| Title | Publication | Paper | Code |
| :--- | :--- | :--- | :--- |
| Mind the Gap: Preserving and Compensating for the Modality Gap in CLIP-Based Continual Learning | ICCV 2025 | [Link](https://arxiv.org/abs/2507.09118) | [Link](https://github.com/linlany/MindtheGap) |
| LoRA Subtraction for Drift-Resistant Space in Exemplar-Free Continual Learning | CVPR 2025 | [Link](https://arxiv.org/abs/2503.18985) | [Link](https://github.com/scarlet0703/LoRA-Sub-DRS) |
| Distribution-Aware Knowledge Aligning and Prototyping for Non-Exemplar Lifelong Person Re-Identification | TPAMI 2025 | [Link](https://ieeexplore.ieee.org/document/11120364) | N/A |
| Unsupervised Continual Domain Shift Learning with Multi-Prototype Modeling | CVPR 2025 | [Link](https://openaccess.thecvf.com/content/CVPR2025/papers/Sun_Unsupervised_Continual_Domain_Shift_Learning_with_Multi-Prototype_Modeling_CVPR_2025_paper.pdf) | N/A |
| Semantic Drift Compensation for Class-Incremental Learning | CVPR 2020 | [Link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yu_Semantic_Drift_Compensation_for_Class-Incremental_Learning_CVPR_2020_paper.pdf) | [Link](https://github.com/yulu0724/SDC-IL) |

### System-Level Solutions (MLOps & Edge AI)

| Title | Publication | Paper | Code |
| :--- | :--- | :--- | :--- |
| Automated Data Quality Validation in an End-to-End GNN Framework | EDBT 2025 | [Link](https://arxiv.org/abs/2502.10667) | [Link](https://github.com/SiSijie/DQuaG) |
| Efficiently Mitigating the Impact of Data Drift on Machine Learning Pipelines | PVLDB 2024 | [Link](https://www.vldb.org/pvldb/vol17/p3072-dong.pdf) | [Link](https://github.com/SiSijie/data-drift-in-ML) |
| Data drift detection and mitigation A comprehensive MLOps approach for real-time systems | IJSRA 2024 | [Link](https://ijsra.net/sites/default/files/IJSRA-2024-0724.pdf) | N/A |
| A Lightweight Concept Drift Detection Method for On-Device Learning on Resource-Limited Edge Devices | IPDPSW 2023 | [Link](https://ieeexplore.ieee.org/document/10196602) | N/A |

### Unsupervised & Interpretable Detection

| Title | Publication | Paper | Code |
| :--- | :--- | :--- | :--- |
| DriftGAN: Using historical data for Unsupervised Recurring Drift Detection | ACM SAC 2024 | [Link](https://www.arxiv.org/abs/2407.06543) | [Link](https://github.com/cfellicious/DriftGAN) |
| DEDRIFT: Robust Similarity Search under Content Drift | ICCV 2023 | [Link](https://openaccess.thecvf.com/content/ICCV2023/papers/Baranchuk_DEDRIFT_Robust_Similarity_Search_under_Content_Drift_ICCV_2023_paper.pdf) | N/A |
| Interpretable Model Drift Detection | CODS-COMAD 2024 | [Link](https://arxiv.org/abs/2503.06606) | N/A |

### Data Drift & Fairness

| Title | Publication | Paper | Code |
| :--- | :--- | :--- | :--- |
| FALCON: Fairness Learning via Contrastive Attention Approach to Continual Semantic | CVPR 2025 | [Link](https://arxiv.org/abs/2311.15965) | [Link](https://github.com/uark-cviu/FALCON/) |

### Toolkits & Libraries

| Toolkit | Description |
| :--- | :--- |
| [Evidently AI](https://github.com/evidentlyai/evidently) | Evidently is ​​an open-source ML and LLM observability framework. Evaluate, test, and monitor any AI-powered system or data pipeline. From tabular data to Gen AI. 100+ metrics. |
| [Deepchecks](https://github.com/deepchecks/deepchecks) | Deepchecks: Tests for Continuous Validation of ML Models & Data. Deepchecks is a holistic open-source solution for all of your AI & ML validation needs, enabling to thoroughly test your data and models from research to production. |
| [Alibi Detect](https://github.com/SeldonIO/alibi-detect) | Alibi Detect is a source-available Python library focused on outlier, adversarial and drift detection. The package aims to cover both online and offline detectors for tabular data, text, images and time series. Both TensorFlow and PyTorch backends are supported for drift detection. |
| [NannyML](https://github.com/NannyML/nannyml) | NannyML is an open-source python library that allows you to estimate post-deployment model performance (without access to targets), detect data drift, and intelligently link data drift alerts back to changes in model performance. Built for data scientists, NannyML has an easy-to-use interface, interactive visualizations, is completely model-agnostic and currently supports all tabular use cases, classification and regression. |
| [Frouros](https://github.com/IFCA-Advanced-Computing/frouros) | Frouros is a Python library for drift detection in machine learning systems that provides a combination of classical and more recent algorithms for both concept and data drift detection. |
| [Cleanlab](https://github.com/cleanlab/cleanlab) | Cleanlab’s open-source library helps you clean data and labels by automatically detecting issues in a ML dataset. To facilitate machine learning with messy, real-world data, this data-centric AI package uses your existing models to estimate dataset problems that can be fixed to train even better models. |
| [Spotlight](https://github.com/Renumics/spotlight) | Spotlight helps you to understand unstructured datasets fast. You can quickly create interactive visualizations and leverage data enrichments (e.g. embeddings, prediction, uncertainties) to identify critical clusters in your data. |

## Contributing

Contributions are welcome! If you have a paper, article, or tool to add, please feel free to open a pull request. Please try to follow the existing format.

## License

This repository is licensed under the [MIT License](LICENSE).
