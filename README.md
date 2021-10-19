# Fine-Tuning Hugging Face Transformers for Text Classification

This tutorial is based on [Hugging Face course](https://huggingface.co/course).

[You can see the YouTube video recorded for this tutorial (Persian)](https://youtu.be/taAURowmzks)


## [Available transformer models on Hugging Face](https://huggingface.co/models)

`distilbert-base-uncased` is recommended, since it's faster than `bert-base-uncased` and offers a good performance. Also it was pretrained with the same corpus as BERT. This model is aimed at being **fine-tuned** for NLP tasks such as text classification, token classification, and question answering, for text generation you should go for models such as `gpt2`. [More information about this model is available here.](https://huggingface.co/distilbert-base-uncased)


## [Available datasets on Hugging Face](https://huggingface.co/datasets)

`sst2` from `glue` benchmark is used on this tutorial. It consists of sentences from movie reviews and human annotations of their sentiment. The task is to predict the sentiment of a given sentence. It uses the two-way (positive/negative) class split, with only sentence-level labels.