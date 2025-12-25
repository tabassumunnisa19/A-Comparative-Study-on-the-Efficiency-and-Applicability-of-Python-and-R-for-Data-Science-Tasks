# A-Comparative-Study-on-the-Efficiency-and-Applicability-of-Python-and-R-for-Data-Science-Tasks

## 📌 Overview
This repository accompanies the research paper **“A Comparative Study on the Efficiency and Applicability of Python and R for Data Science Tasks”**.  
The study provides an evidence-based comparison of Python and R by combining a structured literature survey of 25 peer-reviewed works with lightweight experimental validation on real-world datasets.

The repository contains reproducible experiments implemented in both Python and R, along with result artifacts used in the manuscript.

---

## 📄 Abstract
Python and R are the two most dominant programming languages in data science. Python is widely adopted for end-to-end machine learning pipelines, scalability, and production deployment, while R is preferred for statistical modeling and publication-quality visualization.  
This study synthesizes findings from 25 representative research works and complements them with experimental benchmarking on the Iris, Titanic, and COVID-19 datasets. Runtime performance, predictive accuracy, and visualization rendering time are compared to highlight complementary strengths and practical trade-offs between the two ecosystems.

---

## 📂 Repository Structure

```text

├── notebooks/
│   ├── python_experiment.ipynb
│   └── r_experiment.ipynb
│
├── results/
│   ├── python_results.png
│   └── r_results.png
│
├── paper/
│   └── manuscript.pdf
│
├── environment/
│   ├── requirements.txt
│   └── session_info.txt
│
├── LICENSE
├── CITATION.cff
└── README.md

```
---

## 🧪 Experiments
The experimental comparison focuses on:
- **Iris dataset**: Logistic regression (runtime and accuracy)
- **Titanic dataset**: Data preprocessing and logistic regression
- **COVID-19 dataset**: Time-series visualization and rendering performance

Python experiments were conducted using `pandas`, `NumPy`, `scikit-learn`, and `matplotlib`.  
R experiments were conducted using `tidyverse`, `ggplot2`, `dplyr`, and `caret`.

All experiments were executed on the same hardware configuration to ensure fairness.

---

## 🔁 Reproducibility

### Python

```bash
pip install -r environment/requirements.txt

```

Launch the Python experiment notebook:

```bash
jupyter notebook notebooks/python_experiment.ipynb

```

🧪 R Environment
Ensure R ≥ 4.3.1 is installed.

Install the required R packages:

```bash
install.packages(c("tidyverse", "ggplot2", "dplyr", "caret", "lubridate"))

```

Detailed R session information (package versions, platform, and locale) is documented in:

```bash

environment/session_info.txt
```

This ensures full reproducibility of the reported experiments.

--------
📊 Results

The results/ directory contains all figures generated from the Python and R experiments and used directly in the research paper.
These artifacts serve as fixed experimental evidence supporting the reported runtime, accuracy, and visualization benchmarks.

----------
📜 License

This project is released under the MIT License, allowing reuse, modification, and distribution with appropriate attribution.

See the LICENSE file for details.

-----------

📖 Citation

If you use this work in academic or applied research, please cite the paper or repository using the metadata provided in:

```bash

CITATION.cff
```

This ensures proper attribution and supports reproducible research practices.

-------

👤 Author

Tabassum Unnisa

Independent Researcher, India

🔗 ORCID: https://orcid.org/0009-0005-3967-7304

🌐 Website: https://www.tabassumunnisa.com

Install the required R packages:

