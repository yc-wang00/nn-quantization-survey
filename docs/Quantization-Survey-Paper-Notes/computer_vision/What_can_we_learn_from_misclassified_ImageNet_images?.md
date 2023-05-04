# What can we learn from misclassified ImageNet images?

## Summary

Summary: The paper proposes a Superclassing ImageNet dataset, a subset of ImageNet, to help find patterns of misclassification. It is found that misclassifications are mainly among subclasses within a superclass. A two-stage Super-Sub framework is proposed which improves overall classification performance and reduces parameter storage cost using delta and quantization aware training techniques. This framework is more scalable and generalizable than simply scaling up a vanilla network in size.


## Target Task

computer vision

## Content

<Abstract: Understanding the patterns of misclassiﬁed ImageNet images is particularly important, as it could guide us to design deep neural networks (DNN) that generalize better. However, the richness of ImageNet imposes difﬁculties for researchers to visually ﬁnd any useful patterns of misclassiﬁcation. Here, to help ﬁnd these patterns, we propose "Superclassing ImageNet dataset". It is a subset of ImageNet which consists of 10 superclasses, each containing 7-116 related subclasses (e.g., 52 bird types, 116 dog types). By training neural networks on this dataset, we found that: (i) Misclassiﬁcations are rarely across superclasses, but mainly among subclasses within a superclass. (ii) Ensemble networks trained each only on subclasses of a given superclass perform better than the same network trained on all subclasses of all superclasses. Hence, we propose a two-stage Super-Sub framework, and demonstrate that: (i) The framework improves overall classiﬁcation performance by 3.3%, by ﬁrst inferring a superclass using a generalist superclass-level network, and then using a specialized network for ﬁnal subclass-level classiﬁcation. (ii) Although the total parameter storage cost increases to a factor N+ 1forNsuper-classes compared to using a single network, with ﬁnetuning, delta and quantization aware training techniques this can be reduced to 0:2N+ 1. Another advantage of this efﬁcient implementation is that the memory cost on the GPU during inference is equivalent to using only one network. The reason is we initiate each subclass-level network through addition of small parameter variations (deltas) to the superclass-level network. (iii) Finally, our framework promises to be more scalable and generalizable than the common alternative of simply scaling up a vanilla network in size, since very large networks often suffer from overﬁtting and gradient vanishing.>



---

