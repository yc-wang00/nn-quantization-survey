# FAID diversity via neural networks

## Summary

Summary: The paper proposes a novel approach to design the decoder diversity of Finite Alphabet Iterative Decoders (FAIDs) using a Recurrent Quantized Neural Network (RQNN) to learn FAIDs for Low-Density Parity Check (LDPC) codes over the Binary Symmetric Channel (BSC) with the objective of lowering the error floor while guaranteeing the waterfall performance. The training sets are constructed by sampling from the set of most problematic error patterns - trapping sets, and a frame-error-rate (FER) based loss function is introduced to train the RQNN. The simulation results show that the RQNN-aided decoder diversity increases the error correction capability of LDPC codes and lowers the error floor.


## Target Task

Target: Any task

## Content

Abstract: —Decoder diversity is a powerful error correction
framework in which a collection of decoders collaboratively
correct a set of error patterns otherwise uncorrectable by any
individual decoder. In this paper, we propose a new approach to
design the decoder diversity of ﬁnite alphabet iterative decoders
(FAIDs) for Low-Density Parity Check (LDPC) codes over the
binary symmetric channel (BSC), for the purpose of lowering
the error ﬂoor while guaranteeing the waterfall performance. The
proposed decoder diversity is achieved by training a recurrent
quantized neural network (RQNN) to learn/design FAIDs. We
demonstrated for the ﬁrst time that a machine-learned decoder
can surpass in performance a man-made decoder of the same
complexity. As RQNNs can model a broad class of FAIDs, they
are capable of learning an arbitrary FAID. To provide sufﬁcient
knowledge of the error ﬂoor to the RQNN, the training sets are
constructed by sampling from the set of most problematic error
patterns - trapping sets. In contrast to the existing methods that
use the cross-entropy function as the loss function, we introduce
a frame-error-rate (FER) based loss function to train the RQNN
with the objective of correcting speciﬁc error patterns rather than
reducing the bit error rate (BER). The examples and simulation
results show that the RQNN-aided decoder diversity increases
the error correction capability of LDPC codes and lowers the
error ﬂoor.



---

