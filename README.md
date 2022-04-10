# Deep_Learning_2_NLP
Repository for the NLP part of assignment 2 of the Deep Learning course.

For this part of the assignment news articles are classified in 4 different categories (world, sport, business and science), using a pretrained and from scratch trained DistilBERT model. For this task the [AG News Classification Dataset](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset) is used.

## Before running the code

First of all, make sure python is installed.
Secondly, install the required packages using the following command:

```bash
pip3 install -r requirements.txt
```

## Running the data analysis
To run the data analyis, open the `data_analysis.ipynb` jupyter notebook and execute the cells in order.

This script will analyze the dataset and provide some plots.

## Running the training and testing NLP
The code for the training and testing for the pretrained and scratch trained model is also done in a jupyter notebook.
Namely, in the `DL_Lab2_NLP.ipynb` jupyter notebook. The code can be run by opening the notebook and executing each cell in order.

With this script a pretrained model is finetuned, and a model with the same architecture is trained from scratch. The models will also be saved for later use.
Furthermore, testing is performed on these models so their performance can be compared.





