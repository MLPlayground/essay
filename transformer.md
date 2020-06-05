# Transformer

Transformer is a ground breaking machine learning model for NLP tasks, or more generally, sequence to sequence (Seq2Seq) learning tasks.

For Seq2Seq learning, RNN/LSTM is popular before transformer is introduced. Similar to RNN/LSTM for Seq2Seq learning, Transformer also use the Encoder-Decoder framework. However, Transformer has the following advantages over RNN/LSTM:

- attention mechanism over the whole input sequence
- multi-head attention can capture multiple types of attention
- faster training because of parallelization (no more sequential, no more recurrent) of the (part of) encoder and decoder
- transfer learning made possible through pre-training and fine-tuning
