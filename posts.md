---
layout: allposts
title: Quickstart
permalink: /posts/
---

### 1. Download

Download this GitHub repository.

[//]: # (```bash)
[//]: # (git clone https://github.com/LAMDASZ-ML/TabFSBench.git)
[//]: # (```)

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
