# 24ADI006_24BAD020_EXP-09
# Experiment No. 9: Text Classification and Text Generation Using Transformers

##  Aim
To implement text classification by fine-tuning a pretrained BERT model and develop a sequence-to-sequence text generation application using the pretrained T5-small Transformer model.

##  Introduction
Transformers are deep learning models used in Natural Language Processing (NLP). They use attention mechanisms to understand relationships between words in text.

In this experiment, BERT is used for text classification, and T5-small is used for text generation. The IMDb movie review dataset is used to classify reviews as positive or negative.

##  Parts of the Experiment

### Part A: Dataset Preparation and Text Preprocessing
- Load the IMDb movie review dataset.
- Explore sample reviews and their labels.
- Analyze the class distribution.
- Load the pretrained BERT tokenizer.
- Tokenize the text using padding and truncation.
- Prepare the dataset for model training.

### Part B: Fine-Tuning BERT for Text Classification
- Load the pretrained BERT model.
- Configure it for positive and negative sentiment classification.
- Fine-tune the model using training data.
- Evaluate its performance using accuracy, precision, recall, and F1-score.
- Predict sentiment for new reviews.
- Save the fine-tuned model and tokenizer.

### Part C: Sequence-to-Sequence Text Generation
- Load the pretrained T5-small model and tokenizer.
- Prepare sample paragraphs for summarization.
- Generate summaries using the Transformer model.
- Experiment with beam search and maximum output length.
- Save the generated outputs.

### Part D: Model Testing and Output Analysis
- Test BERT using positive and negative reviews.
- Record the predicted sentiment labels.
- Evaluate the classification performance.
- Test T5-small using different input paragraphs.
- Compare the generated summaries.
- Analyze the relevance, readability, and coherence of the outputs.

##  Dataset Used
**IMDb Movie Reviews Dataset**

The dataset contains movie reviews labelled as:
- 0 – Negative
- 1 – Positive

Dataset link: https://huggingface.co/datasets/stanfordnlp/imdb

##  Models Used

**BERT (bert-base-uncased):** Used for sentiment classification by fine-tuning a pretrained Transformer model.

Model link: https://huggingface.co/google-bert/bert-base-uncased

**T5-small:** Used for sequence-to-sequence text generation, particularly text summarization.

Model link: https://huggingface.co/google-t5/t5-small

##  Evaluation Metrics
- **Accuracy:** Measures the proportion of correctly classified samples.
- **Precision:** Measures how many positive predictions are correct.
- **Recall:** Measures how many actual positive samples are correctly identified.
- **F1-score:** Represents the harmonic mean of precision and recall.

##  Expected Output
- Sample IMDb reviews and class distribution.
- Tokenized text and attention masks.
- BERT training progress and classification metrics.
- Predicted sentiment labels for new reviews.
- Generated text summaries from T5-small.
- Comparison of classification and text generation outputs.
- CSV files containing prediction results and generated summaries.

##  Result
The experiment demonstrates text classification using a fine-tuned BERT model and text generation using a pretrained T5-small model. The classification model predicts positive or negative sentiment, while the generation model produces summaries from input paragraphs. Both models are tested, and their outputs are analyzed.

##  Conclusion
Transformer models are useful for different NLP tasks. BERT effectively performs text classification, while T5-small performs sequence-to-sequence text generation. This experiment provides practical knowledge of text preprocessing, model fine-tuning, evaluation metrics, and Transformer-based text generation.
