# Improved vector quantized diffusion models

## Summary

Summary: The paper proposes two techniques to improve the sample quality of Vector quantized diffusion (VQ-Diffusion) in text-to-image synthesis. It explores a more general and effective implementation of the classiﬁer-free guidance sampling for discrete denoising diffusion model and presents a high-quality inference strategy to alleviate the joint distribution issue. The experiments on various datasets validate the effectiveness of the proposed techniques and show that the improved VQ-Diffusion outperforms the vanilla version by a large margin.


## Target Task

nlp

## Content

<Abstract: > Vector quantized diffusion (VQ-Diffusion) is a powerful generative model for text-to-image synthesis, but sometimes can still generate low-quality samples or weakly correlated images with text input. We ﬁnd these issues are mainly due to the ﬂawed sampling strategy. In this paper, we propose two important techniques to further improve the sample quality of VQ-Diffusion. 1) We explore classiﬁer-free guidance sampling for discrete denoising diffusion model and propose a more general and effective implementation of classiﬁer-free guidance. 2) We present a high-quality inference strategy to alleviate the joint distribution issue in VQ-Diffusion. Finally, we conduct experiments on various datasets to validate their effectiveness and show that the improved VQ-Diffusion suppresses the vanilla version by large margins.



---

