
## Environment Setup

First we must setup our environment to make sure we have all appropriate modules installed. To do this, install all modules using a ```.yaml``` file via ```conda```. 

if you do not have `conda` yet do the following:

1. go to: https://docs.conda.io/en/latest/miniconda.html

2. install miniconda, full aniconda is not needed for this project

3. add to path and restart vscode

To setup the environment run:
```bash
conda env create -f env_setup/data_environment.yml
```
Then activate the environment by:
```bash
conda activate data_env
```

You can deactivate the environment by:

```bash
conda decativate daa_env
```

## Project Setup

Download the kaggle dataset and add it to the `data/raw` folder __Do not push the dataset to the repo to avoid repo bloat__ 

Later when preprocessing is completed it will be added to the `data/processed` folder


