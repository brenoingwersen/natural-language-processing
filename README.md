# Natural Language Processing
This is a repo with some small projects on Natural Language Processing using Python.

## Featured Notebooks
- [Making Transformers Efficient in Production](https://github.com/brenoingwersen/natural-language-processing/blob/main/efficient-transformers-clinc150.ipynb)\
*Date Created: Oct-2023*\
Fine-tune BERT for a multiclass classification problem using the [Clinc150 dataset](https://www.kaggle.com/datasets/hongtrung/clinc150-dataset). The objective of this notebook is to fine-tune the BERT model with a classification head and further improving the model performance by applying techniques:
  - **Knowledge distillation**.
  - **Model quantization**.

- [LinkedIn job posts summarization](https://github.com/brenoingwersen/natural-language-processing/blob/main/linkedin-jobs-summarization-bart.ipynb)\
*Date Created: Oct-2023*\
Fine-tune [BART-Base](https://arxiv.org/abs/1910.13461) for sumarization task using the [LinkedIn dataset](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings).\
The objective of this notebook is to fine-tune the *encoder-decoder* model **BART** to generate the jobs' titles based on their description. Some key features of this notebook include:
  - Preprocessing of job titles (missing values, duplicates and handling of special characters)
  - Quick EDA (char and word counts)
  - Training using **mixed precision fp16** and **8-bit Adam optimizer** to optimize GPU memory consumption and training time.
  - Evaluation with **ROUGE** metric.

- [Sentiment Analysis RoBERTa vs VADER](https://github.com/brenoingwersen/natural-language-processing/blob/main/amazon-reviews-roberta-vader.ipynb)\
*Date Created: Jan-2023*\
Comparisson on Amazon reviews between NLTK VADER and Twitter-RoBERTa-sentiment.

- [BART infilling masking scheme](https://github.com/brenoingwersen/natural-language-processing/blob/main/DataCollatorForInfillingMask.ipynb)\
*Date Created: Sep-2023*\
Custom Data Collator based on the original [facebook/BART article](https://arxiv.org/pdf/1910.13461.pdf).

## Testing stuff
- [Recurrent Neural Nets from scratch](https://github.com/brenoingwersen/natural-language-processing/blob/main/RNN_from_scratch.ipynb)\
*Date Created: Oct-2023*\
Based on the book by Jeremy Howard - [Deep Learning for Coders with FastAI and PyTorch ([Book Link](https://www.amazon.com/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527)). This is a test notebook to implement RNNs from scratch using PyTorch components to create basic language models that predict the next token of a sequence based on the provided context. Nothing fancy.

- [Bag of Words](https://github.com/brenoingwersen/natural-language-processing/blob/main/simple-bow-classifier.ipynb)\
*Date Created: Dec-2022*\
First contact with NLP: Testing a simple linear SVC (SVM with 'linear' kernel) classifier with BoW (Bag of words) and Spacy's word vectors.

## Interesting Links
- [Natural Language Processing Tutorials - Github](https://github.com/ujjwalkarn/Machine-Learning-Tutorials#nlp)

## Free NLP Courses <img width=30 src="https://github.com/brenoingwersen/natural-language-processing/assets/58577881/213c7080-818b-48f8-a4d1-1722d86b6af5" style="vertical-align:middle">
- [Efficient Deep Learning Models in Production](https://www.youtube.com/watch?v=rCFvPEQTxKI)\
Course offered by MIT HAN Lab about methods to reduce computational costs of deeplearning models on production stage.
