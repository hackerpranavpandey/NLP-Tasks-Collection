# DataBricks-LLM-Course---NLP-Tasks
In this repos I have build some nice NLP projects while exploring a course on LLM Applications

Implemented text summarizer, sentiment analysis, translation, zero-shot classification, few-shot learning

All these datasets and model pipeline has been impelmented using Hugging Face API calls load_dataset and transformers
# Datasets used:-
1)-xsum, version=1.2.0 #

2)-poem-sentiment, version=1.0.0


# Models used:-

Text Summarizer - t5-small

Sentiment Analysis -  nickwong64/bert-base-uncased-poems-sentiment

Translation- Helsinki-NLP/opus-mt-en-es 

Zero Shot Classification- zero-shot-classification

Few Shot Learning- EleutherAI/gpt-neo-1.3B

Also implemented searching and sampling optimization using num_beams, do_samples,top_k,top_p features available in the pipeline

## Also implemented the concept of tokenization,encoder,decoder.

Used AutoTokenizer as well ad t5-small
