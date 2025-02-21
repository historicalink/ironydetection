# HistoricalInk: Exploring Large Language Models for Irony Detection in 19th-Century Spanish

This repository contains the notebooks used in the experiments conducted for the paper titled "Historical Ink: Exploring Large Language Models for Irony Detection in 19th-Century Spanish".

## Abstract
This study explores the use of large language models (LLMs) to enhance datasets and improve irony detection in 19th-century Latin American newspapers. Two strategies were employed to evaluate the efficacy of BERT and GPT models in capturing the subtle nuances of irony, through both multi-class and binary classification tasks. First, we implemented dataset enhancements focused on enriching emotional and contextual cues; however, these showed limited impact on historical language analysis. The second strategy, a semi-automated annotation process, effectively addressed class imbalance and augmented the dataset with high-quality annotations. Despite the challenges posed by the complexity of irony, this work contributes to the advancement of sentiment analysis through two key contributions: introducing a novel historical Spanish dataset tagged for sentiment analysis and irony detection, and proposing a semi-automated annotation methodology where human expertise is crucial for refining LLMs results, enriched by incorporating historical and cultural contexts as core features.

## Notebooks

### 1. [`Dataset_Augmentation.ipynb`](https://github.com/historicalink/ironydetection/blob/main/Dataset_Augmentation.ipynb)
This notebook contains the code for the requests made in the semi-autommatic annotation process.

### 2. [`Dataset_Enhancement.ipynb`](https://github.com/historicalink/ironydetection/blob/main/Dataset_Enhancement.ipynb)
This notebook contains the code for the dataset enhancement process and several mock prompts used in the process.

### 3. [`Experiments_with_NN.ipynb`](https://github.com/historicalink/ironydetection/blob/main/Experiments_with_NN.ipynb)
This notebook contains all the process used for the experiments that used the different datasets, the architecture of the Neural Network used and the different processes used for the cleaning and preparation of the datasets. Code was reused with slight differences for each experiment.
