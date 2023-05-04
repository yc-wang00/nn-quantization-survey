# YOLO-Based Face Mask Detection on Low-End Devices Using Pruning and Quantization

## Summary

<Summary: >The paper talks about the use of pruning and quantization techniques to compress a Deep Learning object detection model based on YOLOv4 to recognize the presence of face masks, to be deployed on a Raspberry Pi 4. The performance is measured in terms of Mean Average Precision (mAP) and FPS. The results suggest that with proper pruning and quantization, the FPS can be doubled with a moderate loss in mAP.


## Target Task

computer vision

## Content

<Abstract: >Deploying Deep Learning (DL) based object detection (OD) models in low-end devices may lead to poor performance in terms of frames-per-second (FPS). Pruning and quantization are well-known compression techniques that can potentially lead to a reduction of the computational burden of a DL model, with a possible decrease of performance in terms of detection accuracy. Motivated by the widespread introduction of face mask mandates by many institutions during the Covid-19 pandemic, we aim at training and compressing an OD model based on YOLOv4 to recognize the presence of face masks, to be deployed on a Raspberry Pi 4. We investigate the capability of different kinds of pruning and quantization techniques of increasing the FPS with respect to the uncompressed model, while retaining the detection accuracy. We quantitatively assess the pruned and quantized models in terms of Mean Average Precision (mAP) and FPS, and show that with proper pruning and quantization, the FPS can be doubled with a moderate loss in mAP. The results provide guidelines for compression of other OD models based on YOLO.



---

