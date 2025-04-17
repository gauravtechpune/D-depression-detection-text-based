# Detecting Signs of Depression from Social Media Text

This repository contains the code of our winning solution for the [Shared Task on Detecting Signs of Depression from Social Media Text](https://competitions.codalab.org/competitions/36410) at [LT-EDI-ACL2022](https://sites.google.com/view/lt-edi-2022/home).

More details can be found in our paper:  
**[OPI@LT-EDI-ACL2022: Detecting Signs of Depression from Social Media Text using RoBERTa Pre-trained Language Models](https://aclanthology.org/2022.ltedi-1.40/)**

## 📝 Task Description

The goal of this task is to build a system that, given a social media post in English, can classify the post into one of the following categories based on the signs of depression:

- **Not Depressed**
- **Moderately Depressed**
- **Severely Depressed**

## 📦 Requirements

To run the code, make sure you have the following dependencies installed:

- Python >= 3.8  
- `transformers` == 4.13.0  
- `simpletransformers` == 0.63.7  
- `pandas` == 1.2.5  
- `scikit-learn` == 0.23.1  
- `tqdm` == 4.62.3

You can install the dependencies using pip:

```bash
pip install -r requirements.txt
.
├── data/                   # Dataset files
├── models/                 # Saved models
├── src/                    # Source code
│   ├── train.py            # Training script
│   ├── evaluate.py         # Evaluation script
│   └── utils.py            # Utility functions
├── README.md               # Project overview (this file)
└── requirements.txt        # Python dependencies

