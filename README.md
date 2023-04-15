# Custom NER for Healthcare

## Problem Statement:
A dataset was provided containing a corpus of medical text. The text includes diseases and their treatments mentioned implicitly, making it difficult for a layperson to understand. For instance, "The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy." Here, the patient is said to have cancer that was treated using radiation therapy and chemotherapy.

To make this information accessible to everyone, the aim was to build a supervised Named Entity Recognition (NER) model. This model would learn to extract and display viable treatment options for a given disease, making it easier for people to understand and access relevant medical information.

## Table of Contents
- General Information
- [Datasets](#datasets)
- [Usage](#usage)
- [Requirements](#requirements)
- [Installation](#installation)

## Description



## Datasets

The datasets used in this project is as follows:

- `train_sent`: containing 2,599 sentences in the medical domain
- `test_sent`: containing 1,056 sentences in the medical domain
- `train_label`: containing labels corresponding to the words in `train_sent`
- `test_label`: containing labels corresponding to the words in `test_sent`



