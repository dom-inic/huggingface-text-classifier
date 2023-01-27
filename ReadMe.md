# Text Classification Model

This repository contains a text classification model that uses the Hugging Face library and the Amazon review dataset to identify whether a review is helpful or not.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Hugging Face library
- Pytorch
- pandas
- numpy
- Transformers
- sklearn

### Installation

Clone this repository and install the required libraries on the requirements.txt file:

git clone https://github.com/dom-inic/huggingface-text-classifier.git
cd huggingface-text-classifier
pip install -r requirements.txt

Download distilbert-base-uncased model
install git lfs
cd distilbert-base-uncased
git lfs pull 

## Training the model
you can train the model using code available on the ipynb file as well as evaluate the preformance of the model. 

## Dataset

The Amazon review dataset used to train the model contains a combination of helpful and not helpful reviews. The dataset is preprocessed and can be found in the `data` folder.


