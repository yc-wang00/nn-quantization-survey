# Improving the speed of neural networks on CPUs

## Summary

<Summary: > This paper provides a tutorial for minimizing computational cost in neural networks on modern x86 CPUs through techniques such as data layout, computation batching, and the use of SSE2, SSSE3, and SSE4 instructions. The paper uses speech recognition as an example task and shows a 10x speedup over an unoptimized baseline and a 4x speedup over an optimized floating-point baseline with no accuracy loss. The techniques presented can be applied to neural network training and provide a cost-effective alternative to specialized hardware.


## Target Task

speech recognition

## Content

<Abstract: >Recent advances in deep learning have made the use of large, deep neural networks with tens of millions of parameters suitable for a number of applications that require real-time processing. The sheer size of these networks can represent a challenging computational burden, even for modern CPUs. For this reason, GPUs are routinely used instead to train and run such networks. This paper is a tutorial for students and researchers on some of the techniques that can be used to reduce this computational cost considerably on modern x86 CPUs. We emphasize data layout, batching of the computation, the use of SSE2 instructions, and particularly leverage SSSE3 and SSE4 ﬁxed-point instructions which provide a 3improvement over an optimized ﬂoating-point baseline. We use speech recognition as an example task, and show that a real-time hybrid hidden Markov model / neural network (HMM/NN) large vocabulary system can be built with a 10speedup over an unoptimized baseline and a 4speedup over an aggressively optimized ﬂoating-point baseline at no cost in accuracy. The techniques described extend readily to neural network training and provide an effective alternative to the use of specialized hardware.



---

