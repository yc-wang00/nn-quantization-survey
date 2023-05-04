# Effective quantization approaches for recurrent neural networks

## Summary

Summary: This paper proposes effective quantization approaches such as Binary, Ternary and Quaternary Connect for RNN approaches, along with LSTM, GRU, and ConvLSTM techniques. These approaches are evaluated on different datasets for sentiment analysis and video frame prediction and compared against full precision versions, showing promising results.


## Target Task

any task

## Content

<Abstract:>
Deep learning approaches have shown superior accuracy in different application domains; however, they are very expensive in terms of computation. Recurrent Neural Networks (RNNs) are particularly expensive, as they are used in a large variety of tasks, including machine translation, language understanding, and movie frames generation. To address this issue, researchers have proposed energy-efficient RNN approaches for deploying solutions on special-purpose hardware. This paper proposes several effective quantization approaches, including Binary Connect {-1,1}, Ternary Connect {-1,0,1}, and Quaternary Connect {-1,-0.5,0.5,1}, for RNN techniques such as Long Short Term Memory (LSTM), Gated Recurrent Units (GRU), and Convolutional Long Short Term Memory (ConvLSTM). These proposed approaches are evaluated on different datasets for sentiment analysis on IMDB and on video frame predictions on the moving MNIST dataset, and are compared against the full precision versions of the LSTM, GRU, and ConvLSTM. The experimental results show promising results for both sentiment analysis and video frame prediction.



---

