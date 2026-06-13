# Wheat Seeds Dataset Clustering & Exploration

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/0x41hd/clustering-seeds-dataset/blob/main/Seeds.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An exploratory data analysis (EDA) and visualization project focused on the **Seeds Dataset** (geometric properties of wheat kernels) using Pandas, Seaborn, and Matplotlib.

## 🌾 Dataset Information
The dataset contains measurements of geometric properties of kernels belonging to three different varieties of wheat: **Kama**, **Rosa**, and **Canadian**.
There are 210 instances with 7 geometric features:
1. Area ($A$)
2. Perimeter ($P$)
3. Compactness ($C = 4\pi A / P^2$)
4. Length of kernel
5. Width of kernel
6. Asymmetry coefficient
7. Length of kernel groove

## 📊 Features & Architecture
* **Data Cleaning:** Automated multi-space delimiter parser with standard column indexing.
* **Exploratory Data Analysis:** Full feature-to-feature correlation scatter mapping customized by target biological seed classes.

## 🚀 Getting Started

### Prerequisites
Install the scientific calculation and visualization bundle via pip:
```bash
pip install -r requirements.txt
