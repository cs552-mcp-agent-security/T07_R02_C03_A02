# Tutorial notebooks index

| # | Title | Architecture | Concepts introduced |
|---|-------|--------------|---------------------|
| 1 | Neural Bag of Words | Embedding average + linear | Word embeddings, basic preprocessing |
| 2 | Recurrent Neural Networks | LSTM | Sequence modelling, padded batches |
| 3 | Convolutional Neural Networks | TextCNN | 1D conv over embeddings |
| 4 | Transformers | Encoder stack | Self-attention, positional embeddings |
| 5 | Multi-class Sentiment Analysis | LSTM on TREC-style data | Multi-class loss, label balancing |
| 6 | Pretrained Transformers | Fine-tuned BERT | Transfer learning, scheduler warmup |

The dataset for notebooks 1-4 and 6 is the IMDb movie-review corpus (25,000 train /
25,000 test, binary positive/negative). Notebook 5 uses a multi-class question-type
dataset.
