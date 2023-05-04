# A tiny CNN architecture for medical face mask detection for resource-constrained endpoints

## Summary

Summary: The paper proposes an architecture for detecting medical face masks that can be deployed on resource-constrained endpoints with extremely low memory footprints. The model is deployed on a small development board with an ARM Cortex-M7 microcontroller clocked at 480 Mhz and having just 496 KB of framebuffer RAM. The model is quantized using the TensorFlow Lite framework to reduce its size further. The proposed model is 138 KB post quantization and runs at the inference speed of 30 FPS.


## Target Task

computer vision

## Content

<Abstract: >The world is going through one of the most dangerous pandemics of all time with the rapid spread of the novel coronavirus (COVID-19). According to the World Health Organisation, the most effective way to thwart the transmission of coronavirus is to wear medical face masks. Monitoring the use of face masks in public places has been a challenge because manual monitoring could be unsafe. This paper proposes an architecture for detecting medical face masks for deployment on resource-constrained endpoints having extremely low memory footprints. A small development board with an ARM Cortex-M7 microcontroller clocked at480 Mhz and having just 496 KB of framebuffer RAM, has been used for the deployment of the model. Using the TensorFlow Lite framework, the model is quantized to further reduce its size. The proposed model is 138 KB post quantization and runs at the inference speed of 30 FPS.



---

