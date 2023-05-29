---
layout: tabs
---
# Resume
email: ghualm.jilani.raza@outlook.com  
linkedin: https://www.linkedin.com/in/ghulam-jilani-raza-a9a931a3/
## Tech Stack 
__ML__ : Pytorch, Keras  
__Development__: Python, C++/Cmake, Rust  
__Model Optimisation/ Compression__: TensorRT, OpenVino, TFLite, Intel NNCF  
__Deployment/Ops__: Docker, AWS, GCP, Grafana, Prometheus  
__Hardware Platforms__: Nvidia Jetsons, Intel CPU/GPU, Intel NCS2  

## Experience
__Hazen.ai / AI Engineer__  
November 2019 - October 2022, Lahore Pakistan  
  

- Optimizing trained object detection & classification models for Hazen’s
  road safety products for inference on edge devices including Nvidia
  Jetsons, Google Edge TPU, Intel Movidius and AXIS smart cameras.

- Developing high throughput Inference pipelines in C++ for various edge
target platforms (Jetson, x86 CPUs, ARM64 CPUs) and optimizing them
for compute resources with rigorous refactoring and profiling resulting in
2-6X speedup.

- Maintaining above mentioned pipelines with best practices of CI/CD and
improving them with rigorous profiling and refactoring.
Took inference time of object detection pipeline on AXIS ARMv8 CPU
from 4s to 750ms.

- Researching and experimenting with various techniques for quantizing
neural networks for deployment on devices with very limited compute
resources. Took Hazen’s ALPR pipeline inference latency from 66ms
(FP16) to 13ms (INT8) using quantization on a tesla T4 GPU resulting in
5x speed up without compromising accuracy.


__aletheia.ai / Senior ML Engineer__  
February 2023 - Present, Lahore Pakistan  

Acting as lead developer/product owner for developing a computer vision based manufacturing analytics 
product for cement manufacturing companies . It involves solving various ML problems including:  


- High accuracy Pakistani license plate recognition
- Vehicle Detection
- Processing 20+ camera streams in parallel
- Accurate counting of cement bags
- Facial Recognition
- System optimization to make sure all components run in real time and
- within acceptable downtime limits.
- Keeping the codebase healthy and sustainable.