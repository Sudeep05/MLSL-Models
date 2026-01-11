# Machine Learning Notebooks: Decision Trees + MNIST

Jupyter notebooks demonstrating **Decision Tree classification** and **MNIST digit recognition**. [file:28][file:29]

## Contents

| Notebook | Description | Dataset |
|----------|-------------|---------|
| `decision-_tree.ipynb` | Decision Tree classifier implementation, training, evaluation | Custom/synthetic data  |
| `tmnst.ipynb` | MNIST handwritten digits (0-9) classification | MNIST dataset (~60k images) | 

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
```
## Tech Stack
```bash
pandas | numpy | scikit-learn | matplotlib | seaborn | jupyter | PIL
```

## Key Concepts Covered
Decision Tree Notebook [file:28]
- Tree construction algorithm
- Entropy/Gini impurity
- Hyperparameter tuning (max_depth, min_samples_split)
- Visualization of decision boundaries
- Cross-validation scoring

MNIST Notebook [file:29]
- Image preprocessing (28x28 → flatten/reshape)
- Data splitting (train/test)
- Model training on 60k+ samples
- Confusion matrix & classification report
- Digit prediction visualization

## Results Preview
Decision Tree: Accuracy ~85-95% (depends on dataset complexity) [file:28]
MNIST: Test accuracy typically 97%+ with basic models [file:29]

## Example Outputs
Decision boundary visualization and tree structure plots in notebooks.
MNIST predictions show correctly classified digits with confidence scores. [file:28][file:29]

## Requirements
- jupyter==1.0.0
- pandas==2.2.3
- numpy==2.1.1
- scikit-learn==1.5.2
- matplotlib==3.9.2
- seaborn==0.13.2
- pillow==10.4.0

## Related Resources
MNIST Dataset - Full TMNST Dataset at - https://www.kaggle.com/datasets/hojjatk/mnist-dataset
Scikit-learn Decision Trees
