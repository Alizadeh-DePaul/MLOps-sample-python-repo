# Sample Python Repository

A simple repository demonstrating how to structure a Python package with a Jupyter notebook. This project is used as a teaching resource for SE 489 at DePaul University.

## Project Structure

```
sample-python-repo/
├── sample_package/
│   ├── __init__.py          # Package initialization
│   └── sample_module.py     # Example module with SampleClass
├── notebooks/
│   └── 00-sample_notebook.ipynb  # Notebook demonstrating package usage
├── requirements.txt         # Project dependencies
├── .gitignore
└── readme.md
```

## Getting Started

### Prerequisites

- Python 3.9+
- pip

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Alizadeh-DePaul/MLOps-sample-python-repo.git
   cd MLOps-sample-python-repo
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

```python
from sample_package import SampleClass

sc = SampleClass()
print(sc.x)              # 42
print(sc.sample_method()) # 42
```

Or open the notebook in `notebooks/00-sample_notebook.ipynb` for an interactive example.

## Pull Request Practice

This repository is also used to practice the pull request workflow:

1. **Fork** the repository to your own GitHub account.
2. **Clone** your fork to your local machine:
   ```bash
   git clone https://github.com/<your-username>/MLOps-sample-python-repo.git
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/my-change
   ```
4. **Make your changes** and commit them:
   ```bash
   git add .
   git commit -m "Describe your change"
   ```
5. **Push** your branch to your fork:
   ```bash
   git push origin feature/my-change
   ```
6. **Open a pull request** on the original repository from your branch.
