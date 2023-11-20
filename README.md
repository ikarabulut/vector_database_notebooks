# Notebooks for vector database learning

These notebooks are separated by lessons. Lessons are from [DeepLearning.AI - Vector Databases: from Embeddings to Applications short course](https://learn.deeplearning.ai/vector-databases-embeddings-applications/lesson/1/introduction)

1. Embeddings: Learn about vector embeddings and apply different techniques across image and sentance transformation

## To run locally

- This project requires [Anaconda](https://docs.anaconda.com/free/anaconda/install/) to install please follow the instructions in the former link.
- All dependencies are located in the environment.yml file
- I ran these notebooks in vsCode. The instructions below will be based on running them in the same tool.

1. Create the virtual environment based on the `environment.yml` file. This will create a conda env with the name `notebook`

```
conda env create -f environment.yml
```

2. Activate the conda environment in your terminal

```
conda activate notebook
```

3. Set your vscode notebook env to the conda env `notebook`

4. Install pip requirements while in `notebook` environment

```
pip install -r requirements.txt
```

**To Exit the conda env run `conda deactivate` in your terminal**
