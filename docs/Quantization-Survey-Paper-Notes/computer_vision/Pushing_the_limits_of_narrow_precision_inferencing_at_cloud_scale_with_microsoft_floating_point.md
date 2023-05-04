# Pushing the limits of narrow precision inferencing at cloud scale with microsoft floating point

## Summary

Summary: The paper explores the effectiveness of Microsoft Floating Point (MSFP) as a datatype for cloud-scale inferencing on custom hardware. MSFP16 incurs 3% lower cost compared to Bﬂoat16 and MSFP12 has 4% lower cost compared to INT8 while delivering similar or better accuracy. It supports various deep learning models without modification, incurs negligible impact on accuracy, and can be integrated with a mature cloud production pipeline. The study demonstrates MSFP's effectiveness on production scenarios, including web search, question-answering, and image classification.


## Target Task

computer vision

## Content

<Abstract: 
In this paper, we explore the limits of Microsoft Floating Point (MSFP), a new class
of datatypes developed for production cloud-scale inferencing on custom hardware.
Through the co-evolution of hardware design and algorithms, MSFP16 incurs 3 
lower cost compared to Bﬂoat16 and MSFP12 has 4 lower cost compared to INT8
while delivering a comparable or better accuracy. MSFP incurs negligible impact to
accuracy (<1%), requires no changes to the model topology, and is integrated with a
mature cloud production pipeline. MSFP supports various classes of deep learning
models including CNNs, RNNs, and Transformers without modiﬁcation. Finally,
we characterize the accuracy and implementation of MSFP and demonstrate its
efﬁcacy on a number of production scenarios, including models that power major
online scenarios such as web search, question-answering, and image classiﬁcation.>



---

