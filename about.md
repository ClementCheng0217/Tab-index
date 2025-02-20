---
layout: page
title: About
permalink: /about/
---

## Introduction

---

**TabFSBench** is a benchmarking tool for feature shifts in tabular data in open-environment scenarios. It aims to analyse the performance and robustness of a model in feature shifts.

**TabFSBench** offers the following advantages:

- **Various Models**: Tree-based models, deep-learning models, LLMs and tabular LLMs.
- **Diverse Experiments**: Single shift, most/least-revelant shift and random shift.
- **Exportable Datasets**: Be able to export the feature-shift version of the given dataset.
- **Addable Components**: Supports to add new datasets and models, and export the given dataset under the specific experiment.

## Datasets

---

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 8px;
            text-align: center;
            border-bottom: 1px solid #ddd;
        }
        th {
            cursor: pointer;
            background-color: #f2f2f2;
        }
        th:hover {
            background-color: #ddd;
        }
        /* 新增合并单元格的样式 */
        .group-header {
            text-align: center;
            background-color: #e0e0e0;
        }
    </style>
</head>

<p>Datasets in TabFSBench. <strong>#Numerical</strong> means numerical features. <strong>#Categorical</strong> means categorical features.</p>
<table>
    <thead>
        <tr>
            <th>Tasks</th>
            <th>Dataset</th>
            <th>#Samples</th>
            <th>#Numerical</th>
            <th>#Categorical</th>
            <th>#Labels</th>
            <th>Link</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="4">Binary Classification</td>
            <td align="center">credit</td>
            <td>1,000</td>
            <td>7</td>
            <td>13</td>
            <td>2</td>
            <td>https://www.openml.org/search?type=data&sort=runs&id=31&status=active</td>
        </tr>
        <tr>
            <td>electricity</td>
            <td>45,312</td>
            <td>8</td>
            <td>0</td>
            <td>2</td>
            <td>https://www.kaggle.com/datasets/vstacknocopyright/electricity</td>
        </tr>
        <tr>
            <td>heart</td>
            <td>918</td>
            <td>6</td>
            <td>5</td>
            <td>2</td>
            <td>https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction</td>
        </tr>
        <tr>
            <td>MiniBooNE</td>
            <td>72,998</td>
            <td>50</td>
            <td>0</td>
            <td>2</td>
            <td>https://www.kaggle.com/datasets/alexanderliapatis/miniboone</td>
        </tr>
        <tr>
            <td rowspan="4">Multi-Class Classification</td>
            <td>Iris</td>
            <td>150</td>
            <td>4</td>
            <td>0</td>
            <td>3</td>
            <td>https://www.kaggle.com/datasets/uciml/iris</td>
        </tr>
        <tr>
            <td>penguins</td>
            <td>345</td>
            <td>4</td>
            <td>2</td>
            <td>3</td>
            <td>https://www.kaggle.com/datasets/youssefaboelwafa/clustering-penguins-species</td>
        </tr>
        <tr>
            <td>eye_movements</td>
            <td>10,936</td>
            <td>27</td>
            <td>0</td>
            <td>4</td>
            <td>https://www.kaggle.com/datasets/vinnyr12/eye-movements</td>
        </tr>
        <tr>
            <td>jannis</td>
            <td>83,733</td>
            <td>54</td>
            <td>0</td>
            <td>4</td>
            <td>https://www.openml.org/search?type=data&status=active&id=45021</td>
        </tr>
        <tr>
            <td rowspan="4">Regression</td>
            <td>abalone</td>
            <td>4,178</td>
            <td>7</td>
            <td>1</td>
            <td>\</td>
            <td>https://www.kaggle.com/datasets/rodolfomendes/abalone-dataset</td>
        </tr>
        <tr>
            <td>bike</td>
            <td>10,886</td>
            <td>6</td>
            <td>3</td>
            <td>\</td>
            <td>https://www.kaggle.com/datasets/abdullapathan/bikesharingdemand</td>
        </tr>
        <tr>
            <td>concrete</td>
            <td>1,031</td>
            <td>8</td>
            <td>0</td>
            <td>\</td>
            <td>https://www.kaggle.com/datasets/maajdl/yeh-concret-data</td>
        </tr>
        <tr>
            <td>laptop</td>
            <td>1,275</td>
            <td>8</td>
            <td>14</td>
            <td>\</td>
            <td>https://www.kaggle.com/datasets/owm4096/laptop-prices</td>
        </tr>
    </tbody>
</table>

## Models

---

TabFSBench is possible to test three kinds of models' performance directly, including tree-based models, deep learning models and tabular LLMs. For LLMs, TabFSBnech provides text files(.json) about the given dataset that can be used directly for LLM to finetune.

#### Tree-based models
1. **[CatBoost](https://catboost.ai/)**: A powerful boosting-based model designed for efficient handling of categorical features.
2. **[LightGBM](https://lightgbm.readthedocs.io/en/latest/index.html)**: A machine-learning model based on the Boosting algorithm.
3. **[XGBoost](https://xgboost.readthedocs.io/en/latest/index.html)**: A machine-learning model incrementally building multiple decision trees by optimizing the loss function.

#### Deep learning models
We use LAMDA-TALENT to evaluate deep-learning models. You can get details from **[LAMDA-TALENT](https://github.com/qile2000/LAMDA-TALENT)**.
1. **MLP**: A multi-layer neural network, which is implemented according to [RTDL](https://arxiv.org/abs/2106.11959).
2. **ResNet**: A DNN that uses skip connections across many layers, which is implemented according to [RTDL](https://arxiv.org/abs/2106.11959).
3. **[SNN](https://arxiv.org/abs/1706.02515)**: An MLP-like architecture utilizing the SELU activation, which facilitates the training of deeper neural networks.
4. **[DANets](https://arxiv.org/abs/2112.02962)**: A neural network designed to enhance tabular data processing by grouping correlated features and reducing computational complexity.
5. **[TabCaps](https://openreview.net/pdf?id=OgbtSLESnI)**: A capsule network that encapsulates all feature values of a record into vectorial features.
6. **[DCNv2](https://arxiv.org/abs/2008.13535)**: Consists of an MLP-like module combined with a feature crossing module, which includes both linear layers and multiplications.
7. **[NODE](https://arxiv.org/abs/1909.06312)**: A tree-mimic method that generalizes oblivious decision trees, combining gradient-based optimization with hierarchical representation learning.
8. **[GrowNet](https://arxiv.org/abs/2002.07971)**: A gradient boosting framework that uses shallow neural networks as weak learners.
9. **[TabNet](https://arxiv.org/abs/1908.07442)**: A tree-mimic method using sequential attention for feature selection, offering interpretability and self-supervised learning capabilities.
10. **[TabR](https://arxiv.org/abs/2307.14338)**: A deep learning model that integrates a KNN component to enhance tabular data predictions through an efficient attention-like mechanism.
11. **[ModernNCA](https://arxiv.org/abs/2407.03257)**: A deep tabular model inspired by traditional Neighbor Component Analysis, which makes predictions based on the relationships with neighbors in a learned embedding space.
12. **[AutoInt](https://arxiv.org/abs/1810.11921)**: A token-based method that uses a multi-head self-attentive neural network to automatically learn high-order feature interactions.
13. **[Saint](https://arxiv.org/abs/2106.01342)**: A token-based method that leverages row and column attention mechanisms for tabular data.
14. **[TabTransformer](https://arxiv.org/abs/2012.06678)**: A token-based method that enhances tabular data modeling by transforming categorical features into contextual embeddings.
15. **[FT-Transformer](https://arxiv.org/abs/2106.11959)**: A token-based method which transforms features to embeddings and applies a series of attention-based transformations to the embeddings.
16. **[TANGOS](https://openreview.net/pdf?id=n6H86gW8u0d)**: A regularization-based method for tabular data that uses gradient attributions to encourage neuron specialization and orthogonalization.
17. **[SwitchTab](https://arxiv.org/abs/2401.02013)**: A self-supervised method tailored for tabular data that improves representation learning through an asymmetric encoder-decoder framework. Following the original paper, our toolkit uses a supervised learning form, optimizing both reconstruction and supervised loss in each epoch.
18. **[TabPFN](https://arxiv.org/abs/2207.01848)**: A general model which involves the use of pre-trained deep neural networks that can be directly applied to any tabular task. TabFSBench uses the first version of TabPFN and supports to evaluate [TabPFNv2](https://www.nature.com/articles/s41586-024-08328-6) by updating the version. 

#### LLMs
1. **[Llama3-8B](https://huggingface.co/meta-llama/Meta-Llama-3-8B)**: Llama3-8B is released by Meta AI in April 2024.
   - Due to memory limitations, TabFSBench only provides json files for LLM fine-tuning and testing ( `datasetname_train.json / datasetname_test_i.json` , i means the degree of feature shifts), asking users to use LLM locally.
   - TabFSBench provides the context of **Credit** Dataset. Users can rewrite background, features_information, declaration and question of `llm()` in `./model/utils.py`.

#### Tabular LLMs
1. **[TabLLM](https://arxiv.org/abs/2210.10723)**: A framework that leverages LLMs for efficient tabular data classification.
2. **[UniPredict](https://arxiv.org/abs/2310.03266)**: A framework that firstly trains on multiple datasets to acquire a rich repository of prior knowledge. UniPredict-Light model that TabFSBench used is available at [Google Drive](https://drive.google.com/file/d/1ABsv0C9HSJ9-M3kpkGRIFEw-4ebKdA3h/view?usp=sharing). After downloading the model, place it in `./model/tabularLLM/files/unified/models` and rename it to `light_state.pt`.

## Experimental Results

---

#### 1. Most models have the limited applicability in feature-shift scenarios.
- Most models can’t handle feature shifts well.
- No Model Consistently Outperforms.
  
<img src="https://s2.loli.net/2025/01/31/wvLWCdt3HrXMagG.png"  width="800px">

#### 2. Shifted features’ importance has a linear trend with model performance degradation.

- Single strong correlated feature shifted causes greater model performance degradation.
- Shifted feature set’s correlations have a relationship with model performance degradation linearly.

We use performance gap to measure the model performance Gap $Delta$. Sum of shifted feature set's correlations refers to the sum of Pearson correlation coefficients of shifted features. Notably, model performance Gap $Delta$ and sum of shifted feature set's correlations demonstrate a strong correlation, with a Pearson correlation coefficient of $\rho$ = 0.7405.

<img src="https://s2.loli.net/2025/01/31/7Hi8fX61DbTeq5L.png"  width="800px">

#### 3. Model closed-environment performance correlates with feature-shift performance.

Model closed-environment performance vs. model feature-shift performance. Closed-environment means that the dataset does not have any degree of feature shift. Feature-shift means average model performance in all degrees of feature shifts.

<img src="https://s2.loli.net/2025/01/31/SId5jgqNUvJxKzk.png"  width="800px">
