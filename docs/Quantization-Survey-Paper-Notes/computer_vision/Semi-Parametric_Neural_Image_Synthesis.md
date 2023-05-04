# Semi-Parametric Neural Image Synthesis

## Summary

Summary: The paper proposes a semi-parametric approach to generative image synthesis by combining diffusion or autoregressive models with a separate image database and retrieval strategy. The model is conditioned on nearest neighbors retrieved from the external database during training, providing content information, and focused on learning scene composition. The approach transfers a trained model to a novel domain by replacing the database for one with different contents without requiring paired text-image data. The method reduces the parameter count of the generative model and outperforms the state-of-the-art with negligible memory and computational overhead for the external database and retrieval.


## Target Task

computer vision

## Content

<Abstract: >Our work proposes a semi-parametric approach to generative image synthesis, complementing diffusion or autoregressive models with a separate image database and retrieval strategy. During training, the generative model is conditioned on nearest neighbors retrieved from the external database, providing content information, while focusing on learning scene composition. Our approach transfers a trained model to a novel domain by swapping the database for one with different contents, performing competitively on tasks that the model was not trained on, such as class-conditional synthesis, zero-shot stylization or text-to-image synthesis, without requiring paired text-image data. Our method significantly reduces the parameter count of the generative model and outperforms the state-of-the-art, with negligible memory and computational overhead for the external database and retrieval.



---

