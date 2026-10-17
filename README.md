# NLP and Text Analytics

Sentiment classification, Tamil moderation data, text features and language-processing exercises.

| Notebook | What it covers | Stage |
| --- | --- | --- |
| [07_tamil_moderation_dataset_export.ipynb](07_tamil_moderation_dataset_export.ipynb) | Load a Tamil hate-speech dataset and export its splits to CSV for moderation research. | Data preparation |
| [24_airline_sentiment_lstm.ipynb](24_airline_sentiment_lstm.ipynb) | Tweet tokenization, embeddings, LSTM sequence classification and three sentiment labels. | Prototype |
| [32_character_encoding_and_reconstruction.ipynb](32_character_encoding_and_reconstruction.ipynb) | Character one-hot encoding and a small NumPy network trained by backpropagation. | Learning experiment |
| [42_text_features_and_viterbi_examples.ipynb](42_text_features_and_viterbi_examples.ipynb) | Text preprocessing, word/subword features, TF-IDF and Viterbi/POS-tagging exercises. | Learning experiment |
| [55_csv_text_preprocessing_and_word_statistics.ipynb](55_csv_text_preprocessing_and_word_statistics.ipynb) | CSV text loading, punctuation cleanup, token counts and unigram probabilities. | Learning experiment |

## Running these notebooks

NumPy, pandas and Python text-processing libraries. The sentiment model uses Keras; the dataset export uses Hugging Face Datasets. Provide each notebook's CSV/JSON input where referenced.

Open one notebook in Colab or Jupyter, read its setup cells, set the input paths, and then run the sections you need. Training and network operations are not run automatically by this repository.

The sentiment notebook's public copy uses a three-class softmax, sparse categorical cross-entropy and argmax decoding. It needs a new training run before reporting model performance.

## About this collection

These notebooks are organised from an existing Colab archive. The table identifies project experiments, prototypes and learning exercises. Dataset files and model weights are supplied separately. GPU training and external-data workflows were not rerun during preparation.

CSV text-processing checks and the NumPy character-reconstruction run passed on small local inputs.

[Browse all AI, ML and automation topics](https://github.com/captof-omuamua/Colab-AI-ML-Projects).

## Airline sentiment project

The [consolidated project guide](projects/airline-sentiment/README.md) brings the semester archive into this collection. Use [24_airline_sentiment_lstm.ipynb](24_airline_sentiment_lstm.ipynb) as the reviewed version; the earlier semester variant is preserved separately. Tweets.csv remains excluded because it contains user/location metadata.
