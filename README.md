# 🧬 SGAT-TM

**Stacked Graph Attention Network with Temporal Modeling for lncRNA-miRNA Association Network**

## 📌 Overview

SGAT-TM is a graph-based deep learning approach for modeling **lncRNA-miRNA associations** from biological feature data. The architecture combines attention-based graph representation learning with temporal modeling to learn useful representations for association prediction.

## 🎯 Objectives

- Learn representations of lncRNA and miRNA features.
- Model relationships using graph attention mechanisms.
- Capture temporal information with GRU-based modeling.
- Train and evaluate the SGAT-TM architecture for association prediction.

## 🧠 Model Workflow

```text
Biological Features
        ↓
Data Loading & Preprocessing
        ↓
Feature Representation
        ↓
Self / Graph Attention
        ↓
Temporal Modeling (GRU)
        ↓
MLP / Prediction Module
        ↓
Association Prediction
```

## 🛠️ Tech Stack

- Python
- PyTorch
- PyTorch Geometric
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## 📂 Repository Structure

```text
SGAT-TM/
├── data/
│   ├── lncRNA_feature.pkl
│   ├── miRNA_feature.pkl
│   ├── lncRNA_idx.csv
│   ├── miRNA_idx.csv
│   └── splits.pkl
│
├── code/
│   ├── main.py       # Training and evaluation entry point
│   ├── model.py      # SGAT-TM model architecture
│   ├── layer.py      # Custom model layers
│   ├── dataset.py    # Data loading and preparation
│   └── funcs.py      # Metrics and utility functions
│
├── requirements.txt
└── README.md
```

## ⚙️ Installation

```bash
git clone https://github.com/Deep-k-coder/SGAT-TM.git
cd SGAT-TM
pip install -r requirements.txt
```

> Some PyTorch Geometric dependencies can be environment/CUDA-version specific. Follow the versions in `requirements.txt` for the intended environment.

## ▶️ Training

```bash
python3 code/main.py --epoch XXXX --lr XXXX
```

Replace `XXXX` with the desired experiment values.

## 📊 Evaluation

The project includes utility functions for calculating evaluation metrics and optional visualizations. Add experiment-specific results and plots when publishing reproducible experiments.

## 📚 Publication

Shivani Saxena, Ahsan Z. Rizvi, **"Stacked graph attention network with temporal modeling for lncRNA-miRNA association network,"** *IEEE/ACM Transactions on Computational Biology and Bioinformatics*, 2025.

DOI: `10.1109/TCBBIO.2025.3587877`

## 🔬 Research Area

```text
Artificial Intelligence
        ↓
Deep Learning
        ↓
Graph Neural Networks
        ↓
Graph Attention Networks
        ↓
Computational Biology
        ↓
lncRNA-miRNA Association Prediction
```

## 👨‍💻 Repository

Maintained by **Deep Koshiya** as part of an AI/ML and computational-biology project workflow.

GitHub: https://github.com/Deep-k-coder

## 📄 License

Please refer to the original project/publication terms and dataset licensing before redistributing research data or code.
