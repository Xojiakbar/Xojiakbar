<div align="center">

# 🧠 Health AI: Early-Stage Alzheimer’s Detection

### Deep Learning Prototype for Handwriting-Based Cognitive Screening

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange?logo=tensorflow)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-ML-blue?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Research%20Prototype-brightgreen)

</div>

---

## 🚀 About the Project

**Health AI: Early-Stage Alzheimer’s Detection** is a research prototype that uses digital handwriting data to distinguish between:

* **ES-AD** — Early-stage Alzheimer’s Disease subjects
* **HC** — Healthy control subjects

The project explores handwriting dynamics as potential digital biomarkers for early cognitive impairment screening.

> ⚠️ **Disclaimer:** This project is for research and educational purposes only. It is not a medical diagnostic tool.

---

## ✨ Key Features

* 🖊️ Digital pen trajectory analysis
* ⏱️ Pen-up and pen-down duration extraction
* 📈 X/Y velocity-based feature engineering
* 🧠 Fully connected neural network model
* 📊 Handwriting behavior visualization
* 🔬 ES-AD vs HC classification workflow

---

## 🧩 Project Workflow

```text
Raw handwriting data
        ↓
Pen trajectory preprocessing
        ↓
Feature extraction
        ↓
Data normalization
        ↓
Deep learning model
        ↓
ES-AD / HC classification
```

---

## 📁 Repository Structure

```text
Health-AI-Early-Stage-Alzheimer-s-Detection/
├── README.md
└── internship.ipynb
```

---

## 📊 Dataset

The dataset includes handwriting and drawing tasks collected from two acquisition partitions:

* **V3:** patient list and diagnostic labels
* **V4:** patient list and diagnostic labels

Example tasks include:

* free-text writing,
* copied text writing,
* loop drawing,
* handwriting/drawing sequences.

> The raw medical dataset is not included in this repository. Update the dataset path inside the notebook before running the code.

---

## 🧠 Extracted Features

The notebook uses digital pen recordings with features such as:

| Feature Group | Examples                             |
| ------------- | ------------------------------------ |
| Trajectory    | `X`, `Y`, movement differences       |
| Temporal      | time, pen-up time, pen-down time     |
| Pressure      | pen pressure `P`                     |
| Orientation   | azimuth `Az`, altitude `Al`          |
| Kinematic     | x/y velocity, pen-in/pen-up velocity |

---

## 🛠️ Tech Stack

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib

---

## ⚙️ Installation

```bash
git clone https://github.com/Xojiakbar/Health-AI-Early-Stage-Alzheimer-s-Detection.git
cd Health-AI-Early-Stage-Alzheimer-s-Detection
```

```bash
python -m venv .venv
source .venv/bin/activate
```

For Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib jupyter
```

---

## ▶️ Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
internship.ipynb
```

Update the dataset path:

```python
all_data = pd.read_csv(
    "path/to/patient/Test1.txt",
    skiprows=21,
    sep=" ",
    header=None
)
```

Then run the notebook cells in order.

---

## 📌 Roadmap

* [ ] Add `requirements.txt`
* [ ] Remove hard-coded local paths
* [ ] Add reusable preprocessing scripts
* [ ] Add accuracy, precision, recall, F1-score, and ROC-AUC
* [ ] Add model saving and loading
* [ ] Add anonymized sample data or synthetic examples
* [ ] Add clinical validation and ethical notes

---

## 👤 Author

**Khojiakbar Botirov**
GitHub: [@Xojiakbar](https://github.com/Xojiakbar)

---

## 📄 License

No license file is currently included.

---

<div align="center">

⭐ If this project is useful, consider starring the repository.

</div>
::: ​​
