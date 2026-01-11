# Machine Learning Notebooks: Decision Trees + MNIST

Jupyter notebooks demonstrating **Decision Tree classification** and **MNIST digit recognition**. [file:28][file:29]

## Contents

| Notebook | Description | Dataset |
|----------|-------------|---------|
| `decision-_tree.ipynb` | Decision Tree classifier implementation, training, evaluation | Custom/synthetic data  |
| `tmnst.ipynb` | MNIST handwritten digits (0-9) classification | MNIST dataset (~60k images) | 
Full TMNST Dataset at - https://www.kaggle.com/datasets/hojjatk/mnist-dataset

## Quick Start

```bash
# Clone repo & install dependencies
git clone <your-repo-url>
cd repo-name

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows

# Install packages
pip install jupyter pandas numpy scikit-learn matplotlib seaborn pillow

# Launch notebooks
jupyter notebook
