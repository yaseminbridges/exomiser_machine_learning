# Exomiser Machine Learning

This repository encompasses the data scripts utilised in our Exomiser machine learning experiments. Our aim is to enhance the current combined score through rigorous experimentation and analysis.

The workflow is as follows:

1. Sequential Feature Selection
2. Hyperparameter Tuning
3. Cross Validation

The `ml_data_subset.tsv` found in the `data` folder contains a subset of 50 genes from the training data to give an idea of how the code works.

To run the notebooks within this project you will need to have installed Poetry - which is used for dependency management within a virtual environment:

```bash
pip install poetry
git clone https://github.com/yaseminbridges/exomiser_machine_learning.git
cd exomiser_machine_learning
poetry install
poetry shell
```

