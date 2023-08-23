# Document Layout Detection With YOLOv8

![Header Image](/images/banner-yolov8.png)

This repository contains an implementation of document layout detection using YOLOv8, an evolution of the YOLO (You Only Look Once) object detection model. The goal of this project is to utilize the power of YOLOv8 to accurately detect various regions within documents. But This is just a showcase of how you can do this task with Yolov8. I urge you to use this code and try different yolov8 models with different hyperparameters to get more robust results. 

## About YOLO and Document Layout

YOLOv8, an evolution of the YOLO (You Only Look Once) object detection model, introduces advancements in architecture to achieve accurate and efficient object detection in real-time. It combines the strengths of YOLOv4 and YOLOv5 to enhance detection performance.

The YOLOv8 architecture employs a deep neural network with a streamlined backbone and feature fusion modules. It incorporates state-of-the-art techniques like CSPDarknet53 for feature extraction and PANet for effective feature fusion across different scales. This architecture optimally balances speed and accuracy, making it suitable for a wide range of object detection tasks.

With YOLOv8, objects of various sizes and complexities can be detected in images or videos with remarkable accuracy. Its design emphasizes versatility and ease of integration, making it a valuable choice for applications that demand real-time object detection without sacrificing detection quality.

Document layout detection is a crucial task in fields like OCR (Optical Character Recognition) and information extraction. By leveraging YOLOv8, i aim to create a robust model that can identify and categorize different regions within documents, such as text blocks, images, headers, and footers.

## Results

Here are results from Different Yolov8 Models: Yolov8 Nano, Small and Medium, Respectively.
![Result 1](/images/yolov8Nano3.png)
![Result 2](/images/yolov8Small.png)
![Result 3](/images/yolov8Medium.png)

## Acknowledgements

- [YOLOv8 Paper](https://arxiv.org/pdf/2305.09972.pdf)
- [YOLOv8 GitHub Repository](https://github.com/ultralytics/ultralytics)
- [PublayNet Dataset](https://arxiv.org/pdf/1908.07836.pdf)
