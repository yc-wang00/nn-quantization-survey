# Deep neural network for respiratory sound classification in wearable devices enabled by patient specific model tuning

## Summary

<Summary: > The paper proposes a deep CNN-RNN model that classifies respiratory sounds based on Mel-spectrograms, along with a patient-specific model tuning strategy for reliable anomaly detection. A local log quantization strategy is suggested to reduce the memory footprint while deploying on memory-constrained systems. The proposed model achieves state-of-the-art score on the ICBHI’17 dataset, and the patient-specific re-training strategy can be useful for wearable healthcare solutions.


## Target Task

speech recognition

## Content

<Abstract: >The primary objective of this paper is to build
classiﬁcation models and strategies to identify breathing sound
anomalies (wheeze, crackle) for automated diagnosis of respiratory and pulmonary diseases. In this work we propose a deep CNN-RNN model that classiﬁes respiratory sounds based on Mel-spectrograms. We also implement a patient speciﬁc model tuning strategy that ﬁrst screens respiratory patients and then builds patient speciﬁc classiﬁcation models using limited patient data for reliable anomaly detection. Moreover, we devise a local log quantization strategy for model weights to reduce the memory footprint for deployment in memory constrained systems such as wearable devices. The proposed hybrid CNN-RNN model achieves a score of 66:31% on four-class classiﬁcation of breathing cycles for ICBHI’17 scientiﬁc challenge respiratory sound database. When the model is re-trained with patient speciﬁc data, it produces a score of 71:81% for leave-one-out validation. The proposed weight quantization technique achieves 4reduction in total memory cost without loss of performance. The main contribution of the paper is as follows: Firstly, the proposed
model is able to achieve state of the art score on the ICBHI’17 dataset. Secondly, deep learning models are shown to successfully learn domain speciﬁc knowledge when pre-trained with breathing data and produce signiﬁcantly superior performance compared to generalized models. Finally, local log quantization of trained weights is shown to be able to reduce the memory requirement signiﬁcantly. This type of patient-speciﬁc re-training strategy can be very useful in developing reliable long-term automated patient monitoring systems particularly in wearable healthcare solutions.



---

