# SIG-VC: A Speaker Information Guided Zero-Shot Voice Conversion System for Both Human Beings and Machines

## Summary

<Summary: > The paper presents a novel method called SIG-VC for zero-shot voice conversion, which disentangles speaker and content information by extracting pre-trained speaker verification and acoustic models to remove speaker information from speech. The proposed system outperforms previous state-of-the-art systems in terms of subjective and objective metrics, indicating a significant reduction in the trade-off problem in zero-shot voice conversion.


## Target Task

speech recognition

## Content

<Abstract: > Nowadays, zero-shot voice conversion is gaining attention in extreme conditions where data of source or target speakers is scarce and unseen in the training stage. In this paper, a novel method called SIG-VC is proposed for zero-shot voice conversion. The proposed system disentangles speaker and content information to remove the residual speaker information from the speech. A pre-trained speaker verification system is used for the speaker information extraction, and a pre-trained acoustic model is applied to extract the linguistic feature. By sharing the parameters of some modules in the system and forcing the intermediate representation in the vector space of the selected acoustic feature, the intermediate representation is supervised to remove the speaker information from the linguistic information. Conditioning on the speaker information of the target speaker, the system manages to generate the target speech while adding feedback loss control on the output, resulting in high spoofing capability to speaker verification systems. The proposed system outperforms the previous state-of-the-art system, AGAIN-VC. Subjective and objective metrics are used for evaluation, indicating the significant reduction in the trade-off problem in zero-shot voice conversion.



---

