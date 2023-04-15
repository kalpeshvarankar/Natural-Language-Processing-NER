# Custom NER for Healthcare

This project is designed to enhance your knowledge on Name Entity Recognition (NER) and its applications in healthcare. In this project, you will learn how to build a custom NER to extract disease names and their treatments from medical datasets.

## Table of Contents
- [Description](#description)
- [Datasets](#datasets)
- [Usage](#usage)
- [Requirements](#requirements)
- [Installation](#installation)

## Description

In this project, you will be working with four datasets: `train_sent`, `test_sent`, `train_label`, and `test_label`. The `train_sent` and `test_sent` datasets contain individual words that form sentences in the medical domain, and the `train_label` and `test_label` datasets contain corresponding labels for each word in the `train_sent` and `test_sent` datasets. Your task is to build a custom NER model that can extract disease names and their treatments from these datasets.

## Datasets

The datasets used in this project are as follows:

- `train_sent`: contains 2,599 sentences in the medical domain
- `test_sent`: contains 1,056 sentences in the medical domain
- `train_label`: contains labels corresponding to the words in `train_sent`
- `test_label`: contains labels corresponding to the words in `test_sent`

## Usage

To use this project, follow these steps:

1. Clone this repository
2. Install the required packages (see Requirements section)
3. Run the `main.py` script to train and evaluate the custom NER model

## Requirements

To run this project, you will need to install the following packages:

- Python 3.x
- pandas
- sklearn
- nltk

## Installation

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
