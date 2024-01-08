# Project Name

## Project Structure

- `_Notebooks/`: Contains all the Jupyter notebooks.
- `_Dataset/`: Contains the dataset files for training and testing the models.
- `Results/`: Contains the experimental results.
- `Static/`: Contains the static files

## How to Compile and Run Notebooks

1. Install the required dependencies by running the following command:
    ```bash
    pip install -r requirements.txt
    ```

2. Open the desired notebook from the `_Notebooks/` directory.

3. Run the notebook cells sequentially to execute the code.

4. Additional notes: for the gnn notebooks ignore the first 3 blocks if the notebook is runned on a local machine

## Notebook Descriptions

### Notebook 1: Data Preprocessing

- Description: This notebook covers the data preprocessing steps of the raw dataset.
- File: `_Notebooks/data_preprocessing.ipynb`

### Notebook 2: Disorder Subclass prediction using decision trees experiments

- Description: This notebook presents the training and results of a series of decision trees models on the proposed datasets.
- File: `_Notebooks/disorder_subclass_decision_tree_experiments.ipynb`

### Notebook 3: Disorder Subclass prediction using MLP

- Description: This notebook presents the training and results of a series of MLP models on the proposed datasets.
- File: `_Notebooks/disorder_subclass_graph_nn_experiments.ipynb`

### Notebook 4: Disorder Subclass prediction using GNN

- Description: This notebook presents the training and results of a series of GNN models on the proposed datasets.
- File: `_Notebooks/disorder_subclass_nn_experiments.ipynb`

### Notebook 5: Disorder Subclass prediction using decision trees experiments by adding genetic_disorder as a predicted feature

- Description: This notebook presents the training and results of a series of decision trees models on the proposed datasets, with the feature that we first predict the genetic disorder, add it as a feature and then predict the disorder subclass.
- File: `_Notebooks/disorder_subclass_with_genetic_disorder_predicted_decision_tree_experiments.ipynb`

### Notebook 6: Genetic disorder prediction using decision trees experiments

- Description: This notebook presents the training and results of a series of decision trees models on the proposed datasets.
- File: `_Notebooks/genetic_disorder_decision_trees_experiments.ipynb`

### Notebook 7: Disorder Subclass prediction using MLP

- Description: This notebook presents the training and results of a series of MLP models on the proposed datasets.
- File: `_Notebooks/genetic_disorder_graph_nn_experiments.ipynb`

### Notebook 8: Disorder Subclass prediction using GNN

- Description: This notebook presents the training and results of a series of GNN models on the proposed datasets.
- File: `_Notebooks/genetic_disorder_nn_experiments.ipynb`
