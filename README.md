# Natural Language Processing
This is a repo with some small projects on Natural Language Processing using Python.

## Featured Notebooks
- [Sentiment Analysis RoBERTa vs VADER](https://github.com/brenoingwersen/natural-language-processing/blob/main/amazon-reviews-roberta-vader.ipynb)\
*Date Created: Jan-2023*\
Comparisson on Amazon reviews between NLTK VADER and Twitter-RoBERTa-sentiment.

- [BART infilling masking scheme](https://github.com/brenoingwersen/natural-language-processing/blob/main/DataCollatorForInfillingMask.ipynb)\
*Date Created: Sep-2023*\
Custom Data Collator based on the original [facebook/BART article](https://arxiv.org/pdf/1910.13461.pdf).

- [LinkedIn job posts summarization](https://github.com/brenoingwersen/natural-language-processing/blob/main/linkedin-jobs-summarization-bart.ipynb)\
*Date Created: Oct-2023*\
Attempting to summarize LinkedIn jobs' descriptions to its respective titles using the [LinkedIn dataset](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings) using the transformer encoder-decoder pretrained [model BART](https://arxiv.org/abs/1910.13461).\
Note: unfortunately due to low resources the finetune couldn't be run even with hyperparameters tunning such as *batch size*, *max sequence length* and *gradient accumulation*.

## Testing stuff
- [Bag of Words](https://github.com/brenoingwersen/natural-language-processing/blob/main/simple-bow-classifier.ipynb)\
*Date Created: Dec-2022*\
First contact with NLP: Testing a simple linear SVC (SVM with 'linear' kernel) classifier with BoW (Bag of words) and Spacy's word vectors.

## Interesting Links
- [Natural Language Processing Tutorials - Github](https://github.com/ujjwalkarn/Machine-Learning-Tutorials#nlp)
