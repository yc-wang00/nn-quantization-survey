# Increasing compactness of deep learning based speech enhancement models with parameter pruning and quantization techniques

## Summary

Summary: The paper proposes a novel parameter pruning technique to remove redundant channels in a neural network and applies a parameter quantization technique to reduce its size. By integrating both techniques, the resulting SE model size was reduced by 10.03% with minor performance losses of 1.43% for STOI and 3.24% for PESQ. The proposed techniques can be useful for SE systems in devices with limited resources.


## Target Task

speech recognition

## Content

<Abstract: >Most recent studies on deep learning based speech enhancement (SE) focused on improving denoising performance. However, successful SE applications require striking a desirable balance between denoising performance and computational cost in real scenarios. In this study, we propose a novel parameter pruning (PP) technique, which removes redundant channels in a neural network. In addition, a parameter quantization (PQ) technique was applied to reduce the size of a neural network by representing weights with fewer cluster centroids. Because the techniques are derived based on different concepts, the PP and PQ can be integrated to provide even more compact SE models. The experimental results show that the PP and PQ techniques produce a compacted SE model with a size of only 10.03 % compared to that of the original model, resulting in minor performance losses of 1.43% (from 0.70 to 0.69) for STOI and 3.24% (from 1.85 to 1.79) for PESQ. The promising results suggest that the PP and PQ techniques can be used in an SE system in devices with limited storage and computation resources.



---

