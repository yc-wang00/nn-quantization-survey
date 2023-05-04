# Inferring context from pixels for multimodal image classification

## Summary

<Summary: >This work proposes a framework for image classification models that consists of a phrase generator that maps image pixels to contextual phrases, and a multimodal model that uses both textual and visual features to produce labels. This approach shows improved performance and prediction interpretability on diverse benchmark datasets, including few-shot learning with minimally labeled concepts and baseline zero-shot learning on the ImageNet dataset.


## Target Task

computer vision

## Content

<Abstract: >Image classification models take image pixels as input and predict labels in a predefined taxonomy. While contextual information (e.g. text surrounding an image) can provide valuable orthogonal signals to improve classification, the typical setting in literature assumes the unavailability of text and thus focuses on models that rely purely on pixels. In this work, we also focus on the setting where only pixels are available in the input. However, we demonstrate that if we predict textual information from pixels, we can subsequently use the predicted text to train models that improve overall performance. We propose a framework that consists of two main components: (1) a phrase generator that maps image pixels to a contextual phrase, and (2) a multimodal model that uses textual features from the phrase generator and visual features from the image pixels to produce labels in the output taxonomy. We evaluate our framework on diverse benchmark datasets (specifically, the WebVision dataset for evaluating multi-class classification and OpenImages dataset for evaluating multi-label classification), demonstrating performance improvements over approaches based exclusively on pixels and showcasing benefits in prediction interpretability. We additionally present results to demonstrate that our framework provides improvements in few-shot learning of minimally labeled concepts. We further demonstrate the unique benefits of the multimodal nature of our framework by utilizing intermediate image/text co-embeddings to perform baseline zero-shot learning on the ImageNet dataset.



---

