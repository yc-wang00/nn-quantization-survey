# Up or down? adaptive rounding for post-training quantization

## Summary

Summary: 
This paper presents AdaRound, a weight-rounding mechanism for post-training quantization that is adaptable to the data and task loss. The proposed method outperforms the predominant approach of rounding weights to the nearest fixed-point value and achieved a new state-of-the-art for post-training quantization on several networks and tasks. The method is fast and does not require fine-tuning of the network, and only uses a small amount of unlabelled data. The weights of Resnet18 and Resnet50 can be quantized to 4 bits without fine-tuning while staying within an accuracy loss of 1%.


## Target Task

computer vision

## Content

<Abstract: >
When quantizing neural networks, assigning each ﬂoating-point weight to its nearest ﬁxed-point value is the predominant approach. We ﬁnd that, perhaps surprisingly, this is not the best we can do. In this paper, we propose AdaRound, a better weight-rounding mechanism for post-training quantization that adapts to the data and the task loss. AdaRound is fast, does not require fine-tuning of the network, and only uses a small amount of unlabelled data. AdaRound not only outperforms rounding-to-nearest by a significant margin but also establishes a new state-of-the-art for post-training quantization on several networks and tasks. Without ﬁne-tuning, we can quantize the weights of Resnet18 and Resnet50 to 4 bits while staying within an accuracy loss of 1%.



---

