# 📊 Platzi Clustering

[![Python](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](https://github.com/jasonssdev/platzi-clustering/pulls)

This repository contains implementations of **clustering algorithms** for Data Science with Python, developed as part of the Platzi course. The algorithms are implemented using `scikit-learn` and visualized with `matplotlib`, `seaborn`, and `yellowbrick`.

---

## 🌐 Repository Structure

```bash
platzi-clustering/
├── data/                  # Input data
│   ├── raw/              # Raw data
│   └── processed/        # Processed data
├── notebooks/            # Main course notebooks
├── references/           # Reference or sandbox notebooks
├── utils/                # Helper functions or reusable scripts
├── environment.yml       # Conda environment requirements
├── LICENSE               # Apache 2.0 License
├── pyproject.toml        # Project metadata and dependencies
└── README.md             # This file
```

---

## 🚀 Included Algorithms

* K-Means
* Hierarchical Clustering
* DBSCAN
* Silhouette Visualizations
* Comparison between methods

---

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/jasonssdev/platzi-clustering.git
cd platzi-clustering
```

2. Create the environment with Conda:

```bash
conda env create -f environment.yml
conda activate platzi-clustering
```

---

## 🎓 Usage

All the notebooks are in the `notebooks/` folder. You can open them using Jupyter Lab:

```bash
jupyter lab
```

We suggest reviewing the notebooks in order:

1. `01_first_clustering.ipynb`
2. `02_jss_kmeans.ipynb`
3. `03_jss_hierachical_clustering.ipynb`
4. `04_jss_dbscan.ipynb`

---

## 🙌 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork** the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m "Add new feature"`).
4. Push to your fork (`git push origin feature/your-feature-name`).
5. Open a **Pull Request** against the `main` branch.

Make sure your changes are documented and include examples if applicable.

---

## 🤝 Author

**Jason** - [@jasonssdev](https://github.com/jasonssdev)

---

## 👁️ License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for more details.
