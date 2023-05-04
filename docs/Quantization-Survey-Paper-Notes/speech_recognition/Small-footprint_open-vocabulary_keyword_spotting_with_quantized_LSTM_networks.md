# Small-footprint open-vocabulary keyword spotting with quantized LSTM networks

## Summary

<Summary: > The paper presents an open-vocabulary keyword spotting technique using a quantized LSTM neural network trained with CTC. The model is lightweight, weighing less than 500KB and can run on tiny devices. It can handle any user-defined keywords and does not require specific training data for them. The confidence scores are calibrated using predictions of CTC-trained networks and a fast detection algorithm is implemented. The proposed system performs better than standard keyword-filler models.


## Target Task

speech recognition

## Content

<Abstract: > We present a small-footprint, open-vocabulary keyword spotting method based on a quantized long short-term memory (LSTM) neural network trained with connectionist temporal classification (CTC). Our approach is designed to be able to run on tiny devices and handle any arbitrary set of user-defined keywords without requiring training data specific to those keywords. The model weighs less than 500KB and takes advantage of some properties of the predictions of CTC-trained networks to calibrate the confidence scores and implement a fast detection algorithm. Our proposed system outperforms standard keyword-filler models.



---

