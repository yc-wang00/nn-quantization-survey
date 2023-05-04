# DQ-SGD: Dynamic quantization in SGD for communication-efficient distributed learning

## Summary

Summary: The paper proposes a novel dynamically quantized SGD (DQ-SGD) framework that addresses the lack of a systematic approach to dynamically quantize gradients. It adapts the quantization bits by taking into account the desired model performance, the remaining number of iterations, and the norm of gradients, and minimizes communication costs under convergence error constraints, while exploring the trade-off between communication cost and convergence error. Extensive experiments on large-scale natural language processing and computer vision tasks validate the theoretical analysis, showing that the proposed scheme outperforms the baseline quantization methods.


## Target Task

computer vision

## Content

<Abstract:> Gradient quantization is an emerging technique to reduce communication costs in distributed learning. The main challenge with existing gradient quantization algorithms is the lack of a systematic approach to dynamically quantize gradients. In this paper, we propose a novel dynamically quantized SGD (DQ-SGD) framework that allows us to adjust the quantization scheme dynamically for each gradient descent step. We minimize the communication cost under the convergence error constraints while exploring the trade-off between communication cost and convergence error. We derive an upper bound, tight in some cases, for the convergence error for a restricted family of quantization schemes and loss functions. Our DQ-SGD algorithm adapts the quantization bits by taking into account the desired model performance, the remaining number of iterations, and the norm of gradients. We validate our theoretical analysis through extensive experiments on large-scale natural language processing and computer vision tasks, and our proposed scheme outperforms the baseline quantization methods.



---

