# Getting started with machine learning using scikit-learn

Materials for "Getting started with machine learning using scikit-learn" talk at the Big Data Madison meetup. A live version of the slides can be found at https://jrbourbeau.github.io/big-data-madison-ml-sklearn/.


## Installation

The dependencies for generating the slides are:

- `numpy`
- `pandas`
- `jupyter`
- `scikit-learn`
- `mlxtend`
- `matplotlib`
- `graphviz`

### Using `conda`

A `conda` environment with these dependencies installed can be created via:

```bash
conda env create --file environment.yml
source activate big-data-madison-ml-sklearn
```

### Using `pip`

Inside a virtual environment, `pip` install the needed packages via:

```bash
pip install -r requirements.txt
```

Note: to render decision tree graphs [Graphviz](https://www.graphviz.org/download/) must also be installed.


## Usage

The slides for this talk can be generated via:

```bash
jupyter nbconvert machine-learning-sklearn-big-data-madison.ipynb --to slides --post serve
```

To run the corresponding notebook use

```bash
jupyter notebook machine-learning-sklearn-big-data-madison.ipynb
```
