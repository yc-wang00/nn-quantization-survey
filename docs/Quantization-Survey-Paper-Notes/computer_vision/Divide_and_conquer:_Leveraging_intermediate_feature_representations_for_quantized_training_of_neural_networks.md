# Divide and conquer: Leveraging intermediate feature representations for quantized training of neural networks

## Summary

Summary: The paper presents a new knowledge distillation approach called Divide and Conquer Quantization (DCQ) for quantized training of neural networks. The algorithm divides a pretrained full-precision DNN into multiple sections, and trains each section independently in the quantized domain. DCQ improves the performance of DoReFa-Net by 21.6% and 9.3% for binary and ternary quantization. The divide and conquer strategy offers additional speedup through enabling parallelization, and all sections are later stitched together to form the fully quantized network.


## Target Task

computer vision

## Content

<Abstract: >
The paper presents a new approach towards knowledge distillation through teacher-student paradigm, called Divide and Conquer Quantization (DCQ), for quantized training of neural networks. The algorithm harvests rich intermediate representations from the deep layers of a DNN for quantization. It divides a pretrained full-precision DNN to multiple sections, each of which exposes intermediate features to train a team of students independently in the quantized domain. Experiments on various DNNs show that DCQ improves the performance of a state-of-the-art quantized training technique, called DoReFa-Net, by 21.6% and 9.3% for binary and ternary quantization, respectively. The paper proposes a divide and conquer strategy, which makes the training of each student section possible in isolation, offering additional speedup through enabling parallelization, while all these independently trained sections are later stitched together to form the equivalent fully quantized network.



---

