# pneumonia-detection-challenge
## Intro

The objective of this challenge is to train a neural network image classifier to detect the presence of pneumonia in chest x-ray images. In doing so, we hope to learn about your data analysis and interpretation skills and your understanding of the fundamentals of deep learning.

This repository contains some template code and the necessary data to complete the challenge. The template is implemented using PyTorch, but you are free to use whichever framework(s) you like. There will be a period of two weeks to complete the challenge, after which we will assess your results and report.

## Dataset

The data directory for this challenge has the following structure:

```
data
├── test
│   ├── NORMAL
│   └── PNEUMONIA
├── train
│   ├── NORMAL
│   └── PNEUMONIA
└── val
    ├── NORMAL
    └── PNEUMONIA
```

The x-ray images are classified as either NORMAL or PNEUMONIA, according to the directory they are contained in. Please refer to the notebook ```challenge.ipynb```, containing code for loading the data into PyTorch ```DataLoader``` objects, which can be used to iterate through the dataset in training, validation and testing.

## Instructions

Please begin by forking this repository, such that any changes you make will be stored on your own copy.

Your task is to improve upon the performance of the baseline model, along with supplying brief explanations and evidence for the changes you have made.

At the end of the evaluation period, please push any code, documentation, plots/graphs, and other materials to your forked repository, along with a short description of your process and findings in the Report section of this readme.

## Report

[To be filled in by candidate]
