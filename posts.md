---
layout: allposts
title: Quickstart
permalink: /posts/
---

## Quickstart

---

### 1. Download

Download this GitHub repository.

```bash
git clone https://github.com/LAMDASZ-ML/TabFSBench.git
cd TabFSBench
```

### 2. Environment setup

Create a new Python 3.10 environment and install 'requirements.txt'.

```bash
conda create --name tabfsbench python=3.10
pip install -r requirements.txt
```
### 3. Run
You need to input four parameters to use TabFSBench. There are dataset, model, task and degree.

**dataset** and **model**: input the full name. 

**task**: You can choose 'single', 'least', 'most' or 'random' as TaskName.

**degree**: Degree refers to the number of missing columns as a percentage of the total number of columns in the dataset, in the range 0-1. If you want to see the performance of the model at all missing degrees, set Degree to 'all'.

**export_dataset**: Whether to export the dataset or not. Default is 'False'.
```bash
python run_experiment.py --dataset DatasetName --model ModelName --task TaskName --degree Degree --export_dataset True/False
```

In **example.sh** you can get different kinds of instruction samples.

## How to Add New Datasets

---

Datasets used in TabFSBench are placed in the project's current directory, corresponding to the file name.

Each dataset folder consists of:

- `dataset.csv`, which must be included.

- `info.json`, which must include the following two contents (task can be "regression", "multiclass" or "binary", link can be from Kaggle or OpenML, num_classes is optional):
  

  ```json
  {
    "task": "binary", 
    "link": "www.kaggle.com",
    "num_classes":
  }
  ```

## How to Add New Models

---

TabFSBench provides two methods to evaluate new model on feature-shift experiments.

1. Export the dataset. Set export_dataset as True, then can get a csv file of a given dataset in a specific experiment.
2. Import model python file.
   - Add the model name in `./run_experiment.py`.
   - Add the model function in the `./model/utils.py` by leveraging parameters like dataset, model, train_set and test_sets.

