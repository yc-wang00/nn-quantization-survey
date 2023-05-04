# Deep compression: Compressing deep neural networks with pruning, trained quantization and huffman coding

## Summary

<Summary:> 

This paper proposes a three-stage pipeline called "deep compression" to reduce the storage requirement of neural networks between 35% and 49% without affecting their accuracy. The method involves pruning the network by learning only important connections, quantizing the weights by enforcing weight sharing, and applying Huffman coding. The retrained network fine-tuned the remaining connections and quantized centroids without a loss of accuracy. The method was applied to the AlexNet and VGG-16 models, reducing their storage requirement effectively, enabling the model to fit into on-chip SRAM caches.


## Target Task

computer vision

## Content

<Abstract: >Neural networks are computationally and memory intensive, making them difficult to deploy on hardware systems with limited resources. To address this issue, we introduce a three-stage pipeline called "deep compression" that can reduce the storage requirement of neural networks by between 35% and 49% without affecting their accuracy. Our method involves pruning the network by learning only important connections, quantizing the weights to enforce weight sharing, and applying Huffman coding. After pruning and quantizing, we retrain the network to fine-tune the remaining connections and quantized centroids. On the ImageNet dataset, our method reduced the storage required by AlexNet by 35%, from 240MB to 6.9MB, and reduced the size of VGG-16 by 49%, from 552MB to 11.3MB, with no loss of accuracy. This allows fitting the model into on-chip SRAM cache rather than off-chip DRAM memory.



---

