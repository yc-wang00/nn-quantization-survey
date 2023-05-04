# YOLOv6: A single-stage object detection framework for industrial applications

## Summary

<Summary: > The paper discusses the improvements made to the popular YOLO series of object detection models, resulting in the creation of YOLOv6. The authors assimilate various advancements in network design, training strategies, testing techniques, quantization, and optimization methods. They have built a suite of deployment-ready networks at various scales to accommodate different use cases. The model achieves state-of-the-art results, with the quantized version of YOLOv6-S bringing a new state-of-the-art 43.3% AP at 869 FPS, while YOLOv6-M/L achieves better accuracy performance than other detectors with similar inference speed. Their code is available on GitHub.


## Target Task

computer vision

## Content

<Abstract: > For years, YOLO series have been de facto industry-level standard for efficient object detection. The YOLO community has prospered overwhelmingly to enrich its use in a multitude of hardware platforms and abundant scenarios. In this technical report, we strive to push its limits to the next level, stepping forward with an unwavering mindset for industry application. Considering the diverse requirements for speed and accuracy in the real environment, we extensively examine the up-to-date object detection advancements either from industry or academy. Specifically, we heavily assimilate ideas from recent network design, training strategies, testing techniques, quantization and optimization methods. On top of this, we integrate our thoughts and practice to build a suite of deployment-ready networks at various scales to accommodate diversified use cases. With the generous permission of YOLO authors, we name it YOLOv6. We also express our warm welcome to users and contributors for further enhancement. For a glimpse of performance, our YOLOv6-N hits 35.9% AP on COCO dataset at a throughput of 1234 FPS on an NVIDIA Tesla T4 GPU. YOLOv6-S strikes 43.5% AP at 495 FPS, outperforming other mainstream detectors at the same scale (YOLOv5-S, YOLOX-S and PPYOLOE-S). Our quantized version of YOLOv6-S even brings a new state-of-the-art 43.3% AP at 869 FPS. Furthermore, YOLOv6-M/L also achieves better accuracy performance (i.e., 49.5%/52.3%) than other detectors with the similar inference speed. We carefully conducted experiments to validate the effectiveness of each component. Our code is made available at https://github.com/meituan/YOLOv6.



---

