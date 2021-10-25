## Sentiment Analysis

**Author**: Abhinav Sethi

The enclosed notebook file contains annotated code for the sentiment analysis task using the BERT model.

## Installation 

This notebook was developed using google collab. If this needs to be executed on another environment then the transformers library installation needs to be removed and executed separately on the terminal using:

```bash
pip install transformers pandas numpy torch sklearn  
```

## Usage
The configuration section lists down all the paraments used in the model.
In this section change the following variables:

```bash
MODEL_PATH = <path_to_saved_model>
DATASET_PATH = <path_to_dataset_folder>
```

The code expects the dataset to be already split among train, validation, and test sets. The file names for which must be Train.csv, Valid.csv, and Test.csv respectively. 

## Dataset
The dataset used for this project can be found here: [Google Drive Link](https://drive.google.com/drive/folders/1nxTiis6Wo-BcdehLDA584eOzujnY1vTX?usp=sharing)