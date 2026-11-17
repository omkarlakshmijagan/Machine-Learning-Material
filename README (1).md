# Machine Learning — Course Materials & Laboratory Programs

[![GitHub Repository](https://img.shields.io/badge/GitHub-Machine--Learning--Material-181717?logo=github)](https://github.com/omkarlakshmijagan/Machine-Learning-Material)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A collection of **Machine Learning course materials**, including syllabus documents, unit-wise lecture presentations, and hands-on Python laboratory experiments. Intended for students, educators, and beginners studying foundational machine learning concepts and algorithms.

## 📚 Repository Overview

This repository brings together teaching resources and practical notebooks for learning Machine Learning (ML). The materials are organized around lecture presentations and a set of nine lab experiments that progress from Python scientific-computing tools to supervised and unsupervised learning algorithms.

### What's included

- **Course syllabus:** A top-level Machine Learning syllabus in PDF format.
- **Lecture slides:** PowerPoint presentations for **Units 1–4**.
- **Laboratory syllabus:** A separate PDF syllabus within the lab folder.
- **Nine Jupyter notebooks:** Exercises on data handling, visualization, regression, classification, and clustering.

## 🗂️ Repository Structure

```text
Machine-Learning-Material/
├── LICENSE
├── ML Syllabus.pdf
├── ML Unit 1.pptx
├── ML Unit 2.pptx
├── ML Unit 3.pptx
├── ML Unit 4.pptx
└── ML lab new syallabus programs/
    ├── Syllabus.pdf
    ├── ML Lab Exp 1.ipynb
    ├── ML Lab Exp 2.ipynb
    ├── ML Lab Exp 3.ipynb
    ├── ML Lab Exp 4.ipynb
    ├── ML Lab Exp 5.ipynb
    ├── ML Lab Exp 6.ipynb
    ├── ML Lab Exp 7.ipynb
    ├── ML Lab Exp 8.ipynb
    └── ML Lab Exp 9.ipynb
```

## 🎓 Course Materials

| Resource | Description | Open |
|---|---|---|
| ML Syllabus | Main course syllabus | [View PDF](ML%20Syllabus.pdf) |
| Unit 1 | Lecture presentation | [View PPTX](ML%20Unit%201.pptx) |
| Unit 2 | Lecture presentation | [View PPTX](ML%20Unit%202.pptx) |
| Unit 3 | Lecture presentation | [View PPTX](ML%20Unit%203.pptx) |
| Unit 4 | Lecture presentation | [View PPTX](ML%20Unit%204.pptx) |
| Laboratory Syllabus | Syllabus for practical sessions | [View PDF](ML%20lab%20new%20syallabus%20programs/Syllabus.pdf) |

> Refer to the syllabus PDFs for the official unit-wise topics and laboratory requirements.

## 🧪 Machine Learning Laboratory Experiments

| Experiment | Main topics / algorithm | Notebook |
|---|---|---|
| **1** | NumPy arrays, matrix operations, and SciPy numerical integration | [Exp 1](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%201.ipynb) |
| **2** | Pandas data manipulation and Matplotlib visualization | [Exp 2](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%202.ipynb) |
| **3** | Simple Linear Regression, including a manual implementation | [Exp 3](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%203.ipynb) |
| **4** | Linear Regression with scikit-learn and regression evaluation metrics | [Exp 4](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%204.ipynb) |
| **5** | Decision Tree Classification and hyperparameter tuning using GridSearchCV | [Exp 5](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%205.ipynb) |
| **6** | K-Nearest Neighbors (KNN) classification using the Iris dataset | [Exp 6](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%206.ipynb) |
| **7** | Support Vector Machine (SVM) classification | [Exp 7](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%207.ipynb) |
| **8** | Logistic Regression using the scikit-learn breast cancer dataset | [Exp 8](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%208.ipynb) |
| **9** | K-Means Clustering with synthetic data and cluster visualization | [Exp 9](ML%20lab%20new%20syallabus%20programs/ML%20Lab%20Exp%209.ipynb) |

### Topics and skills practiced

- **Scientific computing:** NumPy and SciPy.
- **Data preparation and exploration:** Pandas, data handling, and visualizations.
- **Supervised learning:** Linear Regression, Decision Trees, KNN, SVM, and Logistic Regression.
- **Unsupervised learning:** K-Means Clustering.
- **Model assessment:** Train/test splitting, regression error metrics, accuracy, confusion matrices, and classification reports.
- **Model tuning:** Decision Tree hyperparameter search with GridSearchCV.

## 🚀 Getting Started

### Prerequisites

Install **Python 3** and a notebook environment such as **JupyterLab**, **Jupyter Notebook**, or **Visual Studio Code** with its Jupyter extension.

The notebooks use the following Python libraries:

```bash
pip install numpy scipy pandas matplotlib seaborn scikit-learn jupyterlab
```

### Clone the repository

```bash
git clone https://github.com/omkarlakshmijagan/Machine-Learning-Material.git
cd Machine-Learning-Material
```

### Start JupyterLab

```bash
jupyter lab
```

In the file browser, open the folder **`ML lab new syallabus programs`** and select a notebook (for example, `ML Lab Exp 1.ipynb`). Run its cells in order.

Alternatively, open the `.ipynb` files in **Google Colab** by uploading a notebook there.

> **Dataset note:** Some exercises refer to a local file named `house_prices.csv`, which is **not included in the currently listed repository files**. Supply an appropriate dataset and adjust file paths, column selection, and preprocessing before running those cells. Some example notebook cells may also need adjustments to run independently.

## 🧭 Suggested Learning Sequence

1. **Start with the syllabus** to understand the course structure and learning objectives.
2. **Study the lecture slides** for Units 1–4 alongside the prescribed syllabus.
3. **Complete Experiments 1–2** to build familiarity with numerical computing, tabular data, and visualization.
4. **Complete Experiments 3–4** to practice predictive modeling with Linear Regression.
5. **Complete Experiments 5–8** to compare different classification algorithms and evaluation methods.
6. **Complete Experiment 9** to explore unsupervised clustering.
7. **Extend the notebooks** by experimenting with new datasets, preprocessing choices, and model hyperparameters.

## 🎯 Learning Outcomes

After working through the available materials, learners should be better equipped to:

- Manipulate and visualize datasets using common Python ML libraries.
- Understand the core workflow of model training, prediction, and evaluation.
- Implement or apply widely used regression and classification techniques.
- Interpret model-performance metrics and experiment with hyperparameters.
- Apply K-Means to identify groups in unlabeled data.
- Use Jupyter notebooks to document reproducible experiments.

## 🤝 Contributions

Suggestions, improvements, corrections, and educational examples are welcome. To propose a change:

1. Fork the repository.
2. Create a new branch for your changes.
3. Update notebooks, lecture resources, or documentation.
4. Open a pull request describing the changes.

Please ensure that any contributed datasets or third-party materials can be shared under the applicable terms.

## 👨‍🏫 Maintainer

**Dr. B. Omkar Lakshmi Jagan**  
GitHub: [@omkarlakshmijagan](https://github.com/omkarlakshmijagan)

## 📄 License

This repository includes an [MIT License](LICENSE), with copyright attributed to **Dr. B. Omkar Lakshmi Jagan (2026)**. Check the rights and attribution of any third-party teaching content separately.

---

**Explore the repository:** [Machine-Learning-Material](https://github.com/omkarlakshmijagan/Machine-Learning-Material)

*Learn the concepts. Run the experiments. Explore machine learning.*
