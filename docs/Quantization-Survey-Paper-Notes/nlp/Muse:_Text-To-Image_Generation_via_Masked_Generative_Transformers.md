# Muse: Text-To-Image Generation via Masked Generative Transformers

## Summary

Summary: The paper presents Muse, a text-to-image Transformer model that uses a masked modeling task in discrete token space to predict randomly masked image tokens. The model is more efficient than diffusion or autoregressive models and achieves state-of-the-art image generation performance, with an FID score of 6.06 on CC3M and an FID of 7.88 on zero-shot COCO evaluation. Additionally, Muse enables image editing applications such as inpainting, outpainting, and mask-free editing without the need for fine-tuning or inverting the model.


## Target Task

nlp

## Content

<Abstract: > We present Muse, a text-to-image Transformer model that achieves state-of-the-art image generation performance while being significantly more efficient than diffusion or autoregressive models. Muse is trained on a masked modeling task in discrete token space: given the text embedding extracted from a pre-trained large language model (LLM), Muse is trained to predict randomly masked image tokens. Our 900M parameter model achieves a new SOTA on CC3M, with an FID score of 6.06. The Muse 3B parameter model achieves an FID of 7.88 on zero-shot COCO evaluation, along with a CLIP score of 0.32. Muse also directly enables a number of image editing applications without the need to fine-tune or invert the model: inpainting, outpainting, and mask-free editing.



---

