# 🧬 SGAT-TM

> **Stacked Graph Attention Network with Temporal Modeling for lncRNA-miRNA Association Network**

A graph-based deep-learning project for modeling **lncRNA-miRNA associations** using graph attention and temporal representation learning.

## 📌 Overview

SGAT-TM combines graph-based representation learning with temporal modeling to learn useful representations of biological entities and support association prediction.

The repository contains the project code, data layout, dependency configuration, and documentation needed to understand the research workflow.

## 🧠 Architecture

```text
Biological Feature Data
          ↓
Data Loading & Preprocessing
          ↓
Feature Representation
          ↓
Graph / Self Attention
          ↓
Temporal Modeling (GRU)
          ↓
Prediction Module
          ↓
lncRNA-miRNA Association Prediction
```

### Core Components

| Component | Role |
|---|---|
| Feature representation | Encodes biological feature information |
| Graph attention | Learns relationship-aware representations |
| GRU temporal modeling | Models sequential / temporal information |
| Prediction module | Produces association predictions |

## 🎯 Objectives

- Learn meaningful representations for lncRNA and miRNA features.
- Model biological relationships using attention-based graph learning.
- Capture temporal information using GRU-based modeling.
- Provide a reproducible workflow for association prediction experiments.

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
│   ├── main.py       # Training / evaluation entry point
│   ├── model.py      # Model architecture
│   ├── layer.py      # Custom layers
│   ├── dataset.py    # Dataset preparation
│   └── funcs.py      # Metrics / utilities
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

PyTorch Geometric installations can depend on the local Python/PyTorch/CUDA environment. Use the versions specified by the repository configuration where applicable.

## ▶️ Running the Project

The repository's training entry point is `code/main.py`.

```bash
python3 code/main.py --epoch YOUR_EPOCHS --lr YOUR_LEARNING_RATE
```

Replace the placeholders with the experiment configuration you want to run.

## 📊 Evaluation & Results

The project includes utility functions for evaluation and visualization. Experiment-specific scores, plots, and comparisons should be added here when publishing reproducible runs.

> **No performance numbers are claimed in this README unless they are directly supported by committed experiment results.**

## 🔬 Research Area

```text
Artificial Intelligence
        ↓
Deep Learning
        ↓
Graph Neural Networks
        ↓
Graph Attention
        ↓
Temporal Modeling
        ↓
Computational Biology
        ↓
lncRNA-miRNA Association Prediction
```

## 📚 Publication

Shivani Saxena, Ahsan Z. Rizvi, **"Stacked graph attention network with temporal modeling for lncRNA-miRNA association network,"** *IEEE/ACM Transactions on Computational Biology and Bioinformatics*, 2025.

**DOI:** `10.1109/TCBBIO.2025.3587877`

## 👨‍💻 Author

**Deep Koshiya**  
AI & ML Developer • Python Developer • Computer Vision • Deep Learning

- GitHub: https://github.com/Deep-k-coder
- LinkedIn: https://www.linkedin.com/in/deepkoshiya/
- Portfolio: https://deep-about.netlify.app

## 📄 License & Data

Refer to the original project, publication, dataset, and repository terms before redistributing research code or data.
