# Mixed-precision quantized neural network with progressively decreasing bitwidth for image classification and object detection

## Summary

<Summary: > The paper proposes a mixed-precision quantized neural network with progressively decreasing bitwidth to improve the trade-off between accuracy and compression. This approach sets the parameter bitwidth homogeneously and balances the performance and compression. The higher-precision bottom layers improve the 1-bit network performance by better preserving the original image information, while the lower-precision posterior layers contribute to the regularization of k-bit networks.


## Target Task

computer vision

## Content

<Abstract: >Efficient model inference is an important issue in the deployment of deep neural network on resource constraint platforms. The parameter bitwidth is set homogeneously and there is a trade-off between superior performance and aggressive compression. A simple but effective mixed-precision quantized neural network with progressively decreasing bitwidth is proposed to improve the trade-off between accuracy and compression. The higher-precision bottom layers could boost the 1-bit network performance appreciably due to a better preservation of the original image information while the lower-precision posterior layers contribute to the regularization of k-bit networks.



---

