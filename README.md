# Named Entity Recognition in Natural Language Processing 🤖📊

This repository hosts our group's project on Named Entity Recognition (NER) as part of the China-ASEAN Online Program on Data Science and Big Data Analysis (2020.9-2020.11). Our focus has been to develop models that accurately perform NER tasks within the field of Natural Language Processing.

## About The Project 🌏

The project is in line with the objectives of the program: enhancing students' knowledge and practical abilities in data science and big data analysis. It supports the learning and talent development initiatives under the China-ASEAN cooperation.

## Scripts Overview 📄

### Script 1: BiLSTM-CRF Model 🤖

- **Functionality**: Loads and processes the [dataset](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus![image](https://github.com/PHYRA47/NER-task-in-NLP/assets/102316140/c190f00d-e619-456a-b7cf-d2154d530a55)
), preparing it for the NER task. Utilizes a Bidirectional Long Short-Term Memory (BiLSTM) coupled with a Conditional Random Field (CRF) for sequence tagging.
- **Features**:
  - Tokenization and sentence segmentation
  - Data cleaning and preparation
  - BiLSTM-CRF model construction
  - Model training and evaluation using metrics like precision, recall, and F1-score
  - Performance visualization of training and validation accuracy
 
### Script 2: BiLSTM-CNN Model 📊

- **Functionality**: Enhances the ability to recognize named entities by integrating character-level information into the embeddings. This script employs a hybrid model combining LSTM and Convolutional Neural Networks (CNNs) for effective context capture.
- **Features**:
  - Word and character-level data preparation
  - Embedding layers tailored to capture deep textual features
  - Bidirectional LSTM for context-aware learning
  - CNN layers for extracting local features
  - Model predictions on unseen text and demonstration of the prediction capabilities

