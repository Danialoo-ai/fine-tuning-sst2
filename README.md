# Fine-Tuning BERT for Sentiment Analysis with LoRA
This project demonstrates how to fine-tune a pre-trained __BERT model__ for a sentiment analysis task using the __Stanford Sentiment Treebank v2 (SST-2)__ dataset. To make the fine-tuning process more efficient, this implementation uses __Low-Rank Adaptation (LoRA)__, a Parameter-Efficient Fine-Tuning (PEFT) technique from the Hugging Face ***peft*** library.

The goal is to classify sentences as having either a positive (1) or negative (0) sentiment.

# Key Features
__Model__: ***bert-base-uncased*** from the Hugging Face Hub.

__Dataset__: SST-2, a popular benchmark for sentiment analysis.

__Efficient Fine-Tuning__: Implements LoRA to significantly reduce the number of trainable parameters, making the training process faster and less memory-intensive.

__Libraries__: Built using the Hugging Face ecosystem, including ***transformers***, ***datasets***, ***evaluate***, and ***peft***.
