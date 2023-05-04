# Training quantized nets: A deeper understanding

## Summary

Summary: This paper discusses the current method of deploying deep neural networks on low-power portable devices and suggests training models directly with coarsely quantized weights as a key step towards learning on embedded platforms. The authors investigate training methods for quantized neural networks from a theoretical viewpoint, exploring both accuracy guarantees for training methods under convexity assumptions and the behavior of these algorithms for non-convex problems. The authors show that training algorithms that exploit high-precision representations have an important greedy search phase that purely quantized training methods lack, which explains the difficulty of training using low-precision arithmetic.


## Target Task

computer vision

## Content

<Abstract: >Currently, deep neural networks are deployed on low-power portable devices by ﬁrst training a full-precision model using powerful hardware, and then deriving a corresponding low-precision model for efﬁcient inference on such systems. However, training models directly with coarsely quantized weights is a key step towards learning on embedded platforms that have limited computing resources, memory capacity, and power consumption. Numerous recent publications have studied methods for training quantized networks, but these studies have mostly been empirical. In this work, we investigate training methods for quantized neu-ral networks from a theoretical viewpoint. We ﬁrst explore accuracy guarantees for training methods under convexity assumptions. We then look at the behavior of these algorithms for non-convex problems, and show that training algorithms that exploit high-precision repre-sentations have an important greedy search phase that purely quantized training methods lack, which explains the difﬁculty of training using low-precision arithmetic.



---

