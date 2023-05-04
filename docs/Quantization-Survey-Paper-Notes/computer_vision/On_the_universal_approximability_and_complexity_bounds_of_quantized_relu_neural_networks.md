# On the universal approximability and complexity bounds of quantized relu neural networks

## Summary

<Summary: > The paper studies the representation power of quantized neural networks and proves the universal approximability of quantized ReLU networks on a wide class of functions. Upper bounds are provided on the number of weights and memory size for a given approximation error bound and the bit-width of weights for function-independent and function-dependent structures. For an approximation error bound of ε, the number of weights needed by a quantized network is no more than O(log5(1/ε)) times that of an unquantized network. This overhead is much lower than the lower bound of the number of weights needed for the error bound, validating the empirical success of quantization techniques. The paper provides the first in-depth study on the complexity bounds of quantized neural networks.


## Target Task

computer vision

## Content

<Abstract: >Compression is a key step to deploy large neural networks on resource-constrained
platforms. As a popular compression technique, quantization constrains the num-
ber of distinct weight values and thus reducing the number of bits required to
represent and store each weight. In this paper, we study the representation power
of quantized neural networks. First, we prove the universal approximability of
quantized ReLU networks on a wide class of functions. Then we provide upper
bounds on the number of weights and the memory size for a given approximation
error bound and the bit-width of weights for function-independent and function-
dependent structures. Our results reveal that, to attain an approximation error
bound of, the number of weights needed by a quantized network is no more
thanO(log5(1=)) times that of an unquantized network. This overhead is of
much lower order than the lower bound of the number of weights needed for the
error bound, supporting the empirical success of various quantization techniques.
To the best of our knowledge, this is the ﬁrst in-depth study on the complexity
bounds of quantized neural networks.



---

