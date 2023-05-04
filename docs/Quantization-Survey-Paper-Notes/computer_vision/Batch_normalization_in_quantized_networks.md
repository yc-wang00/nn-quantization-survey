# Batch normalization in quantized networks

## Summary

<Summary: > This paper discusses the challenges with training quantized neural networks and highlights the important role of the batch normalization layer in preventing gradient explosion. The authors note that while there have been many studies on batch normalization in full-precision networks, there is a lack of research on its impact in quantized training. They show through experiments that batch normalization is crucial in avoiding gradient explosion.


## Target Task

computer vision

## Content

<Abstract: > Implementation of quantized neural networks on computing hardware leads to considerable speed
up and memory saving. However, quantized deep networks are d ifﬁcult to train and batch normal-
ization (BatchNorm) layer plays an important role in traini ng full-precision and quantized networks.
Most studies on BatchNorm are focused on full-precision net works, and there is little research in
understanding BatchNorm affect in quantized training whic h we address here. We show BatchNorm
avoids gradient explosion which is counter-intuitive and r ecently observed in numerical experiments
by other researchers.



---

