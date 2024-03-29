# Videobert: A joint model for video and language representation learning

## Summary

<Summary: >The paper proposes a joint visual-linguistic model called VideoBERT to learn high-level features without any explicit supervision. The model builds upon the BERT model to learn bidirectional joint distributions over sequences of visual and linguistic tokens, derived from vector quantization of video data and off-the-shelf speech recognition outputs, respectively. VideoBERT shows promising results in various tasks like action classification and video captioning. It outperforms the state-of-the-art on video captioning, and quantitative results verify that the model learns high-level semantic features.


## Target Task

nlp

## Content

<Abstract: >Self-supervised learning has become increasingly important to leverage the abundance of unlabeled data available on platforms like YouTube. Whereas most existing approaches learn low-level representations, we propose a joint visual-linguistic model to learn high-level features without any explicit supervision. In particular, inspired by its recent success in language modeling, we build upon the BERT model to learn bidirectional joint distributions over sequences of visual and linguistic tokens, derived from vector quantization of video data and off-the-shelf speech recognition outputs, respectively. We use VideoBERT in numerous tasks, including action classification and video captioning. We show that it can be applied directly to open-vocabulary classification, and confirm that large amounts of training data and cross-modal information are critical to performance. Furthermore, we outperform the state-of-the-art on video captioning, and quantitative results verify that the model learns high-level semantic features.



---

