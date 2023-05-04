# [PDF][PDF] Releq: An automatic reinforcement learning approach for deep quantization of neural networks

## Summary

Summary: This paper discusses the challenges of deploying deep neural networks (DNNs) to devices with limited resources because DNNs are computationally intense and have a large memory footprint. The paper proposes quantizing the weights of DNNs to lower bitwidths as a solution to these challenges. To address the difficulty of deep quantization while preserving accuracy and avoiding manual efforts, the paper proposes an end-to-end framework called ReLeQ which utilizes reinforcement learning algorithm, Proximal Policy Optimization (PPO), to efficiently explore the quantization design space. The proposed ReLeQ framework was evaluated on different neural networks and achieved an average bitwidths of 2.25, 5, and 4 with a final accuracy loss below 0.3%.


## Target Task

computer vision

## Content

<Abstract: >
Despite numerous state-of-the-art applications of Deep Neural Networks (DNNs)
in a wide range of real-world tasks, two major challenges hinder further advances
in DNNs: hyperparameter optimization and constrained power resources, which is
a signiﬁcant concern in embedded devices. DNNs become increasingly difﬁcult
to train and deploy as they grow in size due to both computational intensity and
the large memory footprint. Recent efforts show that quantizing weights of deep
neural networks to lower bitwidths takes a signiﬁcant step toward mitigating the
mentioned issues, by reducing memory bandwidth and using limited computational
resources which is important for deploying DNN models to devices with limited
resources. This paper builds upon the algorithmic insight that the bitwidth of
operations in DNNs can be reduced without compromising their classiﬁcation
accuracy. Deep quantization (quantizing bitwidths below eight) while maintaining
accuracy, requires magniﬁcent manual effort and hyper-parameter tuning as well as
re-training. This paper tackles the aforementioned problems by designing an end
to end framework, dubbed ReLeQ, to automate DNN quantization. We formulate
DNN quantization as an optimization problem and use a state-of-the-art policy
gradient based Reinforcement Learning (RL) algorithm, Proximal Policy Optimiza-
tion (PPO) to efﬁciently explore the large design space of DNN quantization and
solve the deﬁned optimization problem. To show the effectiveness of ReLeQ, we
evaluated it across several neural networks including MNIST, CIFAR10, SVHN.
ReLeQ quantizes the weights of these networks to average bitwidths of 2.25, 5 and
4 respectively while maintaining the ﬁnal accuracy loss below 0.3%.



---

