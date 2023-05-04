# TGAVC: Improving autoencoder voice conversion with text-guided and adversarial training

## Summary

<Summary: >The paper proposes a new framework called TextGuided AutoVC (TGA VC) for non-parallel many-to-many voice conversion. The proposed framework uses an expected content embedding based on text transcriptions to guide the extraction of voice content and adversarial training to eliminate the speaker identity information from estimated content embedding. The content encoder is trained to extract speaker-independent content embedding from speech. Experimental results on the AIShell-3 dataset show that the TGA VC outperforms AutoVC in terms of naturalness and similarity of converted speech.


## Target Task

speech recognition

## Content

<Abstract: >Non-parallel many-to-many voice conversion remains an
interesting but challenging speech processing task. Recently, AutoVC, a conditional autoencoder based method, achieved excellent conversion results by disentangling the speaker identity and the speech content using information-constraining bottlenecks. In this paper, a novel voice conversion framework, named TextGuided AutoVC(TGA VC), is proposed to more effectively separate content and timbre from speech, where an expected content embedding produced based on the text transcriptions is designed to guide the extraction of voice content. In addition, the adversarial training is applied to eliminate the speaker identity information in the estimated content embedding extracted from speech. Under the guidance of the expected content embedding and the adversarial training, the content encoder is trained to extract speaker-independent content embedding from speech. Experiments on AIShell-3 dataset show that the proposed model outperforms AutoVC in terms of naturalness and similarity of converted speech.



---

