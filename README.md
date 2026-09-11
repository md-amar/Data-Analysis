# 📊 Data-Analysis

A hands-on collection of Jupyter notebooks for learning **pandas** — from data inspection and indexing to filtering and beyond. Each notebook builds on the previous one, making this repo a complete beginner-to-intermediate guide for tabular data manipulation in Python.
 
---

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- Jupyter Notebook or JupyterLab (or VS Code with the Jupyter extension)
- pandas

### Installation

```bash
# Clone the repository
git clone https://github.com/malcommathela/Data-Analysis.git
cd Data-Analysis

# Create a virtual environment (recommended)
python -m venv .venv

# Activate it
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# Install dependencies
pip install pandas jupyter
```

### Running the Notebooks

```bash
jupyter notebook
# or
jupyter lab
```

Then open any `.ipynb` file and run the cells top-to-bottom.

---

## 📁 Repository Structure

```
Data-Analysis/
│
├── 📄 README.md                    # You are here!
├── 📄 products.csv                 # Sample dataset used across all notebooks
│
├── 📓 Assignment_1_Week_1.ipynb  # Week 1 assignment
├── 📓 Panda_Indexes.ipynb          # Indexing, sorting & reindexing
├── 📓 Pandas.ipynb                 # Data inspection & selection (iloc, loc)
├── 📓 Pandas_Filters.ipynb         # Filtering by conditions
├── 📓 Week3.ipynb                  # Week 3 content
└── 📓 Week_4.ipynb                 # Week 4 content
```

---

## 📓 Notebook Guide

| Notebook | Topic | What You'll Learn |
|----------|-------|-----------------|
| **Assignment_1_Week_1.ipynb** | Week 1 Assignment | Foundational exercises to practice basic pandas operations |
| **Panda_Indexes.ipynb** | Indexing | `set_index()`, `reset_index()`, `sort_index()`, `reindex()`, naming indexes |
| **Pandas.ipynb** | Inspection & Selection | `info()`, `head()`, `tail()`, `iloc[]`, `loc[]`, boolean filtering, slicing, missing values |
| **Pandas_Filters.ipynb** | Filtering | Comparison operators, `&` / `\|`, `isin()`, `between()`, `str.contains()`, `query()`, `where()`, `~` negation |
| **Week3.ipynb** | Week 3 Content | *(Add description after reviewing contents)* |
| **Week_4.ipynb** | Week 4 Content | *(Add description after reviewing contents)* |

> 💡 **Recommended order:** Start with `Pandas.ipynb` → `Panda_Indexes.ipynb` → `Pandas_Filters.ipynb` for the core pandas learning path.

---

## 🗂️ The Dataset

All core notebooks use **`products.csv`** — a synthetic dataset of 15 tech products with the following columns:

| Column | Type | Description |
|--------|------|-------------|
| `Name` | string | Product name |
| `Brand` | string | Manufacturer |
| `Category` | string | Product category (Peripherals, Audio, Storage, etc.) |
| `Price` | float | Price in USD |
| `Stock` | int | Units in stock |
| `Color` | string | Product color |
| `Rating` | float | Customer rating (1–5) |
| `Warranty_Months` | int | Warranty duration |

---

## 🎯 Key Concepts Covered

### 1. Data Inspection
- `df.info()`, `df.describe()`, `df.shape`, `df.dtypes`
- `df.head()`, `df.tail()`
- Missing value detection with `df.isnull().sum()`

### 2. Selection
- **Positional:** `df.iloc[row, col]` — by integer position
- **Label-based:** `df.loc[row_label, col_label]` — by name
- **Boolean:** `df[df['Column'] > value]` — by condition

### 3. Indexing
- `set_index()` / `reset_index()` — promote columns to/from index
- `sort_index()` — order by index values
- `reindex()` — reorder/select columns

### 4. Filtering
- Single & multiple conditions (`&`, `|`, `~`)
- `isin()` — membership checks
- `between()` — range filtering
- `str.contains()` / `str.startswith()` — text filtering
- `query()` — SQL-style syntax
- `where()` — conditional replacement

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **Library:** [pandas](https://pandas.pydata.org/)
- **Environment:** Jupyter Notebook / JupyterLab / VS Code

---

## 📝 Notes

- All notebooks include **Colab badges** for running directly in Google Colab.
- Each notebook is self-contained — you can run them independently, though they share the same `products.csv` dataset.
- Code cells include inline comments explaining what each line does.

---

## 📚 Resources

- [pandas Documentation](https://pandas.pydata.org/docs/)
- [10 Minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)

---

## 👤 Author

**Malcom Mathela**

- GitHub: [@malcommathela](https://github.com/malcommathela)

---

## 📜 License

This project is open for educational use. Feel free to fork, clone, and adapt for your own learning.

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-2.0+-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" />
</p>
