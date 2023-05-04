# Deep asymmetric hashing with dual semantic regression and class structure quantization

## Summary

<Summary: > This paper proposes a dual semantic asymmetric hashing (DSAH) method for generating discriminative hash codes that utilizes class prior to conduct class structure quantization, a label mechanism for characterizing inter-class separability, and a pairwise similarity preserving loss for minimizing the distances between class-related network outputs based on an affinity graph. The proposed method has demonstrated superior performance in comparison with state-of-the-art deep hashing methods in various data sets.


## Target Task

computer vision

## Content

Abstract: Recently, deep hashing methods have been widely used in image retrieval task. Most existing deep hashing approaches adopt one-to-one quantization to reduce information loss. However, such class-unrelated quantization cannot give discriminative feedback for network training. In addition, these methods only utilize single label to integrate supervision information of data for hashing function learning, which may result in inferior network generalization performance and relatively low-quality hash codes since the inter-class information of data is totally ignored. In this paper, we propose a dual semantic asymmetric hashing (DSAH) method, which generates discriminative hash codes under three-fold constraints. Firstly, DSAH utilizes class prior to conduct class structure quantization so as to transmit class information during the quantization process. Secondly, a simple yet effective label mechanism is designed to characterize both the intra-class compactness and inter-class separability of data, thereby achieving semantic-sensitive binary code learning. Finally, a meaningful pairwise similarity preserving loss is devised to minimize the distances between class-related network outputs based on an affinity graph. With these three main components, high-quality hash codes can be generated through network. Extensive experiments conducted on various data sets demonstrate the superiority of DSAH in comparison with state-of-the-art deep hashing methods. Keywords: Asymmetric hashing, dual semantic regression, class structure quantization.



---

