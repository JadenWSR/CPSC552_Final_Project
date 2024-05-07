# CPSC 552 Final Project: Detecting Human-AI Generated Texts: A Multi-Method Classification Approach with Compact Style Embeddings
## Group members:
- Lang Ding(lang.ding@yale.edu)
- Shurui Wang(shurui.wang@yale.edu)
- Alex Wang(alex.wang.ww445@yale.edu)


## Datasets
We used two datasets.

- [Augmented data for LLM from Kaggle](https://www.kaggle.com/datasets/jdragonxherrera/augmented-data-for-llm-detect-ai-generated-text?resource=download&select=final_test.csv). This dataset consists of 433,564 texts labeled as AI-generated or human-generated from multi-resources. Including GPT models and Claude models, this dataset has tests generated from the most up-to-date AI models. It already has a 80/20 split training and testing set. (The file size is too large to upload to Github. To run our code, you need to download the dataset from Kaggle and store it in data folder.)
- [MixSet](https://github.com/Dongping-Chen/MixSet/tree/main) from Github. This dataset contains several subsets of human-written text, Ai-generated text, and mixed human-AI text. The Mixset dataset comprises a total of 12 JSON files, each containing 300 pieces of MixText data. This brings the total to 3,600 pieces of MixText data across the dataset.

Due to the limited size of MixSet, we enhance it by integrating samples from the Augmented Data for LLM, creating a balanced dataset with three categories: pure human, pure AI, and mixed texts. This balanced dataset comprises 7,500 entries for training and 1,500 for testing, with a further 5% of the training set reserved as a validation set.

## Report
Our project report can be found [here]().

## Code
Experiments with MobileBERT can be found [here](https://github.com/JadenWSR/CPSC552_Final_Project/tree/main/Triplet_Model_3_Category_Mobile_Bert.ipynb).

Experiments with DistilBERT  can be found [here](). 

## Video
A 5-minute video explaining our project can be found [here]().