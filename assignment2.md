# Readme

## Requirements
1. kaggle.json. Put this file under /content, then run data import section. It will download the dataset from the kaggle.
2. train.csv, val.csv, test_without_labels.csv. Put these 3 file under /content. (You only need to upload the 3 files when step1 doesn't work, because step 1 will download dataset)
3. youtube_parsed_dataset.csv. This file would be used in domain feature training

## Test different combination
We tested 11 different combinations
1. baseline(modified from Lab9)
2. FastText word embedding
3. FastText + POS word embedding
4. FastText + POST + Domain word embedding
5. Dot product Attention
6. Scaled Dot product Attention
7. Bahdanau Attention
8. 1 Layer Stack
9. 2 Layer Stacks
10. With CRF
11. Without CRF

## Run the whole code in the ipnb notebook
Simply run the whole code, and the test part allow you to adjust different parameters
