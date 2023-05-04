# Dfqf: Data free quantization-aware fine-tuning

## Summary

Summary: The paper proposes a data free quantization-aware fine-tuning (DFQF) technique for neural network quantization. The method fine-tunes the quantized network with generated images instead of real training data through knowledge distillation. The proposed method outperforms existing post-train quantization methods and achieves W4A4 quantization of ResNet20 on the CIFAR10 dataset with less than 1% accuracy drop.


## Target Task

computer vision

## Content

<Abstract: >Data free deep neural network quantization is a practical challenge, since the original training data is often unavailable due to some privacy, proprietary or transmission issues. The existing methods implicitly equate data-free with training-free and quantize model manually through analyzing the weights' distribution. It leads to a significant accuracy drop in lower than 6-bit quantization. In this work, we propose the data free quantization-aware fine-tuning (DFQF), wherein no real training data is required, and the quantized network is fine-tuned with generated images. Specifically, we start with training a generator from the pre-trained full-precision network with inception score loss, batch-normalization statistics loss and adversarial loss to synthesize a fake image set. Then we fine-tune the quantized student network with the full-precision teacher network and the generated images by utilizing knowledge distillation (KD). The proposed DFQF outperforms state-of-the-art post-train quantization methods, and achieve W4A4 quantization of ResNet20 on the CIFAR10 dataset within 1% accuracy drop. 
Keywords: Data-free, Quantization, Adversarial



---

