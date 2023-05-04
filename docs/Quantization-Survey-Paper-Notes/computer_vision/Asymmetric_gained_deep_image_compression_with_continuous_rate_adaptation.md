# Asymmetric gained deep image compression with continuous rate adaptation

## Summary

<Summary: >This paper proposes a continuously rate adjustable learned image compression framework, Asymmetric Gained Variational Autoencoder (AG-VAE), which achieves discrete rate adaptation in a single model with negligible additional computation. Continuous rate adaptation is achieved by using exponential interpolation without performance compromise. The paper also introduces the asymmetric Gaussian entropy model for more accurate entropy estimation. The proposed method achieves comparable quantitative performance with State-Of-The-Art (SOTA) learned image compression methods and better qualitative performance than classical image codecs. The study confirms the usefulness and superiority of gain units and the asymmetric Gaussian entropy model.


## Target Task

computer vision

## Content

<Abstract: >With the development of deep learning techniques, the combination of deep learning with image compression has drawn lots of attention. Recently, learned image compression methods had exceeded their classical counterparts in terms of rate-distortion performance. However, continuous rate adaptation remains an open question. In this paper, we propose a continuously rate adjustable learned image compression framework, Asymmetric Gained Variational Autoencoder (AG-VAE). AG-VAE utilizes a pair of gain units to achieve discrete rate adaptation in one single model with a negligible additional computation. Then, by using exponential interpolation, continuous rate adaptation is achieved without compromising performance. Besides, we propose the asymmetric Gaussian entropy model for more accurate entropy estimation. Exhaustive experiments show that our method achieves comparable quantitative performance with SOTA learned image compression methods and better qualitative performance than classical image codecs. In the ablation study, we confirm the usefulness and superiority of gain units and the asymmetric Gaussian entropy model.



---

