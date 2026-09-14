# Awesome-YOLO-Object-Detection
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🚀🚀🚀 YOLO is a great real-time one-stage object detection framework. This repository lists some awesome public YOLO object detection projects and datasets.

## Contents
- [Awesome-YOLO-Object-Detection](#awesome-yolo-object-detection)
  - [Summary](#summary)
    - [Famous YOLO](#famous-yolo)
    - [Extensional Frameworks](#extensional-frameworks)
    - [Awesome List](#awesome-list)
    - [Paper and Code Overview](#paper-and-code-overview)
      - [Paper Review](#paper-review)
      - [Code Review](#code-review)
    - [Learning Resources](#learning-resources)
  - [Other Versions of YOLO](#other-versions-of-yolo)
    - [PyTorch Implementation](#pytorch-implementation)
    - [C Implementation](#c-implementation)
    - [CPP Implementation](#cpp-implementation)
    - [ROS Implementation](#ros-implementation)
    - [Mojo Implementation](#mojo-implementation)
    - [Rust Implementation](#rust-implementation)
    - [Go Implementation](#go-implementation)
    - [CSharp Implementation](#csharp-implementation)
    - [Tensorflow and Keras Implementation](#tensorflow-and-keras-implementation)
    - [PaddlePaddle Implementation](#paddlepaddle-implementation)
    - [Caffe Implementation](#caffe-implementation)
    - [MXNet Implementation](#mxnet-implementation)
    - [Web Implementation](#web-implementation)
    - [Others](#others)
  - [Lighter and Deployment Frameworks](#lighter-and-deployment-frameworks)
    - [High-performance Inference Engine](#high-performance-inference-engine)
      - [ONNX](#onnx)
      - [TensorRT](#tensorrt)
      - [DeepStream](#deepstream)
      - [OpenVINO](#openvino)
      - [NCNN](#ncnn)
      - [MNN](#mnn)
      - [Other Engine](#other-engine)
    - [NPU and FPGA Hardware Deployment](#npu-and-fpga-hardware-deployment)
      - [RK3588](#rk3588)
      - [FPGA](#fpga)
      - [Other Hardware](#other-hardware)
    - [Pruning Knoweldge-Distillation Quantization](#pruning-knoweldge-distillation-quantization)
      - [Pruning](#pruning)
      - [Quantization](#quantization)
      - [Knoweldge-Distillation](#knoweldge-distillation)
    - [Lightweight Backbones and FPN](#lightweight-backbones-and-fpn)
  - [Object Detection Applications](#object-detection-applications)
    - [Open World Object Detection](#open-world-object-detection)
    - [Few-shot Object Detection](#few-shot-object-detection)
    - [Small Object Detection](#small-object-detection)
    - [Multimodal Image Detection](#multimodal-image-detection)
    - [Video Object Detection](#video-object-detection)
    - [Object Tracking](#object-tracking)
      - [Multi-Object Tracking](#multi-object-tracking)
      - [Dynamic Object Tracking](#Dynamic-object-tracking)
    - [Deep Reinforcement Learning](#deep-reinforcement-learning)
    - [Motion Control Field](#motion-control-field)
    - [Super-Resolution Field](#super-resolution-field)
    - [Spiking Neural Network](#spiking-neural-network)
    - [Attention and Transformer](#attention-and-transformer)
    - [Oriented Object Detection](#oriented-object-detection)
    - [Face Detection and Recognition](#face-detection-and-recognition)
      - [Face Detection](#face-detection)
      - [Face Recognition](#face-recognition)
    - [Face Mask Detection](#face-mask-detection)
    - [Social Distance Detection](#social-distance-detection)
    - [Autonomous Driving Field Detection](#autonomous-driving-field-detection)
      - [Vehicle Detection](#vehicle-detection)
      - [License Plate Detection and Recognition](#license-plate-detection-and-recognition)
      - [Lane Detection](#lane-detection)
      - [Driving Behavior Detection](#driving-behavior-detection)
      - [Parking Slot Detection](#parking-slot-detection)
      - [Traffic Light Detection](#traffic-light-detection)
      - [Traffic Sign Detection](#traffic-sign-detection)
      - [Crosswalk Detection](#crosswalk-detection)
      - [Traffic Accidents Detection](#traffic-accidents-detection)
      - [Road Damage Detection](#road-damage-detection)
    - [Animal Detection](#animal-detection)
    - [Helmet Detection](#helmet-detection)
    - [Hand Detection](#hand-detection)
    - [Gesture Recognition](#gesture-recognition)
    - [Action Detection](#action-detection)
    - [Emotion Recognition](#emotion-recognition)
    - [Human Pose Estimation](#human-pose-estimation)
    - [Distance Measurement](#distance-measurement)
    - [Instance and Semantic Segmentation](#instance-and-semantic-segmentation)
    - [3D Object Detection](#3d-object-detection)
    - [SLAM Field Detection](#slam-field-detection)
    - [Industrial Defect Detection](#industrial-defect-detection)
    - [SAR Image Detection](#sar-image-detection)
    - [Safety Monitoring Field Detection](#safety-monitoring-field-detection)
    - [Anti-UAV Field Detection](#anti-uav-field-detection)
    - [Medical Field Detection](#medical-field-detection)
    - [Chemistry Field Detection](#chemistry-field-detection)
    - [Agricultural Field Detection](#agricultural-field-detection)
    - [Sports Field Detection](#sports-field-detection)
    - [Aerial Imagery Detection](#aerial-imagery-detection)
    - [Adverse Weather Conditions](#adverse-weather-conditions)
    - [Adversarial Attack and Defense](#adversarial-attack-and-defense)
    - [Camouflaged Detection](#camouflaged-detection)
    - [Game Field Detection](#game-field-detection)
    - [Automatic Annotation Tools](#automatic-annotation-tools)
    - [Feature Map Visualization](#feature-map-visualization)
    - [Object Detection Evaluation Metrics](#object-detection-evaluation-metrics)
    - [GUI](#gui)
        - [Swift-Related](#swift-related)
        - [Flutter-Related](#flutter-related)
        - [Streamlit-Related](#streamlit-related)
        - [Gradio-Related](#gradio-related)
        - [QT-Related](#qt-related)
        - [PySide-Related](#pyside-related)
    - [Other Applications](#other-applications)
  - [Object Detection Datasets](#object-detection-datasets)
    - [Datasets Share Platform](#datasets-share-platform)
    - [Datasets Tools](#datasets-tools)
        - [Data Annotation](#data-annotation)
        - [Data Augmentation](#data-augmentation)
        - [Data Management](#data-management)
    - [General Detection and Recognition Datasets](#general-detection-and-recognition-datasets)
        - [General Object Detection Datasets](#general-object-detection-datasets)
        - [General Object Recognition Datasets](#general-object-recognition-datasets)
    - [Autonomous Driving Datasets](#autonomous-driving-datasets)
        - [Diverse Autonomous Driving Datasets](#diverse-autonomous-driving-datasets)
        - [Traffic Sign Detection Datasets](#traffic-sign-detection-datasets)
        - [License Plate Detection and Recognition Datasets](#license-plate-detection-and-recognition-datasets)
    - [Adverse Weather Datasets](#adverse-weather-datasets)
    - [Person Detection Datasets](#person-detection-datasets)
    - [Anti-UAV Datasets](#anti-uav-datasets)
    - [Optical Aerial Imagery Datasets](#optical-aerial-imagery-datasets)
    - [Low-light Image Datasets](#low-light-image-datasets)
    - [Infrared Image Datasets](#infrared-image-datasets)
    - [SAR Image Datasets](#sar-image-datasets)
    - [Sonar Image Datasets](#sonar-image-datasets)
    - [Multimodal Image Datasets](#multimodal-image-datasets)
    - [3D Object Detection Datasets](#3d-object-detection-datasets)
    - [Vehicle-to-Everything Field Datasets](#vehicle-to-everything-field-datasets)
    - [Super-Resolution Field Datasets](#super-resolution-field-datasets)
    - [Face Detection and Recognition Datasets](#general-detection-and-recognition-datasets)
        - [Face Detection Datasets](#face-detection-datasets)
        - [Face Recognition Datasets](#face-recognition-datasets)
  - [Blogs](#blogs)
  - [Videos](#videos)



## Summary

  - ### Famous YOLO

    - [YOLOv1](https://pjreddie.com/darknet/yolov1) ([Darknet](https://github.com/pjreddie/darknet) <img src="https://img.shields.io/github/stars/pjreddie/darknet?style=social"/>) : "You Only Look Once: Unified, Real-Time Object Detection". (**[CVPR 2016](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Redmon_You_Only_Look_CVPR_2016_paper.html)**)

    - [YOLOv2](https://pjreddie.com/darknet/yolov2) ([Darknet](https://github.com/pjreddie/darknet) <img src="https://img.shields.io/github/stars/pjreddie/darknet?style=social"/>) : "YOLO9000: Better, Faster, Stronger". (**[CVPR 2017](https://openaccess.thecvf.com/content_cvpr_2017/html/Redmon_YOLO9000_Better_Faster_CVPR_2017_paper.html)**)

    - [YOLOv3](https://pjreddie.com/darknet/yolo) ([Darknet](https://github.com/pjreddie/darknet) <img src="https://img.shields.io/github/stars/pjreddie/darknet?style=social"/>) : "YOLOv3: An Incremental Improvement". (**[arXiv 2018](https://arxiv.org/abs/1804.02767)**)

    - [YOLOv4](https://github.com/AlexeyAB/darknet) <img src="https://img.shields.io/github/stars/AlexeyAB/darknet?style=social"/> ([WongKinYiu/PyTorch_YOLOv4](https://github.com/WongKinYiu/PyTorch_YOLOv4) <img src="https://img.shields.io/github/stars/WongKinYiu/PyTorch_YOLOv4?style=social"/>) : "YOLOv4: Optimal Speed and Accuracy of Object Detection". (**[arXiv 2020](https://arxiv.org/abs/2004.10934)**)

    - [Scaled-YOLOv4](https://github.com/AlexeyAB/darknet) <img src="https://img.shields.io/github/stars/AlexeyAB/darknet?style=social"/> ([WongKinYiu/ScaledYOLOv4](https://github.com/WongKinYiu/ScaledYOLOv4) <img src="https://img.shields.io/github/stars/WongKinYiu/ScaledYOLOv4?style=social"/>) : "Scaled-YOLOv4: Scaling Cross Stage Partial Network". (**[CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_Scaled-YOLOv4_Scaling_Cross_Stage_Partial_Network_CVPR_2021_paper.html)**)

    - [YOLOv5](https://github.com/ultralytics/yolov5) <img src="https://img.shields.io/github/stars/ultralytics/yolov5?style=social"/> : YOLOv5 🚀 in PyTorch > ONNX > CoreML > TFLite. [docs.ultralytics.com](https://docs.ultralytics.com/). YOLOv5 🚀 is the world's most loved vision AI, representing [Ultralytics](https://ultralytics.com/) open-source research into future vision AI methods, incorporating lessons learned and best practices evolved over thousands of hours of research and development.

    - [YOLOv6](https://github.com/meituan/YOLOv6) <img src="https://img.shields.io/github/stars/meituan/YOLOv6?style=social"/> : "YOLOv6: A Single-Stage Object Detection Framework for Industrial Applications". (**[arXiv 2022](https://arxiv.org/abs/2209.02976)**).

    - [YOLOv7](https://github.com/WongKinYiu/yolov7) <img src="https://img.shields.io/github/stars/WongKinYiu/yolov7?style=social"/> : "YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors". (**[CVPR 2023](https://arxiv.org/abs/2207.02696)**).

    - [YOLOv8](https://github.com/ultralytics/ultralytics) <img src="https://img.shields.io/github/stars/ultralytics/ultralytics?style=social"/> : NEW - YOLOv8 🚀 in PyTorch > ONNX > OpenVINO > CoreML > TFLite. [docs.ultralytics.com](https://docs.ultralytics.com/)

    - [YOLOv9](https://github.com/WongKinYiu/yolov9) <img src="https://img.shields.io/github/stars/WongKinYiu/yolov9?style=social"/> : "YOLOv9: Learning What You Want to Learn Using Programmable Gradient Information". (**[arXiv 2024](https://arxiv.org/abs/2402.13616)**)

    - [MultimediaTechLab/YOLO](https://github.com/MultimediaTechLab/YOLO) <img src="https://img.shields.io/github/stars/MultimediaTechLab/YOLO?style=social"/> : YOLO: Official Implementation of YOLOv9, YOLOv7, YOLO-RD. Welcome to the official implementation of YOLOv7 and YOLOv9, YOLO-RD. This repository will contains the complete codebase, pre-trained models, and detailed instructions for training and deploying YOLOv9.

    - [YOLOv10](https://github.com/THU-MIG/yolov10) <img src="https://img.shields.io/github/stars/THU-MIG/yolov10?style=social"/> : "YOLOv10: Real-Time End-to-End Object Detection". (**[arXiv 2024](https://arxiv.org/abs/2405.14458v1)**)

    - [YOLOv11](https://github.com/ultralytics/ultralytics) <img src="https://img.shields.io/github/stars/ultralytics/ultralytics?style=social"/> : NEW - YOLOv8 🚀 in PyTorch > ONNX > OpenVINO > CoreML > TFLite. [Ultralytics](https://www.ultralytics.com/) [YOLOv11](https://github.com/ultralytics/ultralytics) s a cutting-edge, state-of-the-art (SOTA) model that builds upon the success of previous YOLO versions and introduces new features and improvements to further boost performance and flexibility. YOLO11 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and tracking, instance segmentation, image classification and pose estimation tasks. [docs.ultralytics.com](https://docs.ultralytics.com/)

    - [YOLOv12](https://github.com/sunsmarterjie/yolov12) <img src="https://img.shields.io/github/stars/sunsmarterjie/yolov12?style=social"/> : "YOLOv12: Attention-Centric Real-Time Object Detectors". (**[arXiv 2025](https://arxiv.org/abs/2502.12524)**)

    - [YOLO-World | YOLO-World-v2](https://github.com/AILab-CVC/YOLO-World) <img src="https://img.shields.io/github/stars/AILab-CVC/YOLO-World?style=social"/> : "YOLO-World: Real-Time Open-Vocabulary Object Detection". (**[CVPR 2024](https://arxiv.org/abs/2401.17270)**). [www.yoloworld.cc](https://www.yoloworld.cc/)

    - [YOLOE](https://github.com/THU-MIG/yoloe) <img src="https://img.shields.io/github/stars/THU-MIG/yoloe?style=social"/> : "YOLOE: Real-Time Seeing Anything". (**[arXiv 2025](https://arxiv.org/abs/2503.07465)**).



  - ### Extensional Frameworks

    - [Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL) <img src="https://img.shields.io/github/stars/QwenLM/Qwen2-VL?style=social"/> : Qwen2-VL is the multimodal large language model series developed by Qwen team, Alibaba Cloud. "Qwen2.5-VL Technical Report". (**[arXiv 2025](https://arxiv.org/abs/2502.13923)**). [2025-01-26，Qwen2.5 VL! Qwen2.5 VL! Qwen2.5 VL!](https://qwenlm.github.io/blog/qwen2.5-vl/). "Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution". (**[arXiv 2024](https://arxiv.org/abs/2409.12191)**). "Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond". (**[arXiv 2023](https://arxiv.org/abs/2308.12966)**).

    - [Kimi-VL](https://github.com/MoonshotAI/Kimi-VL) <img src="https://img.shields.io/github/stars/MoonshotAI/Kimi-VL?style=social"/> : Kimi-VL: Mixture-of-Experts Vision-Language Model for Multimodal Reasoning, Long-Context Understanding, and Strong Agent Capabilities. "Kimi-VL Technical Report". (**[arXiv 2025](https://arxiv.org/abs/2504.07491)**).

    - [Visual-RFT](https://github.com/Liuziyu77/Visual-RFT) <img src="https://img.shields.io/github/stars/Liuziyu77/Visual-RFT?style=social"/> : 🌈We introduce Visual Reinforcement Fine-tuning (Visual-RFT), the first comprehensive adaptation of Deepseek-R1's RL strategy to the multimodal field. We use the Qwen2-VL-2/7B model as our base model and design a rule-based verifiable reward, which is integrated into a GRPO-based reinforcement fine-tuning framework to enhance the performance of LVLMs across various visual perception tasks. ViRFT extends R1's reasoning capabilities to multiple visual perception tasks, including various detection tasks like Open Vocabulary Detection, Few-shot Detection, Reasoning Grounding, and Fine-grained Image Classification. "Visual-RFT: Visual Reinforcement Fine-Tuning". (**[arXiv 2025](https://arxiv.org/abs/2503.01785)**).

    - [VLM-R1](https://github.com/om-ai-lab/VLM-R1) <img src="https://img.shields.io/github/stars/om-ai-lab/VLM-R1?style=social"/> : VLM-R1: A stable and generalizable R1-style Large Vision-Language Model. Solve Visual Understanding with Reinforced VLMs. [2025-03-20，Improving Object Detection through Reinforcement Learning with VLM-R1](https://om-ai-lab.github.io/2025_03_20.html).

    - Florence-2 : "Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks". (**[CVPR 2024](https://arxiv.org/abs/2311.06242)**).

    - [maestro](https://github.com/roboflow/maestro) <img src="https://img.shields.io/github/stars/roboflow/maestro?style=social"/> : VLM fine-tuning for everyone. maestro is a streamlined tool to accelerate the fine-tuning of multimodal models. By encapsulating best practices from our core modules, maestro handles configuration, data loading, reproducibility, and training loop setup. It currently offers ready-to-use recipes for popular vision-language models such as [Florence-2](https://arxiv.org/abs/2311.06242), PaliGemma 2, and [Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL). [maestro.roboflow.com](https://maestro.roboflow.com/latest/)

    - [Autodistill](https://github.com/autodistill/autodistill) <img src="https://img.shields.io/github/stars/autodistill/autodistill?style=social"/> : Images to inference with no labeling (use foundation models to train supervised models). Autodistill uses big, slower foundation models to train small, faster supervised models. Using autodistill, you can go from unlabeled images to inference on a custom model running at the edge with no human intervention in between. [docs.autodistill.com](https://docs.autodistill.com/)

    - [EdgeYOLO](https://github.com/LSH9832/edgeyolo) <img src="https://img.shields.io/github/stars/LSH9832/edgeyolo?style=social"/> : an edge-real-time anchor-free object detector with decent performance. "Edge YOLO: Real-time intelligent object detection system based on edge-cloud cooperation in autonomous vehicles". (**[IEEE Transactions on Intelligent Transportation Systems, 2022](https://ieeexplore.ieee.org/abstract/document/9740044)**). "EdgeYOLO: An Edge-Real-Time Object Detector". (**[arXiv 2023](https://arxiv.org/abs/2302.07483)**)

    - [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) <img src="https://img.shields.io/github/stars/Megvii-BaseDetection/YOLOX?style=social"/> : "YOLOX: Exceeding YOLO Series in 2021". (**[arXiv 2021](https://arxiv.org/abs/2107.08430)**)

    - [YOLOR](https://github.com/WongKinYiu/yolor) <img src="https://img.shields.io/github/stars/WongKinYiu/yolor?style=social"/> : "You Only Learn One Representation: Unified Network for Multiple Tasks". (**[arXiv 2021](https://arxiv.org/abs/2105.04206)**)

    - [YOLOF](https://github.com/megvii-model/YOLOF) <img src="https://img.shields.io/github/stars/megvii-model/YOLOF?style=social"/> : "You Only Look One-level Feature". (**[CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_You_Only_Look_One-Level_Feature_CVPR_2021_paper.html)**).

    - [YOLOS](https://github.com/hustvl/YOLOS) <img src="https://img.shields.io/github/stars/hustvl/YOLOS?style=social"/> : "You Only Look at One Sequence: Rethinking Transformer in Vision through Object Detection". (**[NeurIPS 2021](https://proceedings.neurips.cc//paper/2021/hash/dc912a253d1e9ba40e2c597ed2376640-Abstract.html)**)

    - [DAMO-YOLO](https://github.com/tinyvision/DAMO-YOLO) <img src="https://img.shields.io/github/stars/tinyvision/DAMO-YOLO?style=social"/> : DAMO-YOLO: a fast and accurate object detection method with some new techs, including NAS backbones, efficient RepGFPN, ZeroHead, AlignedOTA, and distillation enhancement. "DAMO-YOLO : A Report on Real-Time Object Detection Design". (**[arXiv 2022](https://arxiv.org/abs/2211.15444)**)

    - [YOLO-NAS](https://github.com/Deci-AI/super-gradients) <img src="https://img.shields.io/github/stars/Deci-AI/super-gradients?style=social"/> : Easily train or fine-tune SOTA computer vision models with one open source training library. The home of [Yolo-NAS](https://github.com/Deci-AI/super-gradients/blob/master/YOLONAS.md). [www.supergradients.com](https://www.supergradients.com/). YOLO-NAS and YOLO-NAS-POSE architectures are out! The new YOLO-NAS delivers state-of-the-art performance with the unparalleled accuracy-speed performance, outperforming other models such as YOLOv5, YOLOv6, YOLOv7 and YOLOv8.

    - [LeYOLO](https://github.com/LilianHollard/LeYOLO) <img src="https://img.shields.io/github/stars/LilianHollard/LeYOLO?style=social"/> : "LeYOLO, New Scalable and Efficient CNN Architecture for Object Detection". (**[arXiv 2024](https://arxiv.org/abs/2406.14239)**)

    - [DynamicDet](https://github.com/VDIGPKU/DynamicDet) <img src="https://img.shields.io/github/stars/VDIGPKU/DynamicDet?style=social"/> : "DynamicDet: A Unified Dynamic Architecture for Object Detection". (**[CVPR 2023](https://arxiv.org/abs/2304.05552)**)

    - [DINO](https://github.com/IDEA-Research/DINO) <img src="https://img.shields.io/github/stars/IDEA-Research/DINO?style=social"/> : "DINO: DETR with Improved DeNoising Anchor Boxes for End-to-End Object Detection". (**[ICLR 2023](https://arxiv.org/abs/2203.03605)**).

    - [GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) <img src="https://img.shields.io/github/stars/IDEA-Research/GroundingDINO?style=social"/> : "Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection". (**[ECCV 2024](https://arxiv.org/abs/2303.05499)**).

    - [RT-DETR | RT-DETRv2](https://github.com/lyuwenyu/RT-DETR) <img src="https://img.shields.io/github/stars/lyuwenyu/RT-DETR?style=social"/> : "DETRs Beat YOLOs on Real-time Object Detection". (**[CVPR 2024](https://arxiv.org/abs/2304.08069)**). "RT-DETRv2: Improved Baseline with Bag-of-Freebies for Real-Time Detection Transformer". (**[arXiv 2024](https://arxiv.org/abs/2407.17140)**).

    - [EasyCV](https://github.com/alibaba/EasyCV) <img src="https://img.shields.io/github/stars/alibaba/EasyCV?style=social"/> : An all-in-one toolkit for computer vision. "YOLOX-PAI: An Improved YOLOX, Stronger and Faster than YOLOv6". (**[arXiv 2022](https://arxiv.org/abs/2208.13040)**).

    - [YOLACT & YOLACT++](https://github.com/dbolya/yolact) <img src="https://img.shields.io/github/stars/dbolya/yolact?style=social"/> : You Only Look At CoefficienTs. (**[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/html/Bolya_YOLACT_Real-Time_Instance_Segmentation_ICCV_2019_paper.html), [IEEE TPAMI 2020](https://ieeexplore.ieee.org/abstract/document/9159935)**)

    - [Alpha-IoU](https://github.com/Jacobi93/Alpha-IoU) <img src="https://img.shields.io/github/stars/Jacobi93/Alpha-IoU?style=social"/> : "Alpha-IoU: A Family of Power Intersection over Union Losses for Bounding Box Regression". (**[NeurIPS 2021](https://proceedings.neurips.cc//paper/2021/hash/a8f15eda80c50adb0e71943adc8015cf-Abstract.html)**)

    - [CIoU](https://github.com/Zzh-tju/CIoU) <img src="https://img.shields.io/github/stars/Zzh-tju/CIoU?style=social"/> : Complete-IoU (CIoU) Loss and Cluster-NMS for Object Detection and Instance Segmentation (YOLACT). (**[AAAI 2020](https://ojs.aaai.org/index.php/AAAI/article/view/6999), [IEEE TCYB 2021](https://ieeexplore.ieee.org/abstract/document/9523600)**)

    - [Albumentations](https://github.com/albumentations-team/albumentations) <img src="https://img.shields.io/github/stars/albumentations-team/albumentations?style=social"/> : Albumentations is a Python library for image augmentation. Image augmentation is used in deep learning and computer vision tasks to increase the quality of trained models. The purpose of image augmentation is to create new training samples from the existing data. "Albumentations: Fast and Flexible Image Augmentations". (**[Information 2020](https://www.mdpi.com/2078-2489/11/2/125)**)

    - [doubleZ0108/Data-Augmentation](https://github.com/doubleZ0108/Data-Augmentation) <img src="https://img.shields.io/github/stars/doubleZ0108/Data-Augmentation?style=social"/> : General Data Augmentation Algorithms for Object Detection(esp. Yolo).




  - ### Awesome List

    - [awesome-yolo-object-detection](https://github.com/coderonion/awesome-yolo-object-detection) <img src="https://img.shields.io/github/stars/coderonion/awesome-yolo-object-detection?style=social"/> : 🚀🚀🚀 A collection of some awesome public YOLO object detection series projects and the related object detection datasets.

    - [srebroa/awesome-yolo](https://github.com/srebroa/awesome-yolo) <img src="https://img.shields.io/github/stars/srebroa/awesome-yolo?style=social"/> : 🚀 ⭐ The list of the most popular YOLO algorithms - awesome YOLO.

    - [Bubble-water/YOLO-Summary](https://github.com/Bubble-water/YOLO-Summary) <img src="https://img.shields.io/github/stars/Bubble-water/YOLO-Summary?style=social"/> : YOLO-Summary.

    - [WZMIAOMIAO/deep-learning-for-image-processing](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing) <img src="https://img.shields.io/github/stars/WZMIAOMIAO/deep-learning-for-image-processing?style=social"/> : deep learning for image processing including classification and object-detection etc.

    - [hoya012/deep_learning_object_detection](https://github.com/hoya012/deep_learning_object_detection) <img src="https://img.shields.io/github/stars/hoya012/deep_learning_object_detection?style=social"/> : A paper list of object detection using deep learning.

    - [amusi/awesome-object-detection](https://github.com/amusi/awesome-object-detection) <img src="https://img.shields.io/github/stars/amusi/awesome-object-detection?style=social"/> : Awesome Object Detection.


    - [wenhwu/awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection) <img src="https://img.shields.io/github/stars/wenhwu/awesome-remote-sensing-change-detection?style=social"/> : List of datasets, codes, and contests related to remote sensing change detection.

    - [ZHOUYI1023/awesome-radar-perception](https://github.com/ZHOUYI1023/awesome-radar-perception) <img src="https://img.shields.io/github/stars/ZHOUYI1023/awesome-radar-perception?style=social"/> : A curated list of radar datasets, detection, tracking and fusion.

    - [lartpang/awesome-segmentation-saliency-dataset](https://github.com/lartpang/awesome-segmentation-saliency-dataset) <img src="https://img.shields.io/github/stars/lartpang/awesome-segmentation-saliency-dataset?style=social"/> : A collection of some datasets for segmentation / saliency detection. Welcome to PR...😄

    - [TianhaoFu/Awesome-3D-Object-Detection](https://github.com/TianhaoFu/Awesome-3D-Object-Detection) <img src="https://img.shields.io/github/stars/TianhaoFu/Awesome-3D-Object-Detection?style=social"/> : Papers, code and datasets about deep learning for 3D Object Detection.

    - [xahidbuffon/Awesome_Underwater_Datasets](https://github.com/xahidbuffon/Awesome_Underwater_Datasets) <img src="https://img.shields.io/github/stars/xahidbuffon/Awesome_Underwater_Datasets?style=social"/> : Pointers to large-scale underwater datasets and relevant resources.

    - [M-3LAB/awesome-industrial-anomaly-detection](https://github.com/M-3LAB/awesome-industrial-anomaly-detection) <img src="https://img.shields.io/github/stars/M-3LAB/awesome-industrial-anomaly-detection?style=social"/> : Paper list and datasets for industrial image anomaly detection.

    - [ZhangXiwuu/Awesome_visual_place_recognition_datasets](https://github.com/ZhangXiwuu/Awesome_visual_place_recognition_datasets) <img src="https://img.shields.io/github/stars/ZhangXiwuu/Awesome_visual_place_recognition_datasets?style=social"/> : A curated list of Visual Place Recognition (VPR)/ loop closure detection (LCD) datasets.

    - [ari-dasci/OD-WeaponDetection](https://github.com/ari-dasci/OD-WeaponDetection) <img src="https://img.shields.io/github/stars/ari-dasci/OD-WeaponDetection?style=social"/> : Datasets for weapon detection based on image classification and object detection tasks.

    - [DLLXW/objectDetectionDatasets](https://github.com/DLLXW/objectDetectionDatasets) <img src="https://img.shields.io/github/stars/DLLXW/objectDetectionDatasets?style=social"/> : 目标检测数据集制作:VOC,COCO,YOLO等常用数据集格式的制作和互相转换脚本。

    - [kuanhungchen/awesome-tiny-object-detection](https://github.com/kuanhungchen/awesome-tiny-object-detection) <img src="https://img.shields.io/github/stars/kuanhungchen/awesome-tiny-object-detection?style=social"/> : 🕶 A curated list of Tiny Object Detection papers and related resources.




  - ### Paper and Code Overview

    - #### Paper Review

      - [52CV/CV-Surveys](https://github.com/52CV/CV-Surveys) <img src="https://img.shields.io/github/stars/52CV/CV-Surveys?style=social"/> : 计算机视觉相关综述。包括目标检测、跟踪........

      - [GreenTeaHua/YOLO-Review](https://github.com/GreenTeaHua/YOLO-Review) <img src="https://img.shields.io/github/stars/GreenTeaHua/YOLO-Review?style=social"/> : "A Review of YOLO Object Detection Based on Deep Learning". "基于深度学习的YOLO目标检测综述". (**[Journal of Electronics & Information Technology 2022](https://jeit.ac.cn/cn/article/doi/10.11999/JEIT210790)**)

      - "A Review of Yolo Algorithm Developments". (**[Procedia Computer Science 2022](https://www.sciencedirect.com/science/article/pii/S1877050922001363)**)



    - #### Code Review

      - [iscyy/ultralyticsPro](https://github.com/iscyy/ultralyticsPro) <img src="https://img.shields.io/github/stars/iscyy/ultralyticsPro?style=social"/> : 🔥🔥🔥 专注于YOLO11，YOLOv8、YOLOv10、RT-DETR、YOLOv7、YOLOv5改进模型，Support to improve backbone, neck, head, loss, IoU, NMS and other modules🚀

      - [MMDetection](https://github.com/open-mmlab/mmdetection) <img src="https://img.shields.io/github/stars/open-mmlab/mmdetection?style=social"/> : OpenMMLab Detection Toolbox and Benchmark. [mmdetection.readthedocs.io](https://mmdetection.readthedocs.io/en/latest/). (**[arXiv 2019](https://arxiv.org/abs/1906.07155)**)

      - [MMYOLO](https://github.com/open-mmlab/mmyolo) <img src="https://img.shields.io/github/stars/open-mmlab/mmyolo?style=social"/> : OpenMMLab YOLO series toolbox and benchmark. Implemented RTMDet, RTMDet-Rotated,YOLOv5, YOLOv6, YOLOv7, YOLOv8, YOLOX, PPYOLOE, etc. [mmyolo.readthedocs.io/zh_CN/dev/](https://mmyolo.readthedocs.io/zh_CN/dev/)

      - [iscyy/yoloair](https://github.com/iscyy/yoloair) <img src="https://img.shields.io/github/stars/iscyy/yoloair?style=social"/> :  🔥🔥🔥 专注于YOLO改进模型，Support to improve backbone, neck, head, loss, IoU, NMS and other modules🚀.  YOLOAir是一个基于PyTorch的YOLO算法库。统一模型代码框架、统一应用、统一改进、易于模块组合、构建更强大的网络模型。

      - [iscyy/yoloair2](https://github.com/iscyy/yoloair2) <img src="https://img.shields.io/github/stars/iscyy/yoloair2?style=social"/> : ☁️💡🎈专注于改进YOLOv7，Support to improve Backbone, Neck, Head, Loss, IoU, NMS and other modules.

      - [jizhishutong/YOLOU](https://github.com/jizhishutong/YOLOU) <img src="https://img.shields.io/github/stars/jizhishutong/YOLOU?style=social"/> : YOLOU：United, Study and easier to Deploy. ​ The purpose of our creation of YOLOU is to better learn the algorithms of the YOLO series and pay tribute to our predecessors. YOLOv3、YOLOv4、YOLOv5、YOLOv5-Lite、YOLOv6-v1、YOLOv6-v2、YOLOv7、YOLOX、YOLOX-Lite、PP-YOLOE、PP-PicoDet-Plus、YOLO-Fastest v2、FastestDet、YOLOv5-SPD、TensorRT、NCNN、Tengine、OpenVINO. "微信公众号「集智书童」《[YOLOU开源 | 汇集YOLO系列所有算法，集算法学习、科研改进、落地于一身！](https://mp.weixin.qq.com/s/clupheQ8iHnhR4FJcTtB8A)》"

      - [WangQvQ/Yolov5_Magic](https://github.com/WangQvQ/Yolov5_Magic) <img src="https://img.shields.io/github/stars/WangQvQ/Yolov5_Magic?style=social"/> : YOLO Magic🪄 is an extension based on Ultralytics' YOLOv5, designed to provide more powerful functionality and simpler operations for visual tasks.

      - [positive666/yolo_research](https://github.com/positive666/yolo_research) <img src="https://img.shields.io/github/stars/positive666/yolo_research?style=social"/> : 🚀 yolo_reserach PLUS High-level. based on yolo-high-level project (detect\pose\classify\segment\):include yolov5\yolov7\yolov8\ core ,improvement research ,SwintransformV2 and Attention Series. training skills, business customization, engineering deployment.

      - [augmentedstartups/AS-One](https://github.com/augmentedstartups/AS-One) <img src="https://img.shields.io/github/stars/augmentedstartups/AS-One?style=social"/> : Easy & Modular Computer Vision Detectors and Trackers - Run YOLO-NAS,v8,v7,v6,v5,R,X in under 20 lines of code. [www.augmentedstartups.com](https://www.augmentedstartups.com/)

      - [Oneflow-Inc/one-yolov5](https://github.com/Oneflow-Inc/one-yolov5) <img src="https://img.shields.io/github/stars/Oneflow-Inc/one-yolov5?style=social"/> : A more efficient yolov5 with oneflow backend 🎉🎉🎉. "微信公众号「GiantPandaCV」《[One-YOLOv5 发布，一个训得更快的YOLOv5](https://mp.weixin.qq.com/s/tZ7swUd0biz7G3CiRkHHfw)》"

      - [PaddlePaddle/PaddleYOLO](https://github.com/PaddlePaddle/PaddleYOLO) <img src="https://img.shields.io/github/stars/PaddlePaddle/PaddleYOLO?style=social"/> :  🚀🚀🚀 YOLO series of PaddlePaddle implementation, PP-YOLOE+, YOLOv5, YOLOv6, YOLOv7, YOLOv8, YOLOX, YOLOv5u, YOLOv7u, RTMDet and so on. 🚀🚀🚀

      - [WangRongsheng/BestYOLO](https://github.com/WangRongsheng/BestYOLO) <img src="https://img.shields.io/github/stars/WangRongsheng/BestYOLO?style=social"/> : 🌟Change the world, it will become a better place. | 以科研和竞赛为导向的最好的YOLO实践框架!

      - [KangChou/Cver4s](https://github.com/KangChou/Cver4s) <img src="https://img.shields.io/github/stars/KangChou/Cver4s?style=social"/> : Cver4s：Computer vision algorithm code base.

      - [chaizwj/yolov8-tricks](https://github.com/chaizwj/yolov8-tricks) <img src="https://img.shields.io/github/stars/chaizwj/yolov8-tricks?style=social"/> : 目标检测，采用yolov8作为基准模型，数据集采用VisDrone2019，带有自己的改进策略。









  - ### Learning Resources

    - [zjhellofss/KuiperLLama](https://github.com/zjhellofss/KuiperLLama) <img src="https://img.shields.io/github/stars/zjhellofss/KuiperLLama?style=social"/> : 《动手自制大模型推理框架》。KuiperLLama 动手自制大模型推理框架，支持LLama2/3和Qwen2.5。校招、秋招、春招、实习好项目，带你从零动手实现支持LLama2/3和Qwen2.5的大模型推理框架。

    - [zjhellofss/KuiperInfer](https://github.com/zjhellofss/KuiperInfer) <img src="https://img.shields.io/github/stars/zjhellofss/KuiperInfer?style=social"/> :  校招、秋招、春招、实习好项目！带你从零实现一个高性能的深度学习推理库，支持大模型 llama2 、Unet、Yolov5、Resnet等模型的推理。Implement a high-performance deep learning inference library step by step。

    - [zjhellofss/kuiperdatawhale](https://github.com/zjhellofss/kuiperdatawhale) <img src="https://img.shields.io/github/stars/zjhellofss/kuiperdatawhale?style=social"/> :  从零自制深度学习推理框架。

    - [roboflow/notebooks](https://github.com/roboflow/notebooks) <img src="https://img.shields.io/github/stars/roboflow/notebooks?style=social"/> : Examples and tutorials on using SOTA computer vision models and techniques. Learn everything from old-school ResNet, through YOLO and object-detection transformers like DETR, to the latest models like Grounding DINO and SAM. [roboflow.com/models](https://roboflow.com/models)

    - [yjh0410/PyTorch_YOLO_Tutorial](https://github.com/yjh0410/PyTorch_YOLO_Tutorial) <img src="https://img.shields.io/github/stars/yjh0410/PyTorch_YOLO_Tutorial?style=social"/> : YOLO Tutorial.

    - [HuKai97/yolov5-5.x-annotations](https://github.com/HuKai97/yolov5-5.x-annotations) <img src="https://img.shields.io/github/stars/HuKai97/yolov5-5.x-annotations?style=social"/> : 一个基于yolov5-5.0的中文注释版本！

    - [crkk-feng/yolov5-annotations](https://github.com/crkk-feng/yolov5-annotations) <img src="https://img.shields.io/github/stars/crkk-feng/yolov5-annotations?style=social"/> : A Chinese annotated version of yolov5-5.0.

    - [XiaoJiNu/yolov5-v6-chinese-comment](https://github.com/XiaoJiNu/yolov5-v6-chinese-comment) <img src="https://img.shields.io/github/stars/XiaoJiNu/yolov5-v6-chinese-comment?style=social"/> : yolov5-v6版本注释。

    - [1131624548/About-YOLOv5-7-0](https://github.com/1131624548/About-YOLOv5-7-0) <img src="https://img.shields.io/github/stars/XiaoJiNu/yolov5-v6-chinese-comment?style=social"/> : YOLOv5代码注释。

    - [zyds/yolov5-code](https://github.com/zyds/yolov5-code) <img src="https://img.shields.io/github/stars/zyds/yolov5-code?style=social"/> : 手把手带你实战 YOLOv5。




## Other Versions of YOLO

  - ### PyTorch Implementation

    - [ultralytics/yolov3](https://github.com/ultralytics/yolov3) <img src="https://img.shields.io/github/stars/ultralytics/yolov3?style=social"/> : YOLOv3 in PyTorch > ONNX > CoreML > TFLite.

    - [eriklindernoren/PyTorch-YOLOv3](https://github.com/eriklindernoren/PyTorch-YOLOv3) <img src="https://img.shields.io/github/stars/eriklindernoren/PyTorch-YOLOv3?style=social"/> : Minimal PyTorch implementation of YOLOv3.

    - [Tianxiaomo/pytorch-YOLOv4](https://github.com/Tianxiaomo/pytorch-YOLOv4) <img src="https://img.shields.io/github/stars/Tianxiaomo/pytorch-YOLOv4?style=social"/> : PyTorch ,ONNX and TensorRT implementation of YOLOv4.

    - [ayooshkathuria/pytorch-yolo-v3](https://github.com/ayooshkathuria/pytorch-yolo-v3) <img src="https://img.shields.io/github/stars/ayooshkathuria/pytorch-yolo-v3?style=social"/> : A PyTorch implementation of the YOLO v3 object detection algorithm.

    - [WongKinYiu/PyTorch_YOLOv4](https://github.com/WongKinYiu/PyTorch_YOLOv4) <img src="https://img.shields.io/github/stars/WongKinYiu/PyTorch_YOLOv4?style=social"/> : PyTorch implementation of YOLOv4.

    - [argusswift/YOLOv4-pytorch](https://github.com/argusswift/YOLOv4-pytorch) <img src="https://img.shields.io/github/stars/argusswift/YOLOv4-pytorch?style=social"/> : This is a pytorch repository of YOLOv4, attentive YOLOv4 and mobilenet YOLOv4 with PASCAL VOC and COCO.

    - [longcw/yolo2-pytorch](https://github.com/longcw/yolo2-pytorch) <img src="https://img.shields.io/github/stars/longcw/yolo2-pytorch?style=social"/> : YOLOv2 in PyTorch.

    - [bubbliiiing/yolov5-v6.1-pytorch](https://github.com/bubbliiiing/yolov5-v6.1-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov5-v6.1-pytorch?style=social"/> : 这是一个yolov5-v6.1-pytorch的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov5-pytorch](https://github.com/bubbliiiing/yolov5-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov5-pytorch?style=social"/> : 这是一个YoloV5-pytorch的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov4-pytorch](https://github.com/bubbliiiing/yolov4-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov4-pytorch?style=social"/> : 这是一个YoloV4-pytorch的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov4-tiny-pytorch](https://github.com/bubbliiiing/yolov4-tiny-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov4-tiny-pytorch?style=social"/> : 这是一个YoloV4-tiny-pytorch的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov3-pytorch](https://github.com/bubbliiiing/yolo3-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolo3-pytorch?style=social"/> : 这是一个yolo3-pytorch的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolox-pytorch](https://github.com/bubbliiiing/yolox-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolox-pytorch?style=social"/> : 这是一个yolox-pytorch的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov7-pytorch](https://github.com/bubbliiiing/yolov7-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov7-pytorch?style=social"/> : 这是一个yolov7的库，可以用于训练自己的数据集。

    - [bubbliiiing/yolov8-pytorch](https://github.com/bubbliiiing/yolov8-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov8-pytorch?style=social"/> : 这是一个yolov8-pytorch的仓库，可以用于训练自己的数据集。

    - [BobLiu20/YOLOv3_PyTorch](https://github.com/BobLiu20/YOLOv3_PyTorch) <img src="https://img.shields.io/github/stars/BobLiu20/YOLOv3_PyTorch?style=social"/> : Full implementation of YOLOv3 in PyTorch.

    - [ruiminshen/yolo2-pytorch](https://github.com/ruiminshen/yolo2-pytorch) <img src="https://img.shields.io/github/stars/ruiminshen/yolo2-pytorch?style=social"/> : PyTorch implementation of the YOLO (You Only Look Once) v2.

    - [DeNA/PyTorch_YOLOv3](https://github.com/DeNA/PyTorch_YOLOv3) <img src="https://img.shields.io/github/stars/DeNA/PyTorch_YOLOv3?style=social"/> : Implementation of YOLOv3 in PyTorch.

    - [abeardear/pytorch-YOLO-v1](https://github.com/abeardear/pytorch-YOLO-v1) <img src="https://img.shields.io/github/stars/abeardear/pytorch-YOLO-v1?style=social"/> : an experiment for yolo-v1, including training and testing.

    - [wuzhihao7788/yolodet-pytorch](https://github.com/wuzhihao7788/yolodet-pytorch) <img src="https://img.shields.io/github/stars/wuzhihao7788/yolodet-pytorch?style=social"/> : reproduce the YOLO series of papers in pytorch, including YOLOv4, PP-YOLO, YOLOv5，YOLOv3, etc.

    - [uvipen/Yolo-v2-pytorch](https://github.com/uvipen/Yolo-v2-pytorch) <img src="https://img.shields.io/github/stars/uvipen/Yolo-v2-pytorch?style=social"/> : YOLO for object detection tasks.

    - [Peterisfar/YOLOV3](https://github.com/Peterisfar/YOLOV3) <img src="https://img.shields.io/github/stars/Peterisfar/YOLOV3?style=social"/> : yolov3 by pytorch.

    - [misads/easy_detection](https://github.com/misads/easy_detection) <img src="https://img.shields.io/github/stars/misads/easy_detection?style=social"/> : 一个简单方便的目标检测框架(PyTorch环境可直接运行，不需要cuda编译)，支持Faster_RCNN、Yolo系列(v2~v5)、EfficientDet、RetinaNet、Cascade-RCNN等经典网络。

    - [miemiedetection](https://github.com/miemie2013/miemiedetection) <img src="https://img.shields.io/github/stars/miemie2013/miemiedetection?style=social"/> : Pytorch and ncnn implementation of PPYOLOE、YOLOX、PPYOLO、PPYOLOv2、SOLOv2 an so on.

    - [pjh5672/YOLOv1](https://github.com/pjh5672/YOLOv1) <img src="https://img.shields.io/github/stars/pjh5672/YOLOv1?style=social"/> : YOLOv1 implementation using PyTorch.

    - [pjh5672/YOLOv2](https://github.com/pjh5672/YOLOv2) <img src="https://img.shields.io/github/stars/pjh5672/YOLOv2?style=social"/> : YOLOv2 implementation using PyTorch.

    - [pjh5672/YOLOv3](https://github.com/pjh5672/YOLOv3) <img src="https://img.shields.io/github/stars/pjh5672/YOLOv3?style=social"/> : YOLOv3 implementation using PyTorch.

    - [Iywie/pl_YOLO](https://github.com/Iywie/pl_YOLO) <img src="https://img.shields.io/github/stars/Iywie/pl_YOLO?style=social"/> : YOLOv7, YOLOX and YOLOv5 are working right now.

    - [DavidLandup0/deepvision](https://github.com/DavidLandup0/deepvision) <img src="https://img.shields.io/github/stars/DavidLandup0/deepvision?style=social"/> : PyTorch and TensorFlow/Keras image models with automatic weight conversions and equal API/implementations - Vision Transformer (ViT), ResNetV2, EfficientNetV2, (planned...) DeepLabV3+, ConvNeXtV2, YOLO, NeRF, etc.

    - [theos-ai/easy-yolov7](https://github.com/theos-ai/easy-yolov7) <img src="https://img.shields.io/github/stars/theos-ai/easy-yolov7?style=social"/> : This a clean and easy-to-use implementation of YOLOv7 in PyTorch, made with ❤️ by Theos AI.

  - ### C Implementation

    - [ggml](https://github.com/ggerganov/ggml) <img src="https://img.shields.io/github/stars/ggerganov/ggml?style=social"/> : Tensor library for machine learning. Written in C.

    - [rockcarry/ffcnn](https://github.com/rockcarry/ffcnn) <img src="https://img.shields.io/github/stars/rockcarry/ffcnn?style=social"/> : ffcnn is a cnn neural network inference framework, written in 600 lines C language.

    - [ar7775/Object-Detection-System-Yolo](https://github.com/ar7775/Object-Detection-System-Yolo) <img src="https://img.shields.io/github/stars/ar7775/Object-Detection-System-Yolo?style=social"/> : Object Detection System.

    - [lstuma/YOLO_utils](https://github.com/lstuma/YOLO_utils) <img src="https://img.shields.io/github/stars/lstuma/YOLO_utils?style=social"/> : A few utilities for the YOLO project implemented in C for extra speed.

    - [RajneeshKumar12/yolo-detection-app](https://github.com/RajneeshKumar12/yolo-detection-app) <img src="https://img.shields.io/github/stars/RajneeshKumar12/yolo-detection-app?style=social"/> : Yolo app for object detection.

    - [Deyht/CIANNA](https://github.com/Deyht/CIANNA) <img src="https://img.shields.io/github/stars/Deyht/CIANNA?style=social"/> : CIANNA - Convolutional Interactive Artificial Neural Networks by/for Astrophysicists.









  - ### CPP Implementation

    - [walktree/libtorch-yolov3](https://github.com/walktree/libtorch-yolov3) <img src="https://img.shields.io/github/stars/walktree/libtorch-yolov3?style=social"/> : A Libtorch implementation of the YOLO v3 object detection algorithm, written with pure C++.

    - [yasenh/libtorch-yolov5](https://github.com/yasenh/libtorch-yolov5) <img src="https://img.shields.io/github/stars/yasenh/libtorch-yolov5?style=social"/> : A LibTorch inference implementation of the yolov5.

    - [Nebula4869/YOLOv5-LibTorch](https://github.com/Nebula4869/YOLOv5-LibTorch) <img src="https://img.shields.io/github/stars/Nebula4869/YOLOv5-LibTorch?style=social"/> : Real time object detection with deployment of YOLOv5 through LibTorch C++ API.

    - [ncdhz/YoloV5-LibTorch](https://github.com/ncdhz/YoloV5-LibTorch) <img src="https://img.shields.io/github/stars/ncdhz/YoloV5-LibTorch?style=social"/> : 一个 C++ 版本的 YoloV5 封装库.

    - [Rane2021/yolov5_train_cpp_inference](https://github.com/Rane2021/yolov5_train_cpp_inference) <img src="https://img.shields.io/github/stars/Rane2021/yolov5_train_cpp_inference?style=social"/> : yolov5训练和c++推理代码，效果出色。

    - [stephanecharette/DarkHelp](https://github.com/stephanecharette/DarkHelp) <img src="https://img.shields.io/github/stars/stephanecharette/DarkHelp?style=social"/> : The DarkHelp C++ API is a wrapper to make it easier to use the Darknet neural network framework within a C++ application.

    - [UNeedCryDear/yolov5-opencv-dnn-cpp](https://github.com/UNeedCryDear/yolov5-opencv-dnn-cpp) <img src="https://img.shields.io/github/stars/UNeedCryDear/yolov5-opencv-dnn-cpp?style=social"/> : 使用opencv模块部署yolov5-6.0版本。

    - [UNeedCryDear/yolov5-seg-opencv-onnxruntime-cpp](https://github.com/UNeedCryDear/yolov5-seg-opencv-onnxruntime-cpp) <img src="https://img.shields.io/github/stars/UNeedCryDear/yolov5-seg-opencv-onnxruntime-cpp?style=social"/> : yolov5 segmentation with onnxruntime and opencv.

    - [hpc203/yolov5-dnn-cpp-python](https://github.com/hpc203/yolov5-dnn-cpp-python) <img src="https://img.shields.io/github/stars/hpc203/yolov5-dnn-cpp-python?style=social"/> : 用opencv的dnn模块做yolov5目标检测，包含C++和Python两个版本的程序。

    - [hpc203/yolox-opencv-dnn](https://github.com/hpc203/yolox-opencv-dnn) <img src="https://img.shields.io/github/stars/hpc203/yolox-opencv-dnn?style=social"/> : 使用OpenCV部署YOLOX，支持YOLOX-S、YOLOX-M、YOLOX-L、YOLOX-X、YOLOX-Darknet53五种结构，包含C++和Python两种版本的程序。

    - [hpc203/yolov7-opencv-onnxrun-cpp-py](https://github.com/hpc203/yolov7-opencv-onnxrun-cpp-py) <img src="https://img.shields.io/github/stars/hpc203/yolov7-opencv-onnxrun-cpp-py?style=social"/> : 分别使用OpenCV、ONNXRuntime部署YOLOV7目标检测，一共包含12个onnx模型，依然是包含C++和Python两个版本的程序。

    - [doleron/yolov5-opencv-cpp-python](https://github.com/doleron/yolov5-opencv-cpp-python) <img src="https://img.shields.io/github/stars/doleron/yolov5-opencv-cpp-python?style=social"/> : Example of using ultralytics YOLO V5 with OpenCV 4.5.4, C++ and Python.

    - [UNeedCryDear/yolov8-opencv-onnxruntime-cpp](https://github.com/UNeedCryDear/yolov8-opencv-onnxruntime-cpp) <img src="https://img.shields.io/github/stars/UNeedCryDear/yolov8-opencv-onnxruntime-cpp?style=social"/> : detection and instance segmentation of yolov8,use onnxruntime and opencv.




  - ### ROS Implementation

    - [mgonzs13/yolov8_ros](https://github.com/mgonzs13/yolov8_ros) <img src="https://img.shields.io/github/stars/mgonzs13/yolov8_ros?style=social"/> : Ultralytics YOLOv8, YOLOv9, YOLOv10, YOLOv11 for ROS 2.

    - [leggedrobotics/darknet_ros](https://github.com/leggedrobotics/darknet_ros) <img src="https://img.shields.io/github/stars/leggedrobotics/darknet_ros?style=social"/> : Real-Time Object Detection for ROS.

    - [engcang/ros-yolo-sort](https://github.com/engcang/ros-yolo-sort) <img src="https://img.shields.io/github/stars/engcang/ros-yolo-sort?style=social"/> : YOLO and SORT, and ROS versions of them.

    - [chrisgundling/YoloLight](https://github.com/chrisgundling/YoloLight) <img src="https://img.shields.io/github/stars/chrisgundling/YoloLight?style=social"/> : Tiny-YOLO-v2 ROS Node for Traffic Light Detection.

    - [Ar-Ray-code/YOLOX-ROS](https://github.com/Ar-Ray-code/YOLOX-ROS) <img src="https://img.shields.io/github/stars/Ar-Ray-code/YOLOX-ROS?style=social"/> : YOLOX + ROS2 object detection package.

    - [Ar-Ray-code/YOLOv5-ROS](https://github.com/Ar-Ray-code/YOLOv5-ROS) <img src="https://img.shields.io/github/stars/Ar-Ray-code/YOLOv5-ROS?style=social"/> : YOLOv5 + ROS2 object detection package.

    - [Tossy0423/yolov4-for-darknet_ros](https://github.com/Tossy0423/yolov4-for-darknet_ros) <img src="https://img.shields.io/github/stars/Tossy0423/yolov4-for-darknet_ros?style=social"/> : This is the environment in which YOLO V4 is ported to darknet_ros.

    - [qianmin/yolov5_ROS](https://github.com/qianmin/yolov5_ROS) <img src="https://img.shields.io/github/stars/qianmin/yolov5_ROS?style=social"/> : run YOLOv5 in ROS，ROS使用YOLOv5。

    - [ailllist/yolov5_ROS](https://github.com/ailllist/yolov5_ROS) <img src="https://img.shields.io/github/stars/ailllist/yolov5_ROS?style=social"/> : yolov5 for ros, not webcam.

    - [Shua-Kang/ros_pytorch_yolov5](https://github.com/Shua-Kang/ros_pytorch_yolov5) <img src="https://img.shields.io/github/stars/Shua-Kang/ros_pytorch_yolov5?style=social"/> : A ROS wrapper for yolov5. (master branch is v5.0 of yolov5; for v6.1, see branch v6.1).

    - [ziyan0302/Yolov5_DeepSort_Pytorch_ros](https://github.com/ziyan0302/Yolov5_DeepSort_Pytorch_ros) <img src="https://img.shields.io/github/stars/ziyan0302/Yolov5_DeepSort_Pytorch_ros?style=social"/> : Connect Yolov5 detection module and DeepSort tracking module via ROS.

    - [U07157135/ROS2-with-YOLOv5](https://github.com/U07157135/ROS2-with-YOLOv5) <img src="https://img.shields.io/github/stars/U07157135/ROS2-with-YOLOv5?style=social"/> : 在無人機上以ROS2技術實現YOLOv5物件偵測。

    - [lukazso/yolov6-ros](https://github.com/lukazso/yolov6-ros) <img src="https://img.shields.io/github/stars/lukazso/yolov6-ros?style=social"/> : ROS package for YOLOv6.

    - [qq44642754a/Yolov5_ros](https://github.com/qq44642754a/Yolov5_ros) <img src="https://img.shields.io/github/stars/qq44642754a/Yolov5_ros?style=social"/> : Real-time object detection with ROS, based on YOLOv5 and PyTorch (基于 YOLOv5的ROS实时对象检测).

    - [lukazso/yolov7-ros](https://github.com/lukazso/yolov7-ros) <img src="https://img.shields.io/github/stars/lukazso/yolov7-ros?style=social"/> : ROS package for official YOLOv7.

    - [phuoc101/yolov7_ros](https://github.com/phuoc101/yolov7_ros) <img src="https://img.shields.io/github/stars/phuoc101/yolov7_ros?style=social"/> : ROS package for official YOLOv7.

    - [ConfusionTechnologies/ros-yolov5-node](https://github.com/ConfusionTechnologies/ros-yolov5-node) <img src="https://img.shields.io/github/stars/ConfusionTechnologies/ros-yolov5-node?style=social"/> : For ROS2, uses ONNX GPU Runtime to inference YOLOv5.

    - [Ar-Ray-code/darknet_ros_fp16](https://github.com/Ar-Ray-code/darknet_ros_fp16) <img src="https://img.shields.io/github/stars/Ar-Ray-code/darknet_ros_fp16?style=social"/> : darknet + ROS2 Humble + OpenCV4 + CUDA 11（cuDNN, Jetson Orin）.

    - [wk123467/yolov5s_trt_ros](https://github.com/wk123467/yolov5s_trt_ros) <img src="https://img.shields.io/github/stars/wk123467/yolov5s_trt_ros?style=social"/> : 利用TensorRT对yolov5s进行加速，并将其应用于ROS，实现交通标志、红绿灯(直接输出路灯状态)、行人和车辆等交通场景的检测。

    - [PardisTaghavi/yolov7_strongsort_ros](https://github.com/PardisTaghavi/yolov7_strongsort_ros) <img src="https://img.shields.io/github/stars/PardisTaghavi/yolov7_strongsort_ros?style=social"/> : Integration of "Yolov7 StrongSort" with ROS for real time object tracking.

    - [af-doom/yolov8_ros_tensorrt-](https://github.com/af-doom/yolov8_ros_tensorrt-) <img src="https://img.shields.io/github/stars/af-doom/yolov8_ros_tensorrt-?style=social"/> : This is a YOLOv8 project based on ROS implementation, where YOLOv8 uses Tensorrt acceleration.

    - [KoKoMier/ros_darknet_yolov4](https://github.com/KoKoMier/ros_darknet_yolov4) <img src="https://img.shields.io/github/stars/KoKoMier/ros_darknet_yolov4?style=social"/> : 这是机器人小组视觉与雷达的结合程序，首先通过yolo目标检测识别到物体，然后把识别到的数据发送给ros里面程序，用于雷达数据结合。

    - [YellowAndGreen/Yolov5-OpenCV-Cpp-Python-ROS](https://github.com/YellowAndGreen/Yolov5-OpenCV-Cpp-Python-ROS) <img src="https://img.shields.io/github/stars/YellowAndGreen/Yolov5-OpenCV-Cpp-Python-ROS?style=social"/> : Inference with YOLOv5, OpenCV 4.5.4 DNN, C++, ROS and Python.

    - [mgonzs13/yolov8_ros](https://github.com/mgonzs13/yolov8_ros) <img src="https://img.shields.io/github/stars/mgonzs13/yolov8_ros?style=social"/> : ROS 2 wrap for Ultralytics [YOLOv8](https://github.com/ultralytics/ultralytics) to perform object detection.

    - [fishros/yolov5_ros2](https://github.com/fishros/yolov5_ros2) <img src="https://img.shields.io/github/stars/fishros/yolov5_ros2?style=social"/> : 基于YoloV5的ROS2功能包，可以快速完成物体识别与位姿发布。

    - [fateshelled/EdgeYOLO-ROS](https://github.com/fateshelled/EdgeYOLO-ROS) <img src="https://img.shields.io/github/stars/fateshelled/EdgeYOLO-ROS?style=social"/> : EdgeYOLO + ROS2 object detection package.

    - [vivaldini/yolov6-uav](https://github.com/vivaldini/yolov6-uav) <img src="https://img.shields.io/github/stars/vivaldini/yolov6-uav?style=social"/> : This repository contains a ROS noetic package for YOLOv6 to recognize objects from UAV and provide their positions.

    - [Alpaca-zip/ultralytics_ros](https://github.com/Alpaca-zip/ultralytics_ros) <img src="https://img.shields.io/github/stars/Alpaca-zip/ultralytics_ros?style=social"/> : ROS/ROS2 package for Ultralytics YOLOv8 real-time object detection.


- ### Mojo Implementation

    - [taalhaataahir0102/Mojo-Yolo](https://github.com/taalhaataahir0102/Mojo-Yolo) <img src="https://img.shields.io/github/stars/taalhaataahir0102/Mojo-Yolo?style=social"/> : Mojo-Yolo.


- ### Rust Implementation

    - [Candle](https://github.com/huggingface/candle) <img src="https://img.shields.io/github/stars/huggingface/candle?style=social"/> : Minimalist ML framework for Rust.

    - [Tokenizers](https://github.com/huggingface/tokenizers) <img src="https://img.shields.io/github/stars/huggingface/tokenizers?style=social"/> : 💥 Fast State-of-the-Art Tokenizers optimized for Research and Production. [huggingface.co/docs/tokenizers](https://huggingface.co/docs/tokenizers/index)

    - [Safetensors](https://github.com/huggingface/safetensors) <img src="https://img.shields.io/github/stars/huggingface/safetensors?style=social"/> : Simple, safe way to store and distribute tensors. [huggingface.co/docs/safetensors](https://huggingface.co/docs/safetensors/index)

    - [Burn](https://github.com/burn-rs/burn) <img src="https://img.shields.io/github/stars/burn-rs/burn?style=social"/> : Burn - A Flexible and Comprehensive Deep Learning Framework in Rust. [burn-rs.github.io/](https://burn-rs.github.io/)

    - [TensorFlow Rust](https://github.com/tensorflow/rust) <img src="https://img.shields.io/github/stars/tensorflow/rust?style=social"/> : Rust language bindings for TensorFlow.

    - [tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch.

    - [dfdx](https://github.com/coreylowman/dfdx) <img src="https://img.shields.io/github/stars/coreylowman/dfdx?style=social"/> : Deep learning in Rust, with shape checked tensors and neural networks.

    - [tract](https://github.com/sonos/tract) <img src="https://img.shields.io/github/stars/sonos/tract?style=social"/> : Sonos' Neural Network inference engine. Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference

    - [ort](https://github.com/pykeio/ort) <img src="https://img.shields.io/github/stars/pykeio/ort?style=social"/> : A Rust wrapper for ONNX Runtime. [docs.rs/ort](https://docs.rs/ort/latest/ort/)

    - [usls](https://github.com/jamjamjon/usls) <img src="https://img.shields.io/github/stars/jamjamjon/usls?style=social"/> : A Rust library integrated with ONNXRuntime, providing a collection of Computer Vison and Vision-Language models.

    - [ptaxom/pnn](https://github.com/ptaxom/pnn) <img src="https://img.shields.io/github/stars/ptaxom/pnn?style=social"/> : pnn is [Darknet](https://github.com/alexeyAB/darknet) compatible neural nets inference engine implemented in Rust. By optimizing was achieved significant performance increment(especially in FP16 mode). pnn provide CUDNN-based and TensorRT-based inference engines.

    - [bencevans/rust-opencv-yolov5](https://github.com/bencevans/rust-opencv-yolov5) <img src="https://img.shields.io/github/stars/bencevans/rust-opencv-yolov5?style=social"/> : YOLOv5 Inference with ONNX & OpenCV in Rust.

    - [masc-it/yolov5-api-rust](https://github.com/masc-it/yolov5-api-rust) <img src="https://img.shields.io/github/stars/masc-it/yolov5-api-rust?style=social"/> : Rust API to run predictions with YoloV5 models.

    - [AndreyGermanov/yolov8_onnx_rust](https://github.com/AndreyGermanov/yolov8_onnx_rust) <img src="https://img.shields.io/github/stars/AndreyGermanov/yolov8_onnx_rust?style=social"/> : YOLOv8 inference using Rust.

    - [igor-yusupov/rusty-yolo](https://github.com/igor-yusupov/rusty-yolo) <img src="https://img.shields.io/github/stars/igor-yusupov/rusty-yolo?style=social"/> : rusty-yolo.

    - [gsuyemoto/yolo-rust](https://github.com/gsuyemoto/yolo-rust) <img src="https://img.shields.io/github/stars/gsuyemoto/yolo-rust?style=social"/> : Run YOLO computer vision model using Rust and OpenCV and/or Torch.

    - [alianse777/darknet-rust](https://github.com/alianse777/darknet-rust) <img src="https://img.shields.io/github/stars/alianse777/darknet-rust?style=social"/> : A Rust wrapper for Darknet, an open source neural network framework written in C and CUDA. [pjreddie.com/darknet/](https://pjreddie.com/darknet/)

    - [12101111/yolo-rs](https://github.com/12101111/yolo-rs) <img src="https://img.shields.io/github/stars/12101111/yolo-rs?style=social"/> : Yolov3 & Yolov4 with TVM and rust.

    - [TKGgunter/yolov4_tiny_rs](https://github.com/TKGgunter/yolov4_tiny_rs) <img src="https://img.shields.io/github/stars/TKGgunter/yolov4_tiny_rs?style=social"/> : A rust implementation of yolov4_tiny algorithm.

    - [flixstn/You-Only-Look-Once](https://github.com/flixstn/You-Only-Look-Once) <img src="https://img.shields.io/github/stars/flixstn/You-Only-Look-Once?style=social"/> : A Rust implementation of Yolo for object detection and tracking.

    - [lenna-project/yolo-plugin](https://github.com/lenna-project/yolo-plugin) <img src="https://img.shields.io/github/stars/lenna-project/yolo-plugin?style=social"/> : Yolo Object Detection Plugin for Lenna.

    - [laclouis5/globox-rs](https://github.com/laclouis5/globox-rs) <img src="https://img.shields.io/github/stars/laclouis5/globox-rs?style=social"/> : Object detection toolbox for parsing, converting and evaluating bounding box annotations.

    - [metobom/tchrs-opencv-webcam-inference](https://github.com/metobom/tchrs-opencv-webcam-inference) <img src="https://img.shields.io/github/stars/metobom/tchrs-opencv-webcam-inference?style=social"/> : This example shows steps for running a Python trained model on webcam feed with opencv and tch-rs. Model will run on GPU.



  - ### Go Implementation

    - [LdDl/go-darknet](https://github.com/LdDl/go-darknet) <img src="https://img.shields.io/github/stars/LdDl/go-darknet?style=social"/> : go-darknet: Go bindings for Darknet (Yolo V4, Yolo V7-tiny, Yolo V3).

    - [adalkiran/distributed-inference](https://github.com/adalkiran/distributed-inference) <img src="https://img.shields.io/github/stars/adalkiran/distributed-inference?style=social"/> : Cross-language and distributed deep learning inference pipeline for WebRTC video streams over Redis Streams. Currently supports YOLOX model, which can run well on CPU.

    - [wimspaargaren/yolov3](https://github.com/wimspaargaren/yolov3) <img src="https://img.shields.io/github/stars/wimspaargaren/yolov3?style=social"/> : Go implementation of the yolo v3 object detection system.

    - [wimspaargaren/yolov5](https://github.com/wimspaargaren/yolov5) <img src="https://img.shields.io/github/stars/wimspaargaren/yolov5?style=social"/> : Go implementation of the yolo v5 object detection system.

    - [genert/real_time_object_detection_go](https://github.com/genert/real_time_object_detection_go) <img src="https://img.shields.io/github/stars/genert/real_time_object_detection_go?style=social"/> : Real Time Object Detection with OpenCV, Go, and Yolo v4.



  - ### CSharp Implementation

    - [ML.NET](https://github.com/dotnet/machinelearning) <img src="https://img.shields.io/github/stars/dotnet/machinelearning?style=social"/> : ML.NET is an open source and cross-platform machine learning framework for .NET.

    - [TorchSharp](https://github.com/dotnet/TorchSharp) <img src="https://img.shields.io/github/stars/dotnet/TorchSharp?style=social"/> : A .NET library that provides access to the library that powers PyTorch.

    - [TensorFlow.NET](https://github.com/SciSharp/TensorFlow.NET) <img src="https://img.shields.io/github/stars/SciSharp/TensorFlow.NET?style=social"/> : .NET Standard bindings for Google's TensorFlow for developing, training and deploying Machine Learning models in C# and F#.

    - [DlibDotNet](https://github.com/takuya-takeuchi/DlibDotNet) <img src="https://img.shields.io/github/stars/takuya-takeuchi/DlibDotNet?style=social"/> : Dlib .NET wrapper written in C++ and C# for Windows, MacOS, Linux and iOS.

    - [DiffSharp](https://github.com/DiffSharp/DiffSharp) <img src="https://img.shields.io/github/stars/DiffSharp/DiffSharp?style=social"/> : DiffSharp: Differentiable Functional Programming.

    - [dme-compunet/YOLOv8](https://github.com/dme-compunet/YOLOv8) <img src="https://img.shields.io/github/stars/dme-compunet/YOLOv8?style=social"/> : Use YOLOv8 in real-time, for object detection, instance segmentation, pose estimation and image classification, via ONNX Runtime. [www.nuget.org/packages/YoloV8](https://www.nuget.org/packages/YoloV8)

    - [techwingslab/yolov5-net](https://github.com/techwingslab/yolov5-net) <img src="https://img.shields.io/github/stars/techwingslab/yolov5-net?style=social"/> : YOLOv5 object detection with C#, ML.NET, ONNX.

    - [sstainba/Yolov8.Net](https://github.com/sstainba/Yolov8.Net) <img src="https://img.shields.io/github/stars/sstainba/Yolov8.Net?style=social"/> : A .net 6 implementation to use Yolov5 and Yolov8 models via the ONNX Runtime.

    - [Alturos.Yolo](https://github.com/AlturosDestinations/Alturos.Yolo) <img src="https://img.shields.io/github/stars/AlturosDestinations/Alturos.Yolo?style=social"/> : C# Yolo Darknet Wrapper (real-time object detection).

    - [ivilson/Yolov7net](https://github.com/ivilson/Yolov7net) <img src="https://img.shields.io/github/stars/ivilson/Yolov7net?style=social"/> : Yolov7 Detector for .Net 6.

    - [sangyuxiaowu/ml_yolov7](https://github.com/sangyuxiaowu/ml_yolov7) <img src="https://img.shields.io/github/stars/sangyuxiaowu/ml_yolov7?style=social"/> : ML.NET Yolov7. "微信公众号「桑榆肖物」《[YOLOv7 在 ML.NET 中使用 ONNX 检测对象](https://mp.weixin.qq.com/s/vXz6gavYJR2mh5KuJO_slA)》"

    - [keijiro/TinyYOLOv2Barracuda](https://github.com/keijiro/TinyYOLOv2Barracuda) <img src="https://img.shields.io/github/stars/keijiro/TinyYOLOv2Barracuda?style=social"/> : Tiny YOLOv2 on Unity Barracuda.

    - [derenlei/Unity_Detection2AR](https://github.com/derenlei/Unity_Detection2AR) <img src="https://img.shields.io/github/stars/derenlei/Unity_Detection2AR?style=social"/> : Localize 2D image object detection in 3D Scene with Yolo in Unity Barracuda and ARFoundation.

    - [died/YOLO3-With-OpenCvSharp4](https://github.com/died/YOLO3-With-OpenCvSharp4) <img src="https://img.shields.io/github/stars/died/YOLO3-With-OpenCvSharp4?style=social"/> : Demo of implement YOLO v3 with OpenCvSharp v4 on C#.

    - [mbaske/yolo-unity](https://github.com/mbaske/yolo-unity) <img src="https://img.shields.io/github/stars/mbaske/yolo-unity?style=social"/> : YOLO In-Game Object Detection for Unity (Windows).

    - [BobLd/YOLOv4MLNet](https://github.com/BobLd/YOLOv4MLNet) <img src="https://img.shields.io/github/stars/BobLd/YOLOv4MLNet?style=social"/> : Use the YOLO v4 and v5 (ONNX) models for object detection in C# using ML.Net.

    - [keijiro/YoloV4TinyBarracuda](https://github.com/keijiro/YoloV4TinyBarracuda) <img src="https://img.shields.io/github/stars/keijiro/YoloV4TinyBarracuda?style=social"/> : YoloV4TinyBarracuda is an implementation of the YOLOv4-tiny object detection model on the Unity Barracuda neural network inference library.

    - [zhang8043/YoloWrapper](https://github.com/zhang8043/YoloWrapper) <img src="https://img.shields.io/github/stars/zhang8043/YoloWrapper?style=social"/> : C#封装YOLOv4算法进行目标检测。

    - [maalik0786/FastYolo](https://github.com/maalik0786/FastYolo) <img src="https://img.shields.io/github/stars/maalik0786/FastYolo?style=social"/> : Fast Yolo for fast initializing, object detection and tracking.

    - [Uehwan/CSharp-Yolo-Video](https://github.com/Uehwan/CSharp-Yolo-Video) <img src="https://img.shields.io/github/stars/Uehwan/CSharp-Yolo-Video?style=social"/> : C# Yolo for Video.

    - [HTTP123-A/HumanDetection_Yolov5NET](https://github.com/https://github.com/HTTP123-A/HumanDetection_Yolov5NET) <img src="https://img.shields.io/github/stars/HTTP123-A/HumanDetection_Yolov5NET?style=social"/> : YOLOv5 object detection with ML.NET, ONNX.

    - [Celine-Hsieh/Hand_Gesture_Training--yolov4](https://github.com/Celine-Hsieh/Hand_Gesture_Training--yolov4) <img src="https://img.shields.io/github/stars/Celine-Hsieh/Hand_Gesture_Training--yolov4?style=social"/> : Recognize the gestures' features using the YOLOv4 algorithm.

    - [lin-tea/YOLOv5DetectionWithCSharp](https://github.com/lin-tea/YOLOv5DetectionWithCSharp) <img src="https://img.shields.io/github/stars/lin-tea/YOLOv5DetectionWithCSharp?style=social"/> : YOLOv5s inference In C# and Training In Python.

    - [MirCore/Unity-Object-Detection-and-Localization-with-VR](https://github.com/MirCore/Unity-Object-Detection-and-Localization-with-VR) <img src="https://img.shields.io/github/stars/MirCore/Unity-Object-Detection-and-Localization-with-VR?style=social"/> : Detect and localize objects from the front-facing camera image of a VR Headset in a 3D Scene in Unity using Yolo and Barracuda.

    - [CarlAreDHopen-eaton/YoloObjectDetection](https://github.com/CarlAreDHopen-eaton/YoloObjectDetection) <img src="https://img.shields.io/github/stars/CarlAreDHopen-eaton/YoloObjectDetection?style=social"/> : Yolo Object Detection Application for RTSP streams.

    - [TimothyMeadows/Yolo6.NetCore](https://github.com/TimothyMeadows/Yolo6.NetCore) <img src="https://img.shields.io/github/stars/TimothyMeadows/Yolo6.NetCore?style=social"/> : You Only Look Once (v6) for .NET Core LTS.

    - [mwetzko/EasyYoloDarknet](https://github.com/mwetzko/EasyYoloDarknet) <img src="https://img.shields.io/github/stars/mwetzko/EasyYoloDarknet?style=social"/> : EasyYoloDarknet.

    - [mwetzko/EasyYoloDarknet](https://github.com/mwetzko/EasyYoloDarknet) <img src="https://img.shields.io/github/stars/mwetzko/EasyYoloDarknet?style=social"/> : Windows optimized Yolo / Darknet Compile, Train and Detect.

    - [cj-mills/Unity-OpenVINO-YOLOX](https://github.com/cj-mills/Unity-OpenVINO-YOLOX) <img src="https://img.shields.io/github/stars/cj-mills/Unity-OpenVINO-YOLOX?style=social"/> : This tutorial series covers how to perform object detection in the Unity game engine with the OpenVINO™ Toolkit.

    - [natml-hub/YOLOX](https://github.com/natml-hub/YOLOX) <img src="https://img.shields.io/github/stars/natml-hub/YOLOX?style=social"/> : High performance object detector based on YOLO series.

    - [thisistherealdiana/YOLO_project](https://github.com/thisistherealdiana/YOLO_project) <img src="https://img.shields.io/github/stars/thisistherealdiana/YOLO_project?style=social"/> : YOLO project made by Diana Kereselidze.

    - [oujunke/Yolo5Net](https://github.com/oujunke/Yolo5Net) <img src="https://img.shields.io/github/stars/oujunke/Yolo5Net?style=social"/> : Yolo5实现于TensorFlow.Net.

    - [wojciechp6/YOLO-UnityBarracuda](https://github.com/wojciechp6/YOLO-UnityBarracuda) <img src="https://img.shields.io/github/stars/wojciechp6/YOLO-UnityBarracuda?style=social"/> : Object detection app build on Unity Barracuda and YOLOv2 Tiny.

    - [RaminAbbaszadi/YoloWrapper-WPF](https://github.com/RaminAbbaszadi/YoloWrapper-WPF) <img src="https://img.shields.io/github/stars/RaminAbbaszadi/YoloWrapper-WPF?style=social"/> : WPF (C#) Yolo Darknet Wrapper.

    - [fengyhack/YoloWpf](https://github.com/fengyhack/YoloWpf) <img src="https://img.shields.io/github/stars/fengyhack/YoloWpf?style=social"/> : GUI demo for Object Detection with YOLO and OpenCVSharp.

    - [hanzhuang111/Yolov5Wpf](https://github.com/hanzhuang111/Yolov5Wpf) <img src="https://img.shields.io/github/stars/hanzhuang111/Yolov5Wpf?style=social"/> : 使用ML.NET部署YOLOV5 的ONNX模型。

    - [MaikoKingma/yolo-winforms-test](https://github.com/MaikoKingma/yolo-winforms-test) <img src="https://img.shields.io/github/stars/MaikoKingma/yolo-winforms-test?style=social"/> : A Windows forms application that can execute pre-trained object detection models via ML.NET. In this instance the You Only Look Once version 4 (yolov4) is used.

    - [SeanAnd/WebcamObjectDetection](https://github.com/SeanAnd/WebcamObjectDetection) <img src="https://img.shields.io/github/stars/SeanAnd/WebcamObjectDetection?style=social"/> : YOLO object detection using webcam in winforms.

    - [Devmawi/BlazorObjectDetection-Sample](https://github.com/Devmawi/BlazorObjectDetection-Sample) <img src="https://img.shields.io/github/stars/Devmawi/BlazorObjectDetection-Sample?style=social"/> : Simple project for demonstrating how to embed a continuously object detection with Yolo on a video in a hybrid Blazor app (WebView2).

    - [Soju06/yolov5-annotation-viewer](https://github.com/Soju06/yolov5-annotation-viewer) <img src="https://img.shields.io/github/stars/Soju06/yolov5-annotation-viewer?style=social"/> : yolov5 annotation viewer.

    - [developer-ken/YoloPredictorMLDotNet](https://github.com/developer-ken/YoloPredictorMLDotNet) <img src="https://img.shields.io/github/stars/developer-ken/YoloPredictorMLDotNet?style=social"/> : YoloPredictorMLDotNet.

    - [LionelC-Kyo/CSharp_YoloV5_Torch](https://github.com/LionelC-Kyo/CSharp_YoloV5_Torch) <img src="https://img.shields.io/github/stars/LionelC-Kyo/CSharp_YoloV5_Torch?style=social"/> : Run Yolo V5 in C# By Torch.

    - [wanglvhang/OnnxYoloDemo](https://github.com/wanglvhang/OnnxYoloDemo) <img src="https://img.shields.io/github/stars/wanglvhang/OnnxYoloDemo?style=social"/> : demo of using c# to run yolo onnx model with onnx runtime, and contains a windows capture tool to get bitmap from windows desktop and window.

    - [BobLd/YOLOv3MLNet](https://github.com/BobLd/YOLOv3MLNet) <img src="https://img.shields.io/github/stars/BobLd/YOLOv3MLNet?style=social"/> : Use the YOLO v3 (ONNX) model for object detection in C# using ML.Net.

    - [zgabi/Yolo.Net](https://github.com/zgabi/Yolo.Net) <img src="https://img.shields.io/github/stars/zgabi/Yolo.Net?style=social"/> : zgabi/Yolo.Net

    - [aliardan/RoadMarkingDetection](https://github.com/aliardan/RoadMarkingDetection) <img src="https://img.shields.io/github/stars/aliardan/RoadMarkingDetection?style=social"/> : Road markings detection using yolov5 model based on ONNX.

    - [TimothyMeadows/Yolo5.NetCore](https://github.com/TimothyMeadows/Yolo5.NetCore) <img src="https://img.shields.io/github/stars/TimothyMeadows/Yolo5.NetCore?style=social"/> : You Only Look Once (v5) for .NET Core LTS.

    - [AD-HO/YOLOv5-ML.NET](https://github.com/AD-HO/YOLOv5-ML.NET) <img src="https://img.shields.io/github/stars/AD-HO/YOLOv5-ML.NET?style=social"/> : Inferencing Yolov5 ONNX model using ML.NET and ONNX Runtime.

    - [ToxicSkill/YOLOV7-Webcam-inference](https://github.com/ToxicSkill/YOLOV7-Webcam-inference) <img src="https://img.shields.io/github/stars/ToxicSkill/YOLOV7-Webcam-inference?style=social"/> : Simple WPF program for webcam inference with yoloV7 models.

    - [aliardan/RoadMarkingDetection](https://github.com/aliardan/RoadMarkingDetection) <img src="https://img.shields.io/github/stars/aliardan/RoadMarkingDetection?style=social"/> : Road markings detection using yolov5 model based on ONNX.

    - [rabbitsun2/csharp_and_microsoft_ml_and_yolo_v5_sample](https://github.com/rabbitsun2/csharp_and_microsoft_ml_and_yolo_v5_sample) <img src="https://img.shields.io/github/stars/rabbitsun2/csharp_and_microsoft_ml_and_yolo_v5_sample?style=social"/> : C#, Microsoft ML, Yolo v5, Microsoft ML.DNN, OpenCVSharp4 연계 프로젝트.

    - [hsysfan/YOLOv5-Seg-OnnxRuntime](https://github.com/hsysfan/YOLOv5-Seg-OnnxRuntime) <img src="https://img.shields.io/github/stars/hsysfan/YOLOv5-Seg-OnnxRuntime?style=social"/> : YOLOv5 Segmenation Implementation in C# and OnnxRuntime.

    - [dme-compunet/YOLOv8](https://github.com/dme-compunet/YOLOv8) <img src="https://img.shields.io/github/stars/dme-compunet/YOLOv8?style=social"/> : Use YOLOv8 in real-time, for object detection, instance segmentation, pose estimation and image classification, via ONNX Runtime.









  - ### Tensorflow and Keras Implementation

    - [YunYang1994/tensorflow-yolov3](https://github.com/YunYang1994/tensorflow-yolov3) <img src="https://img.shields.io/github/stars/YunYang1994/tensorflow-yolov3?style=social"/> : 🔥 TensorFlow Code for technical report: "YOLOv3: An Incremental Improvement".

    - [zzh8829/yolov3-tf2](https://github.com/zzh8829/yolov3-tf2) <img src="https://img.shields.io/github/stars/zzh8829/yolov3-tf2?style=social"/> : YoloV3 Implemented in Tensorflow 2.0.

    - [hunglc007/tensorflow-yolov4-tflite](https://github.com/hunglc007/tensorflow-yolov4-tflite) <img src="https://img.shields.io/github/stars/hunglc007/tensorflow-yolov4-tflite?style=social"/> : YOLOv4, YOLOv4-tiny, YOLOv3, YOLOv3-tiny Implemented in Tensorflow 2.0, Android. Convert YOLO v4 .weights tensorflow, tensorrt and tflite.

    - [gliese581gg/YOLO_tensorflow](https://github.com/gliese581gg/YOLO_tensorflow) <img src="https://img.shields.io/github/stars/gliese581gg/YOLO_tensorflow?style=social"/> : tensorflow implementation of 'YOLO : Real-Time Object Detection'.

    - [llSourcell/YOLO_Object_Detection](https://github.com/llSourcell/YOLO_Object_Detection) <img src="https://img.shields.io/github/stars/llSourcell/YOLO_Object_Detection?style=social"/> : This is the code for "YOLO Object Detection" by Siraj Raval on Youtube.

    - [wizyoung/YOLOv3_TensorFlow](https://github.com/wizyoung/YOLOv3_TensorFlow) <img src="https://img.shields.io/github/stars/wizyoung/YOLOv3_TensorFlow?style=social"/> : Complete YOLO v3 TensorFlow implementation. Support training on your own dataset.

    - [theAIGuysCode/yolov4-deepsort](https://github.com/theAIGuysCode/yolov4-deepsort) <img src="https://img.shields.io/github/stars/theAIGuysCode/yolov4-deepsort?style=social"/> : Object tracking implemented with YOLOv4, DeepSort, and TensorFlow.

    - [mystic123/tensorflow-yolo-v3](https://github.com/mystic123/tensorflow-yolo-v3) <img src="https://img.shields.io/github/stars/mystic123/tensorflow-yolo-v3?style=social"/> : Implementation of YOLO v3 object detector in Tensorflow (TF-Slim).

    - [hizhangp/yolo_tensorflow](https://github.com/hizhangp/yolo_tensorflow) <img src="https://img.shields.io/github/stars/hizhangp/yolo_tensorflow?style=social"/> : Tensorflow implementation of YOLO, including training and test phase.

    - [nilboy/tensorflow-yolo](https://github.com/nilboy/tensorflow-yolo) <img src="https://img.shields.io/github/stars/nilboy/tensorflow-yolo?style=social"/> : tensorflow implementation of 'YOLO : Real-Time Object Detection'(train and test).

    - [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3) <img src="https://img.shields.io/github/stars/qqwweee/keras-yolo3?style=social"/> : A Keras implementation of YOLOv3 (Tensorflow backend).

    - [allanzelener/YAD2K](https://github.com/allanzelener/YAD2K) <img src="https://img.shields.io/github/stars/allanzelener/YAD2K?style=social"/> : YAD2K: Yet Another Darknet 2 Keras.

    - [experiencor/keras-yolo2](https://github.com/experiencor/keras-yolo2) <img src="https://img.shields.io/github/stars/experiencor/keras-yolo2?style=social"/> : YOLOv2 in Keras and Applications.

    - [experiencor/keras-yolo3](https://github.com/experiencor/keras-yolo3) <img src="https://img.shields.io/github/stars/experiencor/keras-yolo3?style=social"/> : Training and Detecting Objects with YOLO3.

    - [SpikeKing/keras-yolo3-detection](https://github.com/SpikeKing/keras-yolo3-detection) <img src="https://img.shields.io/github/stars/SpikeKing/keras-yolo3-detection?style=social"/> : YOLO v3 物体检测算法。

    - [xiaochus/YOLOv3](https://github.com/xiaochus/YOLOv3) <img src="https://img.shields.io/github/stars/xiaochus/YOLOv3?style=social"/> : Keras implementation of yolo v3 object detection.

    - [bubbliiiing/yolo3-keras](https://github.com/bubbliiiing/yolo3-keras) <img src="https://img.shields.io/github/stars/bubbliiiing/yolo3-keras?style=social"/> : 这是一个yolo3-keras的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov4-keras](https://github.com/bubbliiiing/yolov4-keras) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov4-keras?style=social"/> : 这是一个YoloV4-keras的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov4-tf2](https://github.com/bubbliiiing/yolov4-tf2) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov4-tf2?style=social"/> : 这是一个yolo4-tf2（tensorflow2）的源码，可以用于训练自己的模型。

    - [bubbliiiing/yolov4-tiny-tf2](https://github.com/bubbliiiing/yolov4-tiny-tf2) <img src="https://img.shields.io/github/stars/bubbliiiing/yolov4-tiny-tf2?style=social"/> : 这是一个YoloV4-tiny-tf2的源码，可以用于训练自己的模型。

    - [pythonlessons/TensorFlow-2.x-YOLOv3](https://github.com/pythonlessons/TensorFlow-2.x-YOLOv3) <img src="https://img.shields.io/github/stars/pythonlessons/TensorFlow-2.x-YOLOv3?style=social"/> : YOLOv3 implementation in TensorFlow 2.3.1.

    - [miemie2013/Keras-YOLOv4](https://github.com/miemie2013/Keras-YOLOv4) <img src="https://img.shields.io/github/stars/miemie2013/Keras-YOLOv4?style=social"/> : PPYOLO AND YOLOv4.

    - [Ma-Dan/keras-yolo4](https://github.com/Ma-Dan/keras-yolo4) <img src="https://img.shields.io/github/stars/Ma-Dan/keras-yolo4?style=social"/> : A Keras implementation of YOLOv4 (Tensorflow backend).

    - [miranthajayatilake/YOLOw-Keras](https://github.com/miranthajayatilake/YOLOw-Keras) <img src="https://img.shields.io/github/stars/miranthajayatilake/YOLOw-Keras?style=social"/> : YOLOv2 Object Detection w/ Keras (in just 20 lines of code).

    - [maiminh1996/YOLOv3-tensorflow](https://github.com/maiminh1996/YOLOv3-tensorflow) <img src="https://img.shields.io/github/stars/maiminh1996/YOLOv3-tensorflow?style=social"/> : Re-implement YOLOv3 with TensorFlow.

    - [Stick-To/Object-Detection-Tensorflow](https://github.com/Stick-To/Object-Detection-Tensorflow) <img src="https://img.shields.io/github/stars/Stick-To/Object-Detection-Tensorflow?style=social"/> : Object Detection API Tensorflow.

    - [avBuffer/Yolov5_tf](https://github.com/avBuffer/Yolov5_tf) <img src="https://img.shields.io/github/stars/avBuffer/Yolov5_tf?style=social"/> : Yolov5/Yolov4/ Yolov3/ Yolo_tiny in tensorflow.

    - [ruiminshen/yolo-tf](https://github.com/ruiminshen/yolo-tf) <img src="https://img.shields.io/github/stars/ruiminshen/yolo-tf?style=social"/> : TensorFlow implementation of the YOLO (You Only Look Once).

    - [xiao9616/yolo4_tensorflow2](https://github.com/xiao9616/yolo4_tensorflow2) <img src="https://img.shields.io/github/stars/xiao9616/yolo4_tensorflow2?style=social"/> : yolo 4th edition implemented by tensorflow2.0.

    - [sicara/tf2-yolov4](https://github.com/sicara/tf2-yolov4) <img src="https://img.shields.io/github/stars/sicara/tf2-yolov4?style=social"/> : A TensorFlow 2.0 implementation of YOLOv4: Optimal Speed and Accuracy of Object Detection.

    - [LongxingTan/Yolov5](https://github.com/LongxingTan/Yolov5) <img src="https://img.shields.io/github/stars/LongxingTan/Yolov5?style=social"/> : Efficient implementation of YOLOV5 in TensorFlow2.

    - [geekjr/quickai](https://github.com/geekjr/quickai) <img src="https://img.shields.io/github/stars/geekjr/quickai?style=social"/> : QuickAI is a Python library that makes it extremely easy to experiment with state-of-the-art Machine Learning models.

    - [CV_Lab/yolov5_rt_tfjs](https://gitee.com/CV_Lab/yolov5_rt_tfjs) : 🚀 基于TensorFlow.js的YOLOv5实时目标检测项目。

    - [Burf/TFDetection](https://github.com/Burf/TFDetection) <img src="https://img.shields.io/github/stars/Burf/TFDetection?style=social"/> : A Detection Toolbox for Tensorflow2.

    - [taipingeric/yolo-v4-tf.keras](https://github.com/taipingeric/yolo-v4-tf.keras) <img src="https://img.shields.io/github/stars/taipingeric/yolo-v4-tf.keras?style=social"/> : A simple tf.keras implementation of YOLO v4.

    - [david8862/keras-YOLOv3-model-set](https://github.com/david8862/keras-YOLOv3-model-set) <img src="https://img.shields.io/github/stars/david8862/keras-YOLOv3-model-set?style=social"/> : end-to-end YOLOv4/v3/v2 object detection pipeline, implemented on tf.keras with different technologies.


  - ### PaddlePaddle Implementation

    - [PaddlePaddle/PaddleDetection](https://github.com/PaddlePaddle/PaddleDetection) <img src="https://img.shields.io/github/stars/PaddlePaddle/PaddleDetection?style=social"/> : Object Detection toolkit based on PaddlePaddle. "PP-YOLO: An Effective and Efficient Implementation of Object Detector". (**[arXiv 2020](https://arxiv.org/abs/2007.12099)**)

    - [nemonameless/PaddleDetection_YOLOv5](https://github.com/nemonameless/PaddleDetection_YOLOv5) <img src="https://img.shields.io/github/stars/nemonameless/PaddleDetection_YOLOv5?style=social"/> : YOLOv5 of PaddleDetection, Paddle implementation of YOLOv5.

    - [nemonameless/PaddleDetection_YOLOX](https://github.com/nemonameless/PaddleDetection_YOLOX) <img src="https://img.shields.io/github/stars/nemonameless/PaddleDetection_YOLOX?style=social"/> : Paddle YOLOX, 51.8% on COCO val by YOLOX-x, 44.6% on YOLOX-ConvNeXt-s.

    - [nemonameless/PaddleDetection_YOLOset](https://github.com/nemonameless/PaddleDetection_YOLOset) <img src="https://img.shields.io/github/stars/nemonameless/PaddleDetection_YOLOset?style=social"/> : Paddle YOLO set: YOLOv3, PPYOLO, PPYOLOE, YOLOX, YOLOv5, YOLOv7 and so on.

    - [miemie2013/Paddle-YOLOv4](https://github.com/miemie2013/Paddle-YOLOv4) <img src="https://img.shields.io/github/stars/miemie2013/Paddle-YOLOv4?style=social"/> : Paddle-YOLOv4.

    - [Sharpiless/PaddleDetection-Yolov5](https://github.com/Sharpiless/PaddleDetection-Yolov5) <img src="https://img.shields.io/github/stars/Sharpiless/PaddleDetection-Yolov5?style=social"/> : 基于Paddlepaddle复现yolov5，支持PaddleDetection接口。

    - [Nioolek/PPYOLOE_pytorch](https://github.com/Nioolek/PPYOLOE_pytorch) <img src="https://img.shields.io/github/stars/Nioolek/PPYOLOE_pytorch?style=social"/> : An unofficial implementation of Pytorch version PP-YOLOE,based on Megvii YOLOX training code.


  - ### Caffe Implementation

    - [ChenYingpeng/caffe-yolov3](https://github.com/ChenYingpeng/caffe-yolov3) <img src="https://img.shields.io/github/stars/ChenYingpeng/caffe-yolov3?style=social"/> : A real-time object detection framework of Yolov3/v4 based on caffe.

    - [ChenYingpeng/darknet2caffe](https://github.com/ChenYingpeng/darknet2caffe) <img src="https://img.shields.io/github/stars/ChenYingpeng/darknet2caffe?style=social"/> : Convert darknet weights to caffemodel.

    - [eric612/Caffe-YOLOv3-Windows](https://github.com/eric612/Caffe-YOLOv3-Windows) <img src="https://img.shields.io/github/stars/eric612/Caffe-YOLOv3-Windows?style=social"/> : A windows caffe implementation of YOLO detection network.

    - [Harick1/caffe-yolo](https://github.com/Harick1/caffe-yolo) <img src="https://img.shields.io/github/stars/Harick1/caffe-yolo?style=social"/> : Caffe for YOLO.

    - [choasup/caffe-yolo9000](https://github.com/choasup/caffe-yolo9000) <img src="https://img.shields.io/github/stars/choasup/caffe-yolo9000?style=social"/> : Caffe for YOLOv2 & YOLO9000.

    - [gklz1982/caffe-yolov2](https://github.com/gklz1982/caffe-yolov2) <img src="https://img.shields.io/github/stars/gklz1982/caffe-yolov2?style=social"/> : caffe-yolov2.


  - ### MXNet Implementation

    - [Gluon CV Toolkit](https://github.com/dmlc/gluon-cv) <img src="https://img.shields.io/github/stars/dmlc/gluon-cv?style=social"/> : GluonCV provides implementations of the state-of-the-art (SOTA) deep learning models in computer vision.

    - [zhreshold/mxnet-yolo](https://github.com/zhreshold/mxnet-yolo) <img src="https://img.shields.io/github/stars/zhreshold/mxnet-yolo?style=social"/> : YOLO: You only look once real-time object detector.


  - ### Web Implementation

    - [ModelDepot/tfjs-yolo-tiny](https://github.com/ModelDepot/tfjs-yolo-tiny) <img src="https://img.shields.io/github/stars/ModelDepot/tfjs-yolo-tiny?style=social"/> : In-Browser Object Detection using Tiny YOLO on Tensorflow.js.

    - [justadudewhohacks/tfjs-tiny-yolov2](https://github.com/justadudewhohacks/tfjs-tiny-yolov2) <img src="https://img.shields.io/github/stars/justadudewhohacks/tfjs-tiny-yolov2?style=social"/> : Tiny YOLO v2 object detection with tensorflow.js.

    - [reu2018DL/YOLO-LITE](https://github.com/reu2018DL/YOLO-LITE) <img src="https://img.shields.io/github/stars/reu2018DL/YOLO-LITE?style=social"/> : YOLO-LITE is a web implementation of YOLOv2-tiny.

    - [mobimeo/node-yolo](https://github.com/mobimeo/node-yolo) <img src="https://img.shields.io/github/stars/mobimeo/node-yolo?style=social"/> : Node bindings for YOLO/Darknet image recognition library.

    - [Sharpiless/Yolov5-Flask-VUE](https://github.com/Sharpiless/Yolov5-Flask-VUE) <img src="https://img.shields.io/github/stars/Sharpiless/Yolov5-Flask-VUE?style=social"/> : 基于Flask开发后端、VUE开发前端框架，在WEB端部署YOLOv5目标检测模型。

    - [shaqian/tfjs-yolo](https://github.com/shaqian/tfjs-yolo) <img src="https://img.shields.io/github/stars/shaqian/tfjs-yolo?style=social"/> : YOLO v3 and Tiny YOLO v1, v2, v3 with Tensorflow.js.

    - [zqingr/tfjs-yolov3](https://github.com/zqingr/tfjs-yolov3) <img src="https://img.shields.io/github/stars/zqingr/tfjs-yolov3?style=social"/> : A Tensorflow js implementation of YOLOv3 and YOLOv3-tiny.

    - [bennetthardwick/darknet.js](https://github.com/bennetthardwick/darknet.js) <img src="https://img.shields.io/github/stars/bennetthardwick/darknet.js?style=social"/> : A NodeJS wrapper of pjreddie's darknet / yolo.

    - [nihui/ncnn-webassembly-yolov5](https://github.com/nihui/ncnn-webassembly-yolov5) <img src="https://img.shields.io/github/stars/nihui/ncnn-webassembly-yolov5?style=social"/> : Deploy YOLOv5 in your web browser with ncnn and webassembly.

    - [muhk01/Yolov5-on-Flask](https://github.com/muhk01/Yolov5-on-Flask) <img src="https://img.shields.io/github/stars/muhk01/Yolov5-on-Flask?style=social"/> : Running YOLOv5 through web browser using Flask microframework.

    - [tcyfree/yolov5](https://github.com/tcyfree/yolov5) <img src="https://img.shields.io/github/stars/tcyfree/yolov5?style=social"/> : 基于Flask开发后端、VUE开发前端框架，在WEB端部署YOLOv5目标检测模型。

    - [siffyy/YOLOv5-Web-App-for-Vehicle-Detection](https://github.com/siffyy/YOLOv5-Web-App-for-Vehicle-Detection) <img src="https://img.shields.io/github/stars/siffyy/YOLOv5-Web-App-for-Vehicle-Detection?style=social"/> : Repo for Web Application for Vehicle detection from Satellite Imagery using YOLOv5 model.

    - [Devmawi/BlazorObjectDetection-Sample](https://github.com/Devmawi/BlazorObjectDetection-Sample) <img src="https://img.shields.io/github/stars/Devmawi/BlazorObjectDetection-Sample?style=social"/> : A sample for demonstrating online execution of an onnx model by a Blazor app.

    - [Hyuto/yolov5-onnxruntime-web](https://github.com/Hyuto/yolov5-onnxruntime-web) <img src="https://img.shields.io/github/stars/Hyuto/yolov5-onnxruntime-web?style=social"/> : YOLOv5 right in your browser with onnxruntime-web.


  - ### Others

    - [jinfagang/yolov7_d2](https://github.com/jinfagang/yolov7_d2) <img src="https://img.shields.io/github/stars/jinfagang/yolov7_d2?style=social"/> : 🔥🔥🔥🔥 (Earlier YOLOv7 not official one) YOLO with Transformers and Instance Segmentation, with TensorRT acceleration! 🔥🔥🔥

    - [yang-0201/YOLOv6_pro](https://github.com/yang-0201/YOLOv6_pro) <img src="https://img.shields.io/github/stars/yang-0201/YOLOv6_pro?style=social"/> : Make it easier for yolov6 to change the network structure.

    - [j-marple-dev/AYolov2](https://github.com/j-marple-dev/AYolov2) <img src="https://img.shields.io/github/stars/j-marple-dev/AYolov2?style=social"/> : The main goal of this repository is to rewrite the object detection pipeline with a better code structure for better portability and adaptability to apply new experimental methods. The object detection pipeline is based on [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5).

    - [fcakyon/yolov5-pip](https://github.com/fcakyon/yolov5-pip) <img src="https://img.shields.io/github/stars/fcakyon/yolov5-pip?style=social"/> : Packaged version of ultralytics/yolov5.

    - [kadirnar/yolov6-pip](https://github.com/kadirnar/yolov6-pip) <img src="https://img.shields.io/github/stars/kadirnar/yolov6-pip?style=social"/> : Packaged version of yolov6 model.

    - [kadirnar/yolov7-pip](https://github.com/kadirnar/yolov7-pip) <img src="https://img.shields.io/github/stars/kadirnar/yolov7-pip?style=social"/> : Packaged version of yolov7 model.

    - [kadirnar/torchyolo](https://github.com/kadirnar/torchyolo) <img src="https://img.shields.io/github/stars/kadirnar/torchyolo?style=social"/> : PyTorch implementation of YOLOv5, YOLOv6, YOLOv7, YOLOX.

    - [CvPytorch](https://github.com/shanglianlm0525/CvPytorch) <img src="https://img.shields.io/github/stars/shanglianlm0525/CvPytorch?style=social"/> : CvPytorch is an open source COMPUTER VISION toolbox based on PyTorch.

    - [Holocron](https://github.com/frgfm/Holocron) <img src="https://img.shields.io/github/stars/frgfm/Holocron?style=social"/> : PyTorch implementations of recent Computer Vision tricks (ReXNet, RepVGG, Unet3p, YOLOv4, CIoU loss, AdaBelief, PolyLoss).

    - [DL-Practise/YoloAll](https://github.com/DL-Practise/YoloAll) <img src="https://img.shields.io/github/stars/DL-Practise/YoloAll?style=social"/> : YoloAll is a collection of yolo all versions. you you use YoloAll to test yolov3/yolov5/yolox/yolo_fastest.

    - [msnh2012/Msnhnet](https://github.com/msnh2012/Msnhnet) <img src="https://img.shields.io/github/stars/msnh2012/Msnhnet?style=social"/> : (yolov3 yolov4 yolov5 unet ...)A mini pytorch inference framework which inspired from darknet.

    - [xinghanliuying/yolov5-trick](https://github.com/xinghanliuying/yolov5-trick) <img src="https://img.shields.io/github/stars/xinghanliuying/yolov5-trick?style=social"/> : 基于yolov5的改进库。

    - [BMW-InnovationLab/BMW-YOLOv4-Training-Automation](https://github.com/BMW-InnovationLab/BMW-YOLOv4-Training-Automation) <img src="https://img.shields.io/github/stars/BMW-InnovationLab/BMW-YOLOv4-Training-Automation?style=social"/> : YOLOv4-v3 Training Automation API for Linux.

    - [AntonMu/TrainYourOwnYOLO](https://github.com/AntonMu/TrainYourOwnYOLO) <img src="https://img.shields.io/github/stars/AntonMu/TrainYourOwnYOLO?style=social"/> : Train a state-of-the-art yolov3 object detector from scratch!

    - [madhawav/YOLO3-4-Py](https://github.com/madhawav/YOLO3-4-Py) <img src="https://img.shields.io/github/stars/madhawav/YOLO3-4-Py?style=social"/> : A Python wrapper on Darknet. Compatible with YOLO V3.

    - [theAIGuysCode/yolov4-custom-functions](https://github.com/theAIGuysCode/yolov4-custom-functions) <img src="https://img.shields.io/github/stars/theAIGuysCode/yolov4-custom-functions?style=social"/> : A Wide Range of Custom Functions for YOLOv4, YOLOv4-tiny, YOLOv3, and YOLOv3-tiny Implemented in TensorFlow, TFLite, and TensorRT.

    - [tiquasar/FLAITER](https://github.com/tiquasar/FLAITER) <img src="https://img.shields.io/github/stars/tiquasar/FLAITER?style=social"/> : Machine Learning and AI Mobile Application.

    - [kadirnar/Minimal-Yolov6](https://github.com/kadirnar/Minimal-Yolov6) <img src="https://img.shields.io/github/stars/kadirnar/Minimal-Yolov6?style=social"/> : Minimal-Yolov6.

    - [DataXujing/YOLOv6](https://github.com/DataXujing/YOLOv6) <img src="https://img.shields.io/github/stars/DataXujing/YOLOv6?style=social"/> : 🌀 🌀 手摸手 美团 YOLOv6模型训练和TensorRT端到端部署方案教程。

    - [DataXujing/YOLOv7](https://github.com/DataXujing/YOLOv7) <img src="https://img.shields.io/github/stars/DataXujing/YOLOv7?style=social"/> : 🔥🔥🔥 Official YOLOv7训练自己的数据集并实现端到端的TensorRT模型加速推断。

    - [DataXujing/YOLOv8](https://github.com/DataXujing/YOLOv8) <img src="https://img.shields.io/github/stars/DataXujing/YOLOv8?style=social"/> : 🔥 Official YOLOv8模型训练和部署。Official YOLOv8 训练自己的数据集并基于NVIDIA TensorRT和华为昇腾端到端模型加速以及安卓手机端部署。

    - [DataXujing/YOLOv9](https://github.com/DataXujing/YOLOv9) <img src="https://img.shields.io/github/stars/DataXujing/YOLOv9?style=social"/> : 🔥 YOLOv9 paper解析，训练自己的数据集，TensorRT端到端部署， NCNN安卓手机部署。

    - [Code-keys/yolov5-darknet](https://github.com/Code-keys/yolov5-darknet) <img src="https://img.shields.io/github/stars/Code-keys/yolov5-darknet?style=social"/> : yolov5-darknet support yaml && cfg.

    - [Code-keys/yolo-darknet](https://github.com/Code-keys/yolo-darknet) <img src="https://img.shields.io/github/stars/Code-keys/yolo-darknet?style=social"/> : YOLO-family complemented by darknet. yolov5 yolov7 et al ...

    - [pooya-mohammadi/deep_utils](https://github.com/pooya-mohammadi/deep_utils) <img src="https://img.shields.io/github/stars/pooya-mohammadi/deep_utils?style=social"/> : A toolkit full of handy functions including most used models and utilities for deep-learning practitioners!

    - [yl-jiang/YOLOSeries](https://github.com/yl-jiang/YOLOSeries) <img src="https://img.shields.io/github/stars/yl-jiang/YOLOSeries?style=social"/> : YOLO Series.

    - [yjh0410/FreeYOLO](https://github.com/yjh0410/FreeYOLO) <img src="https://img.shields.io/github/stars/yjh0410/FreeYOLO?style=social"/> : FreeYOLO is inspired by many other excellent works, such as YOLOv7 and YOLOX.

    - [open-yolo/yolov7](https://github.com/open-yolo/yolov7) <img src="https://img.shields.io/github/stars/open-yolo/yolov7?style=social"/> : Improved and packaged version of WongKinYiu/yolov7.

    - [iloveai8086/YOLOC](https://github.com/iloveai8086/YOLOC) <img src="https://img.shields.io/github/stars/iloveai8086/YOLOC?style=social"/> : 🚀YOLOC is Combining different modules to build an different Object detection model.

    - [miemie2013/miemiedetection](https://github.com/miemie2013/miemiedetection) <img src="https://img.shields.io/github/stars/miemie2013/miemiedetection?style=social"/> : Pytorch and ncnn implementation of PPYOLOE、YOLOX、PPYOLO、PPYOLOv2、SOLOv2 an so on.

    - [RyanCCC/YOLOSeries](https://github.com/RyanCCC/YOLOSeries) <img src="https://img.shields.io/github/stars/RyanCCC/YOLOSeries?style=social"/> : YOLO算法的实现。

    - [HuKai97/YOLOX-Annotations](https://github.com/HuKai97/YOLOX-Annotations) <img src="https://img.shields.io/github/stars/HuKai97/YOLOX-Annotations?style=social"/> : 一个YOLOX的中文注释版本，供大家参考学习！

    - [isLinXu/YOLOv8_Efficient](https://github.com/isLinXu/YOLOv8_Efficient) <img src="https://img.shields.io/github/stars/isLinXu/YOLOv8_Efficient?style=social"/> : 🚀Simple and efficient use for Ultralytics yolov8🚀

    - [z1069614715/objectdetection_script](https://github.com/z1069614715/objectdetection_script) <img src="https://img.shields.io/github/stars/z1069614715/objectdetection_script?style=social"/> : 一些关于目标检测的脚本的改进思路代码。




## Lighter and Deployment Frameworks


  - ### High-performance Inference Engine
    #### 高性能推理引擎

    - ##### ONNX

        - [ONNX Runtime](https://github.com/microsoft/onnxruntime) <img src="https://img.shields.io/github/stars/microsoft/onnxruntime?style=social"/> : ONNX Runtime: cross-platform, high performance ML inferencing and training accelerator. [onnxruntime.ai](https://onnxruntime.ai/)

        - [ONNX](https://github.com/onnx/onnx) <img src="https://img.shields.io/github/stars/onnx/onnx?style=social"/> : Open Neural Network Exchange. Open standard for machine learning interoperability. [onnx.ai](https://onnx.ai/)

        - [ONNXMLTools](https://github.com/onnx/onnxmltools) <img src="https://img.shields.io/github/stars/onnx/onnxmltools?style=social"/> : ONNXMLTools enables you to convert models from different machine learning toolkits into [ONNX](https://github.com/onnx/onnx). [onnx.ai](https://onnx.ai/)

        - [xboot/libonnx](https://github.com/xboot/libonnx) <img src="https://img.shields.io/github/stars/xboot/libonnx?style=social"/> : A lightweight, portable pure C99 onnx inference engine for embedded devices with hardware acceleration support.

        - [kraiskil/onnx2c](https://github.com/kraiskil/onnx2c) <img src="https://img.shields.io/github/stars/kraiskil/onnx2c?style=social"/> : Open Neural Network Exchange to C compiler. Onnx2c is a [ONNX](https://onnx.ai/) to C compiler. It will read an ONNX file, and generate C code to be included in your project. Onnx2c's target is "Tiny ML", meaning running the inference on microcontrollers.

        - [tract](https://github.com/sonos/tract) <img src="https://img.shields.io/github/stars/sonos/tract?style=social"/> : Sonos' Neural Network inference engine. Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference

        - [ort](https://github.com/pykeio/ort) <img src="https://img.shields.io/github/stars/pykeio/ort?style=social"/> : A Rust wrapper for ONNX Runtime. [docs.rs/ort](https://docs.rs/ort/latest/ort/)

        - [onnxruntime-rs](https://github.com/nbigaouette/onnxruntime-rs) <img src="https://img.shields.io/github/stars/nbigaouette/onnxruntime-rs?style=social"/> : This is an attempt at a Rust wrapper for [Microsoft's ONNX Runtime](https://github.com/microsoft/onnxruntime) (version 1.8).

        - [Wonnx](https://github.com/webonnx/wonnx) <img src="https://img.shields.io/github/stars/webonnx/wonnx?style=social"/> : Wonnx is a GPU-accelerated ONNX inference run-time written 100% in Rust, ready for the web.

        - [altius](https://github.com/maekawatoshiki/altius) <img src="https://img.shields.io/github/stars/maekawatoshiki/altius?style=social"/> : Small ONNX inference runtime written in Rust.

        - [Hyuto/yolo-nas-onnx](https://github.com/Hyuto/yolo-nas-onnx) <img src="https://img.shields.io/github/stars/Hyuto/yolo-nas-onnx?style=social"/> : Inference YOLO-NAS ONNX model. [hyuto.github.io/yolo-nas-onnx/](https://hyuto.github.io/yolo-nas-onnx/)

        - [DanielSarmiento04/yolov10cpp](https://github.com/DanielSarmiento04/yolov10cpp) <img src="https://img.shields.io/github/stars/DanielSarmiento04/yolov10cpp?style=social"/> : Implementation of yolo v10 in c++ std 17 over opencv and onnxruntime.




    - ##### TensorRT

        - [TensorRT](https://github.com/NVIDIA/TensorRT) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT?style=social"/> : NVIDIA® TensorRT™ is an SDK for high-performance deep learning inference on NVIDIA GPUs. This repository contains the open source components of TensorRT. [developer.nvidia.com/tensorrt](https://developer.nvidia.com/tensorrt)

        - [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM?style=social"/> : TensorRT-LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and build TensorRT engines that contain state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs. TensorRT-LLM also contains components to create Python and C++ runtimes that execute those TensorRT engines. [nvidia.github.io/TensorRT-LLM](https://nvidia.github.io/TensorRT-LLM)

        - [NVIDIA/TensorRT-Model-Optimizer](https://github.com/NVIDIA/TensorRT-Model-Optimizer) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT-Model-Optimizer?style=social"/> : TensorRT Model Optimizer is a unified library of state-of-the-art model optimization techniques such as quantization, pruning, distillation, etc. It compresses deep learning models for downstream deployment frameworks like TensorRT-LLM or TensorRT to optimize inference speed on NVIDIA GPUs. [nvidia.github.io/TensorRT-Model-Optimizer](https://nvidia.github.io/TensorRT-Model-Optimizer/)

        - [kalfazed/tensorrt_starter](https://github.com/kalfazed/tensorrt_starter) <img src="https://img.shields.io/github/stars/kalfazed/tensorrt_starter?style=social"/> : This repository give a guidline to learn CUDA and TensorRT from the beginning.

        - [wang-xinyu/tensorrtx](https://github.com/wang-xinyu/tensorrtx) <img src="https://img.shields.io/github/stars/wang-xinyu/tensorrtx?style=social"/> : TensorRTx aims to implement popular deep learning networks with tensorrt network definition APIs.

        - [laugh12321/TensorRT-YOLO](https://github.com/laugh12321/TensorRT-YOLO) <img src="https://img.shields.io/github/stars/laugh12321/TensorRT-YOLO?style=social"/> : 🚀 Easier & Faster YOLO Deployment Toolkit for NVIDIA 🛠️. 🚀 TensorRT-YOLO is an easy-to-use, extremely efficient inference deployment tool for the YOLO series designed specifically for NVIDIA devices. The project not only integrates TensorRT plugins to enhance post-processing but also utilizes CUDA kernels and CUDA graphs to accelerate inference. 🚀 TensorRT-YOLO 是一款专为 NVIDIA 设备设计的易用灵活、极致高效的YOLO系列推理部署工具。项目不仅集成了 TensorRT 插件以增强后处理效果，还使用了 CUDA 核函数以及 CUDA 图来加速推理。

        - [olibartfast/object-detection-inference](https://github.com/olibartfast/object-detection-inference) <img src="https://img.shields.io/github/stars/olibartfast/object-detection-inference?style=social"/> : C++ object detection inference from video or image input source. Inference for object detection from a video or image input source, with support for multiple switchable frameworks to manage the inference process, and optional GStreamer integration for video capture.

        - [shouxieai/tensorRT_Pro](https://github.com/shouxieai/tensorRT_Pro) <img src="https://img.shields.io/github/stars/shouxieai/tensorRT_Pro?style=social"/> : C++ library based on tensorrt integration.

        - [shouxieai/infer](https://github.com/shouxieai/infer) <img src="https://img.shields.io/github/stars/shouxieai/infer?style=social"/> : A new tensorrt integrate. Easy to integrate many tasks.

        - [Melody-Zhou/tensorRT_Pro-YOLOv8](https://github.com/Melody-Zhou/tensorRT_Pro-YOLOv8) <img src="https://img.shields.io/github/stars/Melody-Zhou/tensorRT_Pro-YOLOv8?style=social"/> : This repository is based on [shouxieai/tensorRT_Pro](https://github.com/shouxieai/tensorRT_Pro), with adjustments to support YOLOv8. 前已支持 YOLOv8、YOLOv8-Cls、YOLOv8-Seg、YOLOv8-OBB、YOLOv8-Pose、RT-DETR、ByteTrack、YOLOv9、YOLOv10、RTMO、PP-OCRv4、LaneATT 高性能推理！！！🚀🚀🚀

        - [FeiYull/TensorRT-Alpha](https://github.com/FeiYull/TensorRT-Alpha) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/torch2trt?style=social"/> : 🔥🔥🔥TensorRT for YOLOv8、YOLOv8-Pose、YOLOv8-Seg、YOLOv8-Cls、YOLOv7、YOLOv6、YOLOv5、YOLONAS......🚀🚀🚀CUDA IS ALL YOU NEED.🍎🍎🍎

        - [zhiqwang/yolort](https://github.com/zhiqwang/yolort) <img src="https://img.shields.io/github/stars/zhiqwang/yolort?style=social"/> : yolort is a runtime stack for yolov5 on specialized accelerators such as tensorrt, libtorch, onnxruntime, tvm and ncnn. [zhiqwang.com/yolort](https://zhiqwang.com/yolort/)

        - [1461521844lijin/trt_yolo_video_pipeline](https://github.com/1461521844lijin/trt_yolo_video_pipeline) <img src="https://img.shields.io/github/stars/1461521844lijin/trt_yolo_video_pipeline?style=social"/> : TensorRT+YOLO系列的 多路 多卡 多实例 并行视频分析处理案例。

        - [l-sf/Linfer](https://github.com/l-sf/Linfer) <img src="https://img.shields.io/github/stars/l-sf/Linfer?style=social"/> : 基于TensorRT的C++高性能推理库，Yolov10, YoloPv2，Yolov5/7/X/8，RT-DETR，单目标跟踪OSTrack、LightTrack。

        - [taifyang/yolo-inference](https://github.com/taifyang/yolo-inference) <img src="https://img.shields.io/github/stars/taifyang/yolo-inference?style=social"/> : C++ and Python implementations of YOLOv5, YOLOv6, YOLOv7, YOLOv8, YOLOv9, YOLOv10, YOLOv11 inference.

        - [triple-Mu/YOLOv8-TensorRT](https://github.com/triple-Mu/YOLOv8-TensorRT) <img src="https://img.shields.io/github/stars/triple-Mu/YOLOv8-TensorRT?style=social"/> : YOLOv8 using TensorRT accelerate !

        - [emptysoal/TensorRT-YOLOv8-ByteTrack](https://github.com/emptysoal/TensorRT-YOLOv8-ByteTrack) <img src="https://img.shields.io/github/stars/emptysoal/TensorRT-YOLOv8-ByteTrack?style=social"/> : An object tracking project with YOLOv8 and ByteTrack, speed up by C++ and TensorRT.

        - [Linaom1214/TensorRT-For-YOLO-Series](https://github.com/Linaom1214/TensorRT-For-YOLO-Series) <img src="https://img.shields.io/github/stars/Linaom1214/TensorRT-For-YOLO-Series?style=social"/> : tensorrt for yolo series (YOLOv10,YOLOv9,YOLOv8,YOLOv7,YOLOv6,YOLOX,YOLOv5), nms plugin support.

        - [spacewalk01/yolov11-tensorrt](https://github.com/spacewalk01/yolov11-tensorrt) <img src="https://img.shields.io/github/stars/spacewalk01/yolov11-tensorrt?style=social"/> : C++ implementation of YOLOv11 using TensorRT API.

        - [cyrusbehr/YOLOv8-TensorRT-CPP](https://github.com/cyrusbehr/YOLOv8-TensorRT-CPP) <img src="https://img.shields.io/github/stars/cyrusbehr/YOLOv8-TensorRT-CPP?style=social"/> : YOLOv8 TensorRT C++ Implementation. A C++ Implementation of YoloV8 using TensorRT Supports object detection, semantic segmentation, and body pose estimation.

        - [emptysoal/TensorRT-YOLOv8](https://github.com/emptysoal/TensorRT-YOLOv8) <img src="https://img.shields.io/github/stars/emptysoal/TensorRT-YOLOv8?style=social"/> : Based on tensorrt v8.0+, deploy detect, pose, segment, tracking of YOLOv8 with C++ and python api.

        - [hamdiboukamcha/yolov10-tensorrt](https://github.com/hamdiboukamcha/yolov10-tensorrt) <img src="https://img.shields.io/github/stars/hamdiboukamcha/yolov10-tensorrt?style=social"/> : YOLOv10 C++ TensorRT : Real-Time End-to-End Object Detection.

        - [VIDIA-AI-IOT/torch2trt](https://github.com/NVIDIA-AI-IOT/torch2trt) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/torch2trt?style=social"/> : An easy to use PyTorch to TensorRT converter.

        - [DefTruth/lite.ai.toolkit](https://github.com/DefTruth/lite.ai.toolkit) <img src="https://img.shields.io/github/stars/DefTruth/lite.ai.toolkit?style=social"/> : 🛠 A lite C++ toolkit of awesome AI models with ONNXRuntime, NCNN, MNN and TNN. YOLOX, YOLOP, YOLOv6, YOLOR, MODNet, YOLOX, YOLOv7, YOLOv5. MNN, NCNN, TNN, ONNXRuntime. “🛠Lite.Ai.ToolKit: 一个轻量级的C++ AI模型工具箱，用户友好（还行吧），开箱即用。已经包括 100+ 流行的开源模型。这是一个根据个人兴趣整理的C++工具箱，, 涵盖目标检测、人脸检测、人脸识别、语义分割、抠图等领域。”

        - [PaddlePaddle/FastDeploy](https://github.com/PaddlePaddle/FastDeploy) <img src="https://img.shields.io/github/stars/PaddlePaddle/FastDeploy?style=social"/> : ⚡️An Easy-to-use and Fast Deep Learning Model Deployment Toolkit for ☁️Cloud 📱Mobile and 📹Edge. Including Image, Video, Text and Audio 20+ main stream scenarios and 150+ SOTA models with end-to-end optimization, multi-platform and multi-framework support.

        - [enazoe/yolo-tensorrt](https://github.com/enazoe/yolo-tensorrt) <img src="https://img.shields.io/github/stars/enazoe/yolo-tensorrt?style=social"/> : TensorRT8.Support Yolov5n,s,m,l,x .darknet -> tensorrt. Yolov4 Yolov3 use raw darknet *.weights and *.cfg fils. If the wrapper is useful to you,please Star it.

        - [guojianyang/cv-detect-robot](https://github.com/guojianyang/cv-detect-robot) <img src="https://img.shields.io/github/stars/guojianyang/cv-detect-robot?style=social"/> : 🔥🔥🔥🔥🔥🔥Docker NVIDIA Docker2 YOLOV5 YOLOX YOLO Deepsort TensorRT ROS Deepstream Jetson Nano TX2 NX for High-performance deployment(高性能部署)。

        - [BlueMirrors/Yolov5-TensorRT](https://github.com/BlueMirrors/Yolov5-TensorRT) <img src="https://img.shields.io/github/stars/BlueMirrors/Yolov5-TensorRT?style=social"/> : Yolov5 TensorRT Implementations.

        - [lewes6369/TensorRT-Yolov3](https://github.com/lewes6369/TensorRT-Yolov3) <img src="https://img.shields.io/github/stars/lewes6369/TensorRT-Yolov3?style=social"/> : TensorRT for Yolov3.

        - [CaoWGG/TensorRT-YOLOv4](https://github.com/CaoWGG/TensorRT-YOLOv4) <img src="https://img.shields.io/github/stars/CaoWGG/TensorRT-YOLOv4?style=social"/> :tensorrt5, yolov4, yolov3,yolov3-tniy,yolov3-tniy-prn.

        - [isarsoft/yolov4-triton-tensorrt](https://github.com/isarsoft/yolov4-triton-tensorrt) <img src="https://img.shields.io/github/stars/isarsoft/yolov4-triton-tensorrt?style=social"/> : YOLOv4 on Triton Inference Server with TensorRT.

        - [TrojanXu/yolov5-tensorrt](https://github.com/TrojanXu/yolov5-tensorrt) <img src="https://img.shields.io/github/stars/TrojanXu/yolov5-tensorrt?style=social"/> : A tensorrt implementation of yolov5.

        - [tjuskyzhang/Scaled-YOLOv4-TensorRT](https://github.com/tjuskyzhang/Scaled-YOLOv4-TensorRT) <img src="https://img.shields.io/github/stars/tjuskyzhang/Scaled-YOLOv4-TensorRT?style=social"/> : Implement yolov4-tiny-tensorrt, yolov4-csp-tensorrt, yolov4-large-tensorrt(p5, p6, p7) layer by layer using TensorRT API.

        - [Syencil/tensorRT](https://github.com/Syencil/tensorRT) <img src="https://img.shields.io/github/stars/Syencil/tensorRT?style=social"/> : TensorRT-7 Network Lib 包括常用目标检测、关键点检测、人脸检测、OCR等 可训练自己数据。

        - [SeanAvery/yolov5-tensorrt](https://github.com/SeanAvery/yolov5-tensorrt) <img src="https://img.shields.io/github/stars/SeanAvery/yolov5-tensorrt?style=social"/> : YOLOv5 in TensorRT.

        - [Monday-Leo/YOLOv7_Tensorrt](https://github.com/Monday-Leo/YOLOv7_Tensorrt) <img src="https://img.shields.io/github/stars/Monday-Leo/YOLOv7_Tensorrt?style=social"/> : A simple implementation of Tensorrt YOLOv7.

        - [ibaiGorordo/ONNX-YOLOv6-Object-Detection](https://github.com/ibaiGorordo/ONNX-YOLOv6-Object-Detection) <img src="https://img.shields.io/github/stars/ibaiGorordo/ONNX-YOLOv6-Object-Detection?style=social"/> : Python scripts performing object detection using the YOLOv6 model in ONNX.

        - [ibaiGorordo/ONNX-YOLOv7-Object-Detection](https://github.com/ibaiGorordo/ONNX-YOLOv7-Object-Detection) <img src="https://img.shields.io/github/stars/ibaiGorordo/ONNX-YOLOv7-Object-Detection?style=social"/> : Python scripts performing object detection using the YOLOv7 model in ONNX.

        - [triple-Mu/yolov7](https://github.com/triple-Mu/yolov7) <img src="https://img.shields.io/github/stars/triple-Mu/yolov7?style=social"/> : End2end TensorRT YOLOv7.

        - [hewen0901/yolov7_trt](https://github.com/hewen0901/yolov7_trt) <img src="https://img.shields.io/github/stars/hewen0901/yolov7_trt?style=social"/> : yolov7目标检测算法的c++ tensorrt部署代码。

        - [tsutof/tiny_yolov2_onnx_cam](https://github.com/tsutof/tiny_yolov2_onnx_cam) <img src="https://img.shields.io/github/stars/tsutof/tiny_yolov2_onnx_cam?style=social"/> : Tiny YOLO v2 Inference Application with NVIDIA TensorRT.

        - [Monday-Leo/Yolov5_Tensorrt_Win10](https://github.com/Monday-Leo/Yolov5_Tensorrt_Win10) <img src="https://img.shields.io/github/stars/Monday-Leo/Yolov5_Tensorrt_Win10?style=social"/> : A simple implementation of tensorrt yolov5 python/c++🔥

        - [Wulingtian/yolov5_tensorrt_int8](https://github.com/Wulingtian/yolov5_tensorrt_int8) <img src="https://img.shields.io/github/stars/Wulingtian/yolov5_tensorrt_int8?style=social"/> : TensorRT int8 量化部署 yolov5s 模型，实测3.3ms一帧！

        - [Wulingtian/yolov5_tensorrt_int8_tools](https://github.com/Wulingtian/yolov5_tensorrt_int8_tools) <img src="https://img.shields.io/github/stars/Wulingtian/yolov5_tensorrt_int8_tools?style=social"/> : tensorrt int8 量化yolov5 onnx模型。

        - [MadaoFY/yolov5_TensorRT_inference](https://github.com/MadaoFY/yolov5_TensorRT_inference) <img src="https://img.shields.io/github/stars/MadaoFY/yolov5_TensorRT_inference?style=social"/> : 记录yolov5的TensorRT量化及推理代码，经实测可运行于Jetson平台。

        - [ibaiGorordo/ONNX-YOLOv8-Object-Detection](https://github.com/ibaiGorordo/ONNX-YOLOv8-Object-Detection) <img src="https://img.shields.io/github/stars/ibaiGorordo/ONNX-YOLOv8-Object-Detection?style=social"/> : Python scripts performing object detection using the YOLOv8 model in ONNX.

        - [we0091234/yolov8-tensorrt](https://github.com/we0091234/yolov8-tensorrt) <img src="https://img.shields.io/github/stars/we0091234/yolov8-tensorrt?style=social"/> : yolov8 tensorrt 加速.

        - [FeiYull/yolov8-tensorrt](https://github.com/FeiYull/yolov8-tensorrt) <img src="https://img.shields.io/github/stars/FeiYull/yolov8-tensorrt?style=social"/> : YOLOv8的TensorRT+CUDA加速部署，代码可在Win、Linux下运行。

        - [cvdong/YOLO_TRT_SIM](https://github.com/cvdong/YOLO_TRT_SIM) <img src="https://img.shields.io/github/stars/cvdong/YOLO_TRT_SIM?style=social"/> : 🐇 一套代码同时支持YOLO X, V5, V6, V7, V8 TRT推理 ™️ 🔝 ,前后处理均由CUDA核函数实现 CPP/CUDA🚀

        - [cvdong/YOLO_TRT_PY](https://github.com/cvdong/YOLO_TRT_PY) <img src="https://img.shields.io/github/stars/cvdong/YOLO_TRT_PY?style=social"/> : 🐰 一套代码同时支持YOLOV5, V6, V7, V8 TRT推理 ™️ PYTHON ✈️

        - [Psynosaur/Jetson-SecVision](https://github.com/Psynosaur/Jetson-SecVision) <img src="https://img.shields.io/github/stars/Psynosaur/Jetson-SecVision?style=social"/> : Person detection for Hikvision DVR with AlarmIO ports, uses TensorRT and yolov4.

        - [tatsuya-fukuoka/yolov7-onnx-infer](https://github.com/tatsuya-fukuoka/yolov7-onnx-infer) <img src="https://img.shields.io/github/stars/tatsuya-fukuoka/yolov7-onnx-infer?style=social"/> : Inference with yolov7's onnx model.

        - [MadaoFY/yolov5_TensorRT_inference](https://github.com/MadaoFY/yolov5_TensorRT_inference) <img src="https://img.shields.io/github/stars/MadaoFY/yolov5_TensorRT_inference?style=social"/> : 记录yolov5的TensorRT量化及推理代码，经实测可运行于Jetson平台。

        - [ervgan/yolov5_tensorrt_inference](https://github.com/ervgan/yolov5_tensorrt_inference) <img src="https://img.shields.io/github/stars/ervgan/yolov5_tensorrt_inference?style=social"/> : TensorRT cpp inference for Yolov5 model. Supports yolov5 v1.0, v2.0, v3.0, v3.1, v4.0, v5.0, v6.0, v6.2, v7.0.

        - [AlbinZhu/easy-trt](https://github.com/AlbinZhu/easy-trt) <img src="https://img.shields.io/github/stars/AlbinZhu/easy-trt?style=social"/> : TensorRT for YOLOv10 with CUDA.

        - [PrinceP/tensorrt-cpp-for-onnx](https://github.com/PrinceP/tensorrt-cpp-for-onnx) <img src="https://img.shields.io/github/stars/PrinceP/tensorrt-cpp-for-onnx?style=social"/> : Tensorrt codebase to inference in c++ for all major neural arch using onnx.

        - [hamdiboukamcha/Yolo-V10-cpp-TensorRT](https://github.com/hamdiboukamcha/Yolo-V10-cpp-TensorRT) <img src="https://img.shields.io/github/stars/hamdiboukamcha/Yolo-V10-cpp-TensorRT?style=social"/> : The YOLOv10 C++ TensorRT Project in C++ and optimized using NVIDIA TensorRT.

        - [DataXujing/YOLOv12-TensorRT](https://github.com/DataXujing/YOLOv12-TensorRT) <img src="https://img.shields.io/github/stars/DataXujing/YOLOv12-TensorRT?style=social"/> : YOLOv12 TensorRT 端到端模型加速推理和INT8量化实现。



    - ##### DeepStream

        - [NVIDIA-AI-IOT/deepstream_reference_apps](https://github.com/NVIDIA-AI-IOT/deepstream_reference_apps) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/deepstream_reference_apps?style=social"/> : Reference Apps using DeepStream 6.1.

        - [NVIDIA-AI-IOT/deepstream_python_apps](https://github.com/NVIDIA-AI-IOT/deepstream_python_apps) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/deepstream_python_apps?style=social"/> : DeepStream SDK Python bindings and sample applications.

        - [NVIDIA-AI-IOT/deepstream_python_apps](https://github.com/NVIDIA-AI-IOT/yolov5_gpu_optimization) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/yolov5_gpu_optimization?style=social"/> : This repository provides YOLOV5 GPU optimization sample.

        - [marcoslucianops/DeepStream-Yolo](https://github.com/marcoslucianops/DeepStream-Yolo) <img src="https://img.shields.io/github/stars/marcoslucianops/DeepStream-Yolo?style=social"/> : NVIDIA DeepStream SDK 6.1.1 / 6.1 / 6.0.1 / 6.0 implementation for YOLO models.

        - [DanaHan/Yolov5-in-Deepstream-5.0](https://github.com/DanaHan/Yolov5-in-Deepstream-5.0) <img src="https://img.shields.io/github/stars/DanaHan/Yolov5-in-Deepstream-5.0?style=social"/> : Describe how to use yolov5 in Deepstream 5.0.

        - [ozinc/Deepstream6_YoloV5_Kafka](https://github.com/ozinc/Deepstream6_YoloV5_Kafka) <img src="https://img.shields.io/github/stars/ozinc/Deepstream6_YoloV5_Kafka?style=social"/> : This repository gives a detailed explanation on making custom trained deepstream-Yolo models predict and send message over kafka.

        - [kn1ghtf1re/yolov8-deepstream-6-1](https://github.com/kn1ghtf1re/yolov8-deepstream-6-1) <img src="https://img.shields.io/github/stars/kn1ghtf1re/yolov8-deepstream-6-1?style=social"/> : YOLOv8 by Ultralytics in DeepStream 6.1.

        - [bharath5673/Deepstream](https://github.com/bharath5673/Deepstream) <img src="https://img.shields.io/github/stars/bharath5673/Deepstream?style=social"/> : yolov2 ,yolov5 ,yolov6 ,yolov7 ,yolov7,yolovR ,yolovX on deepstream.

        - [Savant](https://github.com/insight-platform/Savant) <img src="https://img.shields.io/github/stars/insight-platform/Savant?style=social"/> : Python Computer Vision & Video Analytics Framework With Batteries Included. [savant-ai.io](https://savant-ai.io/)

        - [Savant](https://github.com/quangdungluong/DeepStream-YOLOv11) <img src="https://img.shields.io/github/stars/quangdungluong/DeepStream-YOLOv11?style=social"/> : Plug-and-Play Custom Parsers for AI Models in NVIDIA DeepStream SDK. Supported YOLOv11 model.


    - ##### OpenVINO

        - [OpenVINO](https://github.com/openvinotoolkit/openvino) <img src="https://img.shields.io/github/stars/openvinotoolkit/openvino?style=social"/> : This open source version includes several components: namely Model Optimizer, OpenVINO™ Runtime, Post-Training Optimization Tool, as well as CPU, GPU, MYRIAD, multi device and heterogeneous plugins to accelerate deep learning inferencing on Intel® CPUs and Intel® Processor Graphics.

        - [PINTO0309/OpenVINO-YoloV3](https://github.com/PINTO0309/OpenVINO-YoloV3) <img src="https://img.shields.io/github/stars/PINTO0309/OpenVINO-YoloV3?style=social"/> : YoloV3/tiny-YoloV3 + RaspberryPi3/Ubuntu LaptopPC + NCS/NCS2 + USB Camera + Python + OpenVINO.

        - [TNTWEN/OpenVINO-YOLOV4](https://github.com/TNTWEN/OpenVINO-YOLOV4) <img src="https://img.shields.io/github/stars/TNTWEN/OpenVINO-YOLOV4?style=social"/> : This is implementation of YOLOv4,YOLOv4-relu,YOLOv4-tiny,YOLOv4-tiny-3l,Scaled-YOLOv4 and INT8 Quantization in OpenVINO2021.3.

        - [fb029ed/yolov5_cpp_openvino](https://github.com/fb029ed/yolov5_cpp_openvino) <img src="https://img.shields.io/github/stars/fb029ed/yolov5_cpp_openvino?style=social"/> : 用c++实现了yolov5使用openvino的部署。

        - [dlod-openvino/yolov5_infer](https://github.com/dlod-openvino/yolov5_infer) <img src="https://img.shields.io/github/stars/dlod-openvino/yolov5_infer?style=social"/> : Do the YOLOv5 model inference by OpenCV/OpenVINO based on onnx model format.

        - [snail0614/yolov5.6_openvino_cpp](https://github.com/snail0614/yolov5.6_openvino_cpp) <img src="https://img.shields.io/github/stars/snail0614/yolov5.6_openvino_cpp?style=social"/> : yolov5.6.1 OpenVINO的C++实现。

        - [shungfu/openvino_yolov5v7](https://github.com/shungfu/openvino_yolov5v7) <img src="https://img.shields.io/github/stars/shungfu/openvino_yolov5v7?style=social"/> : YOLOv5 YOLOv7 INT8 quantization using OpenVINO.

        - [dacquaviva/yolov5-openvino-cpp-python](https://github.com/dacquaviva/yolov5-openvino-cpp-python) <img src="https://img.shields.io/github/stars/dacquaviva/yolov5-openvino-cpp-python?style=social"/> : Example of using ultralytics YOLOv5 with Openvino in C++ and Python.

        - [rlggyp/YOLOv10-OpenVINO-CPP-Inference](https://github.com/rlggyp/YOLOv10-OpenVINO-CPP-Inference) <img src="https://img.shields.io/github/stars/rlggyp/YOLOv10-OpenVINO-CPP-Inference?style=social"/> : YOLOv10 C++ implementation using OpenVINO for efficient and accurate real-time object detection.




    - ##### NCNN

        - [NCNN](https://github.com/Tencent/ncnn) <img src="https://img.shields.io/github/stars/Tencent/ncnn?style=social"/> : ncnn is a high-performance neural network inference framework optimized for the mobile platform.

        - [Baiyuetribe/ncnn-models](https://github.com/Baiyuetribe/ncnn-models) <img src="https://img.shields.io/github/stars/Baiyuetribe/ncnn-models?style=social"/> : awesome AI models with NCNN, and how they were converted ✨✨✨

        - [Qengineering/YoloV10-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV10-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV10-ncnn-Raspberry-Pi-4?style=social"/> : YoloV10 for a bare Raspberry Pi 4 or 5.

        - [cmdbug/YOLOv5_NCNN](https://github.com/cmdbug/YOLOv5_NCNN) <img src="https://img.shields.io/github/stars/cmdbug/YOLOv5_NCNN?style=social"/> : 🍅 Deploy ncnn on mobile phones. Support Android and iOS. 移动端ncnn部署，支持Android与iOS。

        - [natanielruiz/android-yolo](https://github.com/natanielruiz/android-yolo) <img src="https://img.shields.io/github/stars/natanielruiz/android-yolo?style=social"/> : Real-time object detection on Android using the YOLO network with TensorFlow.

        - [nihui/ncnn-android-yolov5](https://github.com/nihui/ncnn-android-yolov5) <img src="https://img.shields.io/github/stars/nihui/ncnn-android-yolov5?style=social"/> : The YOLOv5 object detection android example.

        - [szaza/android-yolo-v2](https://github.com/szaza/android-yolo-v2) <img src="https://img.shields.io/github/stars/szaza/android-yolo-v2?style=social"/> : Android YOLO real time object detection sample application with Tensorflow mobile.

        - [FeiGeChuanShu/ncnn-android-yolox](https://github.com/FeiGeChuanShu/ncnn-android-yolox) <img src="https://img.shields.io/github/stars/FeiGeChuanShu/ncnn-android-yolox?style=social"/> : Real time yolox Android demo by ncnn.

        - [xiangweizeng/darknet2ncnn](https://github.com/xiangweizeng/darknet2ncnn) <img src="https://img.shields.io/github/stars/xiangweizeng/darknet2ncnn?style=social"/> : Darknet2ncnn converts the darknet model to the ncnn model.

        - [sunnyden/YOLOV5_NCNN_Android](https://github.com/sunnyden/YOLOV5_NCNN_Android) <img src="https://img.shields.io/github/stars/sunnyden/YOLOV5_NCNN_Android?style=social"/> : YOLOv5 C++ Implementation on Android using NCNN framework.

        - [duangenquan/YoloV2NCS](https://github.com/duangenquan/YoloV2NCS) <img src="https://img.shields.io/github/stars/duangenquan/YoloV2NCS?style=social"/> : This project shows how to run tiny yolo v2 with movidius stick.

        - [lp6m/yolov5s_android](https://github.com/lp6m/yolov5s_android) <img src="https://img.shields.io/github/stars/lp6m/yolov5s_android?style=social"/> : Run yolov5s on Android device!

        - [KoheiKanagu/ncnn_yolox_flutter](https://github.com/KoheiKanagu/ncnn_yolox_flutter) <img src="https://img.shields.io/github/stars/KoheiKanagu/ncnn_yolox_flutter?style=social"/> : This is a plugin to run YOLOX on ncnn.

        - [cyrillkuettel/ncnn-android-yolov5](https://github.com/cyrillkuettel/ncnn-android-yolov5) <img src="https://img.shields.io/github/stars/cyrillkuettel/ncnn-android-yolov5?style=social"/> : This is a sample ncnn android project, it depends on ncnn library and opencv.

        - [DataXujing/ncnn_android_yolov6](https://github.com/DataXujing/ncnn_android_yolov6) <img src="https://img.shields.io/github/stars/DataXujing/ncnn_android_yolov6?style=social"/> : 手摸手实现基于QT和NCNN的安卓手机YOLOv6模型的部署！

        - [Qengineering/YoloV3-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV3-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV3-ncnn-Raspberry-Pi-4?style=social"/> : YoloV3 Raspberry Pi 4.

        - [Qengineering/YoloV4-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV4-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV4-ncnn-Raspberry-Pi-4?style=social"/> : YoloV4 on a bare Raspberry Pi 4 with ncnn framework.

        - [Qengineering/YoloV5-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV5-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV5-ncnn-Raspberry-Pi-4?style=social"/> : YoloV5 for a bare Raspberry Pi 4.

        - [Qengineering/YoloV6-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV6-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV6-ncnn-Raspberry-Pi-4?style=social"/> : YoloV6 for a bare Raspberry Pi using ncnn.

        - [Qengineering/YoloV7-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV7-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV7-ncnn-Raspberry-Pi-4?style=social"/> : YoloV7 for a bare Raspberry Pi using ncnn.

        - [Qengineering/YoloV8-ncnn-Raspberry-Pi-4](https://github.com/Qengineering/YoloV8-ncnn-Raspberry-Pi-4) <img src="https://img.shields.io/github/stars/Qengineering/YoloV8-ncnn-Raspberry-Pi-4?style=social"/> : YoloV8 for a bare Raspberry Pi 4.

        - [FeiGeChuanShu/ncnn-android-yolov8](https://github.com/FeiGeChuanShu/ncnn-android-yolov8) <img src="https://img.shields.io/github/stars/FeiGeChuanShu/ncnn-android-yolov8?style=social"/> : Real time yolov8 Android demo by ncnn.

        - [FLamefiREz/yolov10-android-ncnn](https://github.com/FLamefiREz/yolov10-android-ncnn) <img src="https://img.shields.io/github/stars/FLamefiREz/yolov10-android-ncnn?style=social"/> : yolov10-android-ncnn.


    - ##### MNN

        - [MNN](https://github.com/alibaba/MNN) <img src="https://img.shields.io/github/stars/alibaba/MNN?style=social"/> : MNN is a blazing fast, lightweight deep learning framework, battle-tested by business-critical use cases in Alibaba. (**[MLSys 2020](https://proceedings.mlsys.org/paper/2020/hash/8f14e45fceea167a5a36dedd4bea2543-Abstract.html)**)

        - [apxlwl/MNN-yolov3](https://github.com/apxlwl/MNN-yolov3) <img src="https://img.shields.io/github/stars/apxlwl/MNN-yolov3?style=social"/> : MNN demo of Strongeryolo, including channel pruning, android support...







    - ##### Other Engine

        - [TVM](https://github.com/apache/tvm) <img src="https://img.shields.io/github/stars/apache/tvm?style=social"/> : Open deep learning compiler stack for cpu, gpu and specialized accelerators.

        - [ceccocats/tkDNN](https://github.com/ceccocats/tkDNN) <img src="https://img.shields.io/github/stars/ceccocats/tkDNN?style=social"/> : Deep neural network library and toolkit to do high performace inference on NVIDIA jetson platforms. "A Systematic Assessment of Embedded Neural Networks for Object Detection". (**[IEEE ETFA 2020](https://ieeexplore.ieee.org/document/9212130)**)

        - [Tengine](https://github.com/OAID/Tengine) <img src="https://img.shields.io/github/stars/OAID/Tengine?style=social"/> : Tengine is a lite, high performance, modular inference engine for embedded device.

        - [Paddle Lite](https://github.com/paddlepaddle/paddle-lite) <img src="https://img.shields.io/github/stars/paddlepaddle/paddle-lite?style=social"/> : Multi-platform high performance deep learning inference engine (飞桨多端多平台高性能深度学习推理引擎）。

        - [DeployAI/nndeploy](https://github.com/DeployAI/nndeploy) <img src="https://img.shields.io/github/stars/DeployAI/nndeploy?style=social"/> : nndeploy is a cross-platform, high-performing, and straightforward AI model deployment framework. We strive to deliver a consistent and user-friendly experience across various inference framework in complex deployment environments and focus on performance. nndeploy一款跨平台、高性能、简单易用的模型端到端部署框架。我们致力于屏蔽不同推理框架的差异，提供一致且用户友好的编程体验，同时专注于部署全流程的性能。

        - [yhwang-hub/dl_model_infer](https://github.com/yhwang-hub/dl_model_infer) <img src="https://img.shields.io/github/stars/yhwang-hub/dl_model_infer?style=social"/> : his is a c++ version of the AI reasoning library. Currently, it only supports the reasoning of the tensorrt model. The follow-up plan supports the c++ reasoning of frameworks such as Openvino, NCNN, and MNN. There are two versions for pre- and post-processing, c++ version and cuda version. It is recommended to use the cuda version., This repository provides accelerated deployment cases of deep learning CV popular models, and cuda c supports dynamic-batch image process, infer, decode, NMS.

        - [hollance/YOLO-CoreML-MPSNNGraph](https://github.com/hollance/YOLO-CoreML-MPSNNGraph) <img src="https://img.shields.io/github/stars/hollance/YOLO-CoreML-MPSNNGraph?style=social"/> : Tiny YOLO for iOS implemented using CoreML but also using the new MPS graph API.

        - [r4ghu/iOS-CoreML-Yolo](https://github.com/r4ghu/iOS-CoreML-Yolo) <img src="https://img.shields.io/github/stars/r4ghu/iOS-CoreML-Yolo?style=social"/> : This is the implementation of Object Detection using Tiny YOLO v1 model on Apple's CoreML Framework.

        - [airockchip/rknn_model_zoo](https://github.com/airockchip/rknn_model_zoo) <img src="https://img.shields.io/github/stars/airockchip/rknn_model_zoo?style=social"/> : Rockchip Neural Network(RKNN)是瑞芯微为了加速模型推理而基于自身NPU硬件架构定义的一套模型格式.使用该格式定义的模型在Rockchip NPU上可以获得远高于CPU/GPU的性能。

        - [LynxiTechnology/Lynxi-model-zoo](https://github.com/LynxiTechnology/Lynxi-model-zoo) <img src="https://img.shields.io/github/stars/LynxiTechnology/Lynxi-model-zoo?style=social"/> : Lynxi-model-zoo.


  - ### NPU and FPGA Hardware Deployment
    #### NPU 和 FPGA 硬件部署

    - ##### RK3588

        - [Qengineering/YoloV8-NPU](https://github.com/Qengineering/YoloV8-NPU) <img src="https://img.shields.io/github/stars/Qengineering/YoloV8-NPU?style=social"/> : YoloV8 for RK3566/68/88 NPU (Rock 5, Orange Pi 5, Radxa Zero 3).

        - [aemior/yolov8n_rk3588](https://github.com/aemior/yolov8n_rk3588) <img src="https://img.shields.io/github/stars/aemior/yolov8n_rk3588?style=social"/> : This repository contains a demonstration of Yolv8n running on an RK3588 device.

        - [cqu20160901/yolov8n_rknn_Cplusplus_dfl](https://github.com/cqu20160901/yolov8n_rknn_Cplusplus_dfl) <img src="https://img.shields.io/github/stars/cqu20160901/yolov8n_rknn_Cplusplus_dfl?style=social"/> : yolov8 瑞芯微 rknn 板端 C++部署，使用平台 rk3588，全网最简单、运行最快的部署方式。

        - [cqu20160901/yolov8seg_rknn_Cplusplus](https://github.com/cqu20160901/yolov8seg_rknn_Cplusplus) <img src="https://img.shields.io/github/stars/cqu20160901/yolov8seg_rknn_Cplusplus?style=social"/> : yolov8seg 瑞芯微 rknn 板端 C++部署，使用平台 rk3588。

        - [Ley-WL/ultralytics-rknn](https://github.com/Ley-WL/ultralytics-rknn) <img src="https://img.shields.io/github/stars/Ley-WL/ultralytics-rknn?style=social"/> : 基于ultralytics-yolov8, 将其检测/分类/分割/姿态等任务移植到rk3588上。

        - [455670288/rknn-yolov8s-multi-thread-inference](https://github.com/455670288/rknn-yolov8s-multi-thread-inference) <img src="https://img.shields.io/github/stars/455670288/rknn-yolov8s-multi-thread-inference?style=social"/> : yolov8s在rk3588的推理部署，并使用多线程池并行npu推理加速。

        - [leafqycc/rknn-cpp-Multithreading](https://github.com/leafqycc/rknn-cpp-Multithreading) <img src="https://img.shields.io/github/stars/leafqycc/rknn-cpp-Multithreading?style=social"/> : A simple demo of yolov5s running on rk3588/3588s using c++ (about 142 frames). / 一个使用c++在rk3588/3588s上运行的yolov5s简单demo(142帧/s)。

        - [leafqycc/rknn-multi-threaded](https://github.com/leafqycc/rknn-multi-threaded) <img src="https://img.shields.io/github/stars/leafqycc/rknn-multi-threaded?style=social"/> : A simple demo of yolov5s running on rk3588/3588s using Python (about 72 frames). / 一个使用Python在rk3588/3588s上运行的yolov5s简单demo(大约72帧/s)。

        - [wzxzhuxi/rknn-3588-npu-yolo-accelerate](https://github.com/wzxzhuxi/rknn-3588-npu-yolo-accelerate) <img src="https://img.shields.io/github/stars/wzxzhuxi/rknn-3588-npu-yolo-accelerate?style=social"/> : rknn-3588部署yolov5，利用线程池实现npu推理加速；Deploying YOLOv5 on RKNN-3588, utilizing a thread pool to achieve NPU inference acceleration.

        - [kaylorchen/rk3588-yolo-demo](https://github.com/kaylorchen/rk3588-yolo-demo) <img src="https://img.shields.io/github/stars/kaylorchen/rk3588-yolo-demo?style=social"/> : The project is a multi-threaded inference demo of Yolo running on the RK3588 platform, which has been adapted for reading video files and camera feeds. The demo uses the Yolov8n model for file inference, with a maximum inference frame rate of up to 100 frames per second.

        - [MontaukLaw/yolov5_3588_multi_thread](https://github.com/MontaukLaw/yolov5_3588_multi_thread) <img src="https://img.shields.io/github/stars/MontaukLaw/yolov5_3588_multi_thread?style=social"/> : 启动多线程, relu激活, 3588的yolo部署, 帧率150以上.

        - [crab2rab/RKNN-YOLOV5-BatchInference-MultiThreading](https://github.com/crab2rab/RKNN-YOLOV5-BatchInference-MultiThreading) <img src="https://img.shields.io/github/stars/crab2rab/RKNN-YOLOV5-BatchInference-MultiThreading?style=social"/> : RKNN-YOLOV5-BatchInference-MultiThreadingYOLOV5多张图片多线程C++推理。

        - [Qengineering/YoloV10-NPU](https://github.com/Qengineering/YoloV10-NPU) <img src="https://img.shields.io/github/stars/Qengineering/YoloV10-NPU?style=social"/> : YoloV10 NPU for the RK3566/68/88.

        - [cqu20160901/yolov10_rknn_Cplusplus](https://github.com/cqu20160901/yolov10_rknn_Cplusplus) <img src="https://img.shields.io/github/stars/cqu20160901/yolov10_rknn_Cplusplus?style=social"/> : yolov10 瑞芯微 rknn 板端 C++部署，使用平台 rk3588。

        - [Zhou-sx/yolov5_Deepsort_rknn](https://github.com/Zhou-sx/yolov5_Deepsort_rknn) <img src="https://img.shields.io/github/stars/Zhou-sx/yolov5_Deepsort_rknn?style=social"/> : Track vehicles and persons on rk3588 / rk3399pro.

        - [Applied-Deep-Learning-Lab/Yolov5_RK3588](https://github.com/Applied-Deep-Learning-Lab/Yolov5_RK3588) <img src="https://img.shields.io/github/stars/Applied-Deep-Learning-Lab/Yolov5_RK3588?style=social"/> : Yolov5_RK3588.

        - [cqu20160901/yolov10_onnx_rknn_horizon_tensorRT](https://github.com/cqu20160901/yolov10_onnx_rknn_horizon_tensorRT) <img src="https://img.shields.io/github/stars/cqu20160901/yolov10_onnx_rknn_horizon_tensorRT?style=social"/> : yolov10 目标检测部署版本，便于移植不同平台（onnx、tensorRT、rknn、Horizon），全网部署最简单、运行速度最快的部署方式（全网首发）。

        - [icetd/RkYoloRtspServer](https://github.com/icetd/RkYoloRtspServer) <img src="https://img.shields.io/github/stars/icetd/RkYoloRtspServer?style=social"/> : simple yolov5 rtspserver for rk3588.


    - ##### FPGA

        - [Xilinx/Vitis-AI](https://github.com/Xilinx/Vitis-AI/tree/master/demo) <img src="https://img.shields.io/github/stars/Xilinx/Vitis-AI?style=social"/> : Vitis AI offers a unified set of high-level C++/Python programming APIs to run AI applications across edge-to-cloud platforms, including DPU for Alveo, and DPU for Zynq Ultrascale+ MPSoC and Zynq-7000. It brings the benefits to easily port AI applications from cloud to edge and vice versa. 10 samples in [VART Samples](https://github.com/Xilinx/Vitis-AI/tree/master/demo/VART) are available to help you get familiar with the unfied programming APIs. [Vitis-AI-Library](https://github.com/Xilinx/Vitis-AI/tree/master/demo/Vitis-AI-Library) provides an easy-to-use and unified interface by encapsulating many efficient and high-quality neural networks.

        - [tensil-ai/tensil](https://github.com/tensil-ai/tensil) <img src="https://img.shields.io/github/stars/tensil-ai/tensil?style=social"/> : Open source machine learning accelerators. [www.tensil.ai](https://www.tensil.ai/)

        - [19801201/SpinalHDL_CNN_Accelerator](https://github.com/19801201/SpinalHDL_CNN_Accelerator) <img src="https://img.shields.io/github/stars/19801201/SpinalHDL_CNN_Accelerator?style=social"/> : CNN accelerator implemented with Spinal HDL.

        - [dhm2013724/yolov2_xilinx_fpga](https://github.com/dhm2013724/yolov2_xilinx_fpga) <img src="https://img.shields.io/github/stars/dhm2013724/yolov2_xilinx_fpga?style=social"/> : YOLOv2 Accelerator in Xilinx's Zynq-7000 Soc(PYNQ-z2, Zedboard and ZCU102). (**[硕士论文 2019](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CMFD&dbname=CMFDTEMP&filename=1019228234.nh&uid=WEEvREcwSlJHSldRa1FhdXNXaEhoOGhUTzA5T0tESzdFZ2pyR1NJR1ZBaz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MjE5NTN5dmdXN3JBVkYyNkY3RzZGdFBQcTVFYlBJUjhlWDFMdXhZUzdEaDFUM3FUcldNMUZyQ1VSTE9lWnVkdUY=), [电子技术应用 2019](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2019&filename=DZJY201908009&uid=WEEvREcwSlJHSldRa1FhdXNXaEhoOGhUTzA5T0tESzdFZ2pyR1NJR1ZBaz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MDU0NDJDVVJMT2VadWR1Rnl2Z1c3ck1JVGZCZDdHNEg5ak1wNDlGYllSOGVYMUx1eFlTN0RoMVQzcVRyV00xRnI=), [计算机科学与探索 2019](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDTEMP&filename=KXTS201910005&uid=WEEvREcwSlJHSldRa1FhdXNXaEhoOGhUTzA5T0tESzdFZ2pyR1NJR1ZBaz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MjkwNzdXTTFGckNVUkxPZVp1ZHVGeXZnVzdyT0xqWGZmYkc0SDlqTnI0OUZZWVI4ZVgxTHV4WVM3RGgxVDNxVHI=)**)

        - [Yu-Zhewen/Tiny_YOLO_v3_ZYNQ](https://github.com/Yu-Zhewen/Tiny_YOLO_v3_ZYNQ) <img src="https://img.shields.io/github/stars/Yu-Zhewen/Tiny_YOLO_v3_ZYNQ?style=social"/> : Implement Tiny YOLO v3 on ZYNQ. "A Parameterisable FPGA-Tailored Architecture for YOLOv3-Tiny". (**[ARC 2020](https://link.springer.com/chapter/10.1007/978-3-030-44534-8_25)**)

        - [HSqure/ultralytics-pt-yolov3-vitis-ai-edge](https://github.com/HSqure/ultralytics-pt-yolov3-vitis-ai-edge) <img src="https://img.shields.io/github/stars/HSqure/ultralytics-pt-yolov3-vitis-ai-edge?style=social"/> : This demo is only used for inference testing of Vitis AI v1.4 and quantitative compilation of DPU. It is compatible with the training results of [ultralytics/yolov3](https://github.com/ultralytics/yolov3) v9.5.0 (it needs to use the model saving method of Pytorch V1.4).

        - [mcedrdiego/Kria_yolov3_ppe](https://github.com/mcedrdiego/Kria_yolov3_ppe) <img src="https://img.shields.io/github/stars/mcedrdiego/Kria_yolov3_ppe?style=social"/> : Kria KV260 Real-Time Personal Protective Equipment Detection. "Deep Learning for Site Safety: Real-Time Detection of Personal Protective Equipment". (**[Automation in Construction 2020](https://www.sciencedirect.com/science/article/abs/pii/S0926580519308325)**)

        - [xlsjdjdk/Ship-Detection-based-on-YOLOv3-and-KV260](https://github.com/xlsjdjdk/Ship-Detection-based-on-YOLOv3-and-KV260) <img src="https://img.shields.io/github/stars/xlsjdjdk/Ship-Detection-based-on-YOLOv3-and-KV260?style=social"/> : This is the entry project of the Xilinx Adaptive Computing Challenge 2021. It uses YOLOv3 for ship target detection in optical remote sensing images, and deploys DPU on the KV260 platform to achieve hardware acceleration.

        - [Pomiculture/YOLOv4-Vitis-AI](https://github.com/Pomiculture/YOLOv4-Vitis-AI) <img src="https://img.shields.io/github/stars/Pomiculture/YOLOv4-Vitis-AI?style=social"/> : Custom YOLOv4 for apple recognition (clean/damaged) on Alveo U280 accelerator card using Vitis AI framework.

        - [mkshuvo2/ZCU104_YOLOv3_Post_Processing](https://github.com/mkshuvo2/ZCU104_YOLOv3_Post_Processing) <img src="https://img.shields.io/github/stars/mkshuvo2/ZCU104_YOLOv3_Post_Processing?style=social"/> : Tensor outputs form Vitis AI Runner Class for YOLOv3.

        - [puffdrum/v4tiny_pt_quant](https://github.com/puffdrum/v4tiny_pt_quant) <img src="https://img.shields.io/github/stars/puffdrum/v4tiny_pt_quant?style=social"/> : quantization for yolo with xilinx/vitis-ai-pytorch.

        - [chanshann/LITE_YOLOV3_TINY_VITISAI](https://github.com/chanshann/LITE_YOLOV3_TINY_VITISAI) <img src="https://img.shields.io/github/stars/chanshann/LITE_YOLOV3_TINY_VITISAI?style=social"/> : LITE_YOLOV3_TINY_VITISAI.

        - [LukiBa/zybo_yolo](https://github.com/LukiBa/zybo_yolo) <img src="https://img.shields.io/github/stars/LukiBa/zybo_yolo?style=social"/> : YOLO example implementation using Intuitus CNN accelerator on ZYBO ZYNQ-7000 FPGA board.

        - [matsuda-slab/YOLO_ZYNQ_MASTER](https://github.com/matsuda-slab/YOLO_ZYNQ_MASTER) <img src="https://img.shields.io/github/stars/matsuda-slab/YOLO_ZYNQ_MASTER?style=social"/> : Implementation of YOLOv3-tiny on FPGA.

        - [FerberZhang/Yolov2-FPGA-CNN-](https://github.com/FerberZhang/Yolov2-FPGA-CNN-) <img src="https://img.shields.io/github/stars/FerberZhang/Yolov2-FPGA-CNN-?style=social"/> : A demo for accelerating YOLOv2 in xilinx's fpga PYNQ.

        - [ChainZeeLi/FPGA_DPU](https://github.com/ChainZeeLi/FPGA_DPU) <img src="https://img.shields.io/github/stars/ChainZeeLi/FPGA_DPU?style=social"/> : This project is to implement YOLO v3 on Xilinx FPGA with DPU.

        - [xbdxwyh/yolov3_fpga_project](https://github.com/xbdxwyh/yolov3_fpga_project) <img src="https://img.shields.io/github/stars/xbdxwyh/yolov3_fpga_project?style=social"/> : yolov3_fpga_project.

        - [ZLkanyo009/Yolo-compression-and-deployment-in-FPGA](https://github.com/ZLkanyo009/Yolo-compression-and-deployment-in-FPGA) <img src="https://img.shields.io/github/stars/ZLkanyo009/Yolo-compression-and-deployment-in-FPGA?style=social"/> : 基于FPGA量化的人脸口罩检测。

        - [xiying-boy/yolov3-AX7350](https://github.com/xiying-boy/yolov3-AX7350) <img src="https://img.shields.io/github/stars/xiying-boy/yolov3-AX7350?style=social"/> : 基于HLS_YOLOV3的驱动文件。

        - [himewel/yolowell](https://github.com/himewel/yolowell) <img src="https://img.shields.io/github/stars/himewel/yolowell?style=social"/> : A set of hardware architectures to build a co-design of convolutional neural networks inference at FPGA devices.

        - [embedeep/Free-TPU](https://github.com/embedeep/Free-TPU) <img src="https://img.shields.io/github/stars/embedeep/Free-TPU?style=social"/> : Free TPU for FPGA with Lenet, MobileNet, Squeezenet, Resnet, Inception V3, YOLO V3, and ICNet. Deep learning acceleration using Xilinx zynq (Zedboard or ZC702 ) or kintex-7 to solve image classification, detection, and segmentation problem.

        - [yarakigit/design_contest_yolo_change_ps_to_pl](https://github.com/yarakigit/design_contest_yolo_change_ps_to_pl) <img src="https://img.shields.io/github/stars/yarakigit/design_contest_yolo_change_ps_to_pl?style=social"/> : Converts pytorch yolo format weights to C header files for bare-metal (FPGA implementation).

        - [MasLiang/CNN-On-FPGA](https://github.com/MasLiang/CNN-On-FPGA) <img src="https://img.shields.io/github/stars/MasLiang/CNN-On-FPGA?style=social"/> : This is the code of the CNN on FPGA.But this can only be used for reference at present for some files are write coarsly using ISE.

        - [adamgallas/fpga_accelerator_yolov3tiny](https://github.com/adamgallas/fpga_accelerator_yolov3tiny) <img src="https://img.shields.io/github/stars/adamgallas/fpga_accelerator_yolov3tiny?style=social"/> : fpga_accelerator_yolov3tiny.

        - [ylk678910/tiny-yolov3-fpga](https://github.com/ylk678910/tiny-yolov3-fpga) <img src="https://img.shields.io/github/stars/ylk678910/tiny-yolov3-fpga?style=social"/> : Use an all-programmable SoC board to implement locating and tracking tasks. The hardware algorithm, a row-stationary-like strategy, can parallel calculate and reduce the storage buffer area on FPGA.

        - [zhen8838/K210_Yolo_framework](https://github.com/zhen8838/K210_Yolo_framework) <img src="https://img.shields.io/github/stars/zhen8838/K210_Yolo_framework?style=social"/> : Yolo v3 framework base on tensorflow, support multiple models, multiple datasets, any number of output layers, any number of anchors, model prune, and portable model to K210 !

        - [SEASKY-Master/SEASKY_K210](https://github.com/SEASKY-Master/SEASKY_K210) <img src="https://img.shields.io/github/stars/SEASKY-Master/SEASKY_K210?style=social"/> : K210 PCB YOLO.

        - [SEASKY-Master/Yolo-for-k210](https://github.com/SEASKY-Master/Yolo-for-k210) <img src="https://img.shields.io/github/stars/SEASKY-Master/Yolo-for-k210?style=social"/> : Yolo-for-k210.

        - [TonyZ1Min/yolo-for-k210](https://github.com/TonyZ1Min/yolo-for-k210) <img src="https://img.shields.io/github/stars/TonyZ1Min/yolo-for-k210?style=social"/> : keras-yolo-for-k210.

        - [vseasky/yolo-for-k210](https://github.com/vseasky/yolo-for-k210) <img src="https://img.shields.io/github/stars/vseasky/yolo-for-k210?style=social"/> : Yolo-for-k210.

        - [InnoIPA/dpu-sc](https://github.com/InnoIPA/dpu-sc) <img src="https://img.shields.io/github/stars/innoipa/dpu-sc?style=social"/> : dpu-sc presented how to create quick demos to run AI inference(YOLOv4-Tiny, LPRNet) on DPU with MPSoC.

        - [InnoIPA/vaiGO](https://github.com/InnoIPA/vaiGo) <img src="https://img.shields.io/github/stars/innoipa/vaiGO?style=social"/> : vaiGO means Vitis-ai GO. We provide utility and tutorial that make it easy to convert a trained AI model into a bitstream that can be deployed on an FPGA Edge AI Box.

        - [InnoIPA/EXMU-X261-usermanual](https://github.com/InnoIPA/EXMU-X261-usermanual) <img src="https://img.shields.io/github/stars/innoipa/exmu-x261-usermanual?style=social"/> : We have built more defect detection solutions with YOLOv4-tiny on EXMU-X261.





    - ##### Other Hardware

        - [guichristmann/edge-tpu-tiny-yolo](https://github.com/guichristmann/edge-tpu-tiny-yolo) <img src="https://img.shields.io/github/stars/guichristmann/edge-tpu-tiny-yolo?style=social"/> : Run Tiny YOLO-v3 on Google's Edge TPU USB Accelerator.

        - [Charlie839242/-Trash-Classification-Car](https://github.com/Charlie839242/-Trash-Classification-Car) <img src="https://img.shields.io/github/stars/Charlie839242/-Trash-Classification-Car?style=social"/> : 这是一个基于yolo-fastest模型的小车，主控是art-pi开发板，使用了rt thread操作系统。

        - [Charlie839242/Deploy-yolo-fastest-tflite-on-raspberry](https://github.com/Charlie839242/Deploy-yolo-fastest-tflite-on-raspberry) <img src="https://img.shields.io/github/stars/Charlie839242/Deploy-yolo-fastest-tflite-on-raspberry?style=social"/> : This project deploys a yolo fastest model in the form of tflite on raspberry 3b+.

        - [mahxn0/Hisi3559A_Yolov5](https://github.com/mahxn0/Hisi3559A_Yolov5) <img src="https://img.shields.io/github/stars/mahxn0/Hisi3559A_Yolov5?style=social"/> : 基于hisi3559a的yolov5训练部署全流程。

        - [ZhenxinYUAN/YOLO_hi3516Deploy](https://github.com/ZhenxinYUAN/YOLO_hi3516Deploy) <img src="https://img.shields.io/github/stars/ZhenxinYUAN/YOLO_hi3516Deploy?style=social"/> : Deploy Yolo series algorithms on Hisilicon platform hi3516, including yolov3, yolov5, yolox, etc.

        - [jveitchmichaelis/edgetpu-yolo](https://github.com/jveitchmichaelis/edgetpu-yolo) <img src="https://img.shields.io/github/stars/jveitchmichaelis/edgetpu-yolo?style=social"/> : Minimal-dependency Yolov5 export and inference demonstration for the Google Coral EdgeTPU.

        - [xiaqing10/Hisi_YoLoV5](https://github.com/xiaqing10/Hisi_YoLoV5) <img src="https://img.shields.io/github/stars/xiaqing10/Hisi_YoLoV5?style=social"/> : 海思nnie跑yolov5。

        - [BaronLeeLZP/hi3516dv300_nnie-yolov3-demo](https://github.com/BaronLeeLZP/hi3516dv300_nnie-yolov3-demo) <img src="https://img.shields.io/github/stars/BaronLeeLZP/hi3516dv300_nnie-yolov3-demo?style=social"/> : 在海思Hisilicon的Hi3516dv300芯片上，利用nnie和opencv库，简洁了官方yolov3用例中各种复杂的嵌套调用/复杂编译，提供了交叉编译后可成功上板部署运行的demo。

        - [OpenVINO-dev-contest/YOLOv7_OpenVINO](https://github.com/OpenVINO-dev-contest/YOLOv7_OpenVINO) <img src="https://img.shields.io/github/stars/OpenVINO-dev-contest/YOLOv7_OpenVINO?style=social"/> : This repository will demostrate how to deploy a offical YOLOv7 pre-trained model with OpenVINO runtime api.

        - [littledeep/YOLOv5-RK3399Pro](https://github.com/littledeep/YOLOv5-RK3399Pro) <img src="https://img.shields.io/github/stars/littledeep/YOLOv5-RK3399Pro?style=social"/> : PyTorch-->ONNX-->RKNN.

        - [jnulzl/YOLOV5_RK1126](https://github.com/jnulzl/YOLOV5_RK1126) <img src="https://img.shields.io/github/stars/jnulzl/YOLOV5_RK1126?style=social"/> : yolov5 rk1126 cpp code.

        - [Qengineering/YoloCam](https://github.com/Qengineering/YoloCam) <img src="https://img.shields.io/github/stars/Qengineering/YoloCam?style=social"/> : AI camera with live feed, email notification, Gdrive storage and event-triggered GPIO. Raspberry Pi stand-alone AI-powered camera with live feed, email notification and event-triggered cloud storage.

        - [LSH9832/edgeyolo](https://github.com/LSH9832/edgeyolo) <img src="https://img.shields.io/github/stars/LSH9832/edgeyolo?style=social"/> : an edge-real-time anchor-free object detector with decent performance.

        - [liuyuan000/Rv1126_YOLOv5-Lite](https://github.com/liuyuan000/Rv1126_YOLOv5-Lite) <img src="https://img.shields.io/github/stars/liuyuan000/Rv1126_YOLOv5-Lite?style=social"/> : YOLOv5-Lite在Rv1126部署。





  - ### Pruning Knoweldge-Distillation Quantization

    - ##### Pruning
      ###### 剪枝

        - [Torch-Pruning](https://github.com/VainF/Torch-Pruning) <img src="https://img.shields.io/github/stars/VainF/Torch-Pruning?style=social"/> : Towards Any Structural Pruning; LLMs / SAM / Diffusion / Transformers / YOLOv8 / CNNs. "Towards Any Structural Pruning". (**[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/html/Fang_DepGraph_Towards_Any_Structural_Pruning_CVPR_2023_paper.html)**)

        - [SparseML](https://github.com/neuralmagic/sparseml) <img src="https://img.shields.io/github/stars/neuralmagic/sparseml?style=social"/> : Libraries for applying sparsification recipes to neural networks with a few lines of code, enabling faster and smaller models. "Inducing and Exploiting Activation Sparsity for Fast Inference on Deep Neural Networks". (**[PMLR 2020](http://proceedings.mlr.press/v119/kurtz20a.html)**). "Woodfisher: Efficient second-order approximation for neural network compression". (**[NeurIPS 2020](https://proceedings.neurips.cc/paper/2020/hash/d1ff1ec86b62cd5f3903ff19c3a326b2-Abstract.html)**)

        - [SparseZoo](https://github.com/neuralmagic/sparsezoo) <img src="https://img.shields.io/github/stars/neuralmagic/sparsezoo?style=social"/> : Neural network model repository for highly sparse and sparse-quantized models with matching sparsification recipes.

        - [Gumpest/YOLOv5-Multibackbone-Compression](https://github.com/Gumpest/YOLOv5-Multibackbone-Compression) <img src="https://img.shields.io/github/stars/Gumpest/YOLOv5-Multibackbone-Compression?style=social"/> : YOLOv5 Series Multi-backbone(TPH-YOLOv5, Ghostnet, ShuffleNetv2, Mobilenetv3Small, EfficientNetLite, PP-LCNet, SwinTransformer YOLO), Module(CBAM, DCN), Pruning (EagleEye, Network Slimming) and Quantization (MQBench) Compression Tool Box.

        - [SlimYOLOv3](https://github.com/PengyiZhang/SlimYOLOv3) <img src="https://img.shields.io/github/stars/PengyiZhang/SlimYOLOv3?style=social"/> : "SlimYOLOv3: Narrower, Faster and Better for UAV Real-Time Applications". (**[arXiv 2019](https://arxiv.org/abs/1907.11093)**)

        - [uyzhang/yolov5_prune](https://github.com/uyzhang/yolov5_prune) <img src="https://img.shields.io/github/stars/uyzhang/yolov5_prune?style=social"/> : Yolov5 pruning on COCO Dataset.

        - [midasklr/yolov5prune](https://github.com/midasklr/yolov5prune) <img src="https://img.shields.io/github/stars/midasklr/yolov5prune?style=social"/> : yolov5模型剪枝。

        - [ZJU-lishuang/yolov5_prune](https://github.com/ZJU-lishuang/yolov5_prune) <img src="https://img.shields.io/github/stars/ZJU-lishuang/yolov5_prune?style=social"/> : yolov5 prune，Support V2, V3, V4 and V6 versions of yolov5.

        - [sbbug/yolov5-prune-multi](https://github.com/sbbug/yolov5-prune-multi) <img src="https://img.shields.io/github/stars/sbbug/yolov5-prune-multi?style=social"/> : yolov5-prune-multi 无人机视角、多模态、模型剪枝、国产AI芯片部署。

        - [Syencil/mobile-yolov5-pruning-distillation](https://github.com/Syencil/mobile-yolov5-pruning-distillation) <img src="https://img.shields.io/github/stars/Syencil/mobile-yolov5-pruning-distillation?style=social"/> : mobilev2-yolov5s剪枝、蒸馏，支持ncnn，tensorRT部署。ultra-light but better performence！

        - [Lam1360/YOLOv3-model-pruning](https://github.com/Lam1360/YOLOv3-model-pruning) <img src="https://img.shields.io/github/stars/Lam1360/YOLOv3-model-pruning?style=social"/> : 在 oxford hand 数据集上对 YOLOv3 做模型剪枝（network slimming）。

        - [tanluren/yolov3-channel-and-layer-pruning](https://github.com/tanluren/yolov3-channel-and-layer-pruning) <img src="https://img.shields.io/github/stars/tanluren/yolov3-channel-and-layer-pruning?style=social"/> : yolov3 yolov4 channel and layer pruning, Knowledge Distillation 层剪枝，通道剪枝，知识蒸馏。

        - [coldlarry/YOLOv3-complete-pruning](https://github.com/coldlarry/YOLOv3-complete-pruning) <img src="https://img.shields.io/github/stars/coldlarry/YOLOv3-complete-pruning?style=social"/> : 提供对YOLOv3及Tiny的多种剪枝版本，以适应不同的需求。

        - [SpursLipu/YOLOv3v4-ModelCompression-MultidatasetTraining-Multibackbone](https://github.com/SpursLipu/YOLOv3v4-ModelCompression-MultidatasetTraining-Multibackbone) <img src="https://img.shields.io/github/stars/SpursLipu/YOLOv3v4-ModelCompression-MultidatasetTraining-Multibackbone?style=social"/> : YOLO ModelCompression MultidatasetTraining.

        - [talebolano/yolov3-network-slimming](https://github.com/talebolano/yolov3-network-slimming) <img src="https://img.shields.io/github/stars/talebolano/yolov3-network-slimming?style=social"/> : yolov3 network slimming剪枝的一种实现。


        - [Bigtuo/YOLOX-Lite](https://github.com/Bigtuo/YOLOX-Lite) <img src="https://img.shields.io/github/stars/Bigtuo/YOLOX-Lite?style=social"/> : 将YOLOv5-Lite代码中的head更换为YOLOX head。

        - [YINYIPENG-EN/Pruning_for_YOLOV5_pytorch](https://github.com/YINYIPENG-EN/Pruning_for_YOLOV5_pytorch) <img src="https://img.shields.io/github/stars/YINYIPENG-EN/Pruning_for_YOLOV5_pytorch?style=social"/> : Pruning_for_YOLOV5_pytorch.

        - [chumingqian/Model_Compression_For_YOLOV3-V4](https://github.com/chumingqian/Model_Compression_For_YOLOV3-V4) <img src="https://img.shields.io/github/stars/chumingqian/Model_Compression_For_YOLOV3-V4?style=social"/> : In this repository using the dynamic sparse training( variable sparse rate s which can speed up the sparse training process), channel pruning and knowledge distilling for YOLOV3 and YOLOV4.

        - [xhwNobody/yolov5_prune_sfp](https://github.com/xhwNobody/yolov5_prune_sfp) <img src="https://img.shields.io/github/stars/xhwNobody/yolov5_prune_sfp?style=social"/> : 基于SFP和FPGM的yolov5的软剪枝实现。



    - ##### Quantization
      ###### 量化

        - [dog-qiuqiu/FastestDet](https://github.com/dog-qiuqiu/FastestDet) <img src="https://img.shields.io/github/stars/dog-qiuqiu/FastestDet?style=social"/> : ⚡ A newly designed ultra lightweight anchor free target detection algorithm， weight only 250K parameters， reduces the time consumption by 10% compared with yolo-fastest, and the post-processing is simpler. "知乎「马雪浩」《[FastestDet: 比yolo-fastest更快！更强！更简单！全新设计的超实时Anchor-free目标检测算法](https://zhuanlan.zhihu.com/p/536500269)》"。 "微信公众号「计算机视觉研究院」《[FastestDet：比yolov5更快！更强！全新设计的超实时Anchor-free目标检测算法（附源代码下载）](https://mp.weixin.qq.com/s/Bskc5WQd8ujy16Jl4qekjQ)》"。

        - [dog-qiuqiu/Yolo-Fastest](https://github.com/dog-qiuqiu/Yolo-Fastest) <img src="https://img.shields.io/github/stars/dog-qiuqiu/Yolo-Fastest?style=social"/> : Yolo-Fastest：超超超快的开源ARM实时目标检测算法。 [Zenodo 2021](http://doi.org/10.5281/zenodo.5131532). "知乎「马雪浩」《[Yolo-Fastest：超超超快的开源ARM实时目标检测算法](https://zhuanlan.zhihu.com/p/234506503)》"。

        - [dog-qiuqiu/Yolo-FastestV2](https://github.com/dog-qiuqiu/Yolo-FastestV2) <img src="https://img.shields.io/github/stars/dog-qiuqiu/Yolo-FastestV2?style=social"/> : Yolo-FastestV2:更快，更轻，移动端可达300FPS，参数量仅250k。 "知乎「马雪浩」《[Yolo-FastestV2:更快，更轻，移动端可达300FPS，参数量仅250k](https://zhuanlan.zhihu.com/p/400474142)》"。

        - [YOLObile](https://github.com/nightsnack/YOLObile) <img src="https://img.shields.io/github/stars/nightsnack/YOLObile?style=social"/> : "YOLObile: Real-Time Object Detection on Mobile Devices via Compression-Compilation Co-Design". (**[AAAI 2021](https://www.aaai.org/AAAI21Papers/AAAI-7561.CaiY.pdf)**)

        - [PaddleSlim](https://github.com/PaddlePaddle/PaddleSlim) <img src="https://img.shields.io/github/stars/PaddlePaddle/PaddleSlim?style=social"/> : PaddleSlim is an open-source library for deep model compression and architecture search. PaddleSlim是一个专注于深度学习模型压缩的工具库，提供低比特量化、知识蒸馏、稀疏化和模型结构搜索等模型压缩策略，帮助用户快速实现模型的小型化。

        - [PPL量化工具](https://github.com/openppl-public/ppq) <img src="https://img.shields.io/github/stars/openppl-public/ppq?style=social"/> : PPL Quantization Tool (PPQ) is a powerful offline neural network quantization tool. PPL QuantTool 是一个高效的工业级神经网络量化工具。

        - [PINTO_model_zoo](https://github.com/PINTO0309/PINTO_model_zoo) <img src="https://img.shields.io/github/stars/PINTO0309/PINTO_model_zoo?style=social"/> : A repository for storing models that have been inter-converted between various frameworks. Supported frameworks are TensorFlow, PyTorch, ONNX, OpenVINO, TFJS, TFTRT, TensorFlowLite (Float32/16/INT8), EdgeTPU, CoreML.

        - [ppogg/YOLOv5-Lite](https://github.com/ppogg/YOLOv5-Lite) <img src="https://img.shields.io/github/stars/ppogg/YOLOv5-Lite?style=social"/> : 🍅🍅🍅YOLOv5-Lite: lighter, faster and easier to deploy. Evolved from yolov5 and the size of model is only 930+kb (int8) and 1.7M (fp16). It can reach 10+ FPS on the Raspberry Pi 4B when the input size is 320×320~

        - [AlexeyAB/yolo2_light](https://github.com/AlexeyAB/yolo2_light) <img src="https://img.shields.io/github/stars/AlexeyAB/yolo2_light?style=social"/> : Light version of convolutional neural network Yolo v3 & v2 for objects detection with a minimum of dependencies (INT8-inference, BIT1-XNOR-inference).




    - ##### Knoweldge-Distillation
      ###### 知识蒸馏

        - [torchdistill](https://github.com/yoshitomo-matsubara/torchdistill) <img src="https://img.shields.io/github/stars/yoshitomo-matsubara/torchdistill?style=social"/> : torchdistill: A Modular, Configuration-Driven Framework for Knowledge Distillation. A coding-free framework built on PyTorch for reproducible deep learning studies. 🏆20 knowledge distillation methods presented at CVPR, ICLR, ECCV, NeurIPS, ICCV, etc are implemented so far. 🎁 Trained models, training logs and configurations are available for ensuring the reproducibiliy and benchmark.

        - [wonbeomjang/yolov5-knowledge-distillation](https://github.com/wonbeomjang/yolov5-knowledge-distillation) <img src="https://img.shields.io/github/stars/wonbeomjang/yolov5-knowledge-distillation?style=social"/> : implementation of [Distilling Object Detectors with Fine-grained Feature Imitation](https://github.com/twangnh/Distilling-Object-Detectors) on yolov5. "Distilling Object Detectors with Fine-grained Feature Imitation". (**[CVPR 2019](https://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Distilling_Object_Detectors_With_Fine-Grained_Feature_Imitation_CVPR_2019_paper.html)**)

        - [Sharpiless/Yolov5-distillation-train-inference](https://github.com/Sharpiless/Yolov5-distillation-train-inference) <img src="https://img.shields.io/github/stars/Sharpiless/Yolov5-distillation-train-inference?style=social"/> : Yolov5 distillation training | Yolov5知识蒸馏训练，支持训练自己的数据。

        - [Sharpiless/yolov5-distillation-5.0](https://github.com/Sharpiless/yolov5-distillation-5.0) <img src="https://img.shields.io/github/stars/Sharpiless/yolov5-distillation-5.0?style=social"/> : yolov5 5.0 version distillation || yolov5 5.0版本知识蒸馏，yolov5l >> yolov5s。

        - [Sharpiless/yolov5-knowledge-distillation](https://github.com/Sharpiless/yolov5-knowledge-distillation) <img src="https://img.shields.io/github/stars/Sharpiless/yolov5-knowledge-distillation?style=social"/> : yolov5目标检测模型的知识蒸馏（基于响应的蒸馏）。

        - [chengpanghu/Knowledge-Distillation-yolov5](https://github.com/chengpanghu/Knowledge-Distillation-yolov5) <img src="https://img.shields.io/github/stars/chengpanghu/Knowledge-Distillation-yolov5?style=social"/> : Knowledge-Distillation-yolov5 基于yolov5的知识蒸馏。

        - [magicshuang/yolov5_distillation](https://github.com/magicshuang/yolov5_distillation) <img src="https://img.shields.io/github/stars/magicshuang/yolov5_distillation?style=social"/> : yolov5 知识蒸馏，yolov5-l模型压缩至yolov5-s 压缩算法是 [Distilling Object Detectors with Fine-grained Feature Imitation](https://github.com/twangnh/Distilling-Object-Detectors)。

        - [Sharpiless/Yolov3-MobileNet-Distillation](https://github.com/Sharpiless/Yolov3-MobileNet-Distillation) <img src="https://img.shields.io/github/stars/Sharpiless/Yolov3-MobileNet-Distillation?style=social"/> : 在Yolov3-MobileNet上进行模型蒸馏训练。


        - [SsisyphusTao/Object-Detection-Knowledge-Distillation](https://github.com/SsisyphusTao/Object-Detection-Knowledge-Distillation) <img src="https://img.shields.io/github/stars/SsisyphusTao/Object-Detection-Knowledge-Distillation?style=social"/> : An Object Detection Knowledge Distillation framework powered by pytorch, now having SSD and yolov5.


  - ### Lightweight Backbones and FPN
    #### 轻量级骨干网络和特征金字塔网络

      - [murufeng/awesome_lightweight_networks](https://github.com/murufeng/awesome_lightweight_networks) <img src="https://img.shields.io/github/stars/murufeng/awesome_lightweight_networks?style=social"/> : The implementation of various lightweight networks by using PyTorch. such as：MobileNetV2，MobileNeXt，GhostNet，ParNet，MobileViT、AdderNet，ShuffleNetV1-V2，LCNet，ConvNeXt，etc. ⭐⭐⭐⭐⭐

      - [Bobo-y/flexible-yolov5](https://github.com/Bobo-y/flexible-yolov5) <img src="https://img.shields.io/github/stars/Bobo-y/flexible-yolov5?style=social"/> : More readable and flexible yolov5 with more backbone(resnet, shufflenet, moblienet, efficientnet, hrnet, swin-transformer) and (cbam，dcn and so on), and tensorrt.

      - [XingZeng307/YOLOv5_with_BiFPN](https://github.com/XingZeng307/YOLOv5_with_BiFPN) <img src="https://img.shields.io/github/stars/XingZeng307/YOLOv5_with_BiFPN?style=social"/> : This repo is mainly for replacing PANet with BiFPN in YOLOv5.

      - [dog-qiuqiu/MobileNet-Yolo](https://github.com/dog-qiuqiu/MobileNet-Yolo) <img src="https://img.shields.io/github/stars/dog-qiuqiu/MobileNet-Yolo?style=social"/> : MobileNetV2-YoloV3-Nano: 0.5BFlops 3MB HUAWEI P40: 6ms/img, YoloFace-500k:0.1Bflops 420KB🔥🔥🔥.

      - [eric612/MobileNet-YOLO](https://github.com/eric612/MobileNet-YOLO) <img src="https://img.shields.io/github/stars/eric612/MobileNet-YOLO?style=social"/> : A caffe implementation of MobileNet-YOLO detection network.

      - [eric612/Mobilenet-YOLO-Pytorch](https://github.com/eric612/Mobilenet-YOLO-Pytorch) <img src="https://img.shields.io/github/stars/eric612/Mobilenet-YOLO-Pytorch?style=social"/> : Include mobilenet series (v1,v2,v3...) and yolo series (yolov3,yolov4,...) .

      - [Adamdad/keras-YOLOv3-mobilenet](https://github.com/Adamdad/keras-YOLOv3-mobilenet) <img src="https://img.shields.io/github/stars/Adamdad/keras-YOLOv3-mobilenet?style=social"/> : A Keras implementation of YOLOv3 (Tensorflow backend) inspired by [allanzelener/YAD2K](https://github.com/allanzelener/YAD2K).

      - [fsx950223/mobilenetv2-yolov3](https://github.com/fsx950223/mobilenetv2-yolov3) <img src="https://img.shields.io/github/stars/fsx950223/mobilenetv2-yolov3?style=social"/> : yolov3 with mobilenetv2 and efficientnet.

      - [liux0614/yolo_nano](https://github.com/liux0614/yolo_nano) <img src="https://img.shields.io/github/stars/liux0614/yolo_nano?style=social"/> : Unofficial implementation of yolo nano.

      - [lingtengqiu/Yolo_Nano](https://github.com/lingtengqiu/Yolo_Nano) <img src="https://img.shields.io/github/stars/lingtengqiu/Yolo_Nano?style=social"/> : Pytorch implementation of yolo_Nano for pedestrian detection.

      - [bubbliiiing/mobilenet-yolov4-pytorch](https://github.com/bubbliiiing/mobilenet-yolov4-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/mobilenet-yolov4-pytorch?style=social"/> : 这是一个mobilenet-yolov4的库，把yolov4主干网络修改成了mobilenet，修改了Panet的卷积组成，使参数量大幅度缩小。

      - [bubbliiiing/efficientnet-yolo3-pytorch](https://github.com/bubbliiiing/efficientnet-yolo3-pytorch) <img src="https://img.shields.io/github/stars/bubbliiiing/efficientnet-yolo3-pytorch?style=social"/> : 这是一个efficientnet-yolo3-pytorch的源码，将yolov3的主干特征提取网络修改成了efficientnet。

      - [HuKai97/YOLOv5-ShuffleNetv2](https://github.com/HuKai97/YOLOv5-ShuffleNetv2) <img src="https://img.shields.io/github/stars/HuKai97/YOLOv5-ShuffleNetv2?style=social"/> : YOLOv5的轻量化改进(蜂巢检测项目)。

      - [YOLO-ReT](https://github.com/guotao0628/yoloret) <img src="https://img.shields.io/github/stars/guotao0628/yoloret?style=social"/> : "YOLO-ReT: Towards High Accuracy Real-time Object Detection on Edge GPUs". (**[WACV 2022](https://openaccess.thecvf.com/content/WACV2022/html/Ganesh_YOLO-ReT_Towards_High_Accuracy_Real-Time_Object_Detection_on_Edge_GPUs_WACV_2022_paper.html)**)


















## Object Detection Applications


  - ### Open World Object Detection
    #### 开放世界目标检测

    - [YOLO-World](https://github.com/AILab-CVC/YOLO-World) <img src="https://img.shields.io/github/stars/AILab-CVC/YOLO-World?style=social"/> : "YOLO-World: Real-Time Open-Vocabulary Object Detection". (**[CVPR 2024](https://arxiv.org/abs/2401.17270)**). [www.yoloworld.cc](https://www.yoloworld.cc/)

    - Florence-2 : "Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks". (**[CVPR 2024](https://arxiv.org/abs/2311.06242)**).

    - [maestro](https://github.com/roboflow/maestro) <img src="https://img.shields.io/github/stars/roboflow/maestro?style=social"/> : VLM fine-tuning for everyone. maestro is a streamlined tool to accelerate the fine-tuning of multimodal models. By encapsulating best practices from our core modules, maestro handles configuration, data loading, reproducibility, and training loop setup. It currently offers ready-to-use recipes for popular vision-language models such as [Florence-2](https://arxiv.org/abs/2311.06242), PaliGemma 2, and [Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL). [maestro.roboflow.com](https://maestro.roboflow.com/latest/)

    - [Autodistill](https://github.com/autodistill/autodistill) <img src="https://img.shields.io/github/stars/autodistill/autodistill?style=social"/> : Images to inference with no labeling (use foundation models to train supervised models). Autodistill uses big, slower foundation models to train small, faster supervised models. Using autodistill, you can go from unlabeled images to inference on a custom model running at the edge with no human intervention in between. [docs.autodistill.com](https://docs.autodistill.com/)

    - [DOSOD](https://github.com/D-Robotics-AI-Lab/DOSOD) <img src="https://img.shields.io/github/stars/D-Robotics-AI-Lab/DOSOD?style=social"/> : "A Light-Weight Framework for Open-Set Object Detection with Decoupled Feature Alignment in Joint Space". (**[arXiv 2024](https://arxiv.org/abs/2412.14680)**).

    - [DINO](https://github.com/IDEA-Research/DINO) <img src="https://img.shields.io/github/stars/IDEA-Research/DINO?style=social"/> : "DINO: DETR with Improved DeNoising Anchor Boxes for End-to-End Object Detection". (**[ICLR 2023](https://arxiv.org/abs/2203.03605)**).

    - [GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) <img src="https://img.shields.io/github/stars/IDEA-Research/GroundingDINO?style=social"/> : "Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection". (**[ECCV 2024](https://arxiv.org/abs/2303.05499)**).

    - [UniDetector](https://github.com/zhenyuw16/UniDetector) <img src="https://img.shields.io/github/stars/zhenyuw16/UniDetector?style=social"/> : "Detecting Everything in the Open World: Towards Universal Object Detection". (**[CVPR 2023](https://arxiv.org/abs/2303.11749)**).

    - [buxihuo/OW-YOLO](https://github.com/buxihuo/OW-YOLO) <img src="https://img.shields.io/github/stars/buxihuo/OW-YOLO?style=social"/> : Detect known and unknown objects in the open world（具有区分已知与未知能力的全新检测器））.


  - ### Few-shot Object Detection
    #### 少样本目标检测

    - [Autodistill](https://github.com/autodistill/autodistill) <img src="https://img.shields.io/github/stars/autodistill/autodistill?style=social"/> : Images to inference with no labeling (use foundation models to train supervised models). Autodistill uses big, slower foundation models to train small, faster supervised models. Using autodistill, you can go from unlabeled images to inference on a custom model running at the edge with no human intervention in between. [docs.autodistill.com](https://docs.autodistill.com/)

    - [bingykang/Fewshot_Detection](https://github.com/bingykang/Fewshot_Detection) <img src="https://img.shields.io/github/stars/bingykang/Fewshot_Detection?style=social"/> : "Few-shot Object Detection via Feature Reweighting". (**[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/html/Kang_Few-Shot_Object_Detection_via_Feature_Reweighting_ICCV_2019_paper.html)**).

    - [SSDA-YOLO](https://github.com/hnuzhy/SSDA-YOLO) <img src="https://img.shields.io/github/stars/hnuzhy/SSDA-YOLO?style=social"/> : Codes for my paper "SSDA-YOLO: Semi-supervised Domain Adaptive YOLO for Cross-Domain Object Detection". (**[Computer Vision and Image Understanding, 2023](https://www.sciencedirect.com/science/article/abs/pii/S1077314223000292)**).

    - [OneTeacher](https://github.com/luogen1996/OneTeacher) <img src="https://img.shields.io/github/stars/luogen1996/OneTeacher?style=social"/> : "Towards End-to-end Semi-supervised Learning for One-stage Object Detection". (**[arXiv 2023](https://arxiv.org/abs/2302.11299)**).

    - [Efficient Teacher](https://github.com/AlibabaResearch/efficientteacher) <img src="https://img.shields.io/github/stars/AlibabaResearch/efficientteacher?style=social"/> : "Efficient Teacher: Semi-Supervised Object Detection for YOLOv5". (**[arXiv 2023](https://arxiv.org/abs/2302.07577)**).



  - ### Small Object Detection
    #### 小目标检测


    - [YOLO-Patch-Based-Inference](https://github.com/Koldim2001/YOLO-Patch-Based-Inference) <img src="https://img.shields.io/github/stars/Koldim2001/YOLO-Patch-Based-Inference?style=social"/> : Python library for YOLO small object detection and instance segmentation. This Python library simplifies SAHI-like inference for instance segmentation tasks, enabling the detection of small objects in images. It caters to both object detection and instance segmentation tasks, supporting a wide range of Ultralytics models.

    - [SAHI](https://github.com/obss/sahi) <img src="https://img.shields.io/github/stars/obss/sahi?style=social"/> : "Slicing Aided Hyper Inference and Fine-tuning for Small Object Detection". (**[arXiv 2022](https://arxiv.org/abs/2202.06934v2), [Zenodo 2021](https://doi.org/10.5281/zenodo.5718950)**).

    - [Slim-neck by GSConv](https://github.com/AlanLi1997/slim-neck-by-gsconv) <img src="https://img.shields.io/github/stars/AlanLi1997/slim-neck-by-gsconv?style=social"/> : "Slim-neck by GSConv: A better design paradigm of detector architectures for autonomous vehicles". (**[arXiv 2022](https://arxiv.org/abs/2206.02424)**)

    - [hustvl/TinyDet](https://github.com/hustvl/TinyDet) <img src="https://img.shields.io/github/stars/hustvl/TinyDet?style=social"/> : "TinyDet: accurately detecting small objects within 1 GFLOPs". (**[Science China Information Sciences, 2023](https://link.springer.com/article/10.1007/s11432-021-3504-4)**)

    - [QueryDet](https://github.com/ChenhongyiYang/QueryDet-PyTorch) <img src="https://img.shields.io/github/stars/ChenhongyiYang/QueryDet-PyTorch?style=social"/> : "QueryDet: Cascaded Sparse Query for Accelerating High-Resolution Small Object Detection". (**[CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_QueryDet_Cascaded_Sparse_Query_for_Accelerating_High-Resolution_Small_Object_Detection_CVPR_2022_paper.html)**)

    - [RFLA](https://github.com/Chasel-Tsui/mmdet-rfla) <img src="https://img.shields.io/github/stars/Chasel-Tsui/mmdet-rfla?style=social"/> : "RFLA: Gaussian Receptive Field based Label Assignment for Tiny Object Detection". (**[ECCV 2022](https://arxiv.org/abs/2208.08738)**). "微信公众号「CV技术指南」《[ECCV 2022 | RFLA：基于高斯感受野的微小目标检测标签分配](https://mp.weixin.qq.com/s/h0J775I3D6zoTIeaJRnFgQ)》"

    - [YOLT](https://github.com/avanetten/yolt) <img src="https://img.shields.io/github/stars/avanetten/yolt?style=social"/> : "You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery". (**[arXiv 2018](https://arxiv.org/abs/1805.09512)**). "微信公众号「江大白」《[基于大尺寸图像的小目标检测竞赛经验总结](https://mp.weixin.qq.com/s?__biz=Mzg5NzgyNTU2Mg==&mid=2247498265&idx=1&sn=1eee95f8f4d09d761dc7b94f4ac55c34&source=41#wechat_redirect)》"

    - [SIMRDWN](https://github.com/avanetten/simrdwn) <img src="https://img.shields.io/github/stars/avanetten/simrdwn?style=social"/> : "Satellite Imagery Multiscale Rapid Detection with Windowed Networks". (**[arXiv 2018](https://arxiv.org/abs/1809.09978), [WACV 2019](https://ieeexplore.ieee.org/abstract/document/8659155)**)

    - [YOLTv5](https://github.com/avanetten/yoltv5) <img src="https://img.shields.io/github/stars/avanetten/yoltv5?style=social"/> : YOLTv5 builds upon [YOLT](https://github.com/avanetten/yolt) and [SIMRDWN](https://github.com/avanetten/simrdwn), and updates these frameworks to use the [ultralytics/yolov5](https://github.com/ultralytics/yolov5) version of the YOLO object detection family.

    - [TPH-YOLOv5](https://github.com/cv516Buaa/tph-yolov5) <img src="https://img.shields.io/github/stars/cv516Buaa/tph-yolov5?style=social"/> : "TPH-YOLOv5: Improved YOLOv5 Based on Transformer Prediction Head for Object Detection on Drone-Captured Scenarios". (**[ICCV 2021](https://openaccess.thecvf.com/content/ICCV2021W/VisDrone/html/Zhu_TPH-YOLOv5_Improved_YOLOv5_Based_on_Transformer_Prediction_Head_for_Object_ICCVW_2021_paper.html)**)

    - [mwaseema/Drone-Detection](https://github.com/mwaseema/Drone-Detection) <img src="https://img.shields.io/github/stars/mwaseema/Drone-Detection?style=social"/> : "Dogfight: Detecting Drones from Drones Videos". (**[CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Ashraf_Dogfight_Detecting_Drones_From_Drones_Videos_CVPR_2021_paper.html)**)

    - [CEASA](https://github.com/cuogeihong/ceasc) <img src="https://img.shields.io/github/stars/cuogeihong/ceasc?style=social"/> : "Adaptive Sparse Convolutional Networks with Global Context Enhancement for Faster Object Detection on Drone Images". (**[arXiv 2023](https://arxiv.org/abs/2303.14488)**). "微信公众号「集智书童」《[即插即用 | CEASA模块给你所有，小目标精度提升的同时速度也变快了](https://mp.weixin.qq.com/s/-a4Wz04jLHFiAU88pUyDNQ)》"

    - [KevinMuyaoGuo/yolov5s_for_satellite_imagery](https://github.com/KevinMuyaoGuo/yolov5s_for_satellite_imagery) <img src="https://img.shields.io/github/stars/KevinMuyaoGuo/yolov5s_for_satellite_imagery?style=social"/> : 基于YOLOv5的卫星图像目标检测demo | A demo for satellite imagery object detection based on YOLOv5。

    - [Hongyu-Yue/yoloV5_modify_smalltarget](https://github.com/Hongyu-Yue/yoloV5_modify_smalltarget) <img src="https://img.shields.io/github/stars/Hongyu-Yue/yoloV5_modify_smalltarget?style=social"/> : YOLOV5 小目标检测修改版。

    - [muyuuuu/Self-Supervise-Object-Detection](https://github.com/muyuuuu/Self-Supervise-Object-Detection) <img src="https://img.shields.io/github/stars/muyuuuu/Self-Supervise-Object-Detection?style=social"/> : Self-Supervised Object Detection. 水面漂浮垃圾目标检测，分析源码改善 yolox 检测小目标的缺陷，提出自监督算法预训练无标签数据，提升检测性能。

    - [swricci/small-boat-detector](https://github.com/swricci/small-boat-detector) <img src="https://img.shields.io/github/stars/swricci/small-boat-detector?style=social"/> : Trained yolo v3 model weights and configuration file to detect small boats in satellite imagery.

    - [Resham-Sundar/sahi-yolox](https://github.com/Resham-Sundar/sahi-yolox) <img src="https://img.shields.io/github/stars/Resham-Sundar/sahi-yolox?style=social"/> : YoloX with SAHI Implementation.

    - YOLO-Z : "YOLO-Z: Improving small object detection in YOLOv5 for autonomous vehicles". (**[arXiv 2021](https://arxiv.org/abs/2112.11798)**). "微信公众号「计算机视觉研究院」《[Yolo-Z：改进的YOLOv5用于小目标检测（附原论文下载）](https://mp.weixin.qq.com/s/ehkUapLOMdDghF2kAoAV4w)》".

    - M2S : "A novel Multi to Single Module for small object detection". (**[arXiv 2023](https://arxiv.org/abs/2303.14977)**). "微信公众号「集智书童」《[基于YOLOv5改进再设计 | M2S全面提升小目标精度](https://mp.weixin.qq.com/s/FlKgYYGUHtJAxCF2wrh4NA)》".

    - [ultralytics/xview-yolov3](https://github.com/ultralytics/xview-yolov3) <img src="https://img.shields.io/github/stars/ultralytics/xview-yolov3?style=social"/> : xView 2018 Object Detection Challenge: YOLOv3 Training and Inference.

    - [inderpreet1390/yolov5-small-target](https://github.com/inderpreet1390/yolov5-small-target) <img src="https://img.shields.io/github/stars/inderpreet1390/yolov5-small-target?style=social"/> : Repository for improved yolov5 for small target detection.

    - [AllenSquirrel/YOLOv3_ReSAM](https://github.com/AllenSquirrel/YOLOv3_ReSAM) <img src="https://img.shields.io/github/stars/AllenSquirrel/YOLOv3_ReSAM?style=social"/> : YOLOv3_ReSAM:A Small Target Detection Method With Spatial Attention Module.

    - [kadirnar/yolov5-sahi](https://github.com/kadirnar/yolov5-sahi) <img src="https://img.shields.io/github/stars/kadirnar/yolov5-sahi?style=social"/> : Yolov5 Modelini Kullanarak Özel Nesne Eğitimi ve SAHI Kullanımı.

    - [kadirnar/Yolov6-SAHI](https://github.com/kadirnar/Yolov6-SAHI) <img src="https://img.shields.io/github/stars/kadirnar/Yolov6-SAHI?style=social"/> : Yolov6-SAHI.

    - [zRzRzRzRzRzRzR/Mult-YOLO-alogorithm-of-RoboMaster-Radar-Detection-2023](https://github.com/zRzRzRzRzRzRzR/Mult-YOLO-alogorithm-of-RoboMaster-Radar-Detection-2023) <img src="https://img.shields.io/github/stars/zRzRzRzRzRzRzR/Mult-YOLO-alogorithm-of-RoboMaster-Radar-Detection-2023?style=social"/> : 2023年西交利物浦大学动云科技GMaster战队雷达yolo小目标检测。

    - [quantumxiaol/yolov8-small-target-detection](https://github.com/quantumxiaol/yolov8-small-target-detection) <img src="https://img.shields.io/github/stars/quantumxiaol/yolov8-small-target-detection?style=social"/> : 基于yolov8实现小目标检测，在NWPU VHR-10和DOTA上测试。

    - [shaunyuan22/SODA](https://github.com/shaunyuan22/SODA) <img src="https://img.shields.io/github/stars/shaunyuan22/SODA?style=social"/> : Official code library for SODA: A Large-scale Benchmark for Small Object Detection. "Towards Large-Scale Small Object Detection: Survey and Benchmarks". (**[arXiv 2022](https://arxiv.org/abs/2207.14096)**)

    - [qunshansj/Small-Object-Detection-Head-Improved-YOLOv5-Infrared-Sensing-System](https://github.com/qunshansj/Small-Object-Detection-Head-Improved-YOLOv5-Infrared-Sensing-System) <img src="https://img.shields.io/github/stars/qunshansj/Small-Object-Detection-Head-Improved-YOLOv5-Infrared-Sensing-System?style=social"/> : 基于小目标检测头的改进YOLOv5红外遥感图像小目标检测系统。






  - #### Multimodal Image Detection
    #### 多模态图像检测

      - [NVIDIA-AI-IOT/Lidar_AI_Solution](https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/Lidar_AI_Solution?style=social"/> : This is a highly optimized solution for self-driving 3D-lidar repository. It does a great job of speeding up sparse convolution/CenterPoint/BEVFusion/OSD/Conversion. A project demonstrating Lidar related AI solutions, including three GPU accelerated Lidar/camera DL networks (PointPillars, CenterPoint, BEVFusion) and the related libs (cuPCL, 3D SparseConvolution, YUV2RGB, cuOSD,).

      - [remaro-network/KD-YOLOX-ViT](https://github.com/remaro-network/KD-YOLOX-ViT) <img src="https://img.shields.io/github/stars/remaro-network/KD-YOLOX-ViT?style=social"/> : This repository holds the code for the Python implementation of YOLOX-ViT. Furthermore, it has the implementation of the Knowledge Distillation (KD) method, evaluation metrics of the object detector and the side-scan sonar image dataset for underwater wall detection. "Knowledge Distillation in YOLOX-ViT for Side-Scan Sonar Object Detection". (**[arXiv 2024](https://arxiv.org/abs/2403.09313)**). The Sonar Wall Detection Dataset (SWDD) is publicly accessible at [https://zenodo.org/records/10528135](https://zenodo.org/records/10528135).

      - [wandahangFY/YOLO-MIF](https://github.com/wandahangFY/YOLO-MIF) <img src="https://img.shields.io/github/stars/wandahangFY/YOLO-MIF?style=social"/> : YOLO-MIF(YOLOv8-RGBT) is an improved version of YOLOv8 for object detection in gray-scale images, incorporating multi-information fusion to enhance detection accuracy. The detection of RGBT mode is also added. YOLO-MIF是在灰度图像中进行目标检测的改进型YOLOv8模型，引入了多信息融合策略，提高了检测准确性。 并添加了RGBT模式的检测,分割以及关节点任务。 "YOLO-MIF: Improved YOLOv8 with Multi-Information fusion for object detection in Gray-Scale images". (**[Advanced Engineering Informatics, 2024](https://www.sciencedirect.com/science/article/abs/pii/S1474034624003574)**).

      - [wandahangFY/YOLOv11-RGBT](https://github.com/wandahangFY/YOLOv11-RGBT) <img src="https://img.shields.io/github/stars/wandahangFY/YOLOv11-RGBT?style=social"/> : YOLOv11-RGBT: Towards a Comprehensive Multispectral Object Detection Framework（Supports RGBT detection for all YOLO series from YOLOv3 to YOLOv12, as well as RTDETR.））

      - [mcw1217/Triple_YOLOv8](https://github.com/mcw1217/Triple_YOLOv8) <img src="https://img.shields.io/github/stars/mcw1217/Triple_YOLOv8?style=social"/> : This project uses three types of images as inputs RGB, Depth, and thermal images to perform object detection with YOLOv8.

      - [ljcuestc/YoloMultispectralFusion-Coarse-to-fine-Registration](https://github.com/ljcuestc/YoloMultispectralFusion-Coarse-to-fine-Registration) <img src="https://img.shields.io/github/stars/ljcuestc/YoloMultispectralFusion-Coarse-to-fine-Registration?style=social"/> : "A Novel Multispectral Fusion Defect Detection Framework With Coarse-to-Fine Multispectral Registration". (**[IEEE Transactions on Instrumentation and Measurement, 2023](https://ieeexplore.ieee.org/document/10365549)**)

      - [SuperYOLO](https://github.com/icey-zhang/SuperYOLO) <img src="https://img.shields.io/github/stars/icey-zhang/SuperYOLO?style=social"/> : "SuperYOLO: Super Resolution Assisted Object Detection in Multimodal Remote Sensing Imagery". (**[arXiv 2022](https://arxiv.org/abs/2209.13351)**)

      - [QuincyQAQ/YOLOv8-Multi-Modal-Fusion-Network-RGB-IR](https://github.com/QuincyQAQ/YOLOv8-Multi-Modal-Fusion-Network-RGB-IR) <img src="https://img.shields.io/github/stars/QuincyQAQ/YOLOv8-Multi-Modal-Fusion-Network-RGB-IR?style=social"/> : YOLOv8-Multi-Modal-Fusion-Network-RGB-IR.

      - [mangoggul/YOLO-MultiModal](https://github.com/mangoggul/YOLO-MultiModal) <img src="https://img.shields.io/github/stars/mangoggul/YOLO-MultiModal?style=social"/> : Multi-Modal-YOLO detection.

      - [DocF/multispectral-object-detection](https://github.com/DocF/multispectral-object-detection) <img src="https://img.shields.io/github/stars/DocF/multispectral-object-detection?style=social"/> : Multispectral Object Detection with Yolov5 and Transformer.

      - [Ye-zixiao/Double-YOLO-Kaist](https://github.com/Ye-zixiao/Double-YOLO-Kaist) <img src="https://img.shields.io/github/stars/Ye-zixiao/Double-YOLO-Kaist?style=social"/> : 一种基于YOLOv3/4的双流混合模态道路行人检测方法🌊💧💦。

      - [lzhihan/yolov5_Visible_Infrared_Vehicle_Detection](https://github.com/lzhihan/yolov5_Visible_Infrared_Vehicle_Detection) <img src="https://img.shields.io/github/stars/lzhihan/yolov5_Visible_Infrared_Vehicle_Detection?style=social"/> : 基于可见光和红外图像的深度学习车辆目标检测。

      - [jere357/yolov5-RGBD](https://github.com/jere357/yolov5-RGBD) <img src="https://img.shields.io/github/stars/jere357/yolov5-RGBD?style=social"/> : "fork" from yolov5 with the possibility of running inferences on RGBD(C) images, work in progress. This repo is not a fork of the original repo bcs i already have 1 fork with a PR pending, this is still messy code and a work in progress.

      - [huashu996/dual_result_fusion_yolov5](https://github.com/huashu996/dual_result_fusion_yolov5) <img src="https://img.shields.io/github/stars/huashu996/dual_result_fusion_yolov5?style=social"/> : result set fusion for visible-light and infrared images. 此双模态检测是通过对可见光和红外图像分别训练，得到两个weight，在运行时会对两种图像分别检测，最后对检测结果求极大似然，并且能够对目标进行测距。

      - [MAli-Farooq/Thermal-YOLO](https://github.com/MAli-Farooq/Thermal-YOLO) <img src="https://img.shields.io/github/stars/sierprinsky/YoloV5_blood_cells?style=social"/> : This study is related to object detection in thermal infrared spectrum using YOLO-V5 framework for ADAS application.

      - [OrangeSodahub/CRLFnet](https://github.com/OrangeSodahub/CRLFnet) <img src="https://img.shields.io/github/stars/OrangeSodahub/CRLFnet?style=social"/> : Camera-Radar-Lidar Fusion detection net based on ROS, YOLOv3, OpenPCDet integration.

      - [mjoshi07/Visual-Sensor-Fusion](https://github.com/mjoshi07/Visual-Sensor-Fusion) <img src="https://img.shields.io/github/stars/mjoshi07/Visual-Sensor-Fusion?style=social"/> : LiDAR Fusion with Vision.

      - [Arrowes/CEAM-YOLOv7](https://github.com/Arrowes/CEAM-YOLOv7) <img src="https://img.shields.io/github/stars/Arrowes/CEAM-YOLOv7?style=social"/> : CEAM-YOLOv7: Improved YOLOv7 Based on Channel Expansion and Attention Mechanism for Driver Distraction Behavior Detection.











  - ### Video Object Detection
    #### 视频目标检测

      - [YOLOV](https://github.com/YuHengsss/YOLOV) <img src="https://img.shields.io/github/stars/YuHengsss/YOLOV?style=social"/> : "YOLOV: Making Still Image Object Detectors Great at Video Object Detection". (**[arXiv 2022](https://arxiv.org/abs/2208.09686)**)

      - [StreamYOLO](https://github.com/yancie-yjr/StreamYOLO) <img src="https://img.shields.io/github/stars/yancie-yjr/StreamYOLO?style=social"/> : "Real-time Object Detection for Streaming Perception". (**[CVPR 2022](https://arxiv.org/abs/2203.12338v1)**)

      - [REPP](https://github.com/AlbertoSabater/Robust-and-efficient-post-processing-for-video-object-detection) <img src="https://img.shields.io/github/stars/AlbertoSabater/Robust-and-efficient-post-processing-for-video-object-detection?style=social"/> : "Robust and efficient post-processing for video object detection". (**[IROS 2020](https://ieeexplore.ieee.org/abstract/document/9341600)**)

      - [NoScope](https://github.com/stanford-futuredata/noscope) <img src="https://img.shields.io/github/stars/stanford-futuredata/noscope?style=social"/> : "Noscope: optimizing neural network queries over video at scale". (**[arXiv 2017](https://arxiv.org/abs/1703.02529)**)



  - ### Object Tracking
    #### 目标跟踪

    - ####  Multi-Object Tracking
      #####  多目标跟踪

      - [nmhaddad/fast-track](https://github.com/nmhaddad/fast-track) <img src="https://img.shields.io/github/stars/nmhaddad/fast-track?style=social"/> : Object tracking pipelines complete with RF-DETR, YOLOv9, YOLO-NAS, YOLOv8, and YOLOv7 detection and BYTETracker tracking.

      - [sujanshresstha/YOLOv10_DeepSORT](https://github.com/sujanshresstha/YOLOv10_DeepSORT) <img src="https://img.shields.io/github/stars/sujanshresstha/YOLOv10_DeepSORT?style=social"/> : This repository contains code for object detection and tracking in videos using the YOLOv10 object detection model and the DeepSORT algorithm.

      - [BoxMOT](hhttps://github.com/mikel-brostrom/boxmot) <img src="https://img.shields.io/github/stars/mikel-brostrom/boxmot?style=social"/> : BoxMOT: pluggable SOTA tracking modules for segmentation, object detection and pose estimation models.

      - [mikel-brostrom/Yolov7_StrongSORT_OSNet](https://github.com/mikel-brostrom/Yolov7_StrongSORT_OSNet) <img src="https://img.shields.io/github/stars/mikel-brostrom/Yolov7_StrongSORT_OSNet?style=social"/> : Real-time multi-camera multi-object tracker using [YOLOv7](https://github.com/WongKinYiu/yolov7) and [StrongSORT](https://github.com/dyhBUPT/StrongSORT) with [OSNet](https://github.com/KaiyangZhou/deep-person-reid).

      - [RizwanMunawar/yolov8-object-tracking](https://github.com/RizwanMunawar/yolov8-object-tracking) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov8-object-tracking?style=social"/> : YOLOv8 Object Tracking Using PyTorch, OpenCV and Ultralytics.

      - [xuarehere/yolo_series_deepsort_pytorch](https://github.com/xuarehere/yolo_series_deepsort_pytorch) <img src="https://img.shields.io/github/stars/xuarehere/yolo_series_deepsort_pytorch?style=social"/> : Deepsort with yolo series. This project support the existing yolo detection model algorithm (YOLOv3, YOLOV4, YOLOV4Scaled, YOLOV5, YOLOV6, YOLOV7, YOLOV8, YOLOX, YOLOR, PPYOLOE ).

      - [JackWoo0831/Yolov7-tracker](https://github.com/JackWoo0831/Yolov7-tracker) <img src="https://img.shields.io/github/stars/JackWoo0831/Yolov7-tracker?style=social"/> : Yolo v7 and several Multi-Object Tracker(SORT, DeepSORT, ByteTrack, BoT-SORT, etc.) in VisDrone2019 Dataset. It uses a unified style and integrated tracker for easy embedding in your own projects. YOLOv7 + 各种tracker实现多目标跟踪。

      - [BoT-SORT](https://github.com/NirAharon/BoT-SORT) <img src="https://img.shields.io/github/stars/NirAharon/BoT-SORT?style=social"/> : "BoT-SORT: Robust Associations Multi-Pedestrian Tracking". (**[arXiv 2022](https://arxiv.org/abs/2206.14651)**)

      - [StrongSORT](https://github.com/dyhBUPT/StrongSORT) <img src="https://img.shields.io/github/stars/dyhBUPT/StrongSORT?style=social"/> : "StrongSORT: Make DeepSORT Great Again". (**[arXiv 2022](https://arxiv.org/abs/2202.13514)**)

      - [UAVMOT](https://github.com/LiuShuaiyr/UAVMOT) <img src="https://img.shields.io/github/stars/LiuShuaiyr/UAVMOT?style=social"/> : "Multi-Object Tracking Meets Moving UAV". (**[CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Multi-Object_Tracking_Meets_Moving_UAV_CVPR_2022_paper.html)**)

      - [HKPolyU-UAV/AUTO](https://github.com/HKPolyU-UAV/AUTO) <img src="https://img.shields.io/github/stars/HKPolyU-UAV/AUTO?style=social"/> : "Dynamic Object Tracking on Autonomous UAV System for Surveillance Applications". (**[Sensors 2021](https://www.mdpi.com/1424-8220/21/23/7888)**)

      - [bharath5673/StrongSORT-YOLO](https://github.com/bharath5673/StrongSORT-YOLO) <img src="https://img.shields.io/github/stars/bharath5673/StrongSORT-YOLO?style=social"/> : Real-time multi-camera multi-object tracker using (YOLOv5, YOLOv7) and [StrongSORT](https://github.com/dyhBUPT/StrongSORT) with OSNet.

      - [mikel-brostrom/Yolov7_StrongSORT_OSNet](https://github.com/mikel-brostrom/Yolov7_StrongSORT_OSNet) <img src="https://img.shields.io/github/stars/mikel-brostrom/Yolov7_StrongSORT_OSNet?style=social"/> : Real-time multi-camera multi-object tracker using YOLOv7 and StrongSORT with OSNet.

      - [kadirnar/yolov5-strongsort](https://github.com/kadirnar/yolov5-strongsort) <img src="https://img.shields.io/github/stars/kadirnar/yolov5-strongsort?style=social"/> : Minimal PyTorch implementation of YOLOv5 and [StrongSORT](https://github.com/dyhBUPT/StrongSORT).

      - [ZQPei/deep_sort_pytorch](https://github.com/ZQPei/deep_sort_pytorch) <img src="https://img.shields.io/github/stars/ZQPei/deep_sort_pytorch?style=social"/> : MOT using deepsort and yolov3 with pytorch.

      - [Qidian213/deep_sort_yolov3](https://github.com/Qidian213/deep_sort_yolov3) <img src="https://img.shields.io/github/stars/Qidian213/deep_sort_yolov3?style=social"/> : Real-time Multi-person tracker using YOLO v3 and deep_sort with tensorflow.

      - [CSTrack](https://github.com/JudasDie/SOTS) <img src="https://img.shields.io/github/stars/JudasDie/SOTS?style=social"/> : "Rethinking the competition between detection and ReID in Multi-Object Tracking". (**[arXiv 2020](https://arxiv.org/abs/2010.12138)**)

      - [ROLO](https://github.com/Guanghan/ROLO) <img src="https://img.shields.io/github/stars/Guanghan/ROLO?style=social"/> : ROLO is short for Recurrent YOLO, aimed at simultaneous object detection and tracking.

      - [FastMOT](https://github.com/GeekAlexis/FastMOT) <img src="https://img.shields.io/github/stars/GeekAlexis/FastMOT?style=social"/> : "FastMOT: High-Performance Multiple Object Tracking Based on Deep SORT and KLT". (**[Zenodo 2020](https://doi.org/10.5281/zenodo.4294717)**)

      - [Sharpiless/Yolov5-deepsort-inference](https://github.com/Sharpiless/Yolov5-deepsort-inference) <img src="https://img.shields.io/github/stars/Sharpiless/Yolov5-deepsort-inference?style=social"/> : 使用YOLOv5+Deepsort实现车辆行人追踪和计数，代码封装成一个Detector类，更容易嵌入到自己的项目中。

      - [Sharpiless/Yolov5-Deepsort](https://github.com/Sharpiless/Yolov5-Deepsort) <img src="https://img.shields.io/github/stars/Sharpiless/Yolov5-Deepsort?style=social"/> : 最新版本yolov5+deepsort目标检测和追踪，能够显示目标类别，支持5.0版本可训练自己数据集。

      - [LeonLok/Multi-Camera-Live-Object-Tracking](https://github.com/LeonLok/Multi-Camera-Live-Object-Tracking) <img src="https://img.shields.io/github/stars/LeonLok/Multi-Camera-Live-Object-Tracking?style=social"/> : Multi-camera live traffic and object counting with YOLO v4, Deep SORT, and Flask.

      - [LeonLok/Deep-SORT-YOLOv4](https://github.com/LeonLok/Deep-SORT-YOLOv4) <img src="https://img.shields.io/github/stars/LeonLok/Deep-SORT-YOLOv4?style=social"/> : People detection and optional tracking with Tensorflow backend.

      - [obendidi/Tracking-with-darkflow](https://github.com/obendidi/Tracking-with-darkflow) <img src="https://img.shields.io/github/stars/obendidi/Tracking-with-darkflow?style=social"/> : Real-time people Multitracker using YOLO v2 and deep_sort with tensorflow.

      - [DrewNF/Tensorflow_Object_Tracking_Video](https://github.com/DrewNF/Tensorflow_Object_Tracking_Video) <img src="https://img.shields.io/github/stars/DrewNF/Tensorflow_Object_Tracking_Video?style=social"/> : Object Tracking in Tensorflow ( Localization Detection Classification ) developed to partecipate to ImageNET VID competition.

      - [dyh/unbox_yolov5_deepsort_counting](https://github.com/dyh/unbox_yolov5_deepsort_counting) <img src="https://img.shields.io/github/stars/dyh/unbox_yolov5_deepsort_counting?style=social"/> : yolov5 deepsort 行人 车辆 跟踪 检测 计数。

      - [theAIGuysCode/yolov3_deepsort](https://github.com/theAIGuysCode/yolov3_deepsort) <img src="https://img.shields.io/github/stars/theAIGuysCode/yolov3_deepsort?style=social"/> : Object tracking implemented with YOLOv3, Deep Sort and Tensorflow.

      - [weixu000/libtorch-yolov3-deepsort](https://github.com/weixu000/libtorch-yolov3-deepsort) <img src="https://img.shields.io/github/stars/weixu000/libtorch-yolov3-deepsort?style=social"/> : libtorch-yolov3-deepsort.

      - [pmj110119/YOLOX_deepsort_tracker](https://github.com/pmj110119/YOLOX_deepsort_tracker) <img src="https://img.shields.io/github/stars/pmj110119/YOLOX_deepsort_tracker?style=social"/> : using yolox+deepsort for object-tracking.

      - [abhyantrika/nanonets_object_tracking](https://github.com/abhyantrika/nanonets_object_tracking) <img src="https://img.shields.io/github/stars/abhyantrika/nanonets_object_tracking?style=social"/> : nanonets_object_tracking.

      - [mattzheng/keras-yolov3-KF-objectTracking](https://github.com/mattzheng/keras-yolov3-KF-objectTracking) <img src="https://img.shields.io/github/stars/mattzheng/keras-yolov3-KF-objectTracking?style=social"/> : 以kears-yolov3做detector，以Kalman-Filter算法做tracker，进行多人物目标追踪。

      - [rohanchandra30/TrackNPred](https://github.com/rohanchandra30/TrackNPred) <img src="https://img.shields.io/github/stars/rohanchandra30/TrackNPred?style=social"/> : A Software Framework for End-to-End Trajectory Prediction.

      - [RichardoMrMu/yolov5-deepsort-tensorrt](https://github.com/RichardoMrMu/yolov5-deepsort-tensorrt) <img src="https://img.shields.io/github/stars/RichardoMrMu/yolov5-deepsort-tensorrt?style=social"/> : A c++ implementation of yolov5 and deepsort.

      - [bamwani/car-counting-and-speed-estimation-yolo-sort-python](https://github.com/bamwani/car-counting-and-speed-estimation-yolo-sort-python) <img src="https://img.shields.io/github/stars/bamwani/car-counting-and-speed-estimation-yolo-sort-python?style=social"/> : This project imlements the following tasks in the project: 1. Vehicle counting, 2. Lane detection. 3.Lane change detection and 4.speed estimation.

      - [ArtLabss/tennis-tracking](https://github.com/ArtLabss/tennis-tracking) <img src="https://img.shields.io/github/stars/ArtLabss/tennis-tracking?style=social"/> : Open-source Monocular Python HawkEye for Tennis.

      - [CaptainEven/YOLOV4_MCMOT](https://github.com/CaptainEven/YOLOV4_MCMOT) <img src="https://img.shields.io/github/stars/CaptainEven/YOLOV4_MCMOT?style=social"/> : Using YOLOV4 as detector for MCMOT.

      - [opendatacam/node-moving-things-tracker](https://github.com/opendatacam/node-moving-things-tracker) <img src="https://img.shields.io/github/stars/opendatacam/node-moving-things-tracker?style=social"/> : javascript implementation of "tracker by detections" for realtime multiple object tracking (MOT).

      - [lanmengyiyu/yolov5-deepmar](https://github.com/lanmengyiyu/yolov5-deepmar) <img src="https://img.shields.io/github/stars/lanmengyiyu/yolov5-deepmar?style=social"/> : 行人轨迹和属性分析。

      - [zengwb-lx/Yolov5-Deepsort-Fastreid](https://github.com/zengwb-lx/Yolov5-Deepsort-Fastreid) <img src="https://img.shields.io/github/stars/zengwb-lx/Yolov5-Deepsort-Fastreid?style=social"/> : YoloV5 + deepsort + Fast-ReID 完整行人重识别系统。

      - [tensorturtle/classy-sort-yolov5](https://github.com/tensorturtle/classy-sort-yolov5) <img src="https://img.shields.io/github/stars/tensorturtle/classy-sort-yolov5?style=social"/> : Ready-to-use realtime multi-object tracker that works for any object category. YOLOv5 + SORT implementation.

      - [supperted825/FairMOT-X](https://github.com/supperted825/FairMOT-X) <img src="https://img.shields.io/github/stars/supperted825/FairMOT-X?style=social"/> : FairMOT for Multi-Class MOT using YOLOX as Detector.

      - [deyiwang89/pytorch-yolov7-deepsort](https://github.com/deyiwang89/pytorch-yolov7-deepsort) <img src="https://img.shields.io/github/stars/deyiwang89/pytorch-yolov7-deepsort?style=social"/> : an implentation of yolov7-deepsort based on pytorch.

      - [xuarehere/yolovx_deepsort_pytorch](https://github.com/xuarehere/yolovx_deepsort_pytorch) <img src="https://img.shields.io/github/stars/xuarehere/yolovx_deepsort_pytorch?style=social"/> : this project support the existing yolo detection model algorithm (YOLOv3, YOLOV4, YOLOV4Scaled, YOLOV5, YOLOV6, YOLOV7 ).

      - [deshwalmahesh/yolov7-deepsort-tracking](https://github.com/deshwalmahesh/yolov7-deepsort-tracking) <img src="https://img.shields.io/github/stars/deshwalmahesh/yolov7-deepsort-tracking?style=social"/> : Modular and ready to deploy code to detect and track videos using YOLO-v7 and DeepSORT.

      - [RizwanMunawar/yolov7-object-tracking](https://github.com/RizwanMunawar/yolov7-object-tracking) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov7-object-tracking?style=social"/> : YOLOv7 Object Tracking Using PyTorch, OpenCV and Sort Tracking.

      - [RizwanMunawar/yolov5-object-tracking](https://github.com/RizwanMunawar/yolov5-object-tracking) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov5-object-tracking?style=social"/> : YOLOv5 Object Tracking + Detection + Object Blurring + Streamlit Dashboard Using OpenCV, PyTorch and Streamlit.

      - [Smorodov/Multitarget-tracker](https://github.com/Smorodov/Multitarget-tracker) <img src="https://img.shields.io/github/stars/Smorodov/Multitarget-tracker?style=social"/> : Multiple Object Tracker, Based on Hungarian algorithm + Kalman filter.

      - [Naughty-Galileo/YoloV5_MCMOT](https://github.com/Naughty-Galileo/YoloV5_MCMOT) <img src="https://img.shields.io/github/stars/Naughty-Galileo/YoloV5_MCMOT?style=social"/> : 多类别多目标跟踪YoloV5+sort/deepsort/bytetrack/BotSort/motdt.


      - [MuhammadMoinFaisal/YOLOv8-DeepSORT-Object-Tracking](https://github.com/MuhammadMoinFaisal/YOLOv8-DeepSORT-Object-Tracking) <img src="https://img.shields.io/github/stars/MuhammadMoinFaisal/YOLOv8-DeepSORT-Object-Tracking?style=social"/> : YOLOv8 Object Tracking using PyTorch, OpenCV and DeepSORT.

      - [sujanshresstha/YOLO-NAS_DeepSORT](https://github.com/sujanshresstha/YOLO-NAS_DeepSORT) <img src="https://img.shields.io/github/stars/sujanshresstha/YOLO-NAS_DeepSORT?style=social"/> : This repository contains code for object tracking in videos using the YOLO-NAS object detection model and the DeepSORT algorithm.




    - ####  Dynamic Object Tracking
      #####  动态目标跟踪

      - [PolyU-AIRO-Lab/AUTO](https://github.com/PolyU-AIRO-Lab/AUTO) <img src="https://img.shields.io/github/stars/PolyU-AIRO-Lab/AUTO?style=social"/> : "Dynamic Object Tracking on Autonomous UAV System for Surveillance Applications". (**[Sensors 2021](https://www.mdpi.com/1424-8220/21/23/7888)**)






  - #### Deep Reinforcement Learning
    #### 深度强化学习

    - [uzkent/EfficientObjectDetection](https://github.com/uzkent/EfficientObjectDetection) <img src="https://img.shields.io/github/stars/uzkent/EfficientObjectDetection?style=social"/> : "Efficient Object Detection in Large Images with Deep Reinforcement Learning". (**[WACV 2020](https://openaccess.thecvf.com/content_WACV_2020/html/Uzkent_Efficient_Object_Detection_in_Large_Images_Using_Deep_Reinforcement_Learning_WACV_2020_paper.html)**)


  - #### Motion Control Field
    #### 运动控制领域

    - [icns-distributed-cloud/adaptive-cruise-control](https://github.com/icns-distributed-cloud/adaptive-cruise-control) <img src="https://img.shields.io/github/stars/icns-distributed-cloud/adaptive-cruise-control?style=social"/> : YOLO-v5 기반 "단안 카메라"의 영상을 활용해 차간 거리를 일정하게 유지하며 주행하는 Adaptive Cruise Control 기능 구현.

    - [LeBronLiHD/ZJU2021_MotionControl_PID_YOLOv5](https://github.com/LeBronLiHD/ZJU2021_MotionControl_PID_YOLOv5) <img src="https://img.shields.io/github/stars/LeBronLiHD/ZJU2021_MotionControl_PID_YOLOv5?style=social"/> : ZJU2021_MotionControl_PID_YOLOv5.

    - [SananSuleymanov/PID_YOLOv5s_ROS_Diver_Tracking](https://github.com/SananSuleymanov/PID_YOLOv5s_ROS_Diver_Tracking) <img src="https://img.shields.io/github/stars/SananSuleymanov/PID_YOLOv5s_ROS_Diver_Tracking?style=social"/> : PID_YOLOv5s_ROS_Diver_Tracking.

    - [sumght-z/apex_yolov5](https://github.com/sumght-z/apex_yolov5) <img src="https://img.shields.io/github/stars/sumght-z/apex_yolov5?style=social"/> : something by yolov5 and PID.



  - #### Super-Resolution Field
    #### 超分辨率领域

    - [Fireboltz/Psychic-CCTV](https://github.com/Fireboltz/Psychic-CCTV) <img src="https://img.shields.io/github/stars/Fireboltz/Psychic-CCTV?style=social"/> : A video analysis tool built completely in python.


  - #### Spiking Neural Network
    #### SNN, 脉冲神经网络

    - [SpikeYOLO](https://github.com/BICLab/SpikeYOLO) <img src="https://img.shields.io/github/stars/BICLab/SpikeYOLO?style=social"/> : Offical implementation of "Integer-Valued Training and Spike-Driven Inference Spiking Neural Network for High-performance and Energy-efficient Object Detection" (**[ECCV 2024 Oral](https://arxiv.org/abs/2407.20708)**)

    - [EMS-YOLO](https://github.com/BICLab/EMS-YOLO) <img src="https://img.shields.io/github/stars/BICLab/EMS-YOLO?style=social"/> : Offical implementation of "Deep Directly-Trained Spiking Neural Networks for Object Detection" (**[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/html/Su_Deep_Directly-Trained_Spiking_Neural_Networks_for_Object_Detection_ICCV_2023_paper.html)**)

    - [Attention-SNN](https://github.com/BICLab/Attention-SNN) <img src="https://img.shields.io/github/stars/BICLab/Attention-SNN?style=social"/> : Offical implementation of "Attention Spiking Neural Networks" (**[IEEE TPAMI 2023](https://ieeexplore.ieee.org/abstract/document/10032591)**)

    - [Spike-Driven-Transformer](https://github.com/BICLab/Spike-Driven-Transformer) <img src="https://img.shields.io/github/stars/BICLab/Spike-Driven-Transformer?style=social"/> : Offical implementation of "Spike-driven Transformer" (**[NeurIPS 2023](https://openreview.net/forum?id=9FmolyOHi5)**)

    - [Spike-Driven-Transformer-V2](https://github.com/BICLab/Spike-Driven-Transformer-V2) <img src="https://img.shields.io/github/stars/BICLab/Spike-Driven-Transformer-V2?style=social"/> : Offical implementation of "Spike-driven Transformer V2: Meta Spiking Neural Network Architecture Inspiring the Design of Next-generation Neuromorphic Chips" (**[ICLR 2024](https://openreview.net/forum?id=1SIBN5Xyw7)**)

    - [Spiking-YOLOv3](https://github.com/cwq159/PyTorch-Spiking-YOLOv3) <img src="https://img.shields.io/github/stars/cwq159/PyTorch-Spiking-YOLOv3?style=social"/> : A PyTorch implementation of Spiking-YOLOv3. Two branches are provided, based on two common PyTorch implementation of YOLOv3([ultralytics/yolov3](https://github.com/ultralytics/yolov3) & [eriklindernoren/PyTorch-YOLOv3](https://github.com/eriklindernoren/PyTorch-YOLOv3)), with support for Spiking-YOLOv3-Tiny at present. (**[AAAI 2020](https://ojs.aaai.org/index.php/AAAI/article/view/6787)**)

    - [fjcu-ee-islab/Spiking_Converted_YOLOv4](https://github.com/fjcu-ee-islab/Spiking_Converted_YOLOv4) <img src="https://img.shields.io/github/stars/fjcu-ee-islab/Spiking_Converted_YOLOv4?style=social"/> : Object Detection Based on Dynamic Vision Sensor with Spiking Neural Network.

    - [Zaabon/spiking_yolo](https://github.com/Zaabon/spiking_yolo) <img src="https://img.shields.io/github/stars/Zaabon/spiking_yolo?style=social"/> : This project is a combined neural network utilizing an spiking CNN with backpropagation and YOLOv3 for object detection.

    - [Dignity-ghost/PyTorch-Spiking-YOLOv3](https://github.com/Dignity-ghost/PyTorch-Spiking-YOLOv3) <img src="https://img.shields.io/github/stars/Dignity-ghost/PyTorch-Spiking-YOLOv3?style=social"/> : A modified repository based on [Spiking-YOLOv3](https://github.com/cwq159/PyTorch-Spiking-YOLOv3) and [YOLOv3](https://pjreddie.com/darknet/yolo), which makes it suitable for VOC-dataset and YOLOv2.

    - [beauty-girl-cxy/spiking-yolov5](https://github.com/beauty-girl-cxy/spiking-yolov5) <img src="https://img.shields.io/github/stars/beauty-girl-cxy/spiking-yolov5?style=social"/> : spiking-yolov5.



  - #### Attention and Transformer
    #### 注意力机制

    - [xmu-xiaoma666/External-Attention-pytorch](https://github.com/xmu-xiaoma666/External-Attention-pytorch) <img src="https://img.shields.io/github/stars/xmu-xiaoma666/External-Attention-pytorch?style=social"/> : 🍀 Pytorch implementation of various Attention Mechanisms, MLP, Re-parameter, Convolution, which is helpful to further understand papers.⭐⭐⭐.

    - [MenghaoGuo/Awesome-Vision-Attentions](https://github.com/MenghaoGuo/Awesome-Vision-Attentions) <img src="https://img.shields.io/github/stars/MenghaoGuo/Awesome-Vision-Attentions?style=social"/> : Summary of related papers on visual attention. Related code will be released based on Jittor gradually. "Attention Mechanisms in Computer Vision: A Survey". (**[arXiv 2021](https://arxiv.org/abs/2111.07624)**)

    - [pprp/awesome-attention-mechanism-in-cv](https://github.com/pprp/awesome-attention-mechanism-in-cv) <img src="https://img.shields.io/github/stars/pprp/awesome-attention-mechanism-in-cv?style=social"/> : 👊 CV中常用注意力模块;即插即用模块;ViT模型. PyTorch Implementation Collection of Attention Module and Plug&Play Module.

    - [AbSViT](https://github.com/bfshi/AbSViT) <img src="https://img.shields.io/github/stars/bfshi/AbSViT?style=social"/> : "Top-Down Visual Attention from Analysis by Synthesis". (**[CVPR 2023](https://arxiv.org/abs/2303.13043)**). "微信公众号「人工智能前沿讲习」《[【源头活水】CVPR 2023 | AbSViT：拥有自上而下注意力机制的视觉Transformer](https://mp.weixin.qq.com/s/FtVd37tOXMfu92eDSvdvbg)》"。 "微信公众号「极市平台」《[CVPR23 Highlight｜拥有top-down attention能力的vision transformer](https://mp.weixin.qq.com/s/UMA3Vk9L71zUEtNkCshYBg)》"。

    - [HaloTrouvaille/YOLO-Multi-Backbones-Attention](https://github.com/HaloTrouvaille/YOLO-Multi-Backbones-Attention) <img src="https://img.shields.io/github/stars/HaloTrouvaille/YOLO-Multi-Backbones-Attention?style=social"/> : This Repository includes YOLOv3 with some lightweight backbones (ShuffleNetV2, GhostNet, VoVNet), some computer vision attention mechanism (SE Block, CBAM Block, ECA Block), pruning,quantization and distillation for GhostNet.

    - [kay-cottage/CoordAttention_YOLOX_Pytorch](https://github.com/kay-cottage/CoordAttention_YOLOX_Pytorch) <img src="https://img.shields.io/github/stars/kay-cottage/CoordAttention_YOLOX_Pytorch?style=social"/> : CoordAttention_YOLOX(基于CoordAttention坐标注意力机制的改进版YOLOX目标检测平台）。 "Coordinate Attention for Efficient Mobile Network Design". (**[CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Hou_Coordinate_Attention_for_Efficient_Mobile_Network_Design_CVPR_2021_paper.html), [ Andrew-Qibin/CoordAttention](https://github.com/Andrew-Qibin/CoordAttention)**)

    - [liangzhendong123/Attention-yolov5](https://github.com/liangzhendong123/Attention-yolov5) <img src="https://img.shields.io/github/stars/liangzhendong123/Attention-yolov5?style=social"/> : 基于注意力机制改进的yolov5模型。

    - [e96031413/AA-YOLO](https://github.com/e96031413/AA-YOLO) <img src="https://img.shields.io/github/stars/e96031413/AA-YOLO?style=social"/> : Attention ALL-CNN Twin Head YOLO (AA -YOLO). "Improving Tiny YOLO with Fewer Model Parameters". (**[IEEE BigMM 2021](https://ieeexplore.ieee.org/abstract/document/9643269/)**)

    - [anonymoussss/YOLOX-SwinTransformer](https://github.com/anonymoussss/YOLOX-SwinTransformer) <img src="https://img.shields.io/github/stars/anonymoussss/YOLOX-SwinTransformer?style=social"/> : YOLOX with Swin-Transformer backbone.

    - [GuanRunwei/MAN-and-CAT](https://github.com/GuanRunwei/MAN-and-CAT) <img src="https://img.shields.io/github/stars/GuanRunwei/MAN-and-CAT?style=social"/> : "MAN and CAT: mix attention to nn and concatenate attention to YOLO". (**[ The Journal of Supercomputing, 2022](https://link.springer.com/article/10.1007/s11227-022-04726-7)**)
















  - ### Oriented Object Detection
    #### 旋转目标检测

    - [AlphaRotate](https://github.com/yangxue0827/RotationDetection) <img src="https://img.shields.io/github/stars/yangxue0827/RotationDetection?style=social"/> : "AlphaRotate: A Rotation Detection Benchmark using TensorFlow". (**[arXiv 2021](https://arxiv.org/abs/2111.06677)**)

    - [hukaixuan19970627/yolov5_obb](https://github.com/hukaixuan19970627/yolov5_obb) <img src="https://img.shields.io/github/stars/hukaixuan19970627/yolov5_obb?style=social"/> : yolov5 + csl_label.(Oriented Object Detection)（Rotation Detection）（Rotated BBox）基于yolov5的旋转目标检测。

    - [BossZard/rotation-yolov5](https://github.com/BossZard/rotation-yolov5) <img src="https://img.shields.io/github/stars/BossZard/rotation-yolov5?style=social"/> : rotation detection based on yolov5.

    - [acai66/yolov5_rotation](https://github.com/acai66/yolov5_rotation) <img src="https://img.shields.io/github/stars/acai66/yolov5_rotation?style=social"/> : rotated bbox detection. inspired by [hukaixuan19970627/yolov5_obb](https://github.com/hukaixuan19970627/yolov5_obb), thanks hukaixuan19970627.

    - [ming71/rotate-yolov3](https://github.com/ming71/rotate-yolov3) <img src="https://img.shields.io/github/stars/ming71/rotate-yolov3?style=social"/> : Arbitrary oriented object detection implemented with yolov3 (attached with some tricks).

    - [ming71/yolov3-polygon](https://github.com/ming71/yolov3-polygon) <img src="https://img.shields.io/github/stars/ming71/yolov3-polygon?style=social"/> : Arbitrary-oriented object detection based on yolov3.

    - [kunnnnethan/R-YOLOv4](https://github.com/kunnnnethan/R-YOLOv4) <img src="https://img.shields.io/github/stars/kunnnnethan/R-YOLOv4?style=social"/> : This is a PyTorch-based R-YOLOv4 implementation which combines YOLOv4 model and loss function from R3Det for arbitrary oriented object detection.

    - [XinzeLee/PolygonObjectDetection](https://github.com/XinzeLee/PolygonObjectDetection) <img src="https://img.shields.io/github/stars/XinzeLee/PolygonObjectDetection?style=social"/> : This repository is based on Ultralytics/yolov5, with adjustments to enable polygon prediction boxes.

    - [hukaixuan19970627/DOTA_devkit_YOLO](https://github.com/hukaixuan19970627/DOTA_devkit_YOLO) <img src="https://img.shields.io/github/stars/hukaixuan19970627/DOTA_devkit_YOLO?style=social"/> : Trans DOTA OBB format(poly format) to YOLO format.

    - [hpc203/rotate-yolov5-opencv-onnxrun](https://github.com/hpc203/rotate-yolov5-opencv-onnxrun) <img src="https://img.shields.io/github/stars/hpc203/rotate-yolov5-opencv-onnxrun?style=social"/> : 分别使用OpenCV、ONNXRuntime部署yolov5旋转目标检测，包含C++和Python两个版本的程序。

    - [hpc203/rotateyolov5-opencv-onnxrun](https://github.com/hpc203/rotateyolov5-opencv-onnxrun) <img src="https://img.shields.io/github/stars/hpc203/rotateyolov5-opencv-onnxrun?style=social"/> : 分别使用OpenCV，ONNXRuntime部署yolov5旋转目标检测，包含C++和Python两个版本的程序。

    - [kunnnnethan/R-YOLOv4](https://github.com/kunnnnethan/R-YOLOv4) <img src="https://img.shields.io/github/stars/kunnnnethan/R-YOLOv4?style=social"/> : This is a PyTorch-based R-YOLOv4 implementation which combines YOLOv4 model and loss function from R3Det for arbitrary oriented object detection.

    - [DDGRCF/YOLOX_OBB](https://github.com/DDGRCF/YOLOX_OBB) <img src="https://img.shields.io/github/stars/DDGRCF/YOLOX_OBB?style=social"/> : YOLOX OBB -- YOLOX 旋转框 | 实例分割。 "知乎「刀刀狗」《[YOLOX OBB -- YOLOX 旋转框检测 超详细！！！](https://zhuanlan.zhihu.com/p/430850089)》"。




  - ### Face Detection and Recognition
    #### 人脸检测与识别

    - ####  Face Detection
      ##### 人脸检测

      - [YOLO5Face](https://github.com/deepcam-cn/yolov5-face) <img src="https://img.shields.io/github/stars/deepcam-cn/yolov5-face?style=social"/> : "YOLO5Face: Why Reinventing a Face Detector". (**[arXiv 2021](https://arxiv.org/abs/2105.12931)**)

      - [derronqi/yolov7-face](https://github.com/derronqi/yolov7-face) <img src="https://img.shields.io/github/stars/derronqi/yolov7-face?style=social"/> : yolov7 face detection with landmark.

      - [derronqi/yolov8-face](https://github.com/derronqi/yolov8-face) <img src="https://img.shields.io/github/stars/derronqi/yolov8-face?style=social"/> : yolov8 face detection with landmark.

      - [we0091234/yolov7-face-tensorrt](https://github.com/we0091234/yolov7-face-tensorrt) <img src="https://img.shields.io/github/stars/we0091234/yolov7-face-tensorrt?style=social"/> : yolov7-face TensorRT.

      - [YOLO-FaceV2](https://github.com/Krasjet-Yu/YOLO-FaceV2) <img src="https://img.shields.io/github/stars/Krasjet-Yu/YOLO-FaceV2?style=social"/> : "YOLO-FaceV2: A Scale and Occlusion Aware Face Detector ". (**[arXiv 2022](https://arxiv.org/abs/2208.02019)**). "微信公众号「江大白」《[超越Yolo5-Face，Yolo-Facev2开源，各类Trick优化，值得学习！](https://mp.weixin.qq.com/s?__biz=Mzg5NzgyNTU2Mg==&mid=2247498561&idx=1&sn=b7ff0592644ab6bc5b716e07294e1c0a&source=41#wechat_redirect)》"

      - [OAID/TengineKit](https://github.com/OAID/TengineKit) <img src="https://img.shields.io/github/stars/OAID/TengineKit?style=social"/> : TengineKit - Free, Fast, Easy, Real-Time Face Detection & Face Landmarks & Face Attributes & Hand Detection & Hand Landmarks & Body Detection & Body Landmarks & Iris Landmarks & Yolov5 SDK On Mobile.

      - [xialuxi/yolov5_face_landmark](https://github.com/xialuxi/yolov5_face_landmark) <img src="https://img.shields.io/github/stars/xialuxi/yolov5_face_landmark?style=social"/> : 基于yolov5的人脸检测，带关键点检测。

      - [sthanhng/yoloface](https://github.com/sthanhng/yoloface) <img src="https://img.shields.io/github/stars/sthanhng/yoloface?style=social"/> : Deep learning-based Face detection using the YOLOv3 algorithm.

      - [DayBreak-u/yolo-face-with-landmark](https://github.com/DayBreak-u/yolo-face-with-landmark) <img src="https://img.shields.io/github/stars/DayBreak-u/yolo-face-with-landmark?style=social"/> : yoloface大礼包 使用pytroch实现的基于yolov3的轻量级人脸检测（包含关键点）。

      - [abars/YoloKerasFaceDetection](https://github.com/abars/YoloKerasFaceDetection) <img src="https://img.shields.io/github/stars/abars/YoloKerasFaceDetection?style=social"/> : Face Detection and Gender and Age Classification using Keras.

      - [dannyblueliu/YOLO-Face-detection](https://github.com/dannyblueliu/YOLO-Face-detection) <img src="https://img.shields.io/github/stars/dannyblueliu/YOLO-Face-detection?style=social"/> : Face detection based on YOLO darknet.

      - [wmylxmj/YOLO-V3-IOU](https://github.com/wmylxmj/YOLO-V3-IOU) <img src="https://img.shields.io/github/stars/wmylxmj/YOLO-V3-IOU?style=social"/> : YOLO3 动漫人脸检测 (Based on keras and tensorflow) 2019-1-19.

      - [pranoyr/head-detection-using-yolo](https://github.com/pranoyr/head-detection-using-yolo) <img src="https://img.shields.io/github/stars/pranoyr/head-detection-using-yolo?style=social"/> : Detection of head using YOLO.

      - [grapeot/AnimeHeadDetector](https://github.com/grapeot/AnimeHeadDetector) <img src="https://img.shields.io/github/stars/grapeot/AnimeHeadDetector?style=social"/> : An object detector for character heads in animes, based on Yolo V3.

      - [Chenyang-ZHU/YOLOv3-Based-Face-Detection-Tracking](https://github.com/Chenyang-ZHU/YOLOv3-Based-Face-Detection-Tracking) <img src="https://img.shields.io/github/stars/Chenyang-ZHU/YOLOv3-Based-Face-Detection-Tracking?style=social"/> : This is a robot project for television live. System will tracking the host's face, making the face in the middle of the screen.

      - [zdfb/Yolov5_face](https://github.com/zdfb/Yolov5_face) <img src="https://img.shields.io/github/stars/zdfb/Yolov5_face?style=social"/> : 基于pytorch的Yolov5人脸检测。

      - [jinfagang/yolov7-face](https://github.com/jinfagang/yolov7-face) <img src="https://img.shields.io/github/stars/jinfagang/yolov7-face?style=social"/> : Next Gen Face detection based on YOLOv7.

      - [Yusepp/YOLOv8-Face](https://github.com/Yusepp/YOLOv8-Face) <img src="https://img.shields.io/github/stars/Yusepp/YOLOv8-Face?style=social"/> : YOLOv8 for Face Detection.



    - ####  Face Recognition
      ##### 人脸识别

      - [ChanChiChoi/awesome-Face_Recognition](https://github.com/ChanChiChoi/awesome-Face_Recognition) <img src="https://img.shields.io/github/stars/ChanChiChoi/awesome-Face_Recognition?style=social"/> : papers about Face Detection; Face Alignment; Face Recognition && Face Identification && Face Verification && Face Representation; Face Reconstruction; Face Tracking; Face Super-Resolution && Face Deblurring; Face Generation && Face Synthesis; Face Transfer; Face Anti-Spoofing; Face Retrieval.

      - [hpc203/10kinds-light-face-detector-align-recognition](https://github.com/hpc203/10kinds-light-face-detector-align-recognition) <img src="https://img.shields.io/github/stars/hpc203/10kinds-light-face-detector-align-recognition?style=social"/> : 10种轻量级人脸检测算法的比拼，其中还包含人脸关键点检测与对齐，人脸特征向量提取和计算距离相似度。

      - [ooooxianyu/yoloV5-arcface_forlearn](https://github.com/ooooxianyu/yoloV5-arcface_forlearn) <img src="https://img.shields.io/github/stars/ooooxianyu/yoloV5-arcface_forlearn?style=social"/> : 简单拼接一些源码，实现的人脸识别项目。可供学习参考。具体使用到：yolov5人脸检测、arcface人脸识别。

      - [zhouyuchong/face-recognition-deepstream](https://github.com/zhouyuchong/face-recognition-deepstream) <img src="https://img.shields.io/github/stars/zhouyuchong/face-recognition-deepstream?style=social"/> : Deepstream app use YOLO, retinaface and arcface for face recognition.

      - [duckzhao/face_detection_and_recognition_yolov5](https://github.com/duckzhao/face_detection_and_recognition_yolov5) <img src="https://img.shields.io/github/stars/duckzhao/face_detection_and_recognition_yolov5?style=social"/> : 使用yolov5构建人脸检测模型，使用预训练的Arcface完成人脸特征提取和识别。

      - [PhucNDA/FaceID--YOLOV5.ArcFace](https://github.com/PhucNDA/FaceID--YOLOV5.ArcFace) <img src="https://img.shields.io/github/stars/PhucNDA/FaceID--YOLOV5.ArcFace?style=social"/> : ONNX implementation of YOLOv5 and Siamese Network (ResNet100) with ArcFace loss for Face Detection and Recognition.



  - ### Face Mask Detection
    #### 口罩检测

    - [Bil369/MaskDetect-YOLOv4-PyTorch](https://github.com/Bil369/MaskDetect-YOLOv4-PyTorch) <img src="https://img.shields.io/github/stars/Bil369/MaskDetect-YOLOv4-PyTorch?style=social"/> : 基于PyTorch&YOLOv4实现的口罩佩戴检测 ⭐ 自建口罩数据集分享。

    - [adityap27/face-mask-detector](https://github.com/adityap27/face-mask-detector) <img src="https://img.shields.io/github/stars/adityap27/face-mask-detector?style=social"/> : 𝐑𝐞𝐚𝐥-𝐓𝐢𝐦𝐞 𝐅𝐚𝐜𝐞 𝐦𝐚𝐬𝐤 𝐝𝐞𝐭𝐞𝐜𝐭𝐢𝐨𝐧 𝐮𝐬𝐢𝐧𝐠 𝐝𝐞𝐞𝐩𝐥𝐞𝐚𝐫𝐧𝐢𝐧𝐠 𝐰𝐢𝐭𝐡 𝐀𝐥𝐞𝐫𝐭 𝐬𝐲𝐬𝐭𝐞𝐦 💻🔔.

    - [VictorLin000/YOLOv3_mask_detect](https://github.com/VictorLin000/YOLOv3_mask_detect) <img src="https://img.shields.io/github/stars/VictorLin000/YOLOv3_mask_detect?style=social"/> : Face mask detection using YOLOv3 on GoogleColab.

    - [amh28/IBM-Data-Science-Capstone-Alejandra-Marquez](https://github.com/amh28/IBM-Data-Science-Capstone-Alejandra-Marquez) <img src="https://img.shields.io/github/stars/amh28/IBM-Data-Science-Capstone-Alejandra-Marquez?style=social"/> : Homemade face mask detector fine-tuning a Yolo-v3 network.

    - [LorenRd/JetsonYolov4](https://github.com/LorenRd/JetsonYolov4) <img src="https://img.shields.io/github/stars/LorenRd/JetsonYolov4?style=social"/> : Face Mask Yolov4 detector - Nvidia Jetson Nano.

    - [Backl1ght/yolov4_face_mask_detection](https://github.com/Backl1ght/yolov4_face_mask_detection) <img src="https://img.shields.io/github/stars/Backl1ght/yolov4_face_mask_detection?style=social"/> : 基于yolov4实现口罩佩戴检测，在验证集上做到了0.954的mAP。

    - [pritul2/yolov5_FaceMask](https://github.com/pritul2/yolov5_FaceMask) <img src="https://img.shields.io/github/stars/pritul2/yolov5_FaceMask?style=social"/> : Detecting person with or without face mask. Trained using YOLOv5.

    - [NisargPethani/FACE-MASK-DETECTION-USING-YOLO-V3](https://github.com/NisargPethani/FACE-MASK-DETECTION-USING-YOLO-V3) <img src="https://img.shields.io/github/stars/NisargPethani/FACE-MASK-DETECTION-USING-YOLO-V3?style=social"/> : FACE-MASK DETECTION.

    - [waittim/mask-detector](https://github.com/waittim/mask-detector) <img src="https://img.shields.io/github/stars/waittim/mask-detector?style=social"/> : Real-time video streaming mask detection based on Python. Designed to defeat COVID-19.

    - [BogdanMarghescu/Face-Mask-Detection-Using-YOLOv4](https://github.com/BogdanMarghescu/Face-Mask-Detection-Using-YOLOv4) <img src="https://img.shields.io/github/stars/BogdanMarghescu/Face-Mask-Detection-Using-YOLOv4?style=social"/> : Face Mask Detector using YOLOv4.

    - [xinghanliuying/yolov5_bus](https://github.com/xinghanliuying/yolov5_bus) <img src="https://img.shields.io/github/stars/xinghanliuying/yolov5_bus?style=social"/> : 手把手教你使用YOLOV5训练自己的目标检测模型。

    - [song-laogou/yolov5-mask-42](https://gitee.com/song-laogou/yolov5-mask-42) : 基于YOLOV5的口罩检测系统-提供教学视频。


  - ### Social Distance Detection
    #### 社交距离检测

    - [Ank-Cha/Social-Distancing-Analyser-COVID-19](https://github.com/Ank-Cha/Social-Distancing-Analyser-COVID-19) <img src="https://img.shields.io/github/stars/Ank-Cha/Social-Distancing-Analyser-COVID-19?style=social"/> : Social Distancing Analyser to prevent COVID19.

    - [abd-shoumik/Social-distance-detection](https://github.com/abd-shoumik/Social-distance-detection) <img src="https://img.shields.io/github/stars/abd-shoumik/Social-distance-detection?style=social"/> : Social distance detection, a deep learning computer vision project with yolo object detection.

    - [ChargedMonk/Social-Distancing-using-YOLOv5](https://github.com/ChargedMonk/Social-Distancing-using-YOLOv5) <img src="https://img.shields.io/github/stars/ChargedMonk/Social-Distancing-using-YOLOv5?style=social"/> : Classifying people as high risk and low risk based on their distance to other people.

    - [JohnBetaCode/Social-Distancing-Analyser](https://github.com/JohnBetaCode/Social-Distancing-Analyser) <img src="https://img.shields.io/github/stars/JohnBetaCode/Social-Distancing-Analyser?style=social"/> : Social Distancing Analyzer.

    - [Ashamaria/Safe-distance-tracker-using-YOLOv3-v3](https://github.com/Ashamaria/Safe-distance-tracker-using-YOLOv3-v3) <img src="https://img.shields.io/github/stars/Ashamaria/Safe-distance-tracker-using-YOLOv3-v3?style=social"/> : Safe Distance Tracker.


  - ### Autonomous Driving Field Detection
    #### 自动驾驶领域检测

    - ####  Vehicle Detection
      #####  车辆检测

      - [jason-li-831202/Vehicle-CV-ADAS](https://github.com/jason-li-831202/Vehicle-CV-ADAS) <img src="https://img.shields.io/github/stars/jason-li-831202/Vehicle-CV-ADAS?style=social"/> : The project can achieve FCWS, LDWS, and LKAS functions solely using only visual sensors. using YOLOv5 / YOLOv5-lite / YOLOv6 / YOLOv7 / YOLOv8 / YOLOv9 / EfficientDet and Ultra-Fast-Lane-Detection-v2.

      - [williamhyin/yolov5s_bdd100k](https://github.com/williamhyin/yolov5s_bdd100k) <img src="https://img.shields.io/github/stars/williamhyin/yolov5s_bdd100k?style=social"/> : Train a yolo v5 object detection model on Bdd100k dataset.

      - [Gaussian_YOLOv3](https://github.com/jwchoi384/Gaussian_YOLOv3) <img src="https://img.shields.io/github/stars/jwchoi384/Gaussian_YOLOv3?style=social"/> : "Gaussian YOLOv3: An Accurate and Fast Object Detector Using Localization Uncertainty for Autonomous Driving". (**[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/html/Choi_Gaussian_YOLOv3_An_Accurate_and_Fast_Object_Detector_Using_Localization_ICCV_2019_paper.html)**)

      - [streamlit/demo-self-driving](https://github.com/streamlit/demo-self-driving) <img src="https://img.shields.io/github/stars/streamlit/demo-self-driving?style=social"/> : Streamlit app demonstrating an image browser for the Udacity self-driving-car dataset with realtime object detection using YOLO.

      - [JunshengFu/vehicle-detection](https://github.com/JunshengFu/vehicle-detection) <img src="https://img.shields.io/github/stars/JunshengFu/vehicle-detection?style=social"/> : Created vehicle detection pipeline with two approaches: (1) deep neural networks (YOLO framework) and (2) support vector machines ( OpenCV + HOG).

      - [xslittlegrass/CarND-Vehicle-Detection](https://github.com/xslittlegrass/CarND-Vehicle-Detection) <img src="https://img.shields.io/github/stars/xslittlegrass/CarND-Vehicle-Detection?style=social"/> : Vehicle detection using YOLO in Keras runs at 21FPS.

      - [Kevinnan-teen/Intelligent-Traffic-Based-On-CV](https://github.com/Kevinnan-teen/Intelligent-Traffic-Based-On-CV) <img src="https://img.shields.io/github/stars/Kevinnan-teen/Intelligent-Traffic-Based-On-CV?style=social"/> : 基于计算机视觉的交通路口智能监控系统。

      - [subodh-malgonde/vehicle-detection](https://github.com/subodh-malgonde/vehicle-detection) <img src="https://img.shields.io/github/stars/subodh-malgonde/vehicle-detection?style=social"/> : Detect vehicles in a video.

      - [CaptainEven/Vehicle-Car-detection-and-multilabel-classification](https://github.com/CaptainEven/Vehicle-Car-detection-and-multilabel-classification) <img src="https://img.shields.io/github/stars/CaptainEven/Vehicle-Car-detection-and-multilabel-classification?style=social"/> : 使用YOLO_v3_tiny和B-CNN实现街头车辆的检测和车辆属性的多标签识别 Using yolo_v3_tiny to do vehicle or car detection and attribute's multilabel classification or recognize。

      - [kaylode/vehicle-counting](https://github.com/kaylode/vehicle-counting) <img src="https://img.shields.io/github/stars/kaylode/vehicle-counting?style=social"/> : Vehicle counting using Pytorch.

      - [MaryamBoneh/Vehicle-Detection](https://github.com/MaryamBoneh/Vehicle-Detection) <img src="https://img.shields.io/github/stars/MaryamBoneh/Vehicle-Detection?style=social"/> : Vehicle Detection Using Deep Learning and YOLO Algorithm.

      - [JeffWang0325/Image-Identification-for-Self-Driving-Cars](https://github.com/JeffWang0325/Image-Identification-for-Self-Driving-Cars) <img src="https://img.shields.io/github/stars/JeffWang0325/Image-Identification-for-Self-Driving-Cars?style=social"/> :  This project achieves some functions of image identification for Self-Driving Cars.

      - [AnarbekovAlt/Traffic-analysis](https://github.com/AnarbekovAlt/Traffic-analysis) <img src="https://img.shields.io/github/stars/AnarbekovAlt/Traffic-analysis?style=social"/> : A traffic analysis system is built on the basis of the YOLO network.

      - [ruhyadi/yolov5-nodeflux](https://github.com/ruhyadi/yolov5-nodeflux) <img src="https://img.shields.io/github/stars/ruhyadi/yolov5-nodeflux?style=social"/> : YOLOv5 Nodeflux Vehicle Detection.

      - [Daheer/Driving-Environment-Detector](https://github.com/Daheer/Driving-Environment-Detector) <img src="https://img.shields.io/github/stars/Daheer/Driving-Environment-Detector?style=social"/> : Detecting road objects using YOLO CNN Architecture.

      - [georgia-tech-db/eva](https://github.com/georgia-tech-db/eva) <img src="https://img.shields.io/github/stars/georgia-tech-db/eva?style=social"/> : Exploratory Video Analytics System.

      - [heathhenley/RhodyCarCounter](https://github.com/heathhenley/RhodyCarCounter) <img src="https://img.shields.io/github/stars/heathhenley/RhodyCarCounter?style=social"/> : An app that uses Yolo to count the cars passing by traffic cams mostly in the Providence, RI area.

      - [zehengl/yyc-traffic-cam](https://github.com/zehengl/yyc-traffic-cam) <img src="https://img.shields.io/github/stars/zehengl/yyc-traffic-cam?style=social"/> : A demo to detect vehicles in traffic cam. [zehengl.github.io/yyc-traffic-cam/](https://zehengl.github.io/yyc-traffic-cam/)

      - [ruhyadi/vehicle-detection-yolov8](https://github.com/ruhyadi/vehicle-detection-yolov8) <img src="https://img.shields.io/github/stars/ruhyadi/vehicle-detection-yolov8?style=social"/> : Vehicle Detection with YOLOv8.




    - ####  License Plate Detection and Recognition
      #####  车牌检测与识别

      - [zeusees/License-Plate-Detector](https://github.com/zeusees/License-Plate-Detector) <img src="https://img.shields.io/github/stars/zeusees/License-Plate-Detector?style=social"/> : License Plate Detection with Yolov5，基于Yolov5车牌检测。

      - [TheophileBuy/LicensePlateRecognition](https://github.com/TheophileBuy/LicensePlateRecognition) <img src="https://img.shields.io/github/stars/TheophileBuy/LicensePlateRecognition?style=social"/> : License Plate Recognition.

      - [alitourani/yolo-license-plate-detection](https://github.com/alitourani/yolo-license-plate-detection) <img src="https://img.shields.io/github/stars/alitourani/yolo-license-plate-detection?style=social"/> : A License-Plate detecttion application based on YOLO.

      - [HuKai97/YOLOv5-LPRNet-Licence-Recognition](https://github.com/HuKai97/YOLOv5-LPRNet-Licence-Recognition) <img src="https://img.shields.io/github/stars/HuKai97/YOLOv5-LPRNet-Licence-Recognition?style=social"/> : 使用YOLOv5和LPRNet进行车牌检测+识别（CCPD数据集）。

      - [xialuxi/yolov5-car-plate](https://github.com/xialuxi/yolov5-car-plate) <img src="https://img.shields.io/github/stars/xialuxi/yolov5-car-plate?style=social"/> : 基于yolov5的车牌检测，包含车牌角点检测。

      - [kyrielw24/License_Plate_Recognition](https://github.com/kyrielw24/License_Plate_Recognition) <img src="https://img.shields.io/github/stars/kyrielw24/License_Plate_Recognition?style=social"/> : 基于Yolo&CNN的车牌识别可视化项目。

      - [we0091234/yolov7_plate](https://github.com/we0091234/yolov7_plate) <img src="https://img.shields.io/github/stars/we0091234/yolov7_plate?style=social"/> : yolov7 车牌检测 车牌识别 中文车牌识别 检测 支持双层车牌 支持13种中文车牌。

      - [MuhammadMoinFaisal/Automatic_Number_Plate_Detection_Recognition_YOLOv8](https://github.com/MuhammadMoinFaisal/Automatic_Number_Plate_Detection_Recognition_YOLOv8) <img src="https://img.shields.io/github/stars/MuhammadMoinFaisal/Automatic_Number_Plate_Detection_Recognition_YOLOv8?style=social"/> : Automatic Number Plate Detection YOLOv8.



    - ####  Lane Detection
      #####  车道线检测

      - [YOLOP](https://github.com/hustvl/YOLOP) <img src="https://img.shields.io/github/stars/hustvl/YOLOP?style=social"/> : "YOLOP: You Only Look Once for Panoptic Driving Perception". (**[arXiv 2021](https://arxiv.org/abs/2108.11250)**).

      - [YOLOPv2](https://github.com/CAIC-AD/YOLOPv2) <img src="https://img.shields.io/github/stars/CAIC-AD/YOLOPv2?style=social"/> : "YOLOPv2: Better, Faster, Stronger for Panoptic Driving Perception". (**[arXiv 2022](https://arxiv.org/abs/2208.11434)**). "微信公众号「集智书童」《[YOLOP v2来啦 | YOLOv7结合YOLOP的多任务版本，超越YOLOP以及HybridNets](https://mp.weixin.qq.com/s/XTD32JCu_YbZjV2Br3KXCA)》"

      - [FeiGeChuanShu/YOLOPv2-ncnn](https://github.com/FeiGeChuanShu/YOLOPv2-ncnn) <img src="https://img.shields.io/github/stars/FeiGeChuanShu/YOLOPv2-ncnn?style=social"/> : YOLOPv2-ncnn.

      - [visualbuffer/copilot](https://github.com/visualbuffer/copilot) <img src="https://img.shields.io/github/stars/visualbuffer/copilot?style=social"/> : Lane and obstacle detection for active assistance during driving.

      - [hpc203/YOLOP-opencv-dnn](https://github.com/hpc203/YOLOP-opencv-dnn) <img src="https://img.shields.io/github/stars/hpc203/YOLOP-opencv-dnn?style=social"/> : 使用OpenCV部署全景驾驶感知网络YOLOP，可同时处理交通目标检测、可驾驶区域分割、车道线检测，三项视觉感知任务。

      - [EdVince/YOLOP-NCNN](https://github.com/EdVince/YOLOP-NCNN) <img src="https://img.shields.io/github/stars/EdVince/YOLOP-NCNN?style=social"/> : YOLOP running in Android by ncnn.

    - ####  Driving Behavior Detection
      #####  驾驶行为检测

      - [JingyibySUTsoftware/Yolov5-deepsort-driverDistracted-driving-behavior-detection](https://github.com/JingyibySUTsoftware/Yolov5-deepsort-driverDistracted-driving-behavior-detection) <img src="https://img.shields.io/github/stars/JingyibySUTsoftware/Yolov5-deepsort-driverDistracted-driving-behavior-detection?style=social"/> : 基于深度学习的驾驶员分心驾驶行为（疲劳+危险行为）预警系统使用YOLOv5+Deepsort实现驾驶员的危险驾驶行为的预警监测。

      - [Arrowes/CEAM-YOLOv7](https://github.com/Arrowes/CEAM-YOLOv7) <img src="https://img.shields.io/github/stars/Arrowes/CEAM-YOLOv7?style=social"/> : "CEAM-YOLOv7:Improved YOLOv7 Based on Channel Expansion and Attention Mechanism for Driver Distraction Behavior Detection". (**[IEEE Access, 2022](https://ieeexplore.ieee.org/abstract/document/9980374/)**).



    - ####  Parking Slot Detection
      #####  停车位检测

      - [visualbuffer/parkingslot](https://github.com/visualbuffer/parkingslot) <img src="https://img.shields.io/github/stars/visualbuffer/parkingslot?style=social"/> : Automated parking occupancy detection.

      - [anil2k/smart-car-parking-yolov5](https://github.com/anil2k/smart-car-parking-yolov5) <img src="https://img.shields.io/github/stars/anil2k/smart-car-parking-yolov5?style=social"/> : Detect free parking lot available for cars.


    - ####  Traffic Light Detection
      #####  交通灯检测

      - [berktepebag/Traffic-light-detection-with-YOLOv3-BOSCH-traffic-light-dataset](https://github.com/berktepebag/Traffic-light-detection-with-YOLOv3-BOSCH-traffic-light-dataset) <img src="https://img.shields.io/github/stars/berktepebag/Traffic-light-detection-with-YOLOv3-BOSCH-traffic-light-dataset?style=social"/> : Detecting Traffic Lights in Real-time with YOLOv3.

      - [mihir-m-gandhi/Adaptive-Traffic-Signal-Timer](https://github.com/mihir-m-gandhi/Adaptive-Traffic-Signal-Timer) <img src="https://img.shields.io/github/stars/mihir-m-gandhi/Adaptive-Traffic-Signal-Timer?style=social"/> : This Adaptive Traffic Signal Timer uses live images from the cameras at traffic junctions for real-time traffic density calculation using YOLO object detection and sets the signal timers accordingly.

      - [wade0125/Traffic_Light_Detection_Yolo](https://github.com/wade0125/Traffic_Light_Detection_Yolo) <img src="https://img.shields.io/github/stars/wade0125/Traffic_Light_Detection_Yolo?style=social"/> : Traffic Light Detection Yolo.

      - [LIU42/PassingRules](https://github.com/LIU42/PassingRules) <img src="https://img.shields.io/github/stars/LIU42/PassingRules?style=social"/> : 一种基于 YOLOv8 的路口交通信号灯通行规则识别模型及算法.



    - ####  Traffic Sign Detection
      #####  交通标志检测

      - [Ai-trainee/Traffic-Sign-Recognition-PyQt5-YOLOv5-GUI](https://github.com/Ai-trainee/Traffic-Sign-Recognition-PyQt5-YOLOv5-GUI) <img src="https://img.shields.io/github/stars/Ai-trainee/Traffic-Sign-Recognition-PyQt5-YOLOv5-GUI?style=social"/> : Road Sign Recognition Project Based on YOLOv5. This is a road sign recognition project based on YOLOv5, developed with a PyQt5 interface, YOLOv5 trained model, and MySQL database. 这是一个基于YOLOv5🚀的道路标志识别系统😊，使用了MySQL数据库💽，PyQt5进行界面设计🎨，PyTorch深度学习框架和TensorRT进行加速⚡，同时包含了CSS样式🌈。系统由五个主要模块组成：系统登录模块🔑负责用户登陆；初始化参数模块📋提供YOLOv5模型的初始化参数设置；标志识别模块🔍是系统的核心，负责对道路标志进行识别并将结果导入数据库；数据库模块💾包含基本数据库操作和数据分析两个子模块；图像处理模块🖼️负责单个图像的处理和数据增强。整个系统支持多种数据输入和模型切换，提供了包括mossic和mixup在内的图像增强方法📈。

      - [halftop/TT100K_YOLO_Label](https://github.com/halftop/TT100K_YOLO_Label) <img src="https://img.shields.io/github/stars/halftop/TT100K_YOLO_Label?style=social"/> : Tsinghua-Tencent 100K dataset XML and TXT Label.

      - [amazingcodeLYL/Traffic_signs_detection_darket](https://github.com/amazingcodeLYL/Traffic_signs_detection_darket) <img src="https://img.shields.io/github/stars/amazingcodeLYL/Traffic_signs_detection_darket?style=social"/> : darknet交通标志检测&TT100K数据集。

      - [TalkUHulk/yolov3-TT100k](https://github.com/TalkUHulk/yolov3-TT100k) <img src="https://img.shields.io/github/stars/TalkUHulk/yolov3-TT100k?style=social"/> : 使用yolov3训练的TT100k(交通标志)模型。

      - [TalkUHulk/yolov4-TT100k](https://github.com/TalkUHulk/yolov4-TT100k) <img src="https://img.shields.io/github/stars/TalkUHulk/yolov4-TT100k?style=social"/> : 使用yolov4训练的TT100k(交通标志)模型。

      - [sarah-antillia/YOLO_Realistic_USA_RoadSigns_160classes](https://github.com/sarah-antillia/YOLO_Realistic_USA_RoadSigns_160classes) <img src="https://img.shields.io/github/stars/sarah-antillia/YOLO_Realistic_USA_RoadSigns_160classes?style=social"/> : USA RoadSigns Dataset 160classes annotated by YOLO format.

      - [DickensKP/yolov3-vehicle-pedestrian-trafficsign-detection-system](https://github.com/DickensKP/yolov3-vehicle-pedestrian-trafficsign-detection-system) <img src="https://img.shields.io/github/stars/DickensKP/yolov3-vehicle-pedestrian-trafficsign-detection-system?style=social"/> : 基于bubbliiiing的yolov3-pytorch框架，自主训练的车辆、行人、交通标志识别系统.

      - [mkrupczak3/Coneslayer](https://github.com/mkrupczak3/Coneslayer) <img src="https://img.shields.io/github/stars/mkrupczak3/Coneslayer?style=social"/> : A lightweight neural-network for rapid detection of traffic cones.


    - ####  Crosswalk Detection
      #####  人行横道/斑马线检测

      - [CDNet](https://github.com/zhangzhengde0225/CDNet) <img src="https://img.shields.io/github/stars/zhangzhengde0225/CDNet?style=social"/> : "CDNet: a real-time and robust crosswalk detection network on Jetson nano based on YOLOv5". (**[Neural Computing and Applications 2022](https://link.springer.com/article/10.1007/s00521-022-07007-9)**). "微信公众号「CVer」《[上海交大提出CDNet：基于改进YOLOv5的斑马线和汽车过线行为检测](https://mp.weixin.qq.com/s/2F3WBtfN_7DkhERMOH8-QA)》"。

      - [xN1ckuz/Crosswalks-Detection-using-YoloV5](https://github.com/xN1ckuz/Crosswalks-Detection-using-YoloV5) <img src="https://img.shields.io/github/stars/xN1ckuz/Crosswalks-Detection-using-YoloV5?style=social"/> : Crosswalks Detection using YOLO, project for Computer Vision and Machine Perception course at University of Basilicata, Computer Science and Engineering.


    - ####  Traffic Accidents Detection
      #####  交通事故检测
      - [khaledsabry97/Argus](https://github.com/khaledsabry97/Argus) <img src="https://img.shields.io/github/stars/khaledsabry97/Argus?style=social"/> : "Road Traffic Accidents Detection Based On Crash Estimation". (**[IEEE ICENCO 2021](https://ieeexplore.ieee.org/document/9698968)**)

    - ####  Road Damage Detection
      #####  道路损伤检测
      - [adnanmushtaq1996/Yolov4_Road_Damage_Detection](https://github.com/adnanmushtaq1996/Yolov4_Road_Damage_Detection) <img src="https://img.shields.io/github/stars/adnanmushtaq1996/Yolov4_Road_Damage_Detection?style=social"/> : A Repository to Train a Custom Yolov4 based object detector for road damage detection using the RDD2020 dataset.

      - [E-Kozyreva/detection_potholes_yolov8n](https://github.com/E-Kozyreva/detection_potholes_yolov8n) <img src="https://img.shields.io/github/stars/E-Kozyreva/detection_potholes_yolov8n?style=social"/> : Поиск выбоин на дорогах с использованием YOLOv8 Nano.

      - [mounishvatti/pothole_detection_yolov8](https://github.com/mounishvatti/pothole_detection_yolov8) <img src="https://img.shields.io/github/stars/mounishvatti/pothole_detection_yolov8?style=social"/> : Pothole Detection using Ultralytics YOLOv8



  - ### Animal Detection
    #### 动物检测

    - [SaiSwarup27/Animal-Intrusion-Detection](https://github.com/SaiSwarup27/Animal-Intrusion-Detection) <img src="https://img.shields.io/github/stars/SaiSwarup27/Animal-Intrusion-Detection?style=social"/> : Animal Detection using YOLOv5.

    - [xcapt0/animal_recognition](https://github.com/xcapt0/animal_recognition) <img src="https://img.shields.io/github/stars/xcapt0/animal_recognition?style=social"/> : 🦁 Let the robot recognize the animal instead of you | YOLOv5.

    - [PhamDangNguyen/YOLOv5_Animals](https://github.com/PhamDangNguyen/YOLOv5_Animals) <img src="https://img.shields.io/github/stars/PhamDangNguyen/YOLOv5_Animals?style=social"/> : YOLOv5 for detection Animals.

    - [Sabuj-CSE11/AnimalDetection](https://github.com/Sabuj-CSE11/AnimalDetection) <img src="https://img.shields.io/github/stars/Sabuj-CSE11/AnimalDetection?style=social"/> : Cat and Dogs detection using YoloV5.






  - ### Helmet Detection
    #### 头盔/安全帽检测

    - [PeterH0323/Smart_Construction](https://github.com/PeterH0323/Smart_Construction) <img src="https://img.shields.io/github/stars/PeterH0323/Smart_Construction?style=social"/> : Head Person Helmet Detection on Construction Sites，基于目标检测工地安全帽和禁入危险区域识别系统。

    - [Byronnar/tensorflow-serving-yolov3](https://github.com/Byronnar/tensorflow-serving-yolov3) <img src="https://img.shields.io/github/stars/Byronnar/tensorflow-serving-yolov3?style=social"/> : 对原tensorflow-yolov3版本做了许多细节上的改进，增加了TensorFlow-Serving工程部署，训练了多个数据集，包括Visdrone2019, 安全帽等。

    - [gengyanlei/reflective-clothes-detect-yolov5](https://github.com/gengyanlei/reflective-clothes-detect-yolov5) <img src="https://img.shields.io/github/stars/gengyanlei/reflective-clothes-detect-yolov5?style=social"/> : reflective-clothes-detect-dataset、helemet detection yolov5、工作服(反光衣)检测数据集、安全帽检测、施工人员穿戴检测。

    - [DataXujing/YOLO-V3-Tensorflow](https://github.com/DataXujing/YOLO-V3-Tensorflow) <img src="https://img.shields.io/github/stars/DataXujing/YOLO-V3-Tensorflow?style=social"/> : 👷 👷👷 YOLO V3(Tensorflow 1.x) 安全帽 识别 | 提供数据集下载和与预训练模型。

    - [rafiuddinkhan/Yolo-Training-GoogleColab](https://github.com/rafiuddinkhan/Yolo-Training-GoogleColab) <img src="https://img.shields.io/github/stars/rafiuddinkhan/Yolo-Training-GoogleColab?style=social"/> : Helmet Detection using tiny-yolo-v3 by training using your own dataset and testing the results in the google colaboratory.

    - [BlcaKHat/yolov3-Helmet-Detection](https://github.com/BlcaKHat/yolov3-Helmet-Detection) <img src="https://img.shields.io/github/stars/BlcaKHat/yolov3-Helmet-Detection?style=social"/> : Training a YOLOv3 model to detect the presence of helmet for intrusion or traffic monitoring.

    - [yumulinfeng1/YOLOv4-Hat-detection](https://github.com/yumulinfeng1/YOLOv4-Hat-detection) <img src="https://img.shields.io/github/stars/yumulinfeng1/YOLOv4-Hat-detection?style=social"/> : 基于YOLOv4的安全帽佩戴检测。

    - [FanDady/Helmet-Detection-YoloV5](https://github.com/FanDady/Helmet-Detection-YoloV5) <img src="https://img.shields.io/github/stars/FanDady/Helmet-Detection-YoloV5?style=social"/> : Safety helmet wearing detection on construction site based on YoloV5s-V5.0 including helmet dataset（基于YoloV5-V5.0的工地安全帽检测并且包含开源的安全帽数据集）。

    - [RUI-LIU7/Helmet_Detection](https://github.com/RUI-LIU7/Helmet_Detection) <img src="https://img.shields.io/github/stars/RUI-LIU7/Helmet_Detection?style=social"/> : 使用yolov5算法实现安全帽以及危险区域的监测，同时接入海康摄像头实现实时监测。

    - [ZijianWang1995/PPE_detection](https://github.com/ZijianWang1995/PPE_detection) <img src="https://img.shields.io/github/stars/ZijianWang1995/PPE_detection?style=social"/> : Real-time PPE detection based on YOLO. Open high-quality dataset. "Fast Personal Protective Equipment Detection for Real Construction Sites Using Deep Learning Approaches". (**[Sensors 2021](https://www.mdpi.com/1424-8220/21/10/3478)**)



  - ### Hand Detection
    #### 手部检测

    - [cansik/yolo-hand-detection](https://github.com/cansik/yolo-hand-detection) <img src="https://img.shields.io/github/stars/cansik/yolo-hand-detection?style=social"/> : A pre-trained YOLO based hand detection network.


  - ### Gesture Recognition
    #### 手势/手语识别

    - [MahmudulAlam/Unified-Gesture-and-Fingertip-Detection](https://github.com/MahmudulAlam/Unified-Gesture-and-Fingertip-Detection) <img src="https://img.shields.io/github/stars/MahmudulAlam/Unified-Gesture-and-Fingertip-Detection?style=social"/> : "Unified learning approach for egocentric hand gesture recognition and fingertip detection". (**[Elsevier 2022](https://www.sciencedirect.com/science/article/abs/pii/S0031320321003824)**)

    - [insigh1/Interactive_ABCs_with_American_Sign_Language_using_Yolov5](https://github.com/insigh1/Interactive_ABCs_with_American_Sign_Language_using_Yolov5) <img src="https://img.shields.io/github/stars/insigh1/Interactive_ABCs_with_American_Sign_Language_using_Yolov5?style=social"/> : Interactive ABC's with American Sign Language.

    - [Dreaming-future/YOLO-Object-Detection](https://github.com/Dreaming-future/YOLO-Object-Detection) <img src="https://img.shields.io/github/stars/Dreaming-future/YOLO-Object-Detection?style=social"/> :  YOLO-Object-Detection 集成多种yolo模型，作为一个模板进行目标检测。


  - ### Action Detection
    #### 行为检测

    - [wufan-tb/yolo_slowfast](https://github.com/wufan-tb/yolo_slowfast) <img src="https://img.shields.io/github/stars/wufan-tb/yolo_slowfast?style=social"/> : A realtime action detection frame work based on PytorchVideo.



  - ### Emotion Recognition
    #### 情感识别

    - [Tandon-A/emotic](https://github.com/Tandon-A/emotic) <img src="https://img.shields.io/github/stars/Tandon-A/emotic?style=social"/> : "Context based emotion recognition using emotic dataset". (**[arXiv 2020](https://arxiv.org/abs/2003.13401)**)


  - ### Human Pose Estimation
    #### 人体姿态估计

    - [wmcnally/kapao](https://github.com/wmcnally/kapao) <img src="https://img.shields.io/github/stars/wmcnally/kapao?style=social"/> : KAPAO is a state-of-the-art single-stage human pose estimation model that detects keypoints and poses as objects and fuses the detections to predict human poses. "Rethinking Keypoint Representations: Modeling Keypoints and Poses as Objects for Multi-Person Human Pose Estimation". (**[arXiv 2021](https://arxiv.org/abs/2111.08557)**)

    - [TexasInstruments/edgeai-yolov5](https://github.com/TexasInstruments/edgeai-yolov5) <img src="https://img.shields.io/github/stars/TexasInstruments/edgeai-yolov5?style=social"/> : "YOLO-Pose: Enhancing YOLO for Multi Person Pose Estimation Using Object Keypoint Similarity Loss". (**[arXiv 2022](https://arxiv.org/abs/2204.06806)**)

    - [TexasInstruments/edgeai-yolox](https://github.com/TexasInstruments/edgeai-yolox) <img src="https://img.shields.io/github/stars/TexasInstruments/edgeai-yolox?style=social"/> : "YOLO-Pose: Enhancing YOLO for Multi Person Pose Estimation Using Object Keypoint Similarity Loss". (**[arXiv 2022](https://arxiv.org/abs/2204.06806)**)

    - [jinfagang/VIBE_yolov5](https://github.com/jinfagang/VIBE_yolov5) <img src="https://img.shields.io/github/stars/jinfagang/VIBE_yolov5?style=social"/> : Using YOLOv5 as detection on VIBE. "VIBE: Video Inference for Human Body Pose and Shape Estimation". (**[CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Kocabas_VIBE_Video_Inference_for_Human_Body_Pose_and_Shape_Estimation_CVPR_2020_paper.html)**)

    - [zhuoxiangpang/ism_person_openpose](https://github.com/zhuoxiangpang/ism_person_openpose) <img src="https://img.shields.io/github/stars/zhuoxiangpang/ism_person_openpose?style=social"/> : yolov5人体检测+openpose姿态检测 实现摔倒检测。

    - [pengyang1225/yolov5_person_pose](https://github.com/pengyang1225/yolov5_person_pose) <img src="https://img.shields.io/github/stars/pengyang1225/yolov5_person_pose?style=social"/> : 基于yolov5的person—pose。

    - [hpc203/yolov5_pose_opencv](https://github.com/hpc203/yolov5_pose_opencv) <img src="https://img.shields.io/github/stars/hpc203/yolov5_pose_opencv?style=social"/> : 使用OpenCV部署yolov5-pose目标检测+人体姿态估计，包含C++和Python两个版本的程序。支持yolov5s，yolov5m，yolov5l。

    - [RizwanMunawar/yolov7-pose-estimation](https://github.com/RizwanMunawar/yolov7-pose-estimation) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov7-pose-estimation?style=social"/> : YOLOv7 Pose estimation using OpenCV, PyTorch.

    - [nanmi/yolov7-pose](https://github.com/nanmi/yolov7-pose) <img src="https://img.shields.io/github/stars/nanmi/yolov7-pose?style=social"/> : pose detection base on yolov7.


  - ### Distance Measurement
    #### 距离测量

    - [davidfrz/yolov5_distance_count](https://github.com/davidfrz/yolov5_distance_count) <img src="https://img.shields.io/github/stars/davidfrz/yolov5_distance_count?style=social"/> : 通过yolov5实现目标检测+双目摄像头实现距离测量。

    - [wenyishengkingkong/realsense-D455-YOLOV5](https://github.com/wenyishengkingkong/realsense-D455-YOLOV5) <img src="https://img.shields.io/github/stars/wenyishengkingkong/realsense-D455-YOLOV5?style=social"/> : 利用realsense深度相机实现yolov5目标检测的同时测出距离。

    - [Thinkin99/yolov5_d435i_detection](https://github.com/Thinkin99/yolov5_d435i_detection) <img src="https://img.shields.io/github/stars/Thinkin99/yolov5_d435i_detection?style=social"/> : 使用realsense d435i相机，基于pytorch实现yolov5目标检测，返回检测目标相机坐标系下的位置信息。

    - [MUCHWAY/detect_distance_gazebo](https://github.com/MUCHWAY/detect_distance_gazebo) <img src="https://img.shields.io/github/stars/MUCHWAY/detect_distance_gazebo?style=social"/> : yolov5+camera_distance+gazebo.

    - [magisystem0408/yolov5-DeepSort-RealSenseD435i](https://github.com/magisystem0408/yolov5-DeepSort-RealSenseD435i) <img src="https://img.shields.io/github/stars/magisystem0408/yolov5-DeepSort-RealSenseD435i?style=social"/> : yolov5+Realsence+DeepSense D435i.


  - ### Instance and Semantic Segmentation
    #### 实例和语义分割

    - [SAM](https://github.com/facebookresearch/segment-anything) <img src="https://img.shields.io/github/stars/facebookresearch/segment-anything?style=social"/> : The repository provides code for running inference with the SegmentAnything Model (SAM), links for downloading the trained model checkpoints, and example notebooks that show how to use the model. "Segment Anything". (**[arXiv 2023](https://arxiv.org/abs/2304.02643)**).

    - [Grounded-SAM](https://github.com/IDEA-Research/Grounded-Segment-Anything) <img src="https://img.shields.io/github/stars/IDEA-Research/Grounded-Segment-Anything?style=social"/> : Marrying Grounding DINO with Segment Anything & Stable Diffusion & Tag2Text & BLIP & Whisper & ChatBot - Automatically Detect , Segment and Generate Anything with Image, Text, and Audio Inputs. We plan to create a very interesting demo by combining [Grounding DINO](https://github.com/IDEA-Research/GroundingDINO) and [Segment Anything](https://github.com/facebookresearch/segment-anything) which aims to detect and segment Anything with text inputs!

    - [Laughing-q/yolov5-q](https://github.com/Laughing-q/yolov5-q) <img src="https://img.shields.io/github/stars/Laughing-q/yolov5-q?style=social"/> : This repo is plan for instance segmentation based on yolov5-6.0 and yolact.

    - [TomMao23/multiyolov5](https://github.com/TomMao23/multiyolov5) <img src="https://img.shields.io/github/stars/TomMao23/multiyolov5?style=social"/> : Multi YOLO V5——Detection and Semantic Segmentation.

    - [ArtyZe/yolo_segmentation](https://github.com/ArtyZe/yolo_segmentation) <img src="https://img.shields.io/github/stars/ArtyZe/yolo_segmentation?style=social"/> : image (semantic segmentation) instance segmentation by darknet or yolo.

    - [midasklr/yolov5ds](https://github.com/midasklr/yolov5ds) <img src="https://img.shields.io/github/stars/midasklr/yolov5ds?style=social"/> : multi-task yolov5 with detection and segmentation.

    - [RizwanMunawar/yolov7-segmentation](https://github.com/RizwanMunawar/yolov7-segmentation) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov7-segmentation?style=social"/> : YOLOv7 Instance Segmentation using OpenCV and PyTorch.

    - [leandro-svg/Yolov7_Segmentation_Tensorrt](https://github.com/leandro-svg/Yolov7_Segmentation_Tensorrt) <img src="https://img.shields.io/github/stars/leandro-svg/Yolov7_Segmentation_Tensorrt?style=social"/> : The real-time Instance Segmentation Algorithm Yolov7 running on TensoRT and ONNX.

    - [akashAD98/YOLOV8_SAM](https://github.com/akashAD98/YOLOV8_SAM) <img src="https://img.shields.io/github/stars/akashAD98/YOLOV8_SAM?style=social"/> : Use yolov8 & SAM model to get segmention for custom model.


  - ### 3D Object Detection
    #### 三维目标检测

    - [ADLab-AutoDrive/BEVFusion](https://github.com/ADLab-AutoDrive/BEVFusion) <img src="https://img.shields.io/github/stars/ADLab-AutoDrive/BEVFusion?style=social"/> : "BEVFusion: A Simple and Robust LiDAR-Camera Fusion Framework". (**[NeurIPS 2022](https://arxiv.org/abs/2205.13790)**).

    - [mit-han-lab/bevfusion](https://github.com/mit-han-lab/bevfusion) <img src="https://img.shields.io/github/stars/mit-han-lab/bevfusion?style=social"/> : "BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation". (**[ICRA 2023](https://arxiv.org/abs/2205.13542)**).

    - [SAM3D](https://github.com/DYZhang09/SAM3D) <img src="https://img.shields.io/github/stars/DYZhang09/SAM3D?style=social"/> : "SAM3D: Zero-Shot 3D Object Detection via [Segment Anything](https://github.com/facebookresearch/segment-anything) Model". (**[arXiv 2023](https://arxiv.org/abs/2306.02245)**).

    - [maudzung/YOLO3D-YOLOv4-PyTorch](https://github.com/maudzung/YOLO3D-YOLOv4-PyTorch) <img src="https://img.shields.io/github/stars/maudzung/YOLO3D-YOLOv4-PyTorch?style=social"/> : The PyTorch Implementation based on YOLOv4 of the paper: "YOLO3D: End-to-end real-time 3D Oriented Object Bounding Box Detection from LiDAR Point Cloud". (**[ECCV 2018](https://openaccess.thecvf.com/content_eccv_2018_workshops/w18/html/Ali_YOLO3D_End-to-end_real-time_3D_Oriented_Object_Bounding_Box_Detection_from_ECCVW_2018_paper.html)**)

    - [maudzung/Complex-YOLOv4-Pytorch](https://github.com/maudzung/Complex-YOLOv4-Pytorch) <img src="https://img.shields.io/github/stars/maudzung/Complex-YOLOv4-Pytorch?style=social"/> : The PyTorch Implementation based on YOLOv4 of the paper: "Complex-YOLO: Real-time 3D Object Detection on Point Clouds". (**[arXiv 2018](https://arxiv.org/abs/1803.06199)**)

    - [AI-liu/Complex-YOLO](https://github.com/AI-liu/Complex-YOLO) <img src="https://img.shields.io/github/stars/AI-liu/Complex-YOLO?style=social"/> : This is an unofficial implementation of "Complex-YOLO: Real-time 3D Object Detection on Point Clouds in pytorch". (**[arXiv 2018](https://arxiv.org/abs/1803.06199)**)

    - [ghimiredhikura/Complex-YOLOv3](https://github.com/ghimiredhikura/Complex-YOLOv3) <img src="https://img.shields.io/github/stars/ghimiredhikura/Complex-YOLOv3?style=social"/> : Complete but Unofficial PyTorch Implementation of "Complex-YOLO: Real-time 3D Object Detection on Point Clouds with YoloV3". (**[arXiv 2018](https://arxiv.org/abs/1803.06199)**)

    - [ruhyadi/YOLO3D](https://github.com/ruhyadi/YOLO3D) <img src="https://img.shields.io/github/stars/ruhyadi/YOLO3D?style=social"/> : YOLO 3D Object Detection for Autonomous Driving Vehicle. Reference by [skhadem/3D-BoundingBox](https://github.com/skhadem/3D-BoundingBox), "3D Bounding Box Estimation Using Deep Learning and Geometry". (**[CVPR 2017](https://openaccess.thecvf.com/content_cvpr_2017/html/Mousavian_3D_Bounding_Box_CVPR_2017_paper.html)**)

    - [ruhyadi/yolo3d-lightning](https://github.com/ruhyadi/yolo3d-lightning) <img src="https://img.shields.io/github/stars/ruhyadi/YOLO3D?style=social"/> : YOLO for 3D Object Detection.

    - [Yuanchu/YOLO3D](https://github.com/Yuanchu/YOLO3D) <img src="https://img.shields.io/github/stars/Yuanchu/YOLO3D?style=social"/> : Implementation of a basic YOLO model for object detection in 3D.

    - [EmiyaNing/3D-YOLO](https://github.com/EmiyaNing/3D-YOLO) <img src="https://img.shields.io/github/stars/EmiyaNing/3D-YOLO?style=social"/> : YOLO v5 for Lidar-based 3D BEV Detection.


  - ### SLAM Field Detection
    #### SLAM领域检测

    - [bijustin/YOLO-DynaSLAM](https://github.com/bijustin/YOLO-DynaSLAM) <img src="https://img.shields.io/github/stars/bijustin/YOLO-DynaSLAM?style=social"/> : YOLO Dynamic ORB_SLAM is a visual SLAM system that is robust in dynamic scenarios for RGB-D configuration.

    - [BzdTaisa/YoloPlanarSLAM](https://github.com/BzdTaisa/YoloPlanarSLAM) <img src="https://img.shields.io/github/stars/BzdTaisa/YoloPlanarSLAM?style=social"/> : YOLO-Planar-SLAM.

    - [saransapmaz/cv-slam-object-determination](https://github.com/saransapmaz/cv-slam-object-determination) <img src="https://img.shields.io/github/stars/saransapmaz/cv-slam-object-determination?style=social"/> : Object detection with hector slam and YOLO v3 computer vision algorithm.



  - ### Industrial Defect Detection
    #### 工业缺陷检测

    - [annsonic/Steel_defect](https://github.com/annsonic/Steel_defect) <img src="https://img.shields.io/github/stars/annsonic/Steel_defect?style=social"/> : Exercise: Use YOLO to detect hot-rolled steel strip surface defects (NEU-DET dataset).

    - [VanillaHours/pcbDefectDetectionYOLO](https://github.com/VanillaHours/pcbDefectDetectionYOLO) <img src="https://img.shields.io/github/stars/VanillaHours/pcbDefectDetectionYOLO?style=social"/> : PCB defect detection using YOLOv3, on DeepPCB dataset.

    - [talisma-cassoma/pcb-components-detection-recognition](https://github.com/talisma-cassoma/pcb-components-detection-recognition) <img src="https://img.shields.io/github/stars/talisma-cassoma/pcb-components-detection-recognition?style=social"/> : this code shows the train and test of a YOLOV5 convolutional neural network for detection of electronics components.

    - [Luckycat518/Yolo-MSAPF](https://github.com/Luckycat518/Yolo-MSAPF) <img src="https://img.shields.io/github/stars/Luckycat518/Yolo-MSAPF?style=social"/> : Yolo-MSAPF: Multi-Scale Alignment fusion with Parallel feature Filtering model for high accuracy weld defect detection.

    - [JiaLim98/YOLO-PCB](https://github.com/JiaLim98/YOLO-PCB) <img src="https://img.shields.io/github/stars/JiaLim98/YOLO-PCB?style=social"/> : A Deep Context Learning based PCB Defect Detection Model with Anomalous Trend Alarming System.



  - ### SAR Image Detection
    #### 合成孔径雷达图像检测

    - [humblecoder612/SAR_yolov3](https://github.com/humblecoder612/SAR_yolov3) <img src="https://img.shields.io/github/stars/humblecoder612/SAR_yolov3?style=social"/> : Best Accruacy:speed ratio SAR Ship detection in the world.










  - ### Safety Monitoring Field Detection
    #### 安防监控领域检测

    - [gengyanlei/fire-smoke-detect-yolov4](https://github.com/gengyanlei/fire-smoke-detect-yolov4) <img src="https://img.shields.io/github/stars/gengyanlei/fire-smoke-detect-yolov4?style=social"/> : fire-smoke-detect-yolov4-yolov5 and fire-smoke-detection-dataset 火灾检测，烟雾检测。

    - [CVUsers/Smoke-Detect-by-YoloV5](https://github.com/CVUsers/Smoke-Detect-by-YoloV5) <img src="https://img.shields.io/github/stars/CVUsers/Smoke-Detect-by-YoloV5?style=social"/> : Yolov5 real time smoke detection system.

    - [CVUsers/Fire-Detect-by-YoloV5](https://github.com/CVUsers/Fire-Detect-by-YoloV5) <img src="https://img.shields.io/github/stars/CVUsers/Fire-Detect-by-YoloV5?style=social"/> : 火灾检测，浓烟检测，吸烟检测。

    - [spacewalk01/Yolov5-Fire-Detection](https://github.com/spacewalk01/Yolov5-Fire-Detection) <img src="https://img.shields.io/github/stars/spacewalk01/Yolov5-Fire-Detection?style=social"/> : Train yolov5 to detect fire in an image or video.

    - [roflcoopter/viseron](https://github.com/roflcoopter/viseron) <img src="https://img.shields.io/github/stars/roflcoopter/viseron?style=social"/> : Viseron - Self-hosted NVR with object detection.

    - [dcmartin/motion-ai](https://github.com/dcmartin/motion-ai) <img src="https://img.shields.io/github/stars/dcmartin/motion-ai?style=social"/> : AI assisted motion detection for Home Assistant.

    - [Nico31415/Drowning-Detector](https://github.com/Nico31415/Drowning-Detector) <img src="https://img.shields.io/github/stars/Nico31415/Drowning-Detector?style=social"/> : Using YOLO object detection, this program will detect if a person is drowning.

    - [mc-cat-tty/DoorbellCamDaemon](https://github.com/mc-cat-tty/DoorbellCamDaemon) <img src="https://img.shields.io/github/stars/mc-cat-tty/DoorbellCamDaemon?style=social"/> : Part of DoorbellCam project: daemon for people recognition with YOLO from a RTSP video stream.

    - [Choe-Ji-Hwan/Fire_Detect_Custom_Yolov5](https://github.com/Choe-Ji-Hwan/Fire_Detect_Custom_Yolov5) <img src="https://img.shields.io/github/stars/Choe-Ji-Hwan/Fire_Detect_Custom_Yolov5?style=social"/> : 2022-1 Individual Research Assignment: Using YOLOv5 to simply recognize each type of fire.

    - [bishal116/FireDetection](https://github.com/bishal116/FireDetection) <img src="https://img.shields.io/github/stars/bishal116/FireDetection?style=social"/> : This project builds fire detecton using YOLO v3 model.

    - [Psynosaur/Jetson-SecVision](https://github.com/Psynosaur/Jetson-SecVision) <img src="https://img.shields.io/github/stars/Psynosaur/Jetson-SecVision?style=social"/> : Person detection for Hikvision DVR with AlarmIO ports, uses TensorRT and yolov4.

    - [robmarkcole/fire-detection-from-images](https://github.com/robmarkcole/fire-detection-from-images) <img src="https://img.shields.io/github/stars/robmarkcole/fire-detection-from-images?style=social"/> : Detect fire in images using neural nets.

    - [gaiasd/DFireDataset](https://github.com/gaiasd/DFireDataset) <img src="https://img.shields.io/github/stars/gaiasd/DFireDataset?style=social"/> : D-Fire: an image data set for fire and smoke detection.

    - [MuhammadMoinFaisal/FireDetectionYOLOv8](https://github.com/MuhammadMoinFaisal/FireDetectionYOLOv8) <img src="https://img.shields.io/github/stars/MuhammadMoinFaisal/FireDetectionYOLOv8?style=social"/> : Fire Detection using YOLOv8.

    - [AI-Expert-04/School_Zone_Eye_Level](https://github.com/AI-Expert-04/School_Zone_Eye_Level) <img src="https://img.shields.io/github/stars/AI-Expert-04/School_Zone_Eye_Level?style=social"/> : Prevention of accidents in school zones using deep learning.

    - [roboflow/supervision](https://github.com/roboflow/supervision) <img src="https://img.shields.io/github/stars/roboflow/supervision?style=social"/> : We write your reusable computer vision tools. 💜 [roboflow.github.io/supervision](https://roboflow.github.io/supervision/)

    - [AntroSafin/Fire_Detection_YoloV5](https://github.com/AntroSafin/Fire_Detection_YoloV5) <img src="https://img.shields.io/github/stars/AntroSafin/Fire_Detection_YoloV5?style=social"/> : This is the YoloV5 fire detection application.

    - [harivams-sai/FireDetectionYOLOv8](https://github.com/harivams-sai/FireDetectionYOLOv8) <img src="https://img.shields.io/github/stars/harivams-sai/FireDetectionYOLOv8?style=social"/> : A fire detection model based on YOLOv8 Ultralytics model for object detection. Tech: Python, Computer Vision, Colab Notebook, Fire-detection, YOLOv8.

    - [e-candeloro/SAURUSS-Autonomous-Drone-Surveillance](https://github.com/e-candeloro/SAURUSS-Autonomous-Drone-Surveillance) <img src="https://img.shields.io/github/stars/e-candeloro/SAURUSS-Autonomous-Drone-Surveillance?style=social"/> : An autonomous drone and sensor based surveillance system that use a Tello Drone, an Arduino, a Raspberry Pi and an Android smartphone.

    - [pedbrgs/Fire-Detection](https://github.com/pedbrgs/Fire-Detection) <img src="https://img.shields.io/github/stars/pedbrgs/Fire-Detection?style=social"/> : Fire and smoke detection using spatial and temporal patterns.




  - ### Anti-UAV Field Detection
    #### 反无人机领域检测

    - [Anti-UAV](https://github.com/ZhaoJ9014/Anti-UAV) <img src="https://img.shields.io/github/stars/ZhaoJ9014/Anti-UAV?style=social"/> : 🔥🔥Official Repository for Anti-UAV🔥🔥. Anti-UAV300, Anti-UAV410, Anti-UAV600. Please refer to our [Anti-UAV v1](https://ieeexplore.ieee.org/document/9615243) paper and [Anti-UAV v3](https://arxiv.org/pdf/2306.15767.pdf) paper for more details ([WeChat News](https://zhaoj9014.github.io/pub/Anti-UAV.pdf)). "Anti-UAV: A Large-Scale Benchmark for Vision-Based UAV Tracking". (**[IEEE Transactions on Multimedia, 2022](https://ieeexplore.ieee.org/document/9615243)**). "Evidential Detection and Tracking Collaboration: New Problem, Benchmark and Algorithm for Robust Anti-UAV System". (**[arXiv 2023](https://arxiv.org/abs/2306.15767)**).

    - [DUT-Anti-UAV](https://github.com/wangdongdut/DUT-Anti-UAV) <img src="https://img.shields.io/github/stars/wangdongdut/DUT-Anti-UAV?style=social"/> : DUT Anti-UAV Detection and Tracking. "Vision-based Anti-UAV Detection and Tracking". (**[IEEE Transactions on Intelligent Transportation Systems, 2022](https://arxiv.org/abs/2205.10851)**).




  - ### Medical Field Detection
    #### 医学领域检测

    - [DataXujing/YOLO-v5](https://github.com/DataXujing/YOLO-v5) <img src="https://img.shields.io/github/stars/DataXujing/YOLO-v5?style=social"/> : YOLO v5在医疗领域中消化内镜目标检测的应用。

    - [Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images](https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images) <img src="https://img.shields.io/github/stars/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images?style=social"/> : In this project, a new model for automatic detection of covid-19 using raw chest X-ray images is presented.

    - [fahriwps/breast-cancer-detection](https://github.com/fahriwps/breast-cancer-detection) <img src="https://img.shields.io/github/stars/fahriwps/breast-cancer-detection?style=social"/> : Breast cancer mass detection using YOLO object detection algorithm and GUI.

    - [niehusst/YOLO-Cancer-Detection](https://github.com/niehusst/YOLO-Cancer-Detection) <img src="https://img.shields.io/github/stars/niehusst/YOLO-Cancer-Detection?style=social"/> : An implementation of the YOLO algorithm trained to spot tumors in DICOM images.

    - [safakgunes/Blood-Cancer-Detection-YOLOV5](https://github.com/safakgunes/Blood-Cancer-Detection-YOLOV5) <img src="https://img.shields.io/github/stars/safakgunes/Blood-Cancer-Detection-YOLOV5?style=social"/> : Blood Cancer Detection with YOLOV5.

    - [shchiang0708/YOLOv2_skinCancer](https://github.com/shchiang0708/YOLOv2_skinCancer) <img src="https://img.shields.io/github/stars/shchiang0708/YOLOv2_skinCancer?style=social"/> : YOLOv2_skinCancer.

    - [avral1810/parkinsongait](https://github.com/avral1810/parkinsongait) <img src="https://img.shields.io/github/stars/avral1810/parkinsongait?style=social"/> : Parkinson’s Disease.

    - [sierprinsky/YoloV5_blood_cells](https://github.com/sierprinsky/YoloV5_blood_cells) <img src="https://img.shields.io/github/stars/sierprinsky/YoloV5_blood_cells?style=social"/> : The main idea of this project is to detect blood cells using YOLOV5 over a public roboflow dataset.

    - [LuozyCS/skin_disease_detection_yolov5](https://github.com/LuozyCS/skin_disease_detection_yolov5) <img src="https://img.shields.io/github/stars/LuozyCS/skin_disease_detection_yolov5?style=social"/> : skin_disease_detection_yolov5.

    - [Moqixis/object_detection_yolov5_deepsort](https://github.com/Moqixis/object_detection_yolov5_deepsort) <img src="https://img.shields.io/github/stars/Moqixis/object_detection_yolov5_deepsort?style=social"/> : 基于yolov5+deepsort的息肉目标检测。

    - [mdciri/YOLOv7-Bone-Fracture-Detection](https://github.com/mdciri/YOLOv7-Bone-Fracture-Detection) <img src="https://img.shields.io/github/stars/mdciri/YOLOv7-Bone-Fracture-Detection?style=social"/> : YOLOv7 to detect bone fractures on X-ray images.

    - [MIRACLE-Center/YOLO_Universal_Anatomical_Landmark_Detection](https://github.com/MIRACLE-Center/YOLO_Universal_Anatomical_Landmark_Detection) <img src="https://img.shields.io/github/stars/MIRACLE-Center/YOLO_Universal_Anatomical_Landmark_Detection?style=social"/> : [MICCAI 2021] [You Only Learn Once: Universal Anatomical Landmark Detection](https://arxiv.org/abs/2103.04657)

    - [fahriwps/breast-cancer-detection](https://github.com/fahriwps/breast-cancer-detection) <img src="https://img.shields.io/github/stars/fahriwps/breast-cancer-detection?style=social"/> : Breast cancer mass detection using YOLO object detection algorithm and GUI.

    - [mkang315/CST-YOLO](https://github.com/mkang315/CST-YOLO) <img src="https://img.shields.io/github/stars/mkang315/CST-YOLO?style=social"/> : Official implementation of "CST-YOLO: A Novel Method for Blood Cell Detection Based on Improved YOLOv7 and CNN-Swin Transformer".

    - [mkang315/BGF-YOLO](https://github.com/mkang315/BGF-YOLO) <img src="https://img.shields.io/github/stars/mkang315/BGF-YOLO?style=social"/> : [MICCAI'24] Official implementation of "BGF-YOLO: Enhanced YOLOv8 with Multiscale Attentional Feature Fusion for Brain Tumor Detection".



  - ### Chemistry Field Detection
    #### 化学领域检测

    - [xuguodong1999/COCR](https://github.com/xuguodong1999/COCR) <img src="https://img.shields.io/github/stars/xuguodong1999/COCR?style=social"/> : COCR is designed to convert an image of hand-writing chemical structure to graph of that molecule.


  - ### Agricultural Field Detection
    #### 农业领域检测

    - [liao1fan/MGA-YOLO-for-apple-leaf-disease-detection](https://github.com/liao1fan/MGA-YOLO-for-apple-leaf-disease-detection) <img src="https://img.shields.io/github/stars/liao1fan/MGA-YOLO-for-apple-leaf-disease-detection?style=social"/> : MGA-YOLO: A Lightweight One-Stage Network for Apple Leaf Disease Detection.

    - [tanmaypandey7/wheat-detection](https://github.com/tanmaypandey7/wheat-detection) <img src="https://img.shields.io/github/stars/tanmaypandey7/wheat-detection?style=social"/> : Detecting wheat heads using YOLOv5.

    - [WoodratTradeCo/crop-rows-detection](https://github.com/WoodratTradeCo/crop-rows-detection) <img src="https://img.shields.io/github/stars/WoodratTradeCo/crop-rows-detection?style=social"/> : It is an real-time crop rows detection method using YOLOv5.

    - [denghv/Vegetables_Fruit_Detection](https://github.com/denghv/Vegetables_Fruit_Detection) <img src="https://img.shields.io/github/stars/denghv/Vegetables_Fruit_Detection?style=social"/> : Using YOLOv10 to detect vegetables & fruit.



  - ### Sports Field Detection
    #### 体育领域检测

    - [tomer-erez/pingpong-referee](https://github.com/tomer-erez/pingpong-referee) <img src="https://img.shields.io/github/stars/tomer-erez/pingpong-referee?style=social"/> : using the YOlO algorithm for an automated pingpong referee.



  - ### Aerial Imagery Detection
    #### 遥感图像检测

    - [WALDO](https://github.com/stephansturges/WALDO) <img src="https://img.shields.io/github/stars/stephansturges/WALDO?style=social"/> : Whereabouts Ascertainment for Low-lying Detectable Objects. The SOTA in FOSS AI for drones!




  - ### Adverse Weather Conditions
    #### 恶劣天气情况

    - [Image-Adaptive YOLO](https://github.com/wenyyu/Image-Adaptive-YOLO) <img src="https://img.shields.io/github/stars/wenyyu/Image-Adaptive-YOLO?style=social"/> : "Image-Adaptive YOLO for Object Detection in Adverse Weather Conditions". (**[AAAI 2022](https://arxiv.org/abs/2112.08088)**). "计算机视觉研究院：《[图像自适应YOLO：模糊环境下的目标检测（附源代码）](https://mp.weixin.qq.com/s/QdM6Dx990VhN97MRIP74XA)》"



  - ### Adversarial Attack and Defense
    #### 对抗攻击与防御

    - [EAVISE/adversarial-yolo](https://gitlab.com/EAVISE/adversarial-yolo) : "Fooling automated surveillance cameras: adversarial patches to attack person detection". (**[CVPR 2019](https://openaccess.thecvf.com/content_CVPRW_2019/html/CV-COPS/Thys_Fooling_Automated_Surveillance_Cameras_Adversarial_Patches_to_Attack_Person_Detection_CVPRW_2019_paper.html)**)

    - [git-disl/TOG](https://github.com/git-disl/TOG) <img src="https://img.shields.io/github/stars/git-disl/TOG?style=social"/> : "Adversarial Objectness Gradient Attacks on Real-time Object Detection Systems". (**[IEEE TPS-ISA 2020](https://ieeexplore.ieee.org/abstract/document/9325397)**) | "Understanding Object Detection Through an Adversarial Lens". (**[ESORICS 2020](https://link.springer.com/chapter/10.1007/978-3-030-59013-0_23)**)

    - [VITA-Group/3D_Adversarial_Logo](https://github.com/VITA-Group/3D_Adversarial_Logo) <img src="https://img.shields.io/github/stars/VITA-Group/3D_Adversarial_Logo?style=social"/> : 3D adversarial logo attack on different3D object meshes to fool a YOLOV2 detector. "Can 3D Adversarial Logos Clock Humans?". (**[arXiv 2020](https://arxiv.org/abs/2006.14655)**)

    - [ASGuard-UCI/MSF-ADV](https://github.com/ASGuard-UCI/MSF-ADV) <img src="https://img.shields.io/github/stars/ASGuard-UCI/MSF-ADV?style=social"/> : MSF-ADV is a novel physical-world adversarial attack method, which can fool the Multi Sensor Fusion (MSF) based autonomous driving (AD) perception in the victim autonomous vehicle (AV) to fail in detecting a front obstacle and thus crash into it. "Invisible for both Camera and LiDAR: Security of Multi-Sensor Fusion based Perception in Autonomous Driving Under Physical-World Attacks". (**[IEEE S&P 2021](https://www.computer.org/csdl/proceedings-article/sp/2021/893400b302/1t0x9btzenu)**)

    - [veralauee/DPatch](https://github.com/veralauee/DPatch) <img src="https://img.shields.io/github/stars/veralauee/DPatch?style=social"/> : "DPatch: An Adversarial Patch Attack on Object Detectors". (**[arXiv 2018](https://arxiv.org/abs/1806.02299)**)

    - [Shudeng/GPAttack](https://github.com/Shudeng/GPAttack) <img src="https://img.shields.io/github/stars/Shudeng/GPAttack?style=social"/> : Grid Patch Attack for Object Detection.

    - [Wu-Shudeng/DPAttack](https://github.com/Wu-Shudeng/DPAttack) <img src="https://img.shields.io/github/stars/Wu-Shudeng/DPAttack?style=social"/> : "DPAttack: Diffused Patch Attacks against Universal Object Detection". (**[arXiv 2020](https://arxiv.org/abs/2010.11679)**)

    - [FenHua/DetDak](https://github.com/FenHua/DetDak) <img src="https://img.shields.io/github/stars/FenHua/DetDak?style=social"/> : Patch adversarial attack; object detection; CIKM2020 安全AI挑战者计划第四期：通用目标检测的对抗攻击。 "Object Hider: Adversarial Patch Attack Against Object Detectors". (**[arXiv 2020](https://arxiv.org/abs/2010.14974)**)

    - [THUrssq/Tianchi04](https://github.com/THUrssq/Tianchi04) <img src="https://img.shields.io/github/stars/THUrssq/Tianchi04?style=social"/> : This is NO.4 solution for "CIKM-2020 Alibaba-Tsinghua Adversarial Challenge on Object Detection". "Sparse Adversarial Attack to Object Detection". (**[arXiv 2020](https://arxiv.org/abs/2012.13692)**)

    - [mesunhlf/UPC-tf](https://github.com/mesunhlf/UPC-tf) <img src="https://img.shields.io/github/stars/mesunhlf/UPC-tf?style=social"/> : "Universal Physical Camouflage Attacks on Object Detectors". (**[CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Huang_Universal_Physical_Camouflage_Attacks_on_Object_Detectors_CVPR_2020_paper.html)**)

    - [alex96295/YOLOv3_adversarial_defense](https://github.com/alex96295/YOLOv3_adversarial_defense) <img src="https://img.shields.io/github/stars/alex96295/YOLOv3_adversarial_defense?style=social"/> : YOLOv3_adversarial_defense.

    - [alex96295/YOLO_adversarial_attacks](https://github.com/alex96295/YOLO_adversarial_attacks) <img src="https://img.shields.io/github/stars/alex96295/YOLO_adversarial_attacks?style=social"/> : YOLO_adversarial_attacks.

    - [alex96295/Adversarial-Patch-Attacks-TRAINING-YOLO-SSD-Pytorch](https://github.com/alex96295/Adversarial-Patch-Attacks-TRAINING-YOLO-SSD-Pytorch) <img src="https://img.shields.io/github/stars/alex96295/Adversarial-Patch-Attacks-TRAINING-YOLO-SSD-Pytorch?style=social"/> : This repository has the code needed to train 'Adversarial Patch Attacks' on YOLO and SSD models for object detection in Pytorch.

    - [FranBesq/attack-yolo](https://github.com/FranBesq/attack-yolo) <img src="https://img.shields.io/github/stars/FranBesq/attack-yolo?style=social"/> : Developing adversarial attacks on YOLO algorithm for computer vision.

    - [Rushi314/GPR-Object-Detection](https://github.com/Rushi314/GPR-Object-Detection) <img src="https://img.shields.io/github/stars/Rushi314/GPR-Object-Detection?style=social"/> : Detecting Objects in Ground Penetrating Radars Scans.

    - [realtxy/pso-adversarial-yolo_v3](https://github.com/realtxy/pso-adversarial-yolo_v3) <img src="https://img.shields.io/github/stars/realtxy/pso-adversarial-yolo_v3?style=social"/> : pso-adversarial-yolo_v3.

    - [sowgali/ObjCAM](https://github.com/sowgali/ObjCAM) <img src="https://img.shields.io/github/stars/sowgali/ObjCAM?style=social"/> : Visualizations for adversarial attacks in object detectors like YOLO.

    - [andrewpatrickdu/adversarial-yolov3-cowc](https://github.com/andrewpatrickdu/adversarial-yolov3-cowc) <img src="https://img.shields.io/github/stars/andrewpatrickdu/adversarial-yolov3-cowc?style=social"/> : "Physical Adversarial Attacks on an Aerial Imagery Object Detector".  (**[WACV 2022](https://openaccess.thecvf.com/content/WACV2022/html/Du_Physical_Adversarial_Attacks_on_an_Aerial_Imagery_Object_Detector_WACV_2022_paper.html)**)

    - [IQTLabs/camolo](https://github.com/IQTLabs/camolo) <img src="https://img.shields.io/github/stars/IQTLabs/camolo?style=social"/> : Camouflage YOLO - (CAMOLO) trains adversarial patches to confuse the YOLO family of object detectors.

    - [AdvTexture](https://github.com/WhoTHU/Adversarial_Texture) <img src="https://img.shields.io/github/stars/WhoTHU/Adversarial_Texture?style=social"/> : "Adversarial Texture for Fooling Person Detectors in the Physical World". (**[CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Adversarial_Texture_for_Fooling_Person_Detectors_in_the_Physical_World_CVPR_2022_paper.html)**).  "知乎「WhoTH」《[CVPR2022 Oral 物理对抗样本 如何做一件“隐形衣”](https://zhuanlan.zhihu.com/p/499854846)》"。

    - [SamSamhuns/yolov5_adversarial](https://github.com/SamSamhuns/yolov5_adversarial) <img src="https://img.shields.io/github/stars/SamSamhuns/yolov5_adversarial?style=social"/> : Generate adversarial patches against YOLOv5 🚀





  - ### Camouflaged Detection
    #### 伪装目标检测

    - [Ap1rate/yolov8-SIM](https://github.com/Ap1rate/yolov8-SIM) <img src="https://img.shields.io/github/stars/Ap1rate/yolov8-SIM?style=social"/> : Link to Journal of Ecological Informatics paper ' Camouflaged Detection: Optimization-Based Computer Vision for Alligator sinensis with Low Detectability in Complex Wild Environments '.



  - ### Game Field Detection
    #### 游戏领域检测

    - [SunOner/sunone_aimbot](https://github.com/SunOner/sunone_aimbot) <img src="https://img.shields.io/github/stars/SunOner/sunone_aimbot?style=social"/> : 🌲Aim-bot based on AI for all FPS games. [boosty.to/sunone](https://boosty.to/sunone)

    - [Passer1072/RookieAI_yolov8](https://github.com/Passer1072/RookieAI_yolov8) <img src="https://img.shields.io/github/stars/Passer1072/RookieAI_yolov8?style=social"/> : 基于yolov8实现的AI自瞄项目 AI self-aiming project based on yolov8.

    - [petercunha/Pine](https://github.com/petercunha/Pine) <img src="https://img.shields.io/github/stars/petercunha/Pine?style=social"/> : 🌲 Aimbot powered by real-time object detection with neural networks, GPU accelerated with Nvidia. Optimized for use with CS:GO.

    - [chaoyu1999/FPSAutomaticAiming](https://github.com/chaoyu1999/FPSAutomaticAiming) <img src="https://img.shields.io/github/stars/chaoyu1999/FPSAutomaticAiming?style=social"/> : 基于yolov5的FPS类游戏AI自瞄AI。

    - [Lu-tju/CSGO_AI](https://github.com/Lu-tju/CSGO_AI) <img src="https://img.shields.io/github/stars/Lu-tju/CSGO_AI?style=social"/> : 基于YOLOv3的csgo自瞄。

    - [kir486680/csgo_aim](https://github.com/kir486680/csgo_aim) <img src="https://img.shields.io/github/stars/kir486680/csgo_aim?style=social"/> : Aim assist for CSGO with python and yolo.

    - [c925777075/yolov5-dnf](https://github.com/c925777075/yolov5-dnf) <img src="https://img.shields.io/github/stars/c925777075/yolov5-dnf?style=social"/> : yolov5-DNF.

    - [davidhoung2/APEX-yolov5-aim-assist](https://github.com/davidhoung2/APEX-yolov5-aim-assist) <img src="https://img.shields.io/github/stars/davidhoung2/APEX-yolov5-aim-assist?style=social"/> : using yolov5 to help you aim enemies.

     - [Brednan/CSGO-Aimbot](https://github.com/Brednan/CSGO-Aimbot) <img src="https://img.shields.io/github/stars/Brednan/CSGO-Aimbot?style=social"/> : Aimbot for the FPS game CSGO. It uses YOLOv5 to detect enemy players on my screen, then moves my cursor to the location.

     - [2319590263/yolov5-csgo](https://github.com/2319590263/yolov5-csgo) <img src="https://img.shields.io/github/stars/2319590263/yolov5-csgo?style=social"/> : 基于yolov5实现的csgo自瞄。

     - [SCRN-VRC/YOLOv4-Tiny-in-UnityCG-HLSL](https://github.com/SCRN-VRC/YOLOv4-Tiny-in-UnityCG-HLSL) <img src="https://img.shields.io/github/stars/SCRN-VRC/YOLOv4-Tiny-in-UnityCG-HLSL?style=social"/> : A modern object detector inside fragment shaders.

     - [qcjxs-hn/yolov5-csgo](https://github.com/qcjxs-hn/yolov5-csgo) <img src="https://img.shields.io/github/stars/qcjxs-hn/yolov5-csgo?style=social"/> : 这是一个根据教程写的csgo-ai和我自己训练的模型，还有数据集。

     - [Sequoia](https://github.com/IgaoGuru/Sequoia) <img src="https://img.shields.io/github/stars/IgaoGuru/Sequoia?style=social"/> : A neural network for CounterStrike:GlobalOffensive character detection and classification. Built on a custom-made dataset (csgo-data-collector).

     - [ItGarbager/aimcf_yolov5](https://github.com/ItGarbager/aimcf_yolov5) <img src="https://img.shields.io/github/stars/ItGarbager/aimcf_yolov5?style=social"/> : 使用yolov5算法实现cf角色头部预测。

     - [jiaran-takeme/Target-Detection-for-CSGO-by-YOLOv5](https://github.com/jiaran-takeme/Target-Detection-for-CSGO-by-YOLOv5) <img src="https://img.shields.io/github/stars/jiaran-takeme/Target-Detection-for-CSGO-by-YOLOv5?style=social"/> : Target Detection for CSGO by YOLOv5.

     - [Lucid1ty/Yolov5ForCSGO](https://github.com/Lucid1ty/Yolov5ForCSGO) <img src="https://img.shields.io/github/stars/Lucid1ty/Yolov5ForCSGO?style=social"/> : CSGO character detection and auto aim.

     - [leo4048111/Yolov5-LabelMaker-For-CSGO](https://github.com/leo4048111/Yolov5-LabelMaker-For-CSGO) <img src="https://img.shields.io/github/stars/leo4048111/Yolov5-LabelMaker-For-CSGO?style=social"/> : A simple tool for making CSGO dataset in YOLO format.

     - [soloist-v/AutoStrike](https://github.com/soloist-v/AutoStrike) <img src="https://img.shields.io/github/stars/soloist-v/AutoStrike?style=social"/> : 使用yolov5自动瞄准，支持fps游戏 鼠标移动控制需要自行调整。

     - [slyautomation/osrs_yolov5](https://github.com/slyautomation/osrs_yolov5) <img src="https://img.shields.io/github/stars/slyautomation/osrs_yolov5?style=social"/> : Yolov5 Object Detection In OSRS using Python code, Detecting Cows - Botting.

     - [HarunoWindy/yolo-games-weights](https://github.com/HarunoWindy/yolo-games-weights) <img src="https://img.shields.io/github/stars/HarunoWindy/yolo-games-weights?style=social"/> : YOLOv5 vision deep-learning on detect games UI (current support: onmyoji) YOLOv5深度学习识别游戏UI(目前支持：阴阳师).

     - [mrathena/python.yolo.csgo.autoaim.helper](https://github.com/mrathena/python.yolo.csgo.autoaim.helper) <img src="https://img.shields.io/github/stars/mrathena/python.yolo.csgo.autoaim.helper?style=social"/> : Python Yolo v5 6.2 Csgo.

     - [Aa-bN/AimYolo](https://github.com/Aa-bN/AimYolo) <img src="https://img.shields.io/github/stars/Aa-bN/AimYolo?style=social"/> : AI外挂——基于YOLOv5的射击类游戏瞄准辅助。An AI plug-in - targeting aid for shooting games based on YOLOv5.

     - [suixin1424/cf-yolo-trt](https://github.com/suixin1424/cf-yolo-trt) <img src="https://img.shields.io/github/stars/suixin1424/cf-yolo-trt?style=social"/> : 基于yolov5-trt的穿越火线ai自瞄。

     - [DuGuYifei/Yolov5_FPS_AICheatPrinciple](https://github.com/DuGuYifei/Yolov5_FPS_AICheatPrinciple) <img src="https://img.shields.io/github/stars/DuGuYifei/Yolov5_FPS_AICheatPrinciple?style=social"/> : The AI cheating principle of fps game. (This is only used for learning).

     - [MistyAI/MistyFN](https://github.com/MistyAI/MistyFN) <img src="https://img.shields.io/github/stars/MistyAI/MistyFN?style=social"/> : Aimbot and Triggerbot for Fortnite based on artificial intelligence.

     - [suixin1424/crossfire-yolo-TensorRT](https://github.com/suixin1424/crossfire-yolo-TensorRT) <img src="https://img.shields.io/github/stars/suixin1424/crossfire-yolo-TensorRT?style=social"/> : crossfire-yolo-TensorRT. 基于yolo-trt的穿越火线ai自瞄。

     - [EthanH3514/AL_Yolo](https://github.com/EthanH3514/AL_Yolo) <img src="https://img.shields.io/github/stars/EthanH3514/AL_Yolo?style=social"/> : 基于Yolov5的Apex Legend游戏 AI 辅瞄外挂。

     - [SunOner/yolov8_aimbot](https://github.com/SunOner/yolov8_aimbot) <img src="https://img.shields.io/github/stars/SunOner/yolov8_aimbot?style=social"/> : Aim-bot based on AI for all FPS games.

     - [bigQY/calabiyau-cheat](https://github.com/bigQY/calabiyau-cheat) <img src="https://img.shields.io/github/stars/bigQY/calabiyau-cheat?style=social"/> : 基于yolov10的卡拉彼丘自瞄。






  - ### Automatic Annotation Tools
    #### 自动标注工具


    - [Label Studio](https://github.com/HumanSignal/label-studio) <img src="https://img.shields.io/github/stars/HumanSignal/label-studio?style=social"/> : Label Studio is a multi-type data labeling and annotation tool with standardized output format. [labelstud.io](https://labelstud.io/)

    - [AnyLabeling](https://github.com/vietanhdev/anylabeling) <img src="https://img.shields.io/github/stars/vietanhdev/anylabeling?style=social"/> : 🌟 AnyLabeling 🌟. Effortless AI-assisted data labeling with AI support from YOLO, Segment Anything, MobileSAM!! [anylabeling.nrl.ai](https://anylabeling.nrl.ai/)

    - [X-AnyLabeling](https://github.com/CVHub520/X-AnyLabeling) <img src="https://img.shields.io/github/stars/CVHub520/X-AnyLabeling?style=social"/> : 💫 X-AnyLabeling 💫. X-AnyLabeling：一款多 SOTA 模型集成的高级自动标注工具！ Effortless data labeling with AI support from Segment Anything and other awesome models.

    - [Label Anything](https://github.com/open-mmlab/playground/tree/main/label_anything) <img src="https://img.shields.io/github/stars/open-mmlab/playground?style=social"/> : OpenMMLab PlayGround: Semi-Automated Annotation with Label-Studio and SAM.

    - [LabelImg](https://github.com/heartexlabs/labelImg) <img src="https://img.shields.io/github/stars/heartexlabs/labelImg?style=social"/> : 🖍️ LabelImg is a graphical image annotation tool and label object bounding boxes in images.

    - [labelme](https://github.com/wkentaro/labelme) <img src="https://img.shields.io/github/stars/wkentaro/labelme?style=social"/> : Image Polygonal Annotation with Python (polygon, rectangle, circle, line, point and image-level flag annotation).

    - [DarkLabel](https://github.com/darkpgmr/DarkLabel) <img src="https://img.shields.io/github/stars/darkpgmr/DarkLabel?style=social"/> : Video/Image Labeling and Annotation Tool.

    - [AlexeyAB/Yolo_mark](https://github.com/AlexeyAB/Yolo_mark) <img src="https://img.shields.io/github/stars/AlexeyAB/Yolo_mark?style=social"/> : GUI for marking bounded boxes of objects in images for training neural network Yolo v3 and v2.

    - [Cartucho/OpenLabeling](https://github.com/Cartucho/OpenLabeling) <img src="https://img.shields.io/github/stars/Cartucho/OpenLabeling?style=social"/> : Label images and video for Computer Vision applications.

    - [CVAT](https://github.com/cvat-ai/cvat) <img src="https://img.shields.io/github/stars/cvat-ai/cvat?style=social"/> : Computer Vision Annotation Tool (CVAT). Annotate better with CVAT, the industry-leading data engine for machine learning. Used and trusted by teams at any scale, for data of any scale.

    - [VoTT](https://github.com/Microsoft/VoTT) <img src="https://img.shields.io/github/stars/Microsoft/VoTT?style=social"/> : Visual Object Tagging Tool: An electron app for building end to end Object Detection Models from Images and Videos.

    - [WangRongsheng/KDAT](https://github.com/WangRongsheng/KDAT) <img src="https://img.shields.io/github/stars/WangRongsheng/KDAT?style=social"/> : 一个专为视觉方向目标检测全流程的标注工具集，全称：Kill Object Detection Annotation Tools。

    - [Rectlabel-support](https://github.com/ryouchinsa/Rectlabel-support) <img src="https://img.shields.io/github/stars/ryouchinsa/Rectlabel-support?style=social"/> : RectLabel - An image annotation tool to label images for bounding box object detection and segmentation.

    - [cnyvfang/labelGo-Yolov5AutoLabelImg](https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg) <img src="https://img.shields.io/github/stars/cnyvfang/labelGo-Yolov5AutoLabelImg?style=social"/> : 💕YOLOV5 semi-automatic annotation tool (Based on labelImg)💕一个基于labelImg及YOLOV5的图形化半自动标注工具。

    - [CVUsers/Auto_maker](https://github.com/CVUsers/Auto_maker) <img src="https://img.shields.io/github/stars/CVUsers/Auto_maker?style=social"/> : 深度学习数据自动标注器开源 目标检测和图像分类（高精度高效率）。

    - [MyVision](https://github.com/OvidijusParsiunas/myvision) <img src="https://img.shields.io/github/stars/OvidijusParsiunas/myvision?style=social"/> : Computer vision based ML training data generation tool 🚀

    - [wufan-tb/AutoLabelImg](https://github.com/wufan-tb/AutoLabelImg) <img src="https://img.shields.io/github/stars/wufan-tb/AutoLabelImg?style=social"/> : auto-labelimg based on yolov5, with many other useful tools. AutoLabelImg 多功能自动标注工具。

    - [MrZander/YoloMarkNet](https://github.com/MrZander/YoloMarkNet) <img src="https://img.shields.io/github/stars/MrZander/YoloMarkNet?style=social"/> : Darknet YOLOv2/3 annotation tool written in C#/WPF.

    - [mahxn0/Yolov3_ForTextLabel](https://github.com/mahxn0/Yolov3_ForTextLabel) <img src="https://img.shields.io/github/stars/mahxn0/Yolov3_ForTextLabel?style=social"/> : 基于yolov3的目标/自然场景文字自动标注工具。

    - [MNConnor/YoloV5-AI-Label](https://github.com/MNConnor/YoloV5-AI-Label) <img src="https://img.shields.io/github/stars/MNConnor/YoloV5-AI-Label?style=social"/> : YoloV5 AI Assisted Labeling.

    - [LILINOpenGitHub/Labeling-Tool](https://github.com/LILINOpenGitHub/Labeling-Tool) <img src="https://img.shields.io/github/stars/LILINOpenGitHub/Labeling-Tool?style=social"/> : Free YOLO AI labeling tool. YOLO AI labeling tool is a Windows app for labeling YOLO dataset.

    - [whs0523003/YOLOv5_6.1_autolabel](https://github.com/whs0523003/YOLOv5_6.1_autolabel) <img src="https://img.shields.io/github/stars/whs0523003/YOLOv5_6.1_autolabel?style=social"/> : YOLOv5_6.1 自动标记目标框。

    - [2vin/PyYAT](https://github.com/2vin/PyYAT) <img src="https://img.shields.io/github/stars/2vin/PyYAT?style=social"/> : Semi-Automatic Yolo Annotation Tool In Python.

    - [AlturosDestinations/Alturos.ImageAnnotation](https://github.com/AlturosDestinations/Alturos.ImageAnnotation) <img src="https://img.shields.io/github/stars/AlturosDestinations/Alturos.ImageAnnotation?style=social"/> : A collaborative tool for labeling image data for yolo.

    - [stephanecharette/DarkMark](https://github.com/stephanecharette/DarkMark) <img src="https://img.shields.io/github/stars/stephanecharette/DarkMark?style=social"/> : Marking up images for use with Darknet.

    - [2vin/yolo_annotation_tool](https://github.com/2vin/yolo_annotation_tool) <img src="https://img.shields.io/github/stars/2vin/yolo_annotation_tool?style=social"/> : Annotation tool for YOLO in opencv.

    - [sanfooh/quick_yolo2_label_tool](https://github.com/sanfooh/quick_yolo2_label_tool) <img src="https://img.shields.io/github/stars/sanfooh/quick_yolo2_label_tool?style=social"/> : yolo快速标注工具 quick yolo2 label tool.

    - [folkien/yaya](https://github.com/folkien/yaya) <img src="https://img.shields.io/github/stars/folkien/yaya?style=social"/> : YAYA - Yet annother YOLO annoter for images (in QT5). Support yolo format, image modifications, labeling and detecting with previously trained detector.

    - [pylabel-project/pylabel](https://github.com/pylabel-project/pylabel) <img src="https://img.shields.io/github/stars/pylabel-project/pylabel?style=social"/> : Python library for computer vision labeling tasks. The core functionality is to translate bounding box annotations between different formats-for example, from coco to yolo.

    - [opendatalab/labelU](https://github.com/opendatalab/labelU) <img src="https://img.shields.io/github/stars/opendatalab/labelU?style=social"/> : Uniform, Unlimited, Universal and Unbelievable Annotation Toolbox.




  - ### Feature Map Visualization
    #### 特征图可视化

    - [pooya-mohammadi/yolov5-gradcam](https://github.com/pooya-mohammadi/yolov5-gradcam) <img src="https://img.shields.io/github/stars/pooya-mohammadi/yolov5-gradcam?style=social"/> : Visualizing Yolov5's layers using GradCam.

    - [TorchCAM](https://github.com/frgfm/torch-cam) <img src="https://img.shields.io/github/stars/frgfm/torch-cam?style=social"/> : Class activation maps for your PyTorch models (CAM, Grad-CAM, Grad-CAM++, Smooth Grad-CAM++, Score-CAM, SS-CAM, IS-CAM, XGrad-CAM, Layer-CAM).

    - [Him-wen/OD_Heatmap](https://github.com/Him-wen/OD_Heatmap) <img src="https://img.shields.io/github/stars/Him-wen/OD_Heatmap?style=social"/> : Heatmap visualization of the YOLO model using the Grad-CAM heatmap visualization method can Intuitively show which regions in the image contribute the most to the category classification.



  - ### Object Detection Evaluation Metrics
    #### 目标检测性能评价指标

    - [rafaelpadilla/review_object_detection_metrics](https://github.com/rafaelpadilla/review_object_detection_metrics) <img src="https://img.shields.io/github/stars/rafaelpadilla/review_object_detection_metrics?style=social"/> : Object Detection Metrics. 14 object detection metrics: mean Average Precision (mAP), Average Recall (AR), Spatio-Temporal Tube Average Precision (STT-AP). This project supports different bounding box formats as in COCO, PASCAL, Imagenet, etc. "A Comparative Analysis of Object Detection Metrics with a Companion Open-Source Toolkit".  (**[Electronics 2021](https://www.mdpi.com/2079-9292/10/3/279)**)

    - [rafaelpadilla/Object-Detection-Metrics](https://github.com/rafaelpadilla/Object-Detection-Metrics) <img src="https://img.shields.io/github/stars/rafaelpadilla/Object-Detection-Metrics?style=social"/> : Most popular metrics used to evaluate object detection algorithms. "A Survey on Performance Metrics for Object-Detection Algorithms". (**[IWSSIP 2020](https://ieeexplore.ieee.org/abstract/document/9145130)**)

    - [Cartucho/mAP](https://github.com/Cartucho/mAP) <img src="https://img.shields.io/github/stars/Cartucho/mAP?style=social"/> : mean Average Precision - This code evaluates the performance of your neural net for object recognition.

    - [Lightning-AI/metrics](https://github.com/Lightning-AI/metrics) <img src="https://img.shields.io/github/stars/Lightning-AI/metrics?style=social"/> : Machine learning metrics for distributed, scalable PyTorch applications.

    - [open-mmlab/mmeval](https://github.com/open-mmlab/mmeval) <img src="https://img.shields.io/github/stars/open-mmlab/mmeval?style=social"/> : MMEval is a machine learning evaluation library that supports efficient and accurate distributed evaluation on a variety of machine learning frameworks.

    - [laclouis5/globox](https://github.com/laclouis5/globox) <img src="https://img.shields.io/github/stars/laclouis5/globox?style=social"/> : A package to read and convert object detection databases (COCO, YOLO, PascalVOC, LabelMe, CVAT, OpenImage, ...) and evaluate them with COCO and PascalVOC metrics.


  - ### GUI
    #### 图形用户界面

    - #### Swift-Related

        - [ultralytics/yolo-ios-app](https://github.com/ultralytics/yolo-ios-app) <img src="https://img.shields.io/github/stars/ultralytics/yolo-ios-app?style=social"/> : Ultralytics YOLO iOS App source code for running YOLOv8 in your own iOS apps 🌟. [ultralytics.com/yolo](https://ultralytics.com/yolo)


    - #### Flutter-Related

        - [ultralytics/yolo-flutter-app](https://github.com/ultralytics/yolo-flutter-app) <img src="https://img.shields.io/github/stars/ultralytics/yolo-flutter-app?style=social"/> : A Flutter plugin for Ultralytics YOLO computer vision models. [ultralytics.com](https://ultralytics.com/)

        - [hiennguyen92/flutter_realtime_object_detection](https://github.com/hiennguyen92/flutter_realtime_object_detection) <img src="https://img.shields.io/github/stars/hiennguyen92/flutter_realtime_object_detection?style=social"/> : Flutter App real-time object detection with Tensorflow Lite.





    - #### Streamlit-Related

        - [wjnwjn59/YOLOv10_Streamlit_Demo](https://github.com/wjnwjn59/YOLOv10_Streamlit_Demo) <img src="https://img.shields.io/github/stars/wjnwjn59/YOLOv10_Streamlit_Demo?style=social"/> : A simple object detection web demo using YOLOv10 and Streamlit.

        - [rampal-punia/yolov8-streamlit-detection-tracking](https://github.com/rampal-punia/yolov8-streamlit-detection-tracking) <img src="https://img.shields.io/github/stars/rampal-punia/yolov8-streamlit-detection-tracking?style=social"/> : Object detection and tracking algorithm implemented for Real-Time video streams and static images.

        - [JackDance/YOLOv8-streamlit-app](https://github.com/JackDance/YOLOv8-streamlit-app) <img src="https://img.shields.io/github/stars/JackDance/YOLOv8-streamlit-app?style=social"/> : 🔥🔥🔥 Use streamlit framework to increase yolov8 front-end page interaction function. "知乎「Mr.Luyao」《[深度学习/机器学习项目的前端展示利器--Streamlit](https://zhuanlan.zhihu.com/p/630029493)》"。

        - [streamlit/demo-self-driving](https://github.com/streamlit/demo-self-driving) <img src="https://img.shields.io/github/stars/streamlit/demo-self-driving?style=social"/> : Streamlit app demonstrating an image browser for the Udacity self-driving-car dataset with realtime object detection using YOLO.

        - [xugaoxiang/yolov5-streamlit](https://github.com/xugaoxiang/yolov5-streamlit) <img src="https://img.shields.io/github/stars/xugaoxiang/yolov5-streamlit?style=social"/> : Deploy YOLOv5 detection with Streamlit.

        - [Kedreamix/YoloGesture](https://github.com/Kedreamix/YoloGesture) <img src="https://img.shields.io/github/stars/Kedreamix/YoloGesture?style=social"/> : 基于计算机视觉手势识别控制系统YoLoGesture (利用YOLO实现)，利用yolo进行手势识别的控制系统，最后利用streamlit进行了部署。



    - #### Gradio-Related

        - [zyds/yolov5-code](https://github.com/zyds/yolov5-code) <img src="https://img.shields.io/github/stars/zyds/yolov5-code?style=social"/> : 手把手带你实战 YOLOv5。

        - [KdaiP/yolov8-deepsort-tracking](https://github.com/KdaiP/yolov8-deepsort-tracking) <img src="https://img.shields.io/github/stars/KdaiP/yolov8-deepsort-tracking?style=social"/> : opencv+yolov8+deepsort行人检测与跟踪,以及可选的WebUI界面（基于gradio）。

        - [pengxiang1998/YOLOv8](https://github.com/pengxiang1998/YOLOv8) <img src="https://img.shields.io/github/stars/pengxiang1998/YOLOv8?style=social"/> : 基于Gradio搭建的YOLOv8目标检测推理部署。




    - #### QT-Related

        - [Ai-trainee/Traffic-Sign-Recognition-PyQt5-YOLOv5-GUI](https://github.com/Ai-trainee/Traffic-Sign-Recognition-PyQt5-YOLOv5-GUI) <img src="https://img.shields.io/github/stars/Ai-trainee/Traffic-Sign-Recognition-PyQt5-YOLOv5-GUI?style=social"/> : Road Sign Recognition Project Based on YOLOv5. This is a road sign recognition project based on YOLOv5, developed with a PyQt5 interface, YOLOv5 trained model, and MySQL database. 这是一个基于YOLOv5🚀的道路标志识别系统😊，使用了MySQL数据库💽，PyQt5进行界面设计🎨，PyTorch深度学习框架和TensorRT进行加速⚡，同时包含了CSS样式🌈。系统由五个主要模块组成：系统登录模块🔑负责用户登陆；初始化参数模块📋提供YOLOv5模型的初始化参数设置；标志识别模块🔍是系统的核心，负责对道路标志进行识别并将结果导入数据库；数据库模块💾包含基本数据库操作和数据分析两个子模块；图像处理模块🖼️负责单个图像的处理和数据增强。整个系统支持多种数据输入和模型切换，提供了包括mossic和mixup在内的图像增强方法📈。

        - [parker-int64/yolov5-RGBD](https://github.com/parker-int64/yolov5-RGBD) <img src="https://img.shields.io/github/stars/parker-int64/yolov5-RGBD?style=social"/> : Qt QML based yolov5 + RGBD camera program.

        - [Aimol-l/qml_with_yolov7](https://github.com/Aimol-l/qml_with_yolov7) <img src="https://img.shields.io/github/stars/Aimol-l/qml_with_yolov7?style=social"/> : 用YOLOV7+ByteTrack的方法识别视频/视频流，用QML绘制GUI，并带有统计信息。

        - [xietx1995/YOLO-QT-Camera-Tool](https://github.com/xietx1995/YOLO-QT-Camera-Tool) <img src="https://img.shields.io/github/stars/xietx1995/YOLO-QT-Camera-Tool?style=social"/> : Detecting objects from camera or local video files vi qt and yolo.

        - [Javacr/PyQt5-YOLOv5](https://github.com/Javacr/PyQt5-YOLOv5) <img src="https://img.shields.io/github/stars/Javacr/PyQt5-YOLOv5?style=social"/> : YOLOv5检测界面-PyQt5实现。

        - [zstar1003/yolov5_pyqt5](https://github.com/zstar1003/yolov5_pyqt5) <img src="https://img.shields.io/github/stars/zstar1003/yolov5_pyqt5?style=social"/> : 这是一个使用pyqt5搭建YOLOv5目标检测可视化程序。

        - [scutlrr/Yolov4-QtGUI](https://github.com/scutlrr/Yolov4-QtGUI) <img src="https://img.shields.io/github/stars/scutlrr/Yolov4-QtGUI?style=social"/> : Yolov4-QtGUI是基于[QtGuiDemo](https://github.com/jmu201521121021/QtGuiDemo)项目开发的可视化目标检测界面，可以简便选择本地图片、摄像头来展示图像处理算法的结果。

        - [xugaoxiang/yolov5-pyqt5](https://github.com/xugaoxiang/yolov5-pyqt5) <img src="https://img.shields.io/github/stars/xugaoxiang/yolov5-pyqt5?style=social"/> : 给yolov5加个gui界面，使用pyqt5，yolov5是5.0版本。

        - [mxy493/YOLOv5-Qt](https://github.com/mxy493/YOLOv5-Qt) <img src="https://img.shields.io/github/stars/mxy493/YOLOv5-Qt?style=social"/> : 基于YOLOv5的GUI程序，支持选择要使用的权重文件，设置是否使用GPU，设置置信度阈值等参数。

        - [BonesCat/YoloV5_PyQt5](https://github.com/BonesCat/YoloV5_PyQt5) <img src="https://img.shields.io/github/stars/BonesCat/YoloV5_PyQt5?style=social"/> : Add gui for YoloV5 using PyQt5.

        - [LuckyBoy1798/yolov5-pyqt](https://github.com/LuckyBoy1798/yolov5-pyqt) <img src="https://img.shields.io/github/stars/LuckyBoy1798/yolov5-pyqt?style=social"/> : 基于yolov5+pyqt的甲骨文图形化检测工具。

        - [PySimpleGUI/PySimpleGUI-YOLO](https://github.com/PySimpleGUI/PySimpleGUI-YOLO) <img src="https://img.shields.io/github/stars/PySimpleGUI/PySimpleGUI-YOLO?style=social"/> : A YOLO Artificial Intelligence algorithm demonstration using PySimpleGUI.

        - [prabindh/qt5-opencv3-darknet](https://github.com/prabindh/qt5-opencv3-darknet) <img src="https://img.shields.io/github/stars/prabindh/qt5-opencv3-darknet?style=social"/> : Qt5 + Darknet/Yolo + OpenCV3.

        - [GinkgoX/YOLOv3GUI_Pytorch_PyQt5](https://github.com/GinkgoX/YOLOv3GUI_Pytorch_PyQt5) <img src="https://img.shields.io/github/stars/GinkgoX/YOLOv3GUI_Pytorch_PyQt5?style=social"/> : This is a GUI project for Deep Learning Object Detection based on YOLOv3 model.



        - [FatemeZamanian/Yolov5-Fruit-Detector](https://github.com/FatemeZamanian/Yolov5-Fruit-Detector) <img src="https://img.shields.io/github/stars/FatemeZamanian/Yolov5-Fruit-Detector?style=social"/> : A program to recognize fruits on pictures or videos using yolov5.

        - [BioMeasure/PyQt5_YoLoV5_DeepSort](https://github.com/BioMeasure/PyQt5_YoLoV5_DeepSort) <img src="https://img.shields.io/github/stars/BioMeasure/PyQt5_YoLoV5_DeepSort?style=social"/> : This is a PyQt5 GUI program, which is based on YoloV5 and DeepSort to track person.

        - [DongLizhong/YOLO_SORT_QT](https://github.com/DongLizhong/YOLO_SORT_QT) <img src="https://img.shields.io/github/stars/DongLizhong/YOLO_SORT_QT?style=social"/> : This code uses the opencv dnn module to load the darknet model for detection and add SORT for multi-object tracking(MOT).

        - [Whu-wxy/yolov5_deepsort_ncnn_qt](https://github.com/Whu-wxy/yolov5_deepsort_ncnn_qt) <img src="https://img.shields.io/github/stars/Whu-wxy/yolov5_deepsort_ncnn_qt?style=social"/> : 用ncnn调用yolov5和deep sort模型，opencv读取视频。

        - [jeswanthgalla/PyQt4_GUI_darknet_yolov4](https://github.com/jeswanthgalla/PyQt4_GUI_darknet_yolov4) <img src="https://img.shields.io/github/stars/jeswanthgalla/PyQt4_GUI_darknet_yolov4?style=social"/> : GUI App using PyQt4. Multithreading to process multiple camera streams and using darknet yolov4 model for object detection.

        - [barleo01/yoloobjectdetector](https://github.com/barleo01/yoloobjectdetector) <img src="https://img.shields.io/github/stars/barleo01/yoloobjectdetector?style=social"/> : The pupose of this application is to capture video from a camera, apply a YOLO Object detector and display it on a simple Qt Gui.

        - [Eagle104fred/PyQt5-Yolov5](https://github.com/Eagle104fred/PyQt5-Yolov5) <img src="https://img.shields.io/github/stars/Eagle104fred/PyQt5-Yolov5?style=social"/> : 把YOLOv5的视频显示到pyqt5ui上。

        - [cnyvfang/YOLOv5-GUI](https://github.com/cnyvfang/YOLOv5-GUI) <img src="https://img.shields.io/github/stars/Eagle104fred/PyQt5-Yolov5?style=social"/> : Qt-GUI implementation of the YOLOv5 algorithm (ver.6 and ver.5). YOLOv5算法(ver.6及ver.5)的Qt-GUI实现。

        - [WeNN-Artificial-Intelligence/PyQT-Object-Detection-App](https://github.com/WeNN-Artificial-Intelligence/PyQT-Object-Detection-App) <img src="https://img.shields.io/github/stars/WeNN-Artificial-Intelligence/PyQT-Object-Detection-App?style=social"/> : Real-time object detection app with Python and PyQt framework.

        - [Powercube7/YOLOv5-GUI](https://github.com/Powercube7/YOLOv5-GUI) <img src="https://img.shields.io/github/stars/Powercube7/YOLOv5-GUI?style=social"/> : A simple GUI made for creating jobs in YOLOv5.

        - [cdmstrong/yolov5-pyqt-moke](https://github.com/cdmstrong/yolov5-pyqt-moke) <img src="https://img.shields.io/github/stars/cdmstrong/yolov5-pyqt-moke?style=social"/> : 利用yolov5和pyqt做可视化检测。

        - [GHigher12/Pyqt5_yolov5_unet_centernet](https://github.com/GHigher12/Pyqt5_yolov5_unet_centernet) <img src="https://img.shields.io/github/stars/GHigher12/Pyqt5_yolov5_unet_centernet?style=social"/> : 集yolov5、centernet、unet算法的pyqt5界面，可实现图片目标检测和语义分割。

        - [chenanga/qt5_yolov5_2.0](https://github.com/chenanga/qt5_yolov5_2.0) <img src="https://img.shields.io/github/stars/chenanga/qt5_yolov5_2.0?style=social"/> : Pyqt搭建YOLOV5目标检测界面-第一次优化后的版本。

        - [xun-xh/yolov5-onnx-pyqt-exe](https://github.com/xun-xh/yolov5-onnx-pyqt-exe) <img src="https://img.shields.io/github/stars/xun-xh/yolov5-onnx-pyqt-exe?style=social"/> : 基于Yolov5 + PyQt5 + onnxruntime的目标检测部署。

        - [LPC1616/pyqt-yolox-modbus](https://github.com/LPC1616/pyqt-yolox-modbus) <img src="https://img.shields.io/github/stars/LPC1616/pyqt-yolox-modbus?style=social"/> : qt界面+yolox识别算法+modbus通信。

        - [zawawiAI/yolo_gpt](https://github.com/zawawiAI/yolo_gpt) <img src="https://img.shields.io/github/stars/zawawiAI/yolo_gpt?style=social"/> : This is a GUI application that integrates YOLOv8 object recognition with OpenAI's GPT-3 language generation model.

        - [LSH9832/yolov5_training_tool](https://github.com/LSH9832/yolov5_training_tool) <img src="https://img.shields.io/github/stars/LSH9832/yolov5_training_tool?style=social"/> : 本工具使用PYQT5编写界面。通过使用该工具可以快速部署相应数据集并训练，目前仍在不断更新中，较大的缺点是目前只支持PascalVOC格式的xml标签文件，所以其它格式的标签文件需要先转换为PascalVOC的格式，且目前仅适用于Linux系统且仅在Ubuntu16.04-20.04试运行。

        - [Egrt/YOLO_PyQt5](https://github.com/Egrt/YOLO_PyQt5) <img src="https://img.shields.io/github/stars/Egrt/YOLO_PyQt5?style=social"/> : 使用Pyqt5搭建YOLO系列多线程目标检测系统。

        - [smartwj/yolov5_pyqt5](https://github.com/smartwj/yolov5_pyqt5) <img src="https://img.shields.io/github/stars/smartwj/yolov5_pyqt5?style=social"/> : 基于yolov5的pyqt5目标检测图形上位机工具。

        - [LitChi-bit/YOLOv5-6.0-GUI](https://github.com/LitChi-bit/YOLOv5-6.0-GUI) <img src="https://img.shields.io/github/stars/LitChi-bit/YOLOv5-6.0-GUI?style=social"/> : Qt-GUI implementation of the YOLOv5 algorithm (ver.6).

        - [BraunGe/YOLOv5-GUI](https://github.com/BraunGe/YOLOv5-GUI) <img src="https://img.shields.io/github/stars/BraunGe/YOLOv5-GUI?style=social"/> : A GUI for YOLOv5, support all the 11 inference formats that YOLOv5 supports.

        - [PetervanLunteren/EcoAssist](https://github.com/PetervanLunteren/EcoAssist) <img src="https://img.shields.io/github/stars/PetervanLunteren/EcoAssist?style=social"/> : A no-code platform to train and deploy YOLOv5 object detection models.

        - [SwimmingLiu/yolov7-Pyside6](https://github.com/SwimmingLiu/yolov7-Pyside6) <img src="https://img.shields.io/github/stars/SwimmingLiu/yolov7-Pyside6?style=social"/> : PySide6 implementation of YOLOv7 GUI.


    - #### PySide-Related

        - [JSwimmingLiu/YOLOSHOW](https://github.com/SwimmingLiu/YOLOSHOW) <img src="https://img.shields.io/github/stars/SwimmingLiu/YOLOSHOW?style=social"/> : YOLO SHOW - YOLOv10 / YOLOv9 / YOLOv8 / YOLOv7 / YOLOv5 / RTDETR GUI based on Pyside6.[swimmingliu.cn/posts/diary/yoloshow](https://swimmingliu.cn/posts/diary/yoloshow)

        - [Jai-wei/YOLOv8-PySide6-GUI](https://github.com/Jai-wei/YOLOv8-PySide6-GUI) <img src="https://img.shields.io/github/stars/Jai-wei/YOLOv8-PySide6-GUI?style=social"/> : YoloSide - YOLOv8 GUI By PySide6.







  -         - [HAO7919/YOLOv5-VisionHub](https://github.com/HAO7919/YOLOv5-VisionHub) <img src="https://img.shields.io/github/stars/HAO7919/YOLOv5-VisionHub?style=social"/> : A free all-in-one YOLO desktop detection tool with no installation required. Supports images, videos, live camera, and real-time screen detection. Compatible with YOLOv5/v8/v9/v10/v11. Multi-language UI (9 languages), CPU/GPU auto-switch, adjustable parameters. Download the release package and double-click to run - no Python environment needed.
### Other Applications
    #### 其它应用

    - [Ikomia-dev/IkomiaApi](https://github.com/Ikomia-dev/IkomiaApi) <img src="https://img.shields.io/github/stars/Ikomia-dev/IkomiaApi?style=social"/> : State-of-the-art algorithms in Computer Vision with a few lines of code.

    - [penny4860/Yolo-digit-detector](https://github.com/penny4860/Yolo-digit-detector) <img src="https://img.shields.io/github/stars/penny4860/Yolo-digit-detector?style=social"/> : Implemented digit detector in natural scene using resnet50 and Yolo-v2. I used SVHN as the training set, and implemented it using tensorflow and keras.

    - [chineseocr/table-detect](https://github.com/chineseocr/table-detect) <img src="https://img.shields.io/github/stars/chineseocr/table-detect?style=social"/> : table detect(yolo) , table line(unet) （表格检测/表格单元格定位）。

    - [thisiszhou/SexyYolo](https://github.com/thisiszhou/SexyYolo) <img src="https://img.shields.io/github/stars/thisiszhou/SexyYolo?style=social"/> : An implementation of Yolov3 with Tensorflow1.x, which could detect COCO and sexy or porn person simultaneously.

    - [javirk/Person_remover](https://github.com/javirk/Person_remover) <img src="https://img.shields.io/github/stars/javirk/Person_remover?style=social"/> : People removal in images using Pix2Pix and YOLO.

    - [foschmitz/yolo-python-rtsp](https://github.com/foschmitz/yolo-python-rtsp) <img src="https://img.shields.io/github/stars/foschmitz/yolo-python-rtsp?style=social"/> : Object detection using deep learning with Yolo, OpenCV and Python via Real Time Streaming Protocol (RTSP).

    - [ismail-mebsout/Parsing-PDFs-using-YOLOV3](https://github.com/ismail-mebsout/Parsing-PDFs-using-YOLOV3) <img src="https://img.shields.io/github/stars/ismail-mebsout/Parsing-PDFs-using-YOLOV3?style=social"/> : Parsing pdf tables using YOLOV3.

    - [008karan/PAN_OCR](https://github.com/008karan/PAN_OCR) <img src="https://img.shields.io/github/stars/008karan/PAN_OCR?style=social"/> : Building OCR using YOLO and Tesseract.

    - [zeyad-mansour/lunar](https://github.com/zeyad-mansour/lunar) <img src="https://img.shields.io/github/stars/zeyad-mansour/lunar?style=social"/> : Lunar is a neural network aimbot that uses real-time object detection accelerated with CUDA on Nvidia GPUs.

    - [lannguyen0910/food-recognition](https://github.com/lannguyen0910/food-recognition) <img src="https://img.shields.io/github/stars/lannguyen0910/food-recognition?style=social"/> :  🍔🍟🍗 Food analysis baseline with Theseus. Integrate object detection, image classification and multi-class semantic segmentation. 🍞🍖🍕

    - [killnice/yolov5-D435i](https://github.com/killnice/yolov5-D435i) <img src="https://img.shields.io/github/stars/killnice/yolov5-D435i?style=social"/> : using yolov5 and realsense D435i.

    - [SahilChachra/Video-Analytics-Dashboard](https://github.com/SahilChachra/Video-Analytics-Dashboard) <img src="https://img.shields.io/github/stars/SahilChachra/Video-Analytics-Dashboard?style=social"/> : Video Analytics dashboard built using YoloV5 and Streamlit.

    - [isLinXu/YOLOv5_Efficient](https://github.com/isLinXu/YOLOv5_Efficient) <img src="https://img.shields.io/github/stars/isLinXu/YOLOv5_Efficient?style=social"/> : Use yolov5 efficiently(高效地使用Yolo v5).

    - [HRan2004/Yolo-ArbV2](https://github.com/HRan2004/Yolo-ArbV2) <img src="https://img.shields.io/github/stars/HRan2004/Yolo-ArbV2?style=social"/> : Yolo-ArbV2 在完全保持YOLOv5功能情况下，实现可选多边形信息输出。

    - [Badw0lf613/wmreading_system](https://github.com/Badw0lf613/wmreading_system) <img src="https://img.shields.io/github/stars/Badw0lf613/wmreading_system?style=social"/> : 基于YOLOv5的水表读数系统。

    - [zgcr/SimpleAICV-pytorch-ImageNet-COCO-training](https://github.com/zgcr/SimpleAICV-pytorch-ImageNet-COCO-training) <img src="https://img.shields.io/github/stars/zgcr/SimpleAICV-pytorch-ImageNet-COCO-training?style=social"/> : SimpleAICV:pytorch training example on ImageNet(ILSVRC2012)/COCO2017/VOC2007+2012 datasets.Include ResNet/DarkNet/RetinaNet/FCOS/CenterNet/TTFNet/YOLOv3/YOLOv4/YOLOv5/YOLOX.

    - [ErenKaymakci/Real-Time-QR-Detection-and-Decoding](https://github.com/ErenKaymakci/Real-Time-QR-Detection-and-Decoding) <img src="https://img.shields.io/github/stars/ErenKaymakci/Real-Time-QR-Detection-and-Decoding?style=social"/> : This repo explain how qr codes works, qr detection and decoding.

    - [LUMAIS/AntDet_YOLOv5](https://github.com/LUMAIS/AntDet_YOLOv5) <img src="https://img.shields.io/github/stars/LUMAIS/AntDet_YOLOv5?style=social"/> : Ants and their Activiteis (Trophallaxis) Detection using YOLOv5 based on PyTorch.

    - [Jiseong-Ok/OCR-Yolov5-SwinIR-SVTR](https://github.com/Jiseong-Ok/OCR-Yolov5-SwinIR-SVTR) <img src="https://img.shields.io/github/stars/Jiseong-Ok/OCR-Yolov5-SwinIR-SVTR?style=social"/> : OCR(Korean).

    - [QIN2DIM/hcaptcha-challenger](https://github.com/QIN2DIM/hcaptcha-challenger) <img src="https://img.shields.io/github/stars/QIN2DIM/hcaptcha-challenger?style=social"/> : 🥂 Gracefully face hCaptcha challenge with YOLOv6(ONNX) embedded solution.

    - [bobjiangps/vision](https://github.com/bobjiangps/vision) <img src="https://img.shields.io/github/stars/bobjiangps/vision?style=social"/> : UI auto test framework based on YOLO to recognize elements, less code, less maintenance, cross platform, cross project / 基于YOLO的UI层自动化测试框架, 可识别控件类型，减少代码和维护，一定程度上跨平台跨项目。

    - [RizwanMunawar/yolov7-object-cropping](https://github.com/RizwanMunawar/yolov7-object-cropping) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov7-object-cropping?style=social"/> : YOLOv7 Object Cropping Using OpenCV.

    - [RizwanMunawar/yolov7-object-blurring](https://github.com/RizwanMunawar/yolov7-object-blurring) <img src="https://img.shields.io/github/stars/RizwanMunawar/yolov7-object-blurring?style=social"/> : YOLOv7 Object Blurring Using PyTorch and OpenCV.

    - [pacocp/YOLOF](https://github.com/pacocp/YOLOF) <img src="https://img.shields.io/github/stars/pacocp/YOLOF?style=social"/> : 📹 YOLO meets Optical Flow.

    - [FabianPlum/OmniTrax](https://github.com/FabianPlum/OmniTrax) <img src="https://img.shields.io/github/stars/FabianPlum/OmniTrax?style=social"/> : Deep learning-based multi animal tracking and pose estimation Blender Add-on.

    - [aweihao/ExDark2Yolo](https://github.com/aweihao/ExDark2Yolo) <img src="https://img.shields.io/github/stars/aweihao/ExDark2Yolo?style=social"/> : Convert ExDark annotated format data to YOLO format data. / 将ExDark标注格式的数据转换成YOLO格式的数据。

    - [ozankaraali/yolov3-recaptcha](https://github.com/ozankaraali/yolov3-recaptcha) <img src="https://img.shields.io/github/stars/ozankaraali/yolov3-recaptcha?style=social"/> : Solve Recaptcha with YoloV3. A proof of concept Recaptcha solver using YOLOv3 on Tensorflow 2.0 and Selenium. This tutorial shows that with a better trained object detection weight file, ReCaptcha can be easily solved.

    - [jyp-studio/Invoice_detection](https://github.com/jyp-studio/Invoice_detection) <img src="https://img.shields.io/github/stars/jyp-studio/Invoice_detection?style=social"/> : This is an AI model for detecting and recognizing invoice information by yolov5 and OCR.

    - [vmc-7645/YOLOv8-retail](https://github.com/vmc-7645/YOLOv8-retail) <img src="https://img.shields.io/github/stars/vmc-7645/YOLOv8-retail?style=social"/> : Detect retail products via the YOLOv8 object recognition engine.

    - [TAber-W/RM_4-points_yolov5](https://github.com/TAber-W/RM_4-points_yolov5) <img src="https://img.shields.io/github/stars/TAber-W/RM_4-points_yolov5?style=social"/> : Robomaster 基于yoloface和MobileNet修改的四点模型.

    - [eternal-echo/picking](https://github.com/eternal-echo/picking) <img src="https://img.shields.io/github/stars/eternal-echo/picking?style=social"/> : 基于YOLO v5视觉分拣零件系统设计。

    - [swordswind/yolo_ocr_api_server](https://github.com/swordswind/yolo_ocr_api_server) <img src="https://img.shields.io/github/stars/swordswind/yolo_ocr_api_server?style=social"/> : YOLOv10&EasyOCR融合图像识别API服务器。



## Object Detection Datasets

- ### Datasets Share Platform

    - [OpenDataLab](https://opendatalab.org.cn/) : OpenDataLab 是上海人工智能实验室的大模型数据基座团队打造的数据开放平台，现已成为中国大模型语料数据联盟开源数据服务指定平台，为开发者提供全链条的 AI 数据支持，应对和解决数据处理中的风险与挑战，推动 AI 研究及应用。

    - [Science Data Bank(ScienceDB)](https://www.scidb.cn/en) : Make your research data citable, discoverable and persistently accessible Satisfy flexible data sharing requirements Dedicate to facilitating data dissemination and reusing. Science Data Bank (ScienceDB) is a public, general-purpose data repository aiming to provide data services (e.g. data acquisition, long-term preservation, publishing, sharing and access) for researchers, research projects/teams, journals, institutions, universities, etc. It supports a variety of data acquisition and data licenses. ScienceDB is dedicated to promoting data findable, citable and reusable on the prerequisite of protecting the rights and interests of data owners and it is built and operated by Computer Network Information Center, Chinese Academy of Sciences.

    - [中国科学数据](http://www.csdata.org/) : 《中国科学数据（中英文网络版）》（China Scientific Data）（CN11-6035/N，ISSN 2096-2223）是目前中国唯一的专门面向多学科领域科学数据出版的学术期刊，作为国家网络连续型出版物的首批试点之一，由中国科学院主管，中国科学院计算机网络信息中心和ISC CODATA中国全国委员会合办，国家科技基础条件平台中心、中国科学院网络安全和信息化领导小组办公室指导，国内外公开发行，中英文，季刊。 中国科学引文数据库（CSCD）来源期刊，中国科技核心期刊 ，收录于中国科协高质量科技期刊分级目录。

    - [飞桨AI Studio](https://aistudio.baidu.com/aistudio/datasetoverview) : 飞桨AI Studio开放数据集。

    - [极市开发者平台](https://www.cvmart.net/dataSets) : 极市开发者平台开放数据集。

    - [openvinotoolkit/datumaro](https://github.com/openvinotoolkit/datumaro) <img src="https://img.shields.io/github/stars/openvinotoolkit/datumaro?style=social"/> : Dataset Management Framework, a Python library and a CLI tool to build, analyze and manage Computer Vision datasets.




- ### Datasets Tools

    - #### Data Annotation

        - [Label Studio](https://github.com/HumanSignal/label-studio) <img src="https://img.shields.io/github/stars/HumanSignal/label-studio?style=social"/> : Label Studio is a multi-type data labeling and annotation tool with standardized output format. [labelstud.io](https://labelstud.io/)

        - [X-AnyLabeling](https://github.com/CVHub520/X-AnyLabeling) <img src="https://img.shields.io/github/stars/CVHub520/X-AnyLabeling?style=social"/> : Effortless data labeling with AI support from Segment Anything and other awesome models.

        - [AnyLabeling](https://github.com/vietanhdev/anylabeling) <img src="https://img.shields.io/github/stars/vietanhdev/anylabeling?style=social"/> : Effortless AI-assisted data labeling with AI support from YOLO, Segment Anything (SAM+SAM2), MobileSAM!! AnyLabeling = LabelImg + Labelme + Improved UI + Auto-labeling. [anylabeling.nrl.ai](https://anylabeling.nrl.ai/)

        - [SAMLabelerPro](https://github.com/LSH9832/SAMLabelerPro) <img src="https://img.shields.io/github/stars/LSH9832/SAMLabelerPro?style=social"/> : label your image with Segment Anything Model or MobileSAM, support remote labeling for multiple persons。使用Segment Anything Model或MobileSAM辅助标注的工具，支持多人远程标注。

        - [LabelImg](https://github.com/heartexlabs/labelImg) <img src="https://img.shields.io/github/stars/heartexlabs/labelImg?style=social"/> : 🖍️ LabelImg is a graphical image annotation tool and label object bounding boxes in images.

        - [labelme](https://github.com/wkentaro/labelme) <img src="https://img.shields.io/github/stars/wkentaro/labelme?style=social"/> : Image Polygonal Annotation with Python (polygon, rectangle, circle, line, point and image-level flag annotation).

        - [DarkLabel](https://github.com/darkpgmr/DarkLabel) <img src="https://img.shields.io/github/stars/darkpgmr/DarkLabel?style=social"/> : Video/Image Labeling and Annotation Tool.

        - [AlexeyAB/Yolo_mark](https://github.com/AlexeyAB/Yolo_mark) <img src="https://img.shields.io/github/stars/AlexeyAB/Yolo_mark?style=social"/> : GUI for marking bounded boxes of objects in images for training neural network Yolo v3 and v2.

        - [Cartucho/OpenLabeling](https://github.com/Cartucho/OpenLabeling) <img src="https://img.shields.io/github/stars/Cartucho/OpenLabeling?style=social"/> : Label images and video for Computer Vision applications.

        - [CVAT](https://github.com/cvat-ai/cvat) <img src="https://img.shields.io/github/stars/cvat-ai/cvat?style=social"/> : Computer Vision Annotation Tool (CVAT). Annotate better with CVAT, the industry-leading data engine for machine learning. Used and trusted by teams at any scale, for data of any scale.

        - [VoTT](https://github.com/Microsoft/VoTT) <img src="https://img.shields.io/github/stars/Microsoft/VoTT?style=social"/> : Visual Object Tagging Tool: An electron app for building end to end Object Detection Models from Images and Videos.

        - [WangRongsheng/KDAT](https://github.com/WangRongsheng/KDAT) <img src="https://img.shields.io/github/stars/WangRongsheng/KDAT?style=social"/> : 一个专为视觉方向目标检测全流程的标注工具集，全称：Kill Object Detection Annotation Tools。

        - [Rectlabel-support](https://github.com/ryouchinsa/Rectlabel-support) <img src="https://img.shields.io/github/stars/ryouchinsa/Rectlabel-support?style=social"/> : RectLabel - An image annotation tool to label images for bounding box object detection and segmentation.

        - [cnyvfang/labelGo-Yolov5AutoLabelImg](https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg) <img src="https://img.shields.io/github/stars/cnyvfang/labelGo-Yolov5AutoLabelImg?style=social"/> : 💕YOLOV5 semi-automatic annotation tool (Based on labelImg)💕一个基于labelImg及YOLOV5的图形化半自动标注工具。

        - [CVUsers/Auto_maker](https://github.com/CVUsers/Auto_maker) <img src="https://img.shields.io/github/stars/CVUsers/Auto_maker?style=social"/> : 深度学习数据自动标注器开源 目标检测和图像分类（高精度高效率）。

        - [MyVision](https://github.com/OvidijusParsiunas/myvision) <img src="https://img.shields.io/github/stars/OvidijusParsiunas/myvision?style=social"/> : Computer vision based ML training data generation tool 🚀

        - [wufan-tb/AutoLabelImg](https://github.com/wufan-tb/AutoLabelImg) <img src="https://img.shields.io/github/stars/wufan-tb/AutoLabelImg?style=social"/> : auto-labelimg based on yolov5, with many other useful tools. AutoLabelImg 多功能自动标注工具。

        - [MrZander/YoloMarkNet](https://github.com/MrZander/YoloMarkNet) <img src="https://img.shields.io/github/stars/MrZander/YoloMarkNet?style=social"/> : Darknet YOLOv2/3 annotation tool written in C#/WPF.

        - [mahxn0/Yolov3_ForTextLabel](https://github.com/mahxn0/Yolov3_ForTextLabel) <img src="https://img.shields.io/github/stars/mahxn0/Yolov3_ForTextLabel?style=social"/> : 基于yolov3的目标/自然场景文字自动标注工具。

        - [MNConnor/YoloV5-AI-Label](https://github.com/MNConnor/YoloV5-AI-Label) <img src="https://img.shields.io/github/stars/MNConnor/YoloV5-AI-Label?style=social"/> : YoloV5 AI Assisted Labeling.

        - [LILINOpenGitHub/Labeling-Tool](https://github.com/LILINOpenGitHub/Labeling-Tool) <img src="https://img.shields.io/github/stars/LILINOpenGitHub/Labeling-Tool?style=social"/> : Free YOLO AI labeling tool. YOLO AI labeling tool is a Windows app for labeling YOLO dataset.

        - [whs0523003/YOLOv5_6.1_autolabel](https://github.com/whs0523003/YOLOv5_6.1_autolabel) <img src="https://img.shields.io/github/stars/whs0523003/YOLOv5_6.1_autolabel?style=social"/> : YOLOv5_6.1 自动标记目标框。

        - [2vin/PyYAT](https://github.com/2vin/PyYAT) <img src="https://img.shields.io/github/stars/2vin/PyYAT?style=social"/> : Semi-Automatic Yolo Annotation Tool In Python.

        - [AlturosDestinations/Alturos.ImageAnnotation](https://github.com/AlturosDestinations/Alturos.ImageAnnotation) <img src="https://img.shields.io/github/stars/AlturosDestinations/Alturos.ImageAnnotation?style=social"/> : A collaborative tool for labeling image data for yolo.

        - [stephanecharette/DarkMark](https://github.com/stephanecharette/DarkMark) <img src="https://img.shields.io/github/stars/stephanecharette/DarkMark?style=social"/> : Marking up images for use with Darknet.

        - [2vin/yolo_annotation_tool](https://github.com/2vin/yolo_annotation_tool) <img src="https://img.shields.io/github/stars/2vin/yolo_annotation_tool?style=social"/> : Annotation tool for YOLO in opencv.

        - [sanfooh/quick_yolo2_label_tool](https://github.com/sanfooh/quick_yolo2_label_tool) <img src="https://img.shields.io/github/stars/sanfooh/quick_yolo2_label_tool?style=social"/> : yolo快速标注工具 quick yolo2 label tool.

        - [folkien/yaya](https://github.com/folkien/yaya) <img src="https://img.shields.io/github/stars/folkien/yaya?style=social"/> : YAYA - Yet annother YOLO annoter for images (in QT5). Support yolo format, image modifications, labeling and detecting with previously trained detector.

        - [pylabel-project/pylabel](https://github.com/pylabel-project/pylabel) <img src="https://img.shields.io/github/stars/pylabel-project/pylabel?style=social"/> : Python library for computer vision labeling tasks. The core functionality is to translate bounding box annotations between different formats-for example, from coco to yolo.

        - [opendatalab/labelU](https://github.com/opendatalab/labelU) <img src="https://img.shields.io/github/stars/opendatalab/labelU?style=social"/> : Uniform, Unlimited, Universal and Unbelievable Annotation Toolbox.


    - #### Data Augmentation

      - [Albumentations](https://github.com/albumentations-team/albumentations) <img src="https://img.shields.io/github/stars/albumentations-team/albumentations?style=social"/> : Albumentations is a Python library for image augmentation. Image augmentation is used in deep learning and computer vision tasks to increase the quality of trained models. The purpose of image augmentation is to create new training samples from the existing data. "Albumentations: Fast and Flexible Image Augmentations". (**[Information 2020](https://www.mdpi.com/2078-2489/11/2/125)**). [albumentations.ai](https://albumentations.ai/)

      - [doubleZ0108/Data-Augmentation](https://github.com/doubleZ0108/Data-Augmentation) <img src="https://img.shields.io/github/stars/doubleZ0108/Data-Augmentation?style=social"/> : General Data Augmentation Algorithms for Object Detection(esp. Yolo).




    - #### Data Management

      - [YOLOExplorer](https://github.com/lancedb/yoloexplorer) <img src="https://img.shields.io/github/stars/lancedb/yoloexplorer?style=social"/> : YOLOExplorer : Iterate on your YOLO / CV datasets using SQL, Vector semantic search, and more within seconds. Explore, manipulate and iterate on Computer Vision datasets with precision using simple APIs. Supports SQL filters, vector similarity search, native interface with Pandas and more.



- ### General Detection and Recognition Datasets

    - #### General Object Detection Datasets

        - [COCO](https://cocodataset.org/) : "Microsoft COCO: Common Objects in Context". (**[ECCV 2014](https://link.springer.com/chapter/10.1007/978-3-319-10602-1_48)**)

        - [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/) : "The Pascal Visual Object Classes Challenge: A Retrospective". (**[IJCV 2015](https://link.springer.com/article/10.1007/s11263-014-0733-5)**)

        - [Objects365](http://www.objects365.org/overview.html) : "Objects365: A Large-scale, High-quality Dataset for Object Detection". (**[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/html/Shao_Objects365_A_Large-Scale_High-Quality_Dataset_for_Object_Detection_ICCV_2019_paper.html)**)

        - [V3Det](https://v3det.openxlab.org.cn/) : "V3Det: Vast Vocabulary Visual Detection Dataset". (**[arXiv 2023](https://arxiv.org/abs/2304.03752)**)

        - [ODverse33](https://github.com/SkyCol/ODverse33) <img src="https://img.shields.io/github/stars/SkyCol/ODverse33?style=social"/> : "ODverse33: Is the New YOLO Version Always Better? A Multi Domain benchmark from YOLO v5 to v11". (**[arXiv 2025](https://arxiv.org/abs/2502.14314)**)


    - #### General Object Recognition Datasets

        - [ImageNet](https://image-net.org/challenges/LSVRC/) : "ImageNet Large Scale Visual Recognition Challenge". (**[IJCV 2015](https://link.springer.com/article/10.1007/s11263-015-0816-y)**)




- ### Autonomous Driving Datasets

    - #### Diverse Autonomous Driving Datasets

        - [BDD100K](https://bdd-data.berkeley.edu/) : "BDD100K: A Diverse Driving Dataset for Heterogeneous Multitask Learning". (**[CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Yu_BDD100K_A_Diverse_Driving_Dataset_for_Heterogeneous_Multitask_Learning_CVPR_2020_paper.html)**)

        - [CODA](https://coda-dataset.github.io/) : "CODA: A Real-World Road Corner Case Dataset for Object Detection in Autonomous Driving". (**[ECCV 2022](https://link.springer.com/chapter/10.1007/978-3-031-19839-7_24)**)



    - #### Traffic Sign Detection Datasets

        - [TT100K](http://cg.cs.tsinghua.edu.cn/traffic-sign/) : "Traffic-Sign Detection and Classification in the Wild". (**[CVPR 2016](https://openaccess.thecvf.com/content_cvpr_2016/html/Zhu_Traffic-Sign_Detection_and_CVPR_2016_paper.html)**)

        - [CCTSDB](https://github.com/csust7zhangjm/CCTSDB) <img src="https://img.shields.io/github/stars/csust7zhangjm/CCTSDB?style=social"/> : CSUST Chinese Traffic Sign Detection Benchmark 中国交通数据集由长沙理工大学综合交通运输大数据智能处理湖南省重点实验室张建明老师团队制作完成。 "A Real-Time Chinese Traffic Sign Detection Algorithm Based on Modified YOLOv2". (**[Algorithms, 2017](https://www.mdpi.com/1999-4893/10/4/127)**)

        - [CCTSDB2021](https://github.com/csust7zhangjm/CCTSDB2021) <img src="https://img.shields.io/github/stars/csust7zhangjm/CCTSDB2021?style=social"/> : "CCTSDB 2021: a more comprehensive traffic sign detection benchmark". (**[Human-centric Computing and Information Sciences, 2022](https://centaur.reading.ac.uk/106129/)**)


    - #### License Plate Detection and Recognition Datasets

        - [CCPD](https://github.com/detectRecog/CCPD) <img src="https://img.shields.io/github/stars/csust7zhangjm/CCTSDB2021?style=social"/> : "Towards End-to-End License Plate Detection and Recognition: A Large Dataset and Baseline". (**[ECCV 2018](https://openaccess.thecvf.com/content_ECCV_2018/html/Zhenbo_Xu_Towards_End-to-End_License_ECCV_2018_paper.html)**)





- ### Adverse Weather Datasets

    - [RESID](https://sites.google.com/site/boyilics/website-builder/reside) : "Benchmarking Single-Image Dehazing and Beyond". (**[IEEE Transactions on Image Processing 2018](https://ieeexplore.ieee.org/abstract/document/8451944)**)




- ### Person Detection Datasets

    - [INRIA Person](http://lear.inrialpes.fr/data) : "Histograms of oriented gradients for human detection". (**[CVPR 2005](https://ieeexplore.ieee.org/abstract/document/1467360)**)

    - [CrowdHuman](http://www.crowdhuman.org/) : "CrowdHuman: A Benchmark for Detecting Human in a Crowd". (**[arXiv 2018](https://arxiv.org/abs/1805.00123)**)

    - [PANDA](http://www.panda-dataset.com) : "PANDA: A Gigapixel-Level Human-Centric Video Dataset". (**[CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_PANDA_A_Gigapixel-Level_Human-Centric_Video_Dataset_CVPR_2020_paper.html)**)

    - [TinyPerson](https://github.com/ucas-vg/PointTinyBenchmark) <img src="https://img.shields.io/github/stars/ucas-vg/PointTinyBenchmark?style=social"/> : "Scale Match for Tiny Person Detection". (**[WACV 2020](https://openaccess.thecvf.com/content_WACV_2020/html/Yu_Scale_Match_for_Tiny_Person_Detection_WACV_2020_paper.html)**)

    - [TinyPerson v2 | SeaPerson](https://github.com/ucas-vg/PointTinyBenchmark) <img src="https://img.shields.io/github/stars/ucas-vg/PointTinyBenchmark?style=social"/> : "Object Localization Under Single Coarse Point Supervision". (**[CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Yu_Object_Localization_Under_Single_Coarse_Point_Supervision_CVPR_2022_paper.html)**)


    ## Anti-UAV Datasets

    - [Anti-UAV](https://github.com/ZhaoJ9014/Anti-UAV) <img src="https://img.shields.io/github/stars/ZhaoJ9014/Anti-UAV?style=social"/> : 🔥🔥Official Repository for Anti-UAV🔥🔥. Anti-UAV300, Anti-UAV410, Anti-UAV600. Please refer to our [Anti-UAV v1](https://ieeexplore.ieee.org/document/9615243) paper and [Anti-UAV v3](https://arxiv.org/pdf/2306.15767.pdf) paper for more details ([WeChat News](https://zhaoj9014.github.io/pub/Anti-UAV.pdf)). "Anti-UAV: A Large-Scale Benchmark for Vision-Based UAV Tracking". (**[IEEE Transactions on Multimedia, 2022](https://ieeexplore.ieee.org/document/9615243)**). "Evidential Detection and Tracking Collaboration: New Problem, Benchmark and Algorithm for Robust Anti-UAV System". (**[arXiv 2023](https://arxiv.org/abs/2306.15767)**).

    - [DUT-Anti-UAV](https://github.com/wangdongdut/DUT-Anti-UAV) <img src="https://img.shields.io/github/stars/wangdongdut/DUT-Anti-UAV?style=social"/> : DUT Anti-UAV Detection and Tracking. "Vision-based Anti-UAV Detection and Tracking". (**[IEEE Transactions on Intelligent Transportation Systems, 2022](https://arxiv.org/abs/2205.10851)**).




- ### Optical Aerial Imagery Datasets

    - [COWC](https://github.com/LLNL/cowc) <img src="https://img.shields.io/github/stars/LLNL/cowc?style=social"/> : "A large contextual dataset for classification, detection and counting of cars with deep learning". (**[ECCV 2016](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_48)**)

    - [RSOD](https://github.com/RSIA-LIESMARS-WHU/RSOD-Dataset-) <img src="https://img.shields.io/github/stars/RSIA-LIESMARS-WHU/RSOD-Dataset-?style=social"/> : "Accurate object localization in remote sensing images based on convolutional neural networks". (**[IEEE TGRS 2017](https://ieeexplore.ieee.org/abstract/document/7827088/)**)

    - [LEVIR](http://levir.buaa.edu.cn/Code.htm) : "Random access memories: A new paradigm for target detection in high resolution aerial remote sensing images". (**[IEEE Transactions on Image Processing 2017](https://ieeexplore.ieee.org/abstract/document/8106808)**)

    - [LEVIR-Ship](https://github.com/WindVChen/LEVIR-Ship) <img src="https://img.shields.io/github/stars/WindVChen/LEVIR-Ship?style=social"/> : "A Degraded Reconstruction Enhancement-based Method for Tiny Ship Detection in Remote Sensing Images with A New Large-scale Dataset". (**[IEEE TGRS 2022](https://ieeexplore.ieee.org/abstract/document/9791363)**)

    - [MASATI](https://www.iuii.ua.es/datasets/masati/) : "Automatic ship classification from optical aerial images with convolutional neural networks". (**[Remote Sensing 2018](https://www.mdpi.com/2072-4292/10/4/511)**)

    - [xView](http://xviewdataset.org/) : "xView: Objects in Context in Overhead Imagery". (**[arXiv 2018](https://arxiv.org/abs/1802.07856)**)

    - [DOTA](https://captain-whu.github.io/DOTA/) : "DOTA: A Large-Scale Dataset for Object Detection in Aerial Images". (**[CVPR 2018](https://openaccess.thecvf.com/content_cvpr_2018/html/Xia_DOTA_A_Large-Scale_CVPR_2018_paper.html)**). "Object Detection in Aerial Images: A Large-Scale Benchmark and Challenges". (**[IEEE TPAMI 2021](https://ieeexplore.ieee.org/abstract/document/9560031)**).

    - [ITCVD](https://research.utwente.nl/en/datasets/itcvd-dataset) : "Deep Learning for Vehicle Detection in Aerial Images". (**[IEEE ICIP 2018](https://ieeexplore.ieee.org/abstract/document/8451454)**)

    - [Bridge Dataset](http://www.patreo.dcc.ufmg.br/2019/07/10/bridge-dataset/) : "A Tool for Bridge Detection in Major Infrastructure Works Using Satellite Images". (**[IEEE ICIP 2018](https://ieeexplore.ieee.org/abstract/document/8876942)**)

    - [DIOR](http://www.escience.cn/people/JunweiHan/DIOR.html) : "Object detection in optical remote sensing images: A survey and a new benchmark". (**[ISPRS 2020](https://www.sciencedirect.com/science/article/abs/pii/S0924271619302825)**)

    - [PESMOD](https://github.com/mribrahim/PESMOD) <img src="https://img.shields.io/github/stars/mribrahim/PESMOD?style=social"/> : "UAV Images Dataset for Moving Object Detection from Moving Cameras". (**[arXiv 2021](https://arxiv.org/abs/2103.11460)**)

    - [AI-TOD](https://github.com/jwwangchn/AI-TOD) <img src="https://img.shields.io/github/stars/jwwangchn/AI-TOD?style=social"/> : "Tiny Object Detection in Aerial Images". (**[IEEE ICPR 2021](https://ieeexplore.ieee.org/abstract/document/9413340)**)

    - [RsCarData](https://github.com/ChaoXiao12/Moving-object-detection-DSFNet) <img src="https://img.shields.io/github/stars/ChaoXiao12/Moving-object-detection-DSFNet?style=social"/> : "DSFNet: Dynamic and Static Fusion Network for Moving Object Detection in Satellite Videos". (**[IEEE GRSL 2021](https://ieeexplore.ieee.org/abstract/document/9594855)**)

    - [VISO](https://github.com/The-Learning-And-Vision-Atelier-LAVA/VISO) <img src="https://img.shields.io/github/stars/The-Learning-And-Vision-Atelier-LAVA/VISO?style=social"/> : "Detecting and Tracking Small and Dense Moving Objects in Satellite Videos: A Benchmark". (**[IEEE TGRS 2021](https://ieeexplore.ieee.org/abstract/document/9625976)**)

    - [VisDrone](https://github.com/VisDrone/VisDrone-Dataset) <img src="https://img.shields.io/github/stars/VisDrone/VisDrone-Dataset?style=social"/> : "Detection and Tracking Meet Drones Challenge". (**[IEEE TPAMI 2021](https://ieeexplore.ieee.org/abstract/document/9573394)**)

    - [FAIR1M](http://gaofen-challenge.com/benchmark) : "FAIR1M: A benchmark dataset for fine-grained object recognition in high-resolution remote sensing imagery". (**[ISPRS 2021](https://www.sciencedirect.com/science/article/abs/pii/S0924271621003269)**)

    - [SeaDronesSee](https://github.com/Ben93kie/SeaDronesSee) <img src="https://img.shields.io/github/stars/Ben93kie/SeaDronesSee?style=social"/> : "SeaDronesSee: A Maritime Benchmark for Detecting Humans in Open Water". (**[WACV 2022](https://openaccess.thecvf.com/content/WACV2022/html/Varga_SeaDronesSee_A_Maritime_Benchmark_for_Detecting_Humans_in_Open_Water_WACV_2022_paper.html)**)




- ### Low-light Image Datasets

    - [NightOwls](https://www.nightowls-dataset.org/) : "NightOwls: A Pedestrians at Night Dataset". (**[ACCV 2018](https://link.springer.com/chapter/10.1007/978-3-030-20887-5_43)**).

    - [ExDark](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset) <img src="https://img.shields.io/github/stars/cs-chan/Exclusively-Dark-Image-Dataset?style=social"/> : "Getting to know low-light images with the exclusively dark dataset". (**[CVIU 2019](https://www.sciencedirect.com/science/article/abs/pii/S1077314218304296)**). "Low-light image enhancement using Gaussian Process for features retrieval". (**[Signal Processing: Image Communication, 2019](https://www.sciencedirect.com/science/article/abs/pii/S0923596518310452)**).

    - [DARK FACE](https://flyywh.github.io/CVPRW2019LowLight/) : DARK FACE: Face Detection in Low Light Condition. "Advancing Image Understanding in Poor Visibility Environments: A Collective Benchmark Study". (**[IEEE Transactions on Image Processing 2020](https://ieeexplore.ieee.org/abstract/document/9049390/)**).




- ### Infrared Image Datasets

    - [地/空背景下红外图像弱小飞机目标检测跟踪数据集](https://www.scidb.cn/en/detail?dataSetId=720626420933459968) (**[中国科学数据, 2020](http://www.csdata.org/p/387/)**)

    - [复杂背景下红外弱小运动目标检测数据集](https://www.scidb.cn/en/detail?dataSetId=808025946870251520) (**[中国科学数据, 2021](http://www.csdata.org/p/553/)**)

    - [面向空地应用的红外时敏目标检测跟踪数据集](https://www.scidb.cn/en/detail?dataSetId=de971a1898774dc5921b68793817916e) (**[中国科学数据, 2022](http://www.csdata.org/p/673/)**)

    - [SCUT_FIR_Pedestrian_Dataset](https://github.com/SCUT-CV/SCUT_FIR_Pedestrian_Dataset) <img src="https://img.shields.io/github/stars/SCUT-CV/SCUT_FIR_Pedestrian_Dataset?style=social"/> : "Benchmarking a large-scale FIR dataset for on-road pedestrian detection". (**[Infrared Physics & Technology, 2019](https://www.sciencedirect.com/science/article/abs/pii/S1350449518305589)**)

    - [NUDT-SIRST](https://github.com/YeRen123455/Infrared-Small-Target-Detection) <img src="https://img.shields.io/github/stars/YeRen123455/Infrared-Small-Target-Detection?style=social"/> : "Dense Nested Attention Network for Infrared Small Target Detection". (**[arXiv 2021](https://arxiv.org/abs/2106.00487)**)

    - [SIRST](https://github.com/YimianDai/sirst) <img src="https://img.shields.io/github/stars/YimianDai/sirst?style=social"/> : "Asymmetric Contextual Modulation for Infrared Small Target Detection". (**[WACV 2021](https://openaccess.thecvf.com/content/WACV2021/html/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.html)**)




- ### SAR Image Datasets

    - [SNL VideoSAR](https://www.sandia.gov/radar/pathfinder-radar-isr-and-synthetic-aperture-radar-sar-systems/video/) : "Developments in sar and ifsar systems and technologies at sandia national laboratories". (**[IEEE Aerospace Conference Proceedings, 2003](https://ieeexplore.ieee.org/abstract/document/1235522)**)

    - [MSTAR](https://www.sdms.afrl.af.mil/index.php?collection=mstar) : MSTAR public dataset. "Object recognition results using MSTAR synthetic aperture radar data". (**[IEEE CVBVS 2000](https://ieeexplore.ieee.org/abstract/document/855250/)**)

    - [OpenSARShip](https://opensar.sjtu.edu.cn/) : "OpenSARShip: A Dataset Dedicated to Sentinel-1 Ship Interpretation". (**[IEEE JSTAEORS 2017](https://ieeexplore.ieee.org/abstract/document/8067489)**)

    - [OpenSARShip 2.0](https://opensar.sjtu.edu.cn/) : "OpenSARShip 2.0: A large-volume dataset for deeper interpretation of ship targets in Sentinel-1 imagery". (**[IEEE BIGSARDATA 2017](https://ieeexplore.ieee.org/abstract/document/8124929)**)

    - [SSDD](https://aistudio.baidu.com/aistudio/datasetdetail/54806) : "Ship detection in SAR images based on an improved faster R-CNN". (**[IEEE BIGSARDATA 2017](https://ieeexplore.ieee.org/abstract/document/8124934/)**). "基于深度学习的SAR图像舰船检测数据集及性能分析". (**[第五届高分辨率对地观测学术年会, 2018](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CPFD&dbname=CPFDLAST2019&filename=ZKZD201810001014&uniplatform=NZKPT&v=yO0QaBvz14EhL7pk2vCZgRGQl9EUK4g_ZLMv--RusqdnPK4jBUFATMtsDuwGc8fzPb9iLY3lVOI%3d)**)

    - [AIR-SARShip](https://radars.ac.cn/web/data/getData?newsColumnId=1e6ecbcc-266d-432c-9c8a-0b9a922b5e85) : "高分辨率SAR舰船检测数据集-2.0". "AIR-SARShip-1.0: 高分辨率 SAR 舰船检测数据集". (**[雷达学报 2019](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2020&filename=LDAX201906014&uniplatform=NZKPT&v=pL57X-1uWs_T7QAY3gMTKZ1ZrPt1hdyAPDo3jpXRqPLbyAYbrH6-IAZMrqpRwS3J)**)

    - [SAR-Ship-Dataset](https://github.com/CAESAR-Radi/SAR-Ship-Dataset) <img src="https://img.shields.io/github/stars/CAESAR-Radi/SAR-Ship-Dataset?style=social"/> : "A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds". (**[Remote Sensing, 2019](https://www.mdpi.com/2072-4292/11/7/765)**)

    - [OpenSARUrban](https://opensar.sjtu.edu.cn/) : "OpenSARUrban: A Sentinel-1 SAR Image Dataset for Urban Interpretation". (**[IEEE JSTAEORS 2020](https://ieeexplore.ieee.org/abstract/document/8952866/)**)

    - [HRSID](https://github.com/chaozhong2010/HRSID) <img src="https://img.shields.io/github/stars/chaozhong2010/HRSID?style=social"/> : "HRSID: A High-Resolution SAR Images Dataset for Ship Detection and Instance Segmentation". (**[IEEE Access 2020](https://ieeexplore.ieee.org/abstract/document/9127939)**)

    - [FUSAR-Ship](https://emwlab.fudan.edu.cn/resources/) : 高分辨率船只数据集FUSAR-Ship1.0. (**[雷达学报](https://radars.ac.cn/web/data/getData?dataType=FUSAR)**). "FUSAR-Ship: building a high-resolution SAR-AIS matchup dataset of Gaofen-3 for ship detection and recognition". (**[Science China Information Sciences, 2020](https://link.springer.com/article/10.1007/s11432-019-2772-5)**)

    - [Official-SSDD](https://github.com/TianwenZhang0825/Official-SSDD) <img src="https://img.shields.io/github/stars/TianwenZhang0825/Official-SSDD?style=social"/> : "SAR Ship Detection Dataset (SSDD): Official Release and Comprehensive Data Analysis ". (**[Remote Sensing, 2021](https://www.mdpi.com/2072-4292/13/18/3690)**)

    - [MSAR](https://radars.ac.cn/web/data/getData?dataType=MSAR) : "大规模多类SAR目标检测数据集-1.0"。(**[雷达学报 2022](https://radars.ac.cn/web/data/getData?dataType=MSAR)**)

    - [RSDD-SAR](https://radars.ac.cn/web/data/getData?dataType=SDD-SAR) : "RSDD-SAR:SAR舰船斜框检测数据集"。(**[雷达学报 2022](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2022&filename=LDAX202204006&uniplatform=NZKPT&v=J3WR8KUVzuYM6uPXqbI64hl8oRAk3mvWRv3hrBCH9ZBek54uYq_UkJGY0PGaaxDg)**)


- ### Sonar Image Datasets

    - [SWDD](https://zenodo.org/records/10528135) : SWDD: Sonar Wall Detection Dataset. "Knowledge Distillation in YOLOX-ViT for Side-Scan Sonar Object Detection". (**[arXiv 2024](https://arxiv.org/abs/2403.09313)**). The Sonar Wall Detection Dataset (SWDD) is publicly accessible at [https://zenodo.org/records/10528135](https://zenodo.org/records/10528135).




- ### Multimodal Image Datasets

    - [FLIR_ADAS](https://adas-dataset-v2.flirconservator.com/) : Teledyne FLIR Free ADAS Thermal Dataset v2.

    - [Anti-UAV](https://github.com/ZhaoJ9014/Anti-UAV) <img src="https://img.shields.io/github/stars/ZhaoJ9014/Anti-UAV?style=social"/> : 🔥🔥Official Repository for Anti-UAV🔥🔥. Anti-UAV300, Anti-UAV410, Anti-UAV600. Please refer to our [Anti-UAV v1](https://ieeexplore.ieee.org/document/9615243) paper and [Anti-UAV v3](https://arxiv.org/pdf/2306.15767.pdf) paper for more details ([WeChat News](https://zhaoj9014.github.io/pub/Anti-UAV.pdf)). "Anti-UAV: A Large-Scale Benchmark for Vision-Based UAV Tracking". (**[IEEE Transactions on Multimedia, 2022](https://ieeexplore.ieee.org/document/9615243)**). "Evidential Detection and Tracking Collaboration: New Problem, Benchmark and Algorithm for Robust Anti-UAV System". (**[arXiv 2023](https://arxiv.org/abs/2306.15767)**).

    - [VEDAI](https://downloads.greyc.fr/vedai/) : "Vehicle Detection in Aerial Imagery: A small target detection benchmark". (**[Journal of Visual Communication and Image Representation 2015](https://hal.archives-ouvertes.fr/hal-01122605v2/document)**)

    - [KAIST_rgbt](https://github.com/SoonminHwang/rgbt-ped-detection) <img src="https://img.shields.io/github/stars/SoonminHwang/rgbt-ped-detection?style=social"/> : "Multispectral Pedestrian Detection: Benchmark Dataset and Baseline". (**[CVPR 2015](https://openaccess.thecvf.com/content_cvpr_2015/html/Hwang_Multispectral_Pedestrian_Detection_2015_CVPR_paper.html)**)

    - [LLVIP](https://github.com/bupt-ai-cz/LLVIP) <img src="https://img.shields.io/github/stars/bupt-ai-cz/LLVIP?style=social"/> : "LLVIP: A Visible-Infrared Paired Dataset for Low-Light Vision". (**[ICCV 2021](https://openaccess.thecvf.com/content/ICCV2021W/RLQ/html/Jia_LLVIP_A_Visible-Infrared_Paired_Dataset_for_Low-Light_Vision_ICCVW_2021_paper.html)**)

    - [TNO](https://figshare.com/articles/dataset/TNO_Image_Fusion_Dataset/1008029) : "The TNO multiband image data collection". (**[Data in brief, 2017](https://www.data-in-brief.com/article/S2352-3409(17)30469-9/abstract)**)

    - [MFNet](https://github.com/haqishen/MFNet-pytorch) <img src="https://img.shields.io/github/stars/haqishen/MFNet-pytorch?style=social"/> : MFNet-pytorch, image semantic segmentation using RGB-Thermal images. "MFNet: Towards real-time semantic segmentation for autonomous vehicles with multi-spectral scenes". (**[IROS 2017](https://ieeexplore.ieee.org/abstract/document/8206396/)**). ([MFNet Dataset](https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/) : Multi-spectral Object Detection and Semantic Segmentation Datasets)

    - [MSRS](https://github.com/Linfeng-Tang/MSRS) <img src="https://img.shields.io/github/stars/Linfeng-Tang/MSRS?style=social"/> : MSRS: Multi-Spectral Road Scenarios for Practical Infrared and Visible Image Fusion. "[PIAFusion](https://github.com/Linfeng-Tang/PIAFusion) <img src="https://img.shields.io/github/stars/Linfeng-Tang/PIAFusion?style=social"/>: A progressive infrared and visible image fusion network based on illumination aware". (**[Information Fusion, 2022](https://www.sciencedirect.com/science/article/abs/pii/S156625352200032X)**)

    - [TarDAL](https://github.com/JinyuanLiu-CV/TarDAL) <img src="https://img.shields.io/github/stars/JinyuanLiu-CV/TarDAL?style=social"/> : "Target-Aware Dual Adversarial Learning and a Multi-Scenario Multi-Modality Benchmark To Fuse Infrared and Visible for Object Detection". (**[CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Target-Aware_Dual_Adversarial_Learning_and_a_Multi-Scenario_Multi-Modality_Benchmark_To_CVPR_2022_paper.html)**). ([M3FD Dataset](https://drive.google.com/drive/folders/1H-oO7bgRuVFYDcMGvxstT1nmy0WF_Y_6?usp=sharing))

    - [DroneVehicle](https://github.com/VisDrone/DroneVehicle) <img src="https://img.shields.io/github/stars/VisDrone/DroneVehicle?style=social"/> : "Drone-based RGB-Infrared Cross-Modality Vehicle Detection via Uncertainty-Aware Learning". (**[IEEE TCSVT 2022](https://ieeexplore.ieee.org/abstract/document/9759286/)**)





- ### 3D Object Detection Datasets

    - [Objectron](https://github.com/google-research-datasets/Objectron) <img src="https://img.shields.io/github/stars/google-research-datasets/Objectron?style=social"/> : "Objectron: A Large Scale Dataset of Object-Centric Videos in the Wild with Pose Annotations". (**[CVPR, 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Ahmadyan_Objectron_A_Large_Scale_Dataset_of_Object-Centric_Videos_in_the_CVPR_2021_paper.html?ref=https://githubhelp.com)**)



- ### Vehicle-to-Everything Field Datasets

    - [OpenCOOD|OPV2V](https://github.com/DerrickXuNu/OpenCOOD) <img src="https://img.shields.io/github/stars/DerrickXuNu/OpenCOOD?style=social"/> : OpenCOOD is an Open COOperative Detection framework for autonomous driving. It is also the official implementation of the ICRA 2022 paper [OPV2V](https://mobility-lab.seas.ucla.edu/opv2v/). "OPV2V: An Open Benchmark Dataset and Fusion Pipeline for Perception with Vehicle-to-Vehicle Communication". (**[ICRA, 2022](https://ieeexplore.ieee.org/abstract/document/9812038/)**). [mobility-lab.seas.ucla.edu/opv2v/](https://mobility-lab.seas.ucla.edu/opv2v/)

    - [CoBEVT](https://github.com/DerrickXuNu/CoBEVT) <img src="https://img.shields.io/github/stars/DerrickXuNu/CoBEVT?style=social"/> : "CoBEVT: Cooperative Bird's Eye View Semantic Segmentation with Sparse Transformers". (**[CoRL, 2022](https://arxiv.org/abs/2207.02202)**).

    - [Where2comm](https://github.com/MediaBrain-SJTU/where2comm) <img src="https://img.shields.io/github/stars/MediaBrain-SJTU/where2comm?style=social"/> : "Where2comm: Communication-Efficient Collaborative Perception via Spatial Confidence Maps". (**[Neurips, 2022](https://arxiv.org/abs/2209.12836)**).

    - [PJLab-ADG/LiDARSimLib-and-Placement-Evaluation](https://github.com/PJLab-ADG/LiDARSimLib-and-Placement-Evaluation) <img src="https://img.shields.io/github/stars/PJLab-ADG/LiDARSimLib-and-Placement-Evaluation?style=social"/> : "Analyzing Infrastructure LiDAR Placement with Realistic LiDAR Simulation Library". (**[ICRA, 2023](https://arxiv.org/abs/2211.15975)**).

    - [CoAlign](https://github.com/yifanlu0227/CoAlign) <img src="https://img.shields.io/github/stars/yifanlu0227/CoAlign?style=social"/> : "Robust Collaborative 3D Object Detection in Presence of Pose Errors". (**[ICRA, 2023](https://arxiv.org/abs/2211.07214)**).

    - [V2V4Real](https://github.com/ucla-mobility/V2V4Real) <img src="https://img.shields.io/github/stars/ucla-mobility/V2V4Real?style=social"/> : "V2V4Real: A Real-World Large-Scale Dataset for Vehicle-to-Vehicle Cooperative Perception". (**[CVPR, 2023](https://openaccess.thecvf.com/content/CVPR2023/html/Xu_V2V4Real_A_Real-World_Large-Scale_Dataset_for_Vehicle-to-Vehicle_Cooperative_Perception_CVPR_2023_paper.html)**).

    - [V2X-ViT|V2XSet](https://github.com/DerrickXuNu/v2x-vit) <img src="https://img.shields.io/github/stars/DerrickXuNu/v2x-vit?style=social"/> : "V2X-ViT: Vehicle-to-Everything Cooperative Perception with Vision Transformer". (**[ECCV, 2022](https://link.springer.com/chapter/10.1007/978-3-031-19842-7_7)**).

    - [DAIR-V2X](https://github.com/AIR-THU/DAIR-V2X) <img src="https://img.shields.io/github/stars/AIR-THU/DAIR-V2X?style=social"/> : "DAIR-V2X: A Large-Scale Dataset for Vehicle-Infrastructure Cooperative 3D Object Detection". (**[CVPR, 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Yu_DAIR-V2X_A_Large-Scale_Dataset_for_Vehicle-Infrastructure_Cooperative_3D_Object_Detection_CVPR_2022_paper.html)**). [全球首个车路协同自动驾驶数据集发布](https://thudair.baai.ac.cn)

    - [V2X-Seq](https://github.com/AIR-THU/DAIR-V2X-Seq) <img src="https://img.shields.io/github/stars/AIR-THU/DAIR-V2X-Seq?style=social"/> : "V2X-Seq: A Large-Scale Sequential Dataset for Vehicle-Infrastructure Cooperative Perception and Forecasting". (**[CVPR, 2023](https://openaccess.thecvf.com/content/CVPR2023/html/Yu_V2X-Seq_A_Large-Scale_Sequential_Dataset_for_Vehicle-Infrastructure_Cooperative_Perception_and_CVPR_2023_paper.html)**). [全球首个大规模时序车路协同自动驾驶数据集发布](https://thudair.baai.ac.cn)





- ### Super-Resolution Field Datasets

    - [VideoLQ](https://github.com/ckkelvinchan/RealBasicVSR) <img src="https://img.shields.io/github/stars/ckkelvinchan/RealBasicVSR?style=social"/> : "Investigating Tradeoffs in Real-World Video Super-Resolution". (**[CVPR, 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Chan_Investigating_Tradeoffs_in_Real-World_Video_Super-Resolution_CVPR_2022_paper.html)**)




- ### Face Detection and Recognition Datasets

    - #### Face Detection Datasets

        - [WIDER FACE](http://shuoyang1213.me/WIDERFACE/) : "WIDER FACE: A Face Detection Benchmark". (**[CVPR 2016](https://openaccess.thecvf.com/content_cvpr_2016/html/Yang_WIDER_FACE_A_CVPR_2016_paper.html)**)

        - [UFDD](https://ufdd.info/) : Unconstrained Face Detection Dataset(UFDD). "Pushing the Limits of Unconstrained Face Detection: a Challenge Dataset and Baseline Results". (**[IEEE BTAS 2018](https://ieeexplore.ieee.org/abstract/document/8698561l)**)

        - [HCIILAB/SCUT-HEAD-Dataset-Release](https://github.com/HCIILAB/SCUT-HEAD-Dataset-Release) <img src="https://img.shields.io/github/stars/HCIILAB/SCUT-HEAD-Dataset-Release?style=social"/> : SCUT HEAD is a large-scale head detection dataset, including 4405 images labeld with 111251 heads. "Detecting Heads using Feature Refine Net and Cascaded Multi-scale Architecture". (**[arXiv, 2018](https://arxiv.org/abs/1803.09256)**)






    - #### Face Recognition Datasets

        - [LFW](http://vis-www.cs.umass.edu/lfw/) : Labeled Faces in the Wild(LFW). "Labeled Faces in the Wild: A Database forStudying Face Recognition in Unconstrained Environments". (**[Workshop on faces in'Real-Life'Images: detection, alignment, and recognition. 2008](https://hal.inria.fr/inria-00321923/)**)

        - [YouTube Faces (YTF)](http://www.cs.tau.ac.il/~wolf/ytfaces/) : "Face recognition in unconstrained videos with matched background similarity". (**[CVPR 2011](https://ieeexplore.ieee.org/abstract/document/5995566)**)

        - [CASIA-WebFace](https://pan.baidu.com/s/1k3Cel2wSHQxHO9NkNi3rkg) : "Learning Face Representation from Scratch". (**[arXiv 2014](https://arxiv.org/abs/1411.7923)**)

        - [IJB-A](https://www.nist.gov/programs-projects/face-challenges) : "Pushing the Frontiers of Unconstrained Face Detection and Recognition: IARPA Janus Benchmark A". (**[CVPR 2015](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Klare_Pushing_the_Frontiers_2015_CVPR_paper.html)**)

        - [MS-Celeb-1M](https://academictorrents.com/details/9e67eb7cc23c9417f39778a8e06cca5e26196a97/tech&hit=1&filelist=1) : "MS-Celeb-1M: A Dataset and Benchmark for Large-Scale Face Recognition". (**[ECCV 2016](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_6)**)

        - [MegaFace](http://megaface.cs.washington.edu/) : "The MegaFace Benchmark: 1 Million Faces for Recognition at Scale". (**[CVPR 2016](https://openaccess.thecvf.com/content_cvpr_2016/html/Kemelmacher-Shlizerman_The_MegaFace_Benchmark_CVPR_2016_paper.html)**)

        - [UMDFaces](https://www.umdfaces.io/) : "UMDFaces: An annotated face dataset for training deep networks". (**[IJCB 2017](https://ieeexplore.ieee.org/abstract/document/8272731)**)

        - [IJB-B](https://www.nist.gov/programs-projects/face-challenges) : "IARPA Janus Benchmark-B Face Dataset". (**[CVPR 2017](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w6/html/Whitelam_IARPA_Janus_Benchmark-B_CVPR_2017_paper.html)**)

        - [IJB-C](https://www.nist.gov/programs-projects/face-challenges) : "IARPA Janus Benchmark - C: Face Dataset and Protocol". (**[ICB 2018](https://ieeexplore.ieee.org/abstract/document/8411217)**)

        - [VGGFace2]() : "VGGFace2: A Dataset for Recognising Faces across Pose and Age". (**[FG 2018](https://ieeexplore.ieee.org/abstract/document/8373813)**)





## Blogs

  - 微信公众号「IDEA数字经济研究院」
    - [2024-11-22，IDEA研究院发布DINO-X目标检测视觉大模型：万物识别，开放世界](https://mp.weixin.qq.com/s/bT_SbHlkyGaas-J6MkugPw)
  - [知乎「江大白」| 微信公众号「江大白」](https://www.zhihu.com/people/nan-yang-8-13)
    - [2020-05-27，深入浅出Yolo系列之Yolov3&Yolov4&Yolov5&Yolox核心基础知识完整讲解](https://zhuanlan.zhihu.com/p/143747206)
    - [2020-08-10，深入浅出Yolo系列之Yolov5核心基础知识完整讲解](https://zhuanlan.zhihu.com/p/172121380)
    - [2021-08-09，深入浅出Yolox之自有数据集训练超详细教程](https://zhuanlan.zhihu.com/p/397499216)
    - [2021-08-11，深入浅出Yolo系列之Yolox核心基础完整讲解](https://zhuanlan.zhihu.com/p/397993315)
    - [2022-01-30，深入浅出0基础入门AI及目标检测详细学习路径](https://zhuanlan.zhihu.com/p/463221190)
    - [2022-01-30，深入浅出Yolov5之自有数据集训练超详细教程](https://zhuanlan.zhihu.com/p/463176500)
    - [2022-11-03，实践教程 | 在yolov5上验证的一些想法尝试](https://mp.weixin.qq.com/s/HqXJov5fWIlgKhMp2_Ca7g)
    - [2022-12-17，YOLOv6精度深度优化，感知量化的重参再设计](https://mp.weixin.qq.com/s/lm77Fe4e6e_cx_gJYhp8QA)
    - [2022-12-28，Repvgg重参数化，YOLO检测算法涨点实践！](https://mp.weixin.qq.com/s/QZnpo24537fhGeFj7-MR_Q)
    - [2023-01-16，YOLOv8自有数据集训练，及多任务使用详细教程](https://mp.weixin.qq.com/s/zhoFAKvFOHh0T1R2fvwZxQ)
    - [2023-01-28，YOLOv8+DeepSORT原理讲解及实现（附源码）](https://mp.weixin.qq.com/s/rDpbzIG95TmgpJQH71QY8g)
    - [2023-02-23，深入浅出TensorRT中ONNX模型解析过程](https://mp.weixin.qq.com/s/C3O3QeSUnu4LUBxHZtur7A)
    - [2023-02-24，模型部署 | TensorRT加速PyTorch实战部署教程，值得收藏学习！](https://mp.weixin.qq.com/s/AdnfJ48mnwFejTtHN4v70w)
    - [2023-02-25，YOLOv8+ByteTrack，作者开源多目标跟踪算法](https://mp.weixin.qq.com/s/DZcVdwFZP3TKaTk0n98oeg)
    - [2023-02-27，基于YOLOv5的半监督目标检测，算法进阶之路，阿里团队新作！（附论文及源码）](https://mp.weixin.qq.com/s/9qpuLCvgaQjc_JOdZchxjQ)
    - [2023-03-18，Efficient Teacher，针对YOLOv5的半监督目标检测算法（附论文及源码）](https://mp.weixin.qq.com/s/3YnNAx_2PFqpxLUZZWoYAg)
    - [2023-03-20，onnx模型转换，op不支持时的心得经验分享](https://mp.weixin.qq.com/s/qkktjhALMKgRwSSiq6n5bA)
    - [2023-03-24，深度学习模型训练中，GPU和显存分析](https://mp.weixin.qq.com/s/xyCNXUBE2rTjTUnK6bBm7g)
    - [2023-03-25，PyTorch模型训练，并行加速方法梳理汇总](https://mp.weixin.qq.com/s/54FaTRh8dUXwI4JqO9LAsQ)
    - [2023-03-27，基于YOLO的铝型材表面缺陷识别 ](https://mp.weixin.qq.com/s/sTL6aATIDOh8RpicU2B9tA)
    - [2023-03-31，小目标检测精度优化方式，CEASA模块，即插即用（附论文及源码）](https://mp.weixin.qq.com/s/fXV3rdB_YtSVap0FtK_AeQ)
    - [2023-04-01，GPU 利用率低常见原因分析及优化](https://mp.weixin.qq.com/s/LCJZqnNB6C15EEMPB1X-hQ)
    - [2023-04-03，小目标检测算法，Yolov5优化升级 ，即插即用，值得尝试！](https://mp.weixin.qq.com/s/KEdsJO1z19sq7rTtwyC4Rg)
    - [2023-04-22，CUDA卷积算子，手写详细实现流程](https://mp.weixin.qq.com/s/3rQQ31LWxvDli_1uwGsHIw)
    - [2023-04-28，深入浅出PyTorch模型，int8量化及原理流程](https://mp.weixin.qq.com/s/pij3APMt_wtyS6St89lbdQ)
    - [2023-04-29，AI视觉项目，图像标注工具梳理汇总](https://mp.weixin.qq.com/s/SvgTQfKqGlI5DsrsmfKUhA)
    - [2023-05-08，Label-Studio X SAM，半自动化标注神器（附源码）](https://mp.weixin.qq.com/s/f-sD8ukV3Nm28_-yHi44BA)
    - [2023-05-09，深入浅出多目标跟踪技术的研究与探索](https://mp.weixin.qq.com/s/aYam5aQXJTZ1ysubEfewYA)
    - [2023-05-10，超强目标检测器RT-DETR，保姆级部署教程，从入门到精通（附论文及源码）](https://mp.weixin.qq.com/s/NfUWJ5cBTXvuB45l1hnSfw)
    - [2023-05-13，YOLOCS目标检测算法，YOLOv5的Backbone/Neck/Head全面改进](https://mp.weixin.qq.com/s/exo2JkLluChvLDSif2JvMQ)
    - [2023-05-17，一文看尽深度学习各种注意力机制，学习推荐！](https://mp.weixin.qq.com/s/PkzzElN1uk2Yzu1DsYnOdQ)
    - [2023-05-26，一文读懂PyTorch显存管理机制，推荐学习！](https://mp.weixin.qq.com/s/a9LK35lLE4yfQkqvBp6ujQ)
    - [2023-06-05，两万字长文，目标检测入门看这篇就够了，推荐收藏！](https://mp.weixin.qq.com/s/EBc1JrR5n4BlWGBx8kuiXw)
    - [2023-06-07，手把手带你，自己设计实现一个深度学习框架（附代码实现）](https://mp.weixin.qq.com/s/-8A_XaOwHyg653UyRbArQQ)
    - [2023-06-12，MMDetection目标检测框架详解，及训练自有数据集教程](https://mp.weixin.qq.com/s/U3irSW9UTKt0gY0HCV9slQ)
    - [2023-06-19，万字长文，彻底搞懂YOLOv8网络结构及代码实战！](https://mp.weixin.qq.com/s/vXIx7dBRxgxnvh5BoIRQZw)
    - [2023-06-27，TensorRT模型部署，添加自己插件的落地方式](https://mp.weixin.qq.com/s/E-Iebdd4Es5UK-TrBUJcjA)
    - [2023-06-29，YOLOv7+Transformer部署，TensorRT应用实战（附代码）](https://mp.weixin.qq.com/s/znxT8nsfkq0s5NHRnAxYaw)
    - [2023-07-06，万字长文，基于PyTorch的多种卷积神经网络BackBone代码实现](https://mp.weixin.qq.com/s/TQ88Oex6YTKAkUZL3kLu3A)
    - [2023-07-21，万字长文，YOLOv5手势识别训练转换及模型部署！（附代码）](https://mp.weixin.qq.com/s/1yvJIObEs9H4C9Qd3tb9kA)
    - [2023-08-03，TensorRT模型INT8量化，Python代码部署实现](https://mp.weixin.qq.com/s/Phu7UmPKuSrUOhCQDV2xEQ)
    - [2023-08-12，目标检测算法，检测框位置优化总结](https://mp.weixin.qq.com/s/_JDPP7Yq8E4bXxZtWlOy6Q)
    - [2023-09-01，基于Yolo算法的AI数钢筋，整体解决方案汇总](https://mp.weixin.qq.com/s/plWUuEVkbK-nDycqVDFU8A)
    - [2024-01-26，深入浅出，YOLOv8算法使用指南](https://mp.weixin.qq.com/s/9naZZ7wXugppelcmPHGVlQ)
    - [2024-02-23，目标检测YOLOv9算法，重磅开源！（附论文及源码）](https://mp.weixin.qq.com/s/RVG-9h8zKsWACMr6dDRpUQ)
    - [2024-04-04，CPU推理1ms的Backbone开源，精度速度碾压MobileNet/ShuffleNet等轻量模型！](https://mp.weixin.qq.com/s/FC9KtCPpwEraYuj4qnw_oQ)
    - [2024-04-12，深入浅出，PyTorch模型int8量化原理拆解](https://mp.weixin.qq.com/s/j2QS3LdudrrlyZYQkVrl5Q)
    - [2024-06-18，Mamba-YOLO开源，超越 YOLO ，创新SSM 技术，提升目标检测性能！（附论文及源码）](https://mp.weixin.qq.com/s/UREcCHvyl7yIEv_si9KOjQ)
    - [2024-07-13，YOLOv5、YOLOv8与YOLOv10，性能分析与边缘部署梳理，YOLO算法进化史！](https://mp.weixin.qq.com/s/wTwjDESVipFg2Tnh9Mgp6A)
    - [2024-09-07，YOLOv8算法模型深度解析：架构创新、性能提升与用户友好性改进！](https://mp.weixin.qq.com/s/aYWq8CDXATrk4KAwWQqvIg)
    - [2025-04-14，TPAMI 2025，国防科大提出RGBT-Tiny数据集，助力小目标检测发展！](https://mp.weixin.qq.com/s/UQeB-Opy46bMQ1eTg1ZzRg)
    - [2025-04-16，TPAMI 2025，YOLOv12-BoT-SORT-ReID，无人机检测及追踪算法，问鼎无人机挑战赛（附论文与源码）](https://mp.weixin.qq.com/s/wETR_rxbe5hYiyVLT1Qo8w)


  - [知乎「迪迦奥特曼」](https://www.zhihu.com/people/nemofeng95)
    - [2022-08-12，从百度飞桨YOLOSeries库看各个YOLO模型](https://zhuanlan.zhihu.com/p/550057480)
    - [2022-09-21，YOLO内卷时期该如何选模型？](https://zhuanlan.zhihu.com/p/566469003)
  - [知乎「PoemAI」](https://www.zhihu.com/people/LEYM2)
    - [2022-07-10，YOLO家族进化史（v1-v7）](https://zhuanlan.zhihu.com/p/539932517)
  - [知乎「科技猛兽」](https://www.zhihu.com/people/wang-jia-hao-53-3)
    - [2020-08-14，你一定从未看过如此通俗易懂的YOLO系列(从v1到v5)模型解读 (上)](https://zhuanlan.zhihu.com/p/183261974)
    - [2020-08-21，你一定从未看过如此通俗易懂的YOLO系列(从v1到v5)模型解读 (中)](https://zhuanlan.zhihu.com/p/183781646)
    - [2020-08-17，你一定从未看过如此通俗易懂的YOLO系列(从v1到v5)模型解读 (下)](https://zhuanlan.zhihu.com/p/186014243)
  - [知乎「CV技术指南」| 微信公众号「CV技术指南」](https://www.zhihu.com/people/cvji-zhu-zhi-nan)
    - [2021-08-26，目标检测mAP的计算 & COCO的评价指标](https://mp.weixin.qq.com/s/gpr7JZMRgp8B5RxhVzt_mQ)
    - [2022-04-07，YOLO系列梳理（一）YOLOv1-YOLOv3](https://zhuanlan.zhihu.com/p/494572914)
    - [2022-04-15，YOLO系列梳理与复习（二）YOLOv4 ](https://mp.weixin.qq.com/s/2lndImcah5QJJJiEujGOsA)
    - [2022-04-24，YOLO系列梳理（三）YOLOv5](https://zhuanlan.zhihu.com/p/503971609)
    - [2022-06-26，YOLO系列梳理（九）初尝新鲜出炉的YOLOv6](https://zhuanlan.zhihu.com/p/534090250)
    - [2022-07-19，YOLO系列梳理（十）YOLO官方重回江湖 并带来了YOLOv7](https://zhuanlan.zhihu.com/p/543574708)
    - [2023-03-11，目标跟踪专栏（一）基本任务、常用方法](https://mp.weixin.qq.com/s/DKHOlLtjO2OBtIWlA3cpzg)
    - [2023-04-17，目标跟踪（二）单、多目标跟踪的基本概念与常用数据集](https://mp.weixin.qq.com/s/N50tOvJwNRZhyoVq6Fc-ig)
    - [2023-05-11，全新YOLO模型YOLOCS来啦 | 面面俱到地改进YOLOv5的Backbone/Neck/Head](https://mp.weixin.qq.com/s/wnxOd-DukIpea5j2Dqcpbw)
    - [2024-04-16，YOLC 来袭 | 遥遥领先 ！YOLO与CenterNet思想火花碰撞，让小目标的检测性能原地起飞，落地价值极大 !](https://mp.weixin.qq.com/s/cCegxKb1VWxmhpZZwCk1WA)
  - [知乎「极市平台」| 微信公众号「极市平台」](https://www.zhihu.com/org/ji-shi-jiao-14)
    - [2020-11-17，YOLO算法最全综述：从YOLOv1到YOLOv5](https://zhuanlan.zhihu.com/p/297965943)
    - [2022-08-04，华为轻量级神经网络架构GhostNet再升级，GPU上大显身手的G-GhostNet（IJCV22）](https://mp.weixin.qq.com/s/31Fb3WSBtRUNu8oUkMrBrg)
    - [2022-10-17，Backbone篇｜YOLOv1-v7全系列大解析](https://mp.weixin.qq.com/s/SQ-ojaRlinLY5PsLTZhz2w)
    - [2022-11-15，NeurIPS'22 Spotlight｜华为诺亚GhostNetV2出炉：长距离注意力机制增强廉价操作](https://mp.weixin.qq.com/s/RBpC-0HqzgtHy5xsoBce8Q)
    - [2022-11-21，轻量级的CNN模块！RepGhost：重参数化技术构建硬件高效的 Ghost 模块](https://mp.weixin.qq.com/s/mV2Bl4tBZwZ7n-YleMUE4g)
    - [2023-02-26，厦大纪荣嵘团队新作｜OneTeacher: 解锁 YOLOv5 的正确打开方式](https://mp.weixin.qq.com/s/HAfCpECOxccPfj5b7Pprfw)
    - [2023-04-18，Repvgg-style ConvNets，硬件友好！详解YOLOv6的高效backbone：EfficientRep](https://mp.weixin.qq.com/s/2Md30QdqgWnWwVR7d4sx1Q)
    - [2023-04-19，CVPR23 Highlight｜拥有top-down attention能力的vision transformer](https://mp.weixin.qq.com/s/UMA3Vk9L71zUEtNkCshYBg)
    - [2023-04-26，万字长文，深度全面解读PyTorch内部机制](https://mp.weixin.qq.com/s/JYsJRo8l5-nTFrGwBV-BFA)
    - [2023-05-28，YOLOv10开源｜清华用端到端YOLOv10在速度精度上都生吃YOLOv8和YOLOv9](https://mp.weixin.qq.com/s/VG9itVaOwCpmb48ZAa8Mjw)
    - [2023-10-27，「项目经验掏心窝」第二期：真实上手算法开发后的经验总结&心得体会](https://mp.weixin.qq.com/s/raTAXapLK0mquvC1c6S2Iw)
    - [2024-12-03，注意力机制比矩阵分解更好吗？](https://mp.weixin.qq.com/s/UawQkuRqo-phGvtbC5stQg)
  - 微信公众号「WeThinkln」
    - [2022-09-18，【Make YOLO Great Again】YOLOv1-v7全系列大解析（输入侧篇）](https://mp.weixin.qq.com/s/JLYFP8IA7RcIMSeBKekQlw)
    - [2022-07-31，【Make YOLO Great Again】YOLOv1-v7全系列大解析（Neck篇）](https://mp.weixin.qq.com/s/nEWL9ZAYuVngoejf-muFRw)
    - [2022-08-14，【Make YOLO Great Again】YOLOv1-v7全系列大解析（Head篇）（尝鲜版）](https://mp.weixin.qq.com/s/JDaSWyNdLoHc6j6cOmNIWw)
    - [2022-08-28，【Make YOLO Great Again】YOLOv1-v7全系列大解析（Head篇）（完整版）](https://mp.weixin.qq.com/s/85Xh4l_t65HrGx25ByD_iw)
    - [2022-10-16，【Make YOLO Great Again】YOLOv1-v7全系列大解析（Backbone篇）](https://mp.weixin.qq.com/s/T76JkDf82ZPF5WWVDvJ6GA)
    - [2022-11-13，【Make YOLO Great Again】YOLOv1-v7全系列大解析（Tricks篇）](https://mp.weixin.qq.com/s/xJDMKcS9SRQIWKCAbUpMaQ)
    - [2022-12-11，【Make YOLO Great Again】YOLOv1-v7全系列大解析（汇总篇）](https://mp.weixin.qq.com/s/etaaojeNv8lbBy586FjtQw)
  - 微信公众号「GiantPandaCV」
    - [2022-10-26，One-YOLOv5 发布，一个训得更快的YOLOv5](https://mp.weixin.qq.com/s/tZ7swUd0biz7G3CiRkHHfw)
    - [2022-12-04，One-YOLOv5 v1.1.0发布，大幅优化Eager FP32单卡性能](https://mp.weixin.qq.com/s/N2Xp4IKJAATCmmmQqQ6new)
    - [2022-10-28，《YOLOv5全面解析教程》一，网络结构逐行代码解析](https://mp.weixin.qq.com/s/qR2ODIMidsNR_Eznxry5pg)
    - [2022-11-06，《YOLOv5全面解析教程》二，YOLOv5数据集结构解析&如何制作一个可以获得更好训练效果的数据集](https://mp.weixin.qq.com/s/qDNjLKhkjDT54l06SQ_yEA)
    - [2022-11-10，《YOLOv5全面解析教程》三，IoU深入解析](https://mp.weixin.qq.com/s/1DYz8sp1xR91rr7Q5_X4Qw)
    - [2022-11-12，《YOLOv5全面解析教程》四，目标检测模型精确度评估](https://mp.weixin.qq.com/s/n6ziYYc3BBsobcRkMS9tsQ)
    - [2022-11-18，《YOLOv5全面解析教程》五，计算mAP用到的numpy函数详解](https://mp.weixin.qq.com/s/i8Ygm9BCWNQfyBya7f1Z8Q)
    - [2022-11-20，《YOLOv5全面解析教程》六，YOLOv5使用教程详解（单卡，多卡，多机训练）](https://mp.weixin.qq.com/s/B1q_XsvXpf-fI3vDedoWjA)
    - [2022-11-22，《YOLOv5全面解析教程》七，使用模型融合提升mAP和mAR](https://mp.weixin.qq.com/s/6UvHK0bRxHGk__B8YMQhiw)
    - [2022-11-27，《YOLOv5全面解析教程》八，将训练好的YOLOv5权重导出为其它框架格式](https://mp.weixin.qq.com/s/UoPY_0E0D5g0R5o5eVmbdA)
    - [2022-11-29，《YOLOv5全面解析教程》九，train.py 逐代码解析](https://mp.weixin.qq.com/s/4jOg6De01Yxl1uW-v9Zydg)
    - [2022-12-07，《YOLOv5全面解析教程》十，YOLOv5 的 W & B 科学实验工具教程](https://mp.weixin.qq.com/s/CZ1btWU9cpbJWC2eVLBVQQ)
    - [2022-12-08，《YOLOv5全面解析教程》十一，YOLOv5 数据增强模块 utils/augmentations.py 逐行解析](https://mp.weixin.qq.com/s/uouLlV1G35L8_DQaUm8ogg)
    - [2022-12-14，《YOLOv5全面解析教程》​十二，Loss 计算详细解析](https://mp.weixin.qq.com/s/WfXSQFHgF6Ouwq5re4n1Vw)
    - [2022-12-29，《YOLOv5全面解析教程》​十三，downloads.py 详细解析](https://mp.weixin.qq.com/s/Efa44D7PiwaZkN0jlf4R_w)
    - [2023-01-10，《YOLOv5全面解析教程》​十四，YOLOv5 autoanchor 机制详解](https://mp.weixin.qq.com/s/qC-E2UbjNZT-c04IpXfoYA)
    - [2023-02-07，《YOLOv5全面解析教程》​十五，YOLOv5 Callback机制解读](https://mp.weixin.qq.com/s/osGwscIawS9q07g21rTQcA)
    - [2023-02-18，《YOLOv5全面解析教程》​十六，val.py 源码解读](https://mp.weixin.qq.com/s/sa2MQIaPIkHHxoVRGYMTAw)
    - [2023-04-24，简单聊聊目标检测新范式RT-DETR的骨干：HGNetv2](https://mp.weixin.qq.com/s/gF_qfXPMvPKWGNoEFdnpHw)
  - 微信公众号「PandaCVer」
    - [2022-10-18，改进YOLOv5——魔改YOLOv5提升检测精度](https://mp.weixin.qq.com/s/1iP4H3Ri6uBkq24eOO-viw)
    - [2022-10-23，目标检测算法——YOLOv5&无参SimAM！](https://mp.weixin.qq.com/s/X6MIRbE4ZD9xA-c-UtAa_A)
    - [2022-10-25，目标检测算法——YOLOv5改进结合BotNet（Transformer）](https://mp.weixin.qq.com/s/NVkHPBv8Ps2fCB2QvNz59Q)
    - [2022-10-27，目标检测算法——YOLOv5/YOLOv7更换FReLU激活函数](https://mp.weixin.qq.com/s/4KmjOSGAHHFdp6jYZI_QFw)
    - [2022-10-29，目标检测算法——YOLOv5/YOLOv7改进之GSConv+Slim Neck](https://mp.weixin.qq.com/s/CdNvKCL6fsQD012zrzZNFA)
    - [2022-11-02，目标检测算法——YOLOv5/YOLOv7改进之结合CBAM](https://mp.weixin.qq.com/s/vnqnNW5y47XThOmodEWHYA)
    - [2022-11-07，目标检测算法——YOLOv5/YOLOv7改进之结合GAMAttention](https://mp.weixin.qq.com/s/9gGOO66I1kFpyZcRayjF_Q)
    - [2022-11-08，人工智能前沿——深度学习热门领域（确定选题及研究方向）](https://mp.weixin.qq.com/s/ETkGaGNLx5VqJVSCSsTJNw)
    - [2022-11-10，目标检测算法——YOLOv5/YOLOv7改进之结合​SOCA（单幅图像超分辨率）](https://mp.weixin.qq.com/s/ithO0S7R-D8kXH1ZQlpRRQ)
    - [2022-11-12，目标检测算法——YOLOv5/YOLOv7改进之结合​ASPP（空洞空间卷积池化金字塔）](https://mp.weixin.qq.com/s/QgL2UxbVvXwrfmGxK7uolQ)
    - [2022-11-16，目标检测算法——YOLOv5/YOLOv7改进之结合​RepVGG（速度飙升）](https://mp.weixin.qq.com/s/4TnHyiG88h5oDhD6NZoq2Q)
    - [2022-11-20，知识经验分享——YOLOv5-6.0训练出错及解决方法（RuntimeError）](https://mp.weixin.qq.com/s/9qTFFu7HImaF8t6ozG_NWw)
    - [2022-11-23，目标检测算法——YOLOv5/YOLOv7改进之结合NAMAttention（提升涨点）](https://mp.weixin.qq.com/s/qB8G_pf3oCYBstYyFPrcrw)
    - [2022-11-25，目标检测算法——YOLOv5/YOLOv7改进之结合Criss-Cross Attention](https://mp.weixin.qq.com/s/v3pOvqz6ZewPR3fjnA5SIg)
    - [2022-11-29，目标检测算法——YOLOv7改进|增加小目标检测层](https://mp.weixin.qq.com/s/cFzcJLOG_1_TzS-Ckg6hGA)
    - [2022-11-14，目标检测算法——收藏|小目标检测的定义（一）](https://mp.weixin.qq.com/s/RwthaHf5d7-dT31Cqco6MA)
    - [2022-11-17，目标检测算法——收藏|小目标检测难点分析（二）](https://mp.weixin.qq.com/s/E2ZRBPZjobhlLspJK_DTfA)
    - [2022-11-18，目标检测算法——收藏|小目标检测解决方案（三）](https://mp.weixin.qq.com/s/nuIfgFX_krLtN9EQGNrn2w)
  - 微信公众号「人工智能AI算法工程师」
    - [2023-03-25，投稿指南：目标检测论文写作模板（初稿）](https://mp.weixin.qq.com/s/mi4BIyITyifl7QRhAKqPjg)
    - [2022-06-26，YOLOv5改进之一：添加SE注意力机制](https://mp.weixin.qq.com/s/QwY5C2y7HZ6LPRHC5gScFg)
    - [2022-07-11，YOLOv5改进之二：添加CBAM注意力机制](https://mp.weixin.qq.com/s/pFQEH4zpYogDOMdMQqugcg)
    - [2022-07-13，YOLOv5改进之三：添加Coordinate注意力机制](https://mp.weixin.qq.com/s/NzN88Vtkb3rVjsyPi60edQ)
    - [2022-07-14，YOLOv5改进之四：添加ECA通道注意力机制](https://mp.weixin.qq.com/s/4tnD0OZrOn0RdRSY-1XAxw)
    - [2022-07-15，YOLOv5改进之五：改进特征融合网络PANET为BIFPN](https://mp.weixin.qq.com/s/CgvdOqRC9JLrWa4mIDT_zA)
    - [2022-07-16，YOLOv5改进之六：增加小目标检测层](https://mp.weixin.qq.com/s/0IsvGgxhE5USP0c37HzeAQ)
    - [2022-07-17，YOLOv5改进之七：损失函数改进](https://mp.weixin.qq.com/s/0U4Y_ZEI2YvW1sMHxRfwMQ)
    - [2022-07-18，YOLOv5改进之八：非极大值抑制NMS算法改进Soft-nms](https://mp.weixin.qq.com/s/Q35jjU6qCKhwsVpF_JkFGw)
    - [2022-07-19，YOLOv5改进之九：锚框K-Means算法改进K-Means++](https://mp.weixin.qq.com/s/8tfw3l_qy8IyKKh3njsN_w)
    - [2022-07-20，YOLOv5改进之十：损失函数改进为SIOU](https://mp.weixin.qq.com/s/JMbiPaQKHwIULKLE2jeQNA)
    - [2022-07-21，YOLOv5改进之十一：主干网络C3替换为轻量化网络MobileNetV3](https://mp.weixin.qq.com/s/b3v2zNU4Ek6eO5AajuPI5A)
    - [2022-07-27，YOLOv5改进之十二：主干网络C3替换为轻量化网络ShuffleNetV2](https://mp.weixin.qq.com/s/9E9U64Wl8C02etSE19Q1iw)
    - [2022-07-28，YOLOv5改进之十三：主干网络C3替换为轻量化网络EfficientNetv2](https://mp.weixin.qq.com/s/SIqZyXfpx67uRxL7OSHqDg)
    - [2022-07-31，YOLOv5改进之十四：主干网络C3替换为轻量化网络Ghostnet](https://mp.weixin.qq.com/s/IVR6kJodBWStFcVoVHArEw)
    - [2022-08-01，YOLOv5改进之十五：网络轻量化方法深度可分离卷积](https://mp.weixin.qq.com/s/l3F9vGE2DHxz2otrlM1kfw)
    - [2022-08-03，YOLOv5改进之十六：主干网络C3替换为轻量化网络PP-LCNet](https://mp.weixin.qq.com/s/sHCpHtgcMurvgaXjnQX5HQ)
    - [2022-08-04，YOLOv5改进之十七：CNN+Transformer——融合Bottleneck Transformers](https://mp.weixin.qq.com/s/-hEjujFJuK5V-i9jX00iFw)
    - [2022-08-05，YOLOv5改进之十八：损失函数改进为Alpha-IoU损失函数](https://mp.weixin.qq.com/s/5mwBdny3xI4vZajfZ_KxjQ)
    - [2022-08-06，YOLOv5改进之十九：非极大值抑制NMS算法改进DIoU NMS](https://mp.weixin.qq.com/s/rW9FuDdpNVnO8yQbRon58g)
    - [2022-08-07，YOLOv5改进之二十：Involution新神经网络算子引入网络](https://mp.weixin.qq.com/s/cn7uQtcPN3S_CHJc_INZaQ)
    - [2022-08-08，YOLOv5改进之二十一：CNN+Transformer——主干网络替换为又快又强的轻量化主干EfficientFormer](https://mp.weixin.qq.com/s/D21iFLFTMFfM--vsfh0T5w)
    - [2022-08-09，YOLOv7改进之二十二：涨点神器——引入递归门控卷积（gnConv）](https://mp.weixin.qq.com/s/qq0M1yaCUysp5L3xap6t9g)
    - [2022-08-24，YOLOv7改进之二十三：引入SimAM无参数注意力](https://mp.weixin.qq.com/s/AfrIRsNDAbwfVzdz8XwgFw)
    - [2022-08-27，YOLOv7改进之二十四：引入量子启发的新型视觉主干模型WaveMLP](https://mp.weixin.qq.com/s/O78PFirnfdfuGlmQRpf9rw)
    - [2022-09-03，YOLOv7改进之二十五：引入Swin Transformer](https://mp.weixin.qq.com/s/s4RfXjW17mxUSIuK9QvTxg)
    - [2022-09-19，YOLOv5、v7改进之二十六：改进特征融合网络PANet为ASFF自适应特征融合网络](https://mp.weixin.qq.com/s/Ty8Eo_qbJZMxjTULVVi-xA)
    - [2022-09-21，YOLOv5、v7改进之二十七：解决小目标问题——校正卷积取代特征提取网络中的常规卷积](https://mp.weixin.qq.com/s/o23-u-B2I23bttzp14FJTg)
    - [2022-09-24，YOLOv5、v7改进之二十八：ICLR 2022涨点神器——即插即用的动态卷积ODConv](https://mp.weixin.qq.com/s/-wH_N4-pXY08XdbJ-Iu8zA)
    - [2022-10-08，YOLOv5、YOLOv7改进之二十九：v2.0版本的Swin Transformer 融入](https://mp.weixin.qq.com/s/9g-JMK44YQDd3feTBwCYjA)
    - [2022-10-13，YOLOv5、YOLOv7改进之三十：引入10月4号发表最新的Transformer视觉模型MOAT结构](https://mp.weixin.qq.com/s/Y2kOLVbU5ZnNzPIoiv4voA)
    - [2022-10-14，YOLOv5、v7改进之三十一：CrissCrossAttention注意力机制](https://mp.weixin.qq.com/s/sSZfmjJHS3USGkqFd5N-Nw)
    - [2022-10-16，YOLOv5、v7改进之三十二：SKAttention注意力机制](https://mp.weixin.qq.com/s/fgTTylKkDe36Z45MxMV_ig)
    - [2022-10-17，YOLOv5、v7改进之三十三：引入GAMAttention注意力机制](https://mp.weixin.qq.com/s/Tl5q7TEEPphXvzWQM_f61Q)
    - [2022-10-18，YOLOv5、v7改进之三十四：更换激活函数为FReLU](https://mp.weixin.qq.com/s/k1FIIcaEZxSjuR6aRzotHg)
    - [2022-10-19，YOLOv5、v7改进之三十五：引入NAMAttention注意力机制](https://mp.weixin.qq.com/s/rFe2pex6-YsUpRj8K-pw3g)
    - [2022-10-20，YOLOv5、v7改进之三十六：引入S2-MLPv2注意力机制](https://mp.weixin.qq.com/s/5MuJiodqJ4ixOSdogr5ebw)
    - [2022-10-21，YOLOv5、v7改进之三十七：结合CVPR2022新作ConvNeXt网络](https://mp.weixin.qq.com/s/f9rjpRkeqBCWeTFkadLZpQ)
    - [2022-10-22，YOLOv5、v7改进之三十八：引入最新RepVGG](https://mp.weixin.qq.com/s/7UhjzSwjR2U2h-FC7ZFbCw)
    - [2022-10-23，YOLOv5、v7改进之三十九：引入改进遮挡检测的Tri-Layer插件 | BMVC 2022](https://mp.weixin.qq.com/s/X0f0MLhDYMrMZzx72vyGPg)
    - [2022-10-27，YOLOv5、v7改进之四十：轻量化mobileone主干网络引入](https://mp.weixin.qq.com/s/rHTYQW5aRucVe8MoWUlA4Q)
    - [2022-11-01，YOLOv5、v7改进之四十一：引入SPD-Conv处理低分辨率图像和小对象问题](https://mp.weixin.qq.com/s/TrB7-B-ppU2JkuQ5G46a8Q)
    - [2022-11-02，YOLOv5改进之四十二：引入V7中的ELAN网络，降低网络参数](https://mp.weixin.qq.com/s/cg4KinN-vEhcnoiQlN_tfw)
    - [2022-11-03，YOLOv7、v5改进之四十三：结合最新Non-local Networks and Attention结构](https://mp.weixin.qq.com/s/P9TCtm6d_x6sRXtENTwY_A)
    - [2022-11-19，YOLO系列改进之四十四——融入适配GPU的轻量级 G-GhostNet](https://mp.weixin.qq.com/s/vS7Lm73tgVbQZ6WdKT9J4Q)
    - [2022-11-10，目标检测论文解读复现之一：基于改进YOLOv5的整车原木数量检测方法——TWD-YOLOv5](https://mp.weixin.qq.com/s/akrldqppGT6oyf89BnJe2Q)
    - [2022-11-12，目标检测论文解读复现之二：基于改进YOLOv5的轻量化航空目标检测方法](https://mp.weixin.qq.com/s/fOAzM-1_b29B79E8gxTP1Q)
    - [2022-11-14，目标检测论文解读复现之三：基于改进YOLOv7的X光图像旋转目标检测](https://mp.weixin.qq.com/s/6R9g3D2Xd-TZJ_DAiRcBzQ)
    - [2022-11-15，目标检测论文解读复现之四：改进YOLOv5算法在停车场火灾检测中的应用](https://mp.weixin.qq.com/s/LcImelrj1hbRHlP_QvLd6g)
    - [2022-11-16，目标检测论文解读复现之五：改进YOLOv5的SAR图像舰船目标检测](https://mp.weixin.qq.com/s/UwmamMFM0jnzt1sG-CX6iQ)
    - [2022-11-17，目标检测论文解读复现之六：基于YOLOv5的遥感图像舰船的检测方法](https://mp.weixin.qq.com/s/Qnw_krVnZGxlWUgG8z6q_g)
    - [2022-11-20，目标检测论文解读复现之七：基于SE-YOLOv5s的绝缘子检测](https://mp.weixin.qq.com/s/jZI93jPaLtsCFK-kljjppw)
    - [2022-11-21，目标检测论文解读复现之八：基于YOLOv5s的滑雪人员检测研究](https://mp.weixin.qq.com/s/47YVYj4svWnkbPrvrfOqmw)
    - [2022-11-22，目标检测论文解读复现之九：基于改进YOLOv5的复杂场景下SAR图像船舶检测方法](https://mp.weixin.qq.com/s/8VUZ5RX84krFgBdCO7qMhQ)
    - [2022-11-23，目标检测论文解读复现之十：基于YOLOv5的遥感图像目标检测](https://mp.weixin.qq.com/s/xEzrjEe8CGfgdttJevFbFw)
    - [2022-11-25，目标检测论文解读复现之十一：基于特征融合与注意力的遥感图像小目标检测](https://mp.weixin.qq.com/s/uPwcji5mGSstxI9gWnAXCQ)
    - [2022-11-26，目标检测论文解读复现之十二：基于注意力机制和上下文信息的目标检测算法](https://mp.weixin.qq.com/s/Ii98povs_xjfUdSxe2WYsQ)
    - [2022-11-27，目标检测论文解读复现之十三：改进YOLOv5s的遥感图像目标检测](https://mp.weixin.qq.com/s/MByqnwl2YiujOCyWrgMMKg)
    - [2022-12-12，目标检测论文解读复现之十四：一种基于残差网络优化的航拍小目标检测算法](https://mp.weixin.qq.com/s/M2ilkFpP5VwBHa2bY8BLyw)
    - [2022-12-13，目标检测论文解读复现之十五：基于YOLOv5的光学遥感图像舰船目标检测算法](https://mp.weixin.qq.com/s/qy0hMDcPyKsl5p28E7q30w)
    - [2022-12-14，目标检测论文解读复现之十六：基于改进YOLOv5的小目标检测算法](https://mp.weixin.qq.com/s/Z-FIlLzVE9obCM-YdtGpxg)
    - [2022-12-15，目标检测论文解读复现之十七：融合注意力机制的YOLOv5口罩检测算法](https://mp.weixin.qq.com/s/cQHDZkvyw7bYMRCaXUcPKQ)
    - [2022-12-16，目标检测论文解读复现之十八：基于注意力机制的光线昏暗条件下口罩佩戴检测](https://mp.weixin.qq.com/s/Kxe6CGs8hR6vrYgagMVdPQ)
    - [2022-12-17，目标检测论文解读复现之十九：基于YOLOv5网络模型的人员口罩佩戴实时检测](https://mp.weixin.qq.com/s/67KIqrl1xSFzUmI6vjjAkw)
    - [2022-12-18，目标检测论文解读复现之二十：基于改进Yolov5的地铁隧道附属设施与衬砌表观病害检测方法](https://mp.weixin.qq.com/s/2TXXKXsWFDJG2t48rPWGqQ)
    - [2022-12-19，目标检测论文解读复现之二十一:基于改进YOLOv7的小目标检测](https://mp.weixin.qq.com/s/qlVnBh2FFw5yBOvCsP2G-g)
    - [2022-12-20，目标检测论文解读复现之二十二：多尺度下遥感小目标多头注意力检测](https://mp.weixin.qq.com/s/LH7IqfyXLGbmRXCq_SxDJQ)
    - [2023-01-16，YOLOv7/YOLOv5系列改进之四十四：融入YOLOv8中的C2f模块](https://mp.weixin.qq.com/s/qe_LV_8W4hzUxxgax2O4_g)
    - [2023-01-17，YOLOv7/YOLOv5系列改进之四十五：融入CFPNet网络中的ECVBlock模块，提升小目标检测能力](https://mp.weixin.qq.com/s/HwPwI-nwl8elbiZfDsqHKg)
    - [2023-01-18，学习经验分享之十三：首发全网讲解YOLOv8](https://mp.weixin.qq.com/s/B0WVnNYrRDXcX0pw_2cLjg)
    - [2023-01-24，【目标检测论文解读复现NO.25】基于改进Yolov5的地铁隧道附属设施与衬砌表观病害检测方法](https://mp.weixin.qq.com/s/Zrth5ANIYOrjVaU0p2eRZQ)
    - [2023-01-25，【目标检测论文解读复现NO.26】基于改进YOLOv5s网络的实时输液监测](https://mp.weixin.qq.com/s/URWmI6OVVtDkvxSEfroVVg)
    - [2023-01-28，基于改进YOLOv5的螺纹钢表面缺陷检测](https://mp.weixin.qq.com/s/nToaAvSgSViP4pQrD_Gfgg)
    - [2023-01-30，【目标检测论文解读复现NO.28】基于改进YOLO v5的电厂管道油液泄漏检测](https://mp.weixin.qq.com/s/mtMA87mMQGLA2f4jXlXiUw)
    - [2023-01-31，【目标检测论文解读复现NO.29】基于YOLO-ST的安全帽佩戴精确检测算法](https://mp.weixin.qq.com/s/_tDSg2J3JopTBjQtawnycg)
    - [2023-02-03，【目标检测论文解读复现NO.30】基于改进YOLOv5的宁夏草原蝗虫识别模型研究](https://mp.weixin.qq.com/s/UYdTR8axfUSCFEOiTN5wMw)
    - [2023-02-05，【目标检测论文解读复现NO.31】基于改进YOLO v5复杂场景下肉鹅姿态的检测算法研究](https://mp.weixin.qq.com/s/fMfsXIJ6v2cC18eWjrIbKw)
    - [2023-02-04，【目标检测论文解读复现NO.32】基于改进YOLO的飞机起降阶段跟踪方法](https://mp.weixin.qq.com/s/jycEm-pwYhMkihvfS66YIg)
    - [2023-03-04，【YOLOv8/YOLOv7/YOLOv5系列算法改进NO.55】融入美团最新QARepVGG](https://mp.weixin.qq.com/s/WvHoB5zSPPH1SHRahMLL8g)
    - [2023-03-07，【YOLOv8/YOLOv7/YOLOv5系列算法改进NO.56】引入Contextual Transformer模块](https://mp.weixin.qq.com/s/T_v7QM_9P20vT5mjFg07xw)
    - [2023-03-10，【YOLOv8/YOLOv7/YOLOv5/YOLOv4/Faster-rcnn系列算法改进NO.57】引入可形变卷积](https://mp.weixin.qq.com/s/XVl6o2-xK8BfT4BWbmqxxA)
    - [2023-03-14，【YOLOv8/YOLOv7/YOLOv5/YOLOv4/Faster-rcnn系列算法改进】引入DRconv动态区域感知卷积](https://mp.weixin.qq.com/s/GgN_Y9Kxkz0YP7dxtoMUsA)
    - [2023-03-15，【YOLOv8/YOLOv7/YOLOv5/YOLOv4/Faster-rcnn系列算法改进NO.59】引入ASPP模块](https://mp.weixin.qq.com/s/_YjOXjxggHGPLg9T5bE2YQ)
    - [2023-03-30，【YOLOv8/YOLOv7/YOLOv5/YOLOv4系列算法改进】结合NeurIPS 2022年GhostnetV2网络模块](https://mp.weixin.qq.com/s/YgR-hc1aimba3ij9tfaBAw)
    - [2023-04-08，YOLOv8/YOLOv7/YOLOv5/YOLOv4算法-结合CVPR 2023 即插即用动态稀疏注意力BiFormer模块](https://mp.weixin.qq.com/s/JqDIRqM5XAMzqz-Un2yw8Q)
    - [2023-05-05，英文论文（sci）解读复现：基于注意机制的改进YOLOv5s目标检测算法](https://mp.weixin.qq.com/s/4Xu9UIwcpgGvqOkXVDhoYA)
    - [2023-05-10，英文论文（sci）解读复现：基于注意机制和感受野的YOLOv5在唐卡图像缺陷识别中的应用](https://mp.weixin.qq.com/s/D2yC4Qiztg1FH64f89iJ_A)
    - [2023-06-10，算法改进：针对遥感图像目标检测中的小目标进行改进CATnet（ContextAggregation模块）](https://mp.weixin.qq.com/s/T6VWbQJOWoE3kVTQp0cf7w)
    - [2023-06-27，YOLOv8/YOLOv7/YOLOv5/YOLO/Faster-rcnnv4系列算法改进：注意力机制（EMA）](https://mp.weixin.qq.com/s/itgOWmlFID6KwDfiOcQ9Ag)
    - [2023-07-18，YOLOv8/YOLOv7/YOLOv5/YOLOv4/Faster-rcnn系列算法改进：添加渐近特征金字塔网络](https://mp.weixin.qq.com/s/sdZq3AGcqc4rVywqaEmlYw)
    - [2023-07-27，中科大提出PE-YOLO | 让YOLO家族算法直击黑夜目标检测](https://mp.weixin.qq.com/s/7_6wCWbjqLsv09pd_m2NIQ)
    - [2023-07-28，YOLOv8/YOLOv7/YOLOv5/YOLOv4等系列算法改进：改进边框位置回归损失函数（MPDIoU损失函数）](https://mp.weixin.qq.com/s/hKdFzeEvgOI-IkZebDxORQ)
    - [2023-07-31，远超YOLOP | 超轻超快的TwinLiteNet实现多任务自动驾驶感知](https://mp.weixin.qq.com/s/qXFQeYOrdBNWEblVgodcfg)
    - [2024-05-22，YOLOv8算法改进【NO.132】利用HCANet中具有全局和局部信息的注意力机制CAFM进行DEA-Net形成二次创新模块](https://mp.weixin.qq.com/s/0ZT4YxAInMAy_3dy5YJ5-A)
    - [2024-05-23，YOLOv9/YOLOv8算法改进【NO.133】2024年最新MobileNetV4轻量算法作为YOLO算法的主干特征提取网络](https://mp.weixin.qq.com/s/ua3vW4MSdWk0Mc15q3bvJg)
  - 微信公众号「所向披靡的张大刀」
    - [2022-04-24，【小白入坑篇】目标检测的评价指标map](https://mp.weixin.qq.com/s/q308cHT0XliCK3NtIRjyqA)
    - [2022-07-02，【yolov6系列】细节拆解网络框架](https://mp.weixin.qq.com/s/DFSROue8InARk-96I_Kptg)
    - [2022-07-13，【yolov7系列】网络框架细节拆解](https://mp.weixin.qq.com/s/VEcUIaDrhc1ETIPr39l4rg)
    - [2022-07-23，【yolov7系列二】正负样本分配策略](https://mp.weixin.qq.com/s/nhZ3Q1NHm3op8abdVIGmLA)
    - [2022-07-29，【yolov7系列三】实战从0构建训练自己的数据集](https://mp.weixin.qq.com/s/S80mMimu4YpHwClHIH07eA)
    - [2022-10-23，万字长文解析cv中的注意力机制](https://mp.weixin.qq.com/s/kt3iIuOD3lsZBTIbOSGN0g)
    - [2022-11-23，yolov5的持续发力|分类任务](https://mp.weixin.qq.com/s/YiK5kT-Yd-9k_V_aiSVYqw)
    - [2023-07-12，算法部署服务实战--代码篇](https://mp.weixin.qq.com/s/JrkRpIgTDtq6WN-hM8NwSA)
  - 微信公众号「集智书童」
    - [2022-07-07，YOLOv7官方开源 | Alexey Bochkovskiy站台，精度速度超越所有YOLO，还得是AB](https://mp.weixin.qq.com/s/5SeD09vG6nv46-YuN_uU1w)
    - [2022-07-27，YOLOU开源 | 汇集YOLO系列所有算法，集算法学习、科研改进、落地于一身！](https://mp.weixin.qq.com/s/clupheQ8iHnhR4FJcTtB8A)
    - [2022-09-25，连夜卷出 | 超越所有YOLO检测模型，mmdet开源当今最强最快目标检测模型！](https://mp.weixin.qq.com/s/2XErHzw9hWrrBry9Ij2pjA)
    - [2023-01-09，YOLOv8来啦 | 详细解读YOLOv8的改进模块！YOLOv5官方出品YOLOv8，必卷！](https://mp.weixin.qq.com/s/l3fzlPzMFIxXK18rhqX-kg)
    - [2023-01-10，从标注到部署，MMYOLO 保姆级教程！](https://mp.weixin.qq.com/s/rIi1XBUh_SZuNqKz473tcQ)
    - [2023-01-13，YOLOv8实践 | 手把手教你用YOLOv8训练自己的数据集以及YOLOv8的多任务使用](https://mp.weixin.qq.com/s/vUXOX71rcqb3IzDca0nKVQ)
    - [2023-01-16，YOLOv8 + DeepSORT | YOLO与DeepSORT跟踪的难分难舍，直接用吧（附源码）](https://mp.weixin.qq.com/s/AClsBD7jJPDUjJ_svwRplQ)
    - [2023-02-01，YOLO涨点Trick | 超越CIOU/SIOU，Wise-IOU让Yolov7再涨1.5个点！](https://mp.weixin.qq.com/s/8TS70TpbqgQ5GB37zVgERA)
    - [2023-02-17，EdgeYOLO来袭 | Xaiver超实时，精度和速度完美超越YOLOX、v4、v5、v6](https://mp.weixin.qq.com/s/BK3IRiJdKfPE53KFpvjTCg)
    - [2023-02-22，YOLOv5抛弃Anchor-Base方法 | YOLOv5u正式加入Anchor-Free大家庭](https://mp.weixin.qq.com/s/m09WRKRqC1bngCOzip_hFA)
    - [2023-03-08，全新剪枝框架 | YOLOv5模型缩减4倍，推理速度提升2倍](https://mp.weixin.qq.com/s/p_c0w43ns7rFOzamtOSPVg)
    - [2023-03-31 ，小目标检测 | 即插即用 | YOLOv5可以这样升级](https://mp.weixin.qq.com/s/vgg_m80A06xFWQGgw2WhHg)
    - [2023-03-14，实践教程｜TensorRT中对ONNX模型解析过程](https://mp.weixin.qq.com/s/L-TpXpBJI7y0wKmBr9arjQ)
    - [2023-03-24，目标检测Trick | SEA方法轻松抹平One-Stage与Two-Stage目标检测之间的差距](https://mp.weixin.qq.com/s/spEL2hYmYykkQkc4aNxJAg)
    - [2023-03-30，即插即用 | CEASA模块给你所有，小目标精度提升的同时速度也变快了](https://mp.weixin.qq.com/s/-a4Wz04jLHFiAU88pUyDNQ)
    - [2023-04-05，部署技巧之PAGCP剪枝 | Yolov5/ResNet参数降低50%速度翻倍精度不减](https://mp.weixin.qq.com/s/3_2Dcm8VpoGFksFZE6n2kQ)
    - [2023-04-12，Faster RCNN超快版本来啦 | TinyDet用小于1GFLOPS实现30+AP，小目标炸裂](https://mp.weixin.qq.com/s/-AtF3B_A0rzvS8cUcZQ6Hw)
    - [2023-04-13，即插即用模块 | RFAConv助力YOLOv8再涨2个点](https://mp.weixin.qq.com/s/lsOQiq9wXHxagE_uQ_yOiw)
    - [2023-04-19，YOLO超快时代终结了 | RT-DETR用114FPS实现54.8AP，远超YOLOv8](https://mp.weixin.qq.com/s/V3MUXinJhpq8J4UWTUL17w)
    - [2023-04-21，基于YOLOv5改进再设计 | M2S全面提升小目标精度](https://mp.weixin.qq.com/s/FlKgYYGUHtJAxCF2wrh4NA)
    - [2023-06-06，一文全览 | 2023最新环视自动驾驶3D检测综述！](https://mp.weixin.qq.com/s/4eE5kWGF5FekHHCZOg9rNA)
    - [2023-06-21，AI模型部署实战 | 利用CV-CUDA加速视觉模型部署流程](https://mp.weixin.qq.com/s/kdxz3zn77031MDNxVm_k0Q)
    - [2023-07-20，Q-YOLOP来啦 | 一个具有量化感知全景驾驶感知模型](https://mp.weixin.qq.com/s/kaAoqp-8af0bUA7byYKKPA)
    - [2023-07-29，TensorRT部署系列 | 如何将模型从 PyTorch 转换为 TensorRT 并加速推理？](https://mp.weixin.qq.com/s/F0ZV9yTW8_UHJrvNew8qOA)
    - [2023-08-03，YOLO落地部署 | 一文全览YOLOv5最新的剪枝、量化的进展【必读】](https://mp.weixin.qq.com/s/AzwdSKNs8SnIIRsdG0cZAg)
    - [2023-08-11，YOLOD也来啦 | 优化YOLOv5样本匹配，顺带设计了全新的模块](https://mp.weixin.qq.com/s/erkyca0OtJoyXAXI_I6RmQ)
    - [2023-09-05，YOLO 与 BEV 以及3D目标检测算法究竟应该怎么才可以更好的落地？](https://mp.weixin.qq.com/s/B1iFf936wAORB53QboTXjg)
    - [2024-02-01，太强！AI没有落下的腾讯出YOLO-World爆款 | 开集目标检测速度提升20倍，效果不减](https://mp.weixin.qq.com/s/Fj6wzARTo1l7UEwKxDAh6w)
    - [2024-02-14，YOLOPoint开源 | 新年YOLO依然坚挺，通过结合YOLOv5&SuperPoint，成就多任务SOTA](https://mp.weixin.qq.com/s/8Lkl3aMwjESRyeZfLMu7Tw)
    - [2024-02-23，Focaler-IoU开源 | 高于SIoU+关注困难样本，让YOLOv5再涨1.9%，YOLOv8再涨点0.3%](https://mp.weixin.qq.com/s/A_BABGHKp5Icdmlk3q3lIA)
    - [2024-02-23，YOLOv9开源 | 架构图&模块改进&正负样本匹配&损失函数解读，5分钟即可理解YOLOv9](https://mp.weixin.qq.com/s/31NlBknx4PcXipfuV2w6hw)
    - [2024-03-18，D-YOLO解决落地困难 | 关注特征融合模块+无雾特征子网络，让YOLO家族无惧雨雾和风雪](https://mp.weixin.qq.com/s/2Hlp_zaHN8TKyzk-1f1yjw)
    - [2024-04-15，YOLC 来袭 | 遥遥领先 ！YOLO与CenterNet思想火花碰撞，让小目标的检测性能原地起飞，落地价值极大 !](https://mp.weixin.qq.com/s/6UzdFFKeNOCLK8YdhPYCaQ)
    - [2024-12-14，高效小目标识别，多帧运动检测与YOLO结合提高 UAV 检测精度 !](https://mp.weixin.qq.com/s/6h7FY0U4hwbpOQ6AkH4IEg)
  - 微信公众号「计算机视觉研究院」
    - [2022-10-30，YoloV：视频中目标实时检测依然很棒（附源代码下载）](https://mp.weixin.qq.com/s/Ytr1m2EOJMWF6WmHDmai2A)
    - [2022-11-04，改进的YOLO：AF-FPN替换金字塔模块提升目标检测精度](https://mp.weixin.qq.com/s/JVr1C9nPTYlHS4aei-Zqrg)
    - [2022-12-31，Micro-YOLO：探索目标检测压缩模型的有效方法（附论文下载）](https://mp.weixin.qq.com/s/0_sF3U232i0PEw1NHE2Efw)
    - [2023-02-25，使用ONNXRuntime部署阿里达摩院开源DAMO-YOLO目标检测，一共包含27个onnx模型(代码开源)](https://mp.weixin.qq.com/s/cQo7HMcWcbZgk7XIzj1q2A)
    - [2023-04-03，CVPR 2023 论文分类汇总：一个专为计算机视觉领域研究者打造的学术资源宝库](https://mp.weixin.qq.com/s/g8yUdF0SP-81VpVfFjTqNw)
    - [2023-04-07，Micro-YOLO：探索目标检测压缩模型的有效方法（附论文下载）](https://mp.weixin.qq.com/s/xMq10ZZQnFyXaob0H-Z1qw)
    - [2023-04-07，实用教程详解：模型部署，用DNN模块部署YOLO目标检测（附源代码）](https://mp.weixin.qq.com/s/ny98FTagPQB1-GnHKFu2MA)
    - [2023-04-20，全自动实时移动端AI框架 | YOLO-v4目标检测实时手机端实现](https://mp.weixin.qq.com/s/FPG44PhAxNi7cy_ALcNXmA)
    - [2023-04-22，CVPR目标检测新框架：不再是YOLO，而是只需要一层特征（干货满满，建议收藏）](https://mp.weixin.qq.com/s/5sTxdjhKIPpQ-rCsWfe80A)
    - [2023-04-25，GPT-CV：基于Yolov5的半监督目标检测](https://mp.weixin.qq.com/s/wK-5i30X06SfLgASlRdqJw)
    - [2023-04-25，EdgeYOLO：边缘设备上实时运行的目标检测器及Pytorch实现](https://mp.weixin.qq.com/s/zEFjvUKnrm5Iwa6e9Fy29Q)
    - [2023-04-26，改进的YOLO：AF-FPN替换金字塔模块提升目标检测精度](https://mp.weixin.qq.com/s/xocZNuIOCgGynjZxX_xKgw)
    - [2023-06-22，RestoreDet：低分辨率图像中目标检测](https://mp.weixin.qq.com/s/FqBq9gy-NKfp3W2qgKHb5w)
    - [2023-07-12，GPT理解的CV：基于Yolov5的半监督目标检测](https://mp.weixin.qq.com/s/N4x0_Bu078g1zSMIDPwzZg)
    - [2023-07-12，YoloV8与ChatGPT互通，这功能是真的强大！](https://mp.weixin.qq.com/s/ODIFRyvfbZOiEORLdWGc_A)
    - [2023-07-24，YOLO-S预告：一种用于小目标检测的轻量级、精确的类YOLO网络](https://mp.weixin.qq.com/s/-G2TpQOOhLyYDw5wPODBkw)
    - [2023-08-20，Yolo框架优化：黑夜中也可以实时目标检测](https://mp.weixin.qq.com/s/e0EJVHKW7nkfkMVurMgR2Q)
    - [2023-09-04，CRAS-YOLO：多类别船舶检测与分类模型](https://mp.weixin.qq.com/s/ztdYjDbWzpx2LnWTiVWdrQ)
    - [2023-09-04，Drone-YOLO：一种有效的无人机图像目标检测](https://mp.weixin.qq.com/s/X4HGQhWaxy1bQssrQIYBmQ)
    - [2023-09-05，BFD-YOLO：基于YOLOv7的建筑外墙缺陷检测](https://mp.weixin.qq.com/s/BaqXo4uTeqoY5FhD2jVuxA)
    - [2024-05-26，Yolov10：详解、部署、应用一站式齐全！](https://mp.weixin.qq.com/s/damt3VWade0we1MSCe9_QA)
  - 微信公众号「新机器视觉」
    - [​2023-03-22，YOLO系列的演进，从v1到v7](https://mp.weixin.qq.com/s/0ALtok0vleMif-5_rgCycQ)
    - [2023-03-23，​YOLO系列的演进，从v1到v7（二）](https://mp.weixin.qq.com/s/_aVWQ-NxGwZthA_D_drTRw)
    - [2023-03-24，YOLO系列的演进，从v1到v7（三）](https://mp.weixin.qq.com/s/Ngz7SYEtQ8jsejKG0IknXg)
    - [2023-05-20，机器视觉和模式识别库汇总](https://mp.weixin.qq.com/s/UaqBSCWnGbLLCuy8cvJpkQ)
  - 微信公众号「OpenMMLab」
    - [2022-10-20，社区协作，简洁易用，快来开箱新一代 YOLO 系列开源库](https://mp.weixin.qq.com/s/ZK1hzp6QJarS1xiqkBWcrg)
    - [2023-03-28，建议收藏！超实用的 YOLO 训练&测试技巧合集](https://mp.weixin.qq.com/s/iF2Upd2ThMBlWPim8Gj13g)
    - [​2023-01-12，YOLOv8 深度详解！一文看懂，快速上手](https://mp.weixin.qq.com/s/_RNmB3KtYEt7UuDsCOJ3rQ)
    - [2023-04-04，显著提升模型精度！以 MMYOLO 为例 ，巧用 MMRazor 轻量级骨干网络](https://mp.weixin.qq.com/s/ilCMYZmG_XpvJ_ysB1cgkw)
  - 微信公众号「自动驾驶之心」
    - [2022-10-26，手把手教学！TensorRT部署实战：YOLOv5的ONNX模型部署](https://mp.weixin.qq.com/s/M47rwwbU0FRrgd-Xg9c7ww)
    - [2022-11-12，SSDA-YOLO：用于跨域目标检测的半监督域自适应YOLO方法](https://mp.weixin.qq.com/s/FFRsxSaTeGvs1ssKGCD6lg)
    - [2022-11-30，达摩院 | DAMO-YOLO：兼顾速度与精度的新目标检测框架](https://mp.weixin.qq.com/s/QYsCzgMhW9Mfsa6CYolVuQ)
    - [2022-12-23，通用小目标Trick | 深度学习检测小目标常用方法盘点](https://mp.weixin.qq.com/s/WRVjub3ePxWoCBQXKhS__w)
    - [2023-01-12，纯量产经验 | 谈谈目标检测中正负样本的问题](https://mp.weixin.qq.com/s/esGe2o3_pPXUlrysZoCQKQ)
    - [2023-05-15，最新！自动驾驶中用于目标检测和语义分割的Radar-Camera融合综述](https://mp.weixin.qq.com/s/EHTXisVDv7SV4UEbo7sdbQ)
    - [2023-05-19，25FPS！英伟达首发BEVFusion部署源代码，边缘端实时运行！！！](https://mp.weixin.qq.com/s/79DskdwwSghyldvQF43l6A)
    - [2023-05-21，保姆级开源教程 | 手把手教你部署FreeYOLO](https://mp.weixin.qq.com/s/AhPaSVl2Gh8zWtJ74IUyzw)
    - [2023-05-29，最新SOTA！BEVFusion4D：BEVFusion升级版3D检测时空新框架！](https://mp.weixin.qq.com/s/i3lLadD3_Q5RX5D0JUocPQ)
    - [2023-06-04，万字长文 | Transformer在BEV、2D/3D检测上的应用、量化与加速！](https://mp.weixin.qq.com/s/sEWfs2C62cuThZBXSM0fZA)
    - [2023-06-15，全搞定！基于TensorRT的CNN/Transformer/检测/BEV模型四大部署代码+CUDA加速！](https://mp.weixin.qq.com/s/WjBvj6hCWEYs7IL9DlrK2Q)
    - [2023-08-23，模型部署，今年的香饽饽！TensorRT详细入门指北](https://mp.weixin.qq.com/s/KsPb80tf_zxPyP0xu8ZmHA)
    - [2024-01-10，YOLO进军BEV感知！YOLO+BEV在实时检测上的尝试](https://mp.weixin.qq.com/s/8pceyAzzGvwKNnRE9OJEOA)
  - 微信公众号「CVHub」
    - [2023-01-07，现代目标检测故事 | 40+种网络架构大盘点！从基础架构ResNet到最强检测器Yolov7再到最新部署神器GhostNetV2](https://mp.weixin.qq.com/s/22rRzyZj93-Y4msYwa_LKQ)
    - [2023-02-19，阿里团队新作 | 探讨 YOLOv5 的高效进阶之路！](https://mp.weixin.qq.com/s/B0yHtFMTO5gwt0B-ra18QA)
    - [2023-05-05，超强目标检测器 RT-DETR | Python/C++ 保姆级部署教程，从入门到精通](https://mp.weixin.qq.com/s/W56LHZbZEqqoCPFVf612FA)
    - [2023-06-04，中科院一区顶刊 TCSVT 2023 | DIAL-Filters: 显著提升模糊夜视场景下的检测和分割性能！](https://mp.weixin.qq.com/s/qPbxjDuPOFSD2zsWAGmLQw)
    - [2023-07-12，北航新作 | Q-YOLO: 基于 TensorRT 和 OpenVIVO 的目标检测量化实战方案](https://mp.weixin.qq.com/s/Us7IiYXFtUoQJ6btpcG1lw)
    - [2023-07-30，大连理工联合阿里达摩院发布HQTrack | 高精度视频多目标跟踪大模型](https://mp.weixin.qq.com/s/Jl2mr7tszulZX19Fx4ZNgw)
    - [2024-03-24，SeeClick: 手把手教你如何基于Qwen-VL搭建一个多模态智能体！](https://mp.weixin.qq.com/s/foF9JDyAIk5pLN5F_6dw2g)
    - [2024-09-30，Ultrylytics 官宣: YOLO11 全新发布！](https://mp.weixin.qq.com/s/IfOCnuvFCTIzKIQEFWFLdA)
  - 微信公众号「人工智能感知信息处理算法研究院」
    - [2023-06-15，改进YOLOV5小目标检测之VisDrone2019数据集](https://mp.weixin.qq.com/s/GJza38BBYTl6XAWiiEzpHA)
    - [2023-06-16，改进YOLOV5小目标检测之数据预处理之一](https://mp.weixin.qq.com/s/BXueTqerYFtGg9MOhJ7YYA)
    - [2023-06-17，改进YOLOV5小目标检测之数据预处理之二](https://mp.weixin.qq.com/s/NblhcYo-JWZuJkMS5015sw)
    - [2023-06-22，改进YOLOV5小目标检测消融实验之一](https://mp.weixin.qq.com/s/3_03EmF0wo4hmbes5o37NQ)
    - [2023-06-23，改进YOLOV5小目标检测消融实验之二](https://mp.weixin.qq.com/s/iEEGkLFICJT03kXWQwR_sA)
    - [2023-07-04，基于改进YOLOv5和可变形卷积的水下群体目标检测概述之一](https://mp.weixin.qq.com/s/ZIH6Y1d6yeUV-zE6AnEvuQ)
    - [2023-07-05，基于改进YOLOv5和可变形卷积的水下群体目标检测概述之二](https://mp.weixin.qq.com/s/ptkTsyG2_mOFb6lGUCSkVA)
    - [2023-07-07，YOLOV5算法改进之自适应阈值模块](https://mp.weixin.qq.com/s/XSBtVbtcQTrMf13E_HEeWw)
    - [2023-07-10，改进YOLOV5算法之不同数据集测试](https://mp.weixin.qq.com/s/-0ZsO9D4o4UXuIy_a2gt0w)
    - [2023-07-11，改进YOLOV5算法与同类算法的比较](https://mp.weixin.qq.com/s/KIxhlNBuTnCLnqzKqD_GPA)
    - [2023-07-12，改进YOLOV5自适应阈值模块实验分析 ](https://mp.weixin.qq.com/s/WffWRa6MzaRN4oMF3BvOWg)
    - [2023-07-15，KAYOLO网络模型](https://mp.weixin.qq.com/s/rYrdJPHYE57Kc8QzVDxUfg)
    - [2023-07-19，Yolov8n-IOU损失函数的改进](https://mp.weixin.qq.com/s/x1WRIC9MNQWMTup9XHkwWg)
    - [2023-07-26，YOLOV7算法原理](https://mp.weixin.qq.com/s/KnLwHIWqespSxO0v82cJ3A)
    - [2023-07-30，Flask 部署 YOLOV5](https://mp.weixin.qq.com/s/9dwrXEAi5tht4-tNyZ4tYw)
    - [2023-08-13，目标检测算法的应用](https://mp.weixin.qq.com/s/cX1WlVJqDNePZW18Jlf_Kg)
  - 微信公众号「OneFlow」
    - [2022-12-13，YOLOv5全面解析教程①：网络结构逐行代码解读](https://mp.weixin.qq.com/s/qfZIKgBdHNwPDp5ng0Y_Qw)
    - [2022-12-22，YOLOv5全面解析教程②：如何制作训练效果更好的数据集](https://mp.weixin.qq.com/s/t4Ppf2qokpClRwCN52zF-g)
    - [2023-02-02，YOLOv5全面解析教程③：更快更好的边界框回归损失](https://mp.weixin.qq.com/s/LIOnJqJj_GrpakKbLeWEDQ)
    - [2023-02-17，YOLOv5全面解析教程④：目标检测模型精确度评估](https://mp.weixin.qq.com/s/nvfAU6TwTDoZhF8zFpCaOw)
    - [2023-02-24，YOLOv5全面解析教程⑤：计算mAP用到的Numpy函数详解](https://mp.weixin.qq.com/s/ag7PkcRRSTppEG0GOysqpg)
    - [2023-03-09，YOLOv5全面解析教程⑥：模型训练流程详解](https://mp.weixin.qq.com/s/RriWDozw7ZHTBg7Rr38dNw)
    - [2023-05-23，YOLOv5全面解析教程⑦：使用模型融合提升mAP和mAR](https://mp.weixin.qq.com/s/6PjD5k5o1GQO8v7jIydZ_w)
    - [2023-05-23，YOLOv5全面解析教程⑧：将训练好的YOLOv5权重导为其它框架格式](https://mp.weixin.qq.com/s/4yiN7JZrvAvMi4m5eusbMw)
  - 微信公众号「AIWalker」
    - [2023-03-29，ChatGPT是如何看待YOLO系列算法的贡献呢？~哈哈~ ](https://mp.weixin.qq.com/s/E-TNeTKK5EV70zAenRVbwQ)
    - [2023-05-07，YOLO-NAS | YOLO新高度，引入NAS，出于YOLOv8而优于YOLOv8](https://mp.weixin.qq.com/s/FsWSRguAn2WZKtmPhMbc6g)
    - [2023-05-16，全网唯一复现！手机端 1ms 级延迟的主干网模型 MobileOne](https://mp.weixin.qq.com/s/Wk1sHIQKUe01PqMnpzcCfQ)
    - [2023-08-15，南开大学提出YOLO-MS | 超越YOLOv8与RTMDet，即插即用打破性能瓶颈](https://mp.weixin.qq.com/s/FfG9vNM_a2k_zflWfuimsw)
    - [2024-02-19，U版YOLO-World来了，YOLOv8再度升级，三行代码上手YOLO-World](https://mp.weixin.qq.com/s/yepStVzyrOE4MsgFFuwo0Q)
    - [2024-02-23，YOLOv9来了，可编程梯度信息与广义高效层聚合网络 助力全新检测SOTA前沿](https://mp.weixin.qq.com/s/tFavH5_Sqtnq1_NMRt_AUg)
  - 微信公众号「董董灿是个攻城狮」
    - [2023-03-20，万字长文解析Resnet50的算法原理](https://mp.weixin.qq.com/s/pA86udkaFzCogi2Qw8vBEA)
    - [2023-04-17，万字长文入门神经网络硬件加速](https://mp.weixin.qq.com/s/3aNVGIPf5pLzEv67KI8M5w)
    - [2023-04-19，CUDA卷积算子手写详细实现](https://mp.weixin.qq.com/s/VlrglazJE54Xnm3tjM0uCg)
  - 微信公众号「计算机视觉漫谈」
    - [2020-02-22，YOLO v3实战之钢筋数量AI识别（一）](https://mp.weixin.qq.com/s/EElv2Tc73JKS8jpejEGB1w)
    - [2020-03-07，YOLO v3实战之钢筋智能识别改进方案分享（二）](https://mp.weixin.qq.com/s/lOeRqD2orcLw5FR496r4uw)
  - 微信公众号「智造情报局」
    - [2022-11-07，项目实操：基于yolov5的PCB表面缺陷检测【附完整代码】](https://mp.weixin.qq.com/s/IzMabvYts2BEa5IvAwUfrg)
  - 微信公众号「学姐带你玩AI」
    - [2022-11-21，YOLOv5+Tesseract-OCR 实现车牌号文本识别【实战】](https://mp.weixin.qq.com/s/52Woexamu697tozevSiyQQ)
  - 微信公众号「量子位」
    - [2023-01-12，YOLOv8已至，精度大涨！教你如何在自定义数据集上训练它](https://mp.weixin.qq.com/s/_ccYfjWm6CsH_vxpACUWEA)
  - 微信公众号「笑傲算法江湖」
    - [2023-02-08，代码实战：YOLOv5实现钢材表面缺陷检测](https://mp.weixin.qq.com/s/i_bF6_77MxKqEy7-y7LQdQ)
  - 微信公众号「OpenCV中文网」
    - [2023-04-07，YOLOv8 全家桶再迎新成员！新增Pose Estimation模型!](https://mp.weixin.qq.com/s/wF93AAVnGsQtHdB-DkSTPQ)
  - 微信公众号「深度学习与计算机视觉」
    - [2023-03-28，使用 YOLO 进行目标检测：如何提取人物图像](https://mp.weixin.qq.com/s/vthdOoy3etZmybMLaGzoFg)
  - 微信公众号「机器学习算法工程师」
    - [2023-04-19，惊呆了！基于Transformer的检测模型RT-DETR竟然比YOLO还快！](https://mp.weixin.qq.com/s/wgBaZ-CTB7B4nvYnobMDvw)
  - 微信公众号「计算机视觉与机器学习」
    - [2023-04-19，RT-DETR | 吊打YOLO系列的 DETR部署教程来啦，优雅而简洁！](https://mp.weixin.qq.com/s/oflfbPkhj3ka2ExK7ZZ0VA)
    - [2023-05-16，超强目标检测器 RT-DETR | Python/C++ 保姆级部署教程，从入门到精通](https://mp.weixin.qq.com/s/XwmQILnaLtWPfo-dysLeAA)
  - 微信公众号「人工智能前沿讲习」
    - [2023-04-19，【源头活水】CVPR 2023 | AbSViT：拥有自上而下注意力机制的视觉Transformer](https://mp.weixin.qq.com/s/FtVd37tOXMfu92eDSvdvbg)
  - 微信公众号「AI科技与算法编程」
    - [2023-04-11, YOLOv8 AS-One：目标检测AS-One 来了！（YOLO就是名副其实的卷王之王）](https://mp.weixin.qq.com/s/ofokLwCwgN1GNTqy3NuYmg)
  - 微信公众号「深度学习与NLP」
    - [2023-04-24，[万字干货]-如何给模型加入先验知识？](https://mp.weixin.qq.com/s/RmM9ay4arJWBoNP11Bfbsw)
  - 微信公众号「OpenCV与AI深度学习」
    - [2023-04-23，基于 YOLOv8 的自定义数据集训练](https://mp.weixin.qq.com/s/NrT7aFurdz5IRr3bCFsHQA)
    - [2023-06-19，一文彻底搞懂YOLOv8【网络结构+代码+实操】](https://mp.weixin.qq.com/s/HldcdtBXzh5YawcS0Bb4KQ)
    - [2023-07-04，保姆教程 | YOLOv5在建筑工地中安全帽佩戴检测的应用](https://mp.weixin.qq.com/s/g6jEP5Y2R_DhrI30DBol5Q)
    - [2024-06-05，实战 | YOLOv10 自定义数据集训练实现车牌检测 (数据集+训练+预测 保姆级教程)](https://mp.weixin.qq.com/s/3WSmGP7xdQJc-5YdQXBPFg)
    - [2024-06-21，YOLOv10在PyTorch和OpenVINO中推理对比](https://mp.weixin.qq.com/s/xZ4HlfBPXFbf8OPxmXwbrQ)
    - [2024-07-08，实战 | YOLOv8使用TensorRT加速推理教程（步骤 + 代码）](https://mp.weixin.qq.com/s/VcUifHycY9aw99d3WD1h1w)
    - [2024-07-10，OpenCV使用CUDA加速资料汇总(pdf+视频+源码)](https://mp.weixin.qq.com/s/o-AECBLDucxVLr1Q0yxZ_g)
    - [2024-09-30，YOLOv11来了：将重新定义AI的可能性](https://mp.weixin.qq.com/s/S_yjuxHb8PD3B472mvizfg)
  - 微信公众号「嵌入式视觉」
    - [2023-04-28，深度学习模型压缩方法概述](https://mp.weixin.qq.com/s/m4gZ1beM8QRzNegFPf3Mbg)
    - [2023-05-12，模型压缩-剪枝算法详解](https://mp.weixin.qq.com/s/7BCQD1s_1AZJoowivTnxOg)
  - 微信公众号「机器学习算法那些事」
    - [2023-05-02，labelGo：基于 YOLOv5 的辅助标注工具](https://mp.weixin.qq.com/s/4EFTj6RxOCvX2Wn5euhSAQ)
  - 微信公众号「人工智能技术与咨询」
    - [2023-05-19，基于YOLOv5的光学遥感图像舰船目标检测算法](https://mp.weixin.qq.com/s/Mic_wLbfjQrtX7wLwW1SiA)
    - [2023-06-06，面向弹载图像的深度学习网络压缩方法研究](https://mp.weixin.qq.com/s/pBXUnMpSmLg1BTDrJ19tgQ)
  - 微信公众号「StrongerTang」
    - [2022-10-07，自动驾驶多模态融合感知详解（研究现状及挑战）](https://mp.weixin.qq.com/s/g3KpWyc0QpLseN5-0CKySQ)
  - 微信公众号「北京大学王选计算机研究所」
    - [2022-10-12，NeurIPS 2022 | 面向自动驾驶多模态感知的激光雷达-相机融合框架](https://mp.weixin.qq.com/s/anth7mIqTGpJ4QWvTDbiSQ)
  - 微信公众号「计算机视觉深度学习和自动驾驶」
    - [2022-05-31，BEVFusion: 基于统一BEV表征的多任务多传感器融合](https://mp.weixin.qq.com/s/maKDU3sXbPxlEFz372qZTA)
  - 微信公众号「内推君SIR」
    - [2023-07-28，面经 | 计算机视觉 面经22](https://mp.weixin.qq.com/s/3pUMSOq4-eS2N7WNtbv02A)
  - 微信公众号「古月居」
    - [2023-07-06，YOLOv5训练自己的数据集(超详细)](https://mp.weixin.qq.com/s/UshIczcC8l7eHNf2CSrMKw)
  - 微信公众号「Streamlit」
    - [2023-05-18，Streamlit+Opencv打造人脸实时识别功能](https://mp.weixin.qq.com/s/I1HQ_E4UerZLkDT2-ch2SQ)
  - 微信公众号「FightingCV」
    - [2022-08-17，YOLOAir | 面向小白的目标检测库，更快更方便更完整的YOLO库](https://mp.weixin.qq.com/s/smwx-Ievs3rWMw_D4lSwqg)
    - [2023-07-29，自动驾驶新方法登Nature封面：让黑夜如白昼般清晰，浙大博士一作](https://mp.weixin.qq.com/s/bCUMjzc-Ws0_qjusFjM5Xw)
  - 微信公众号「AILab笔记」
    - [2023-06-08，【文献】视觉transformer研究进展——史上最全综述](https://mp.weixin.qq.com/s/zCbFEl8pvPIfjnfIgv8Hqw)
  - 微信公众号「CVer」
    - [2023-08-02，ICCV 2023｜目标检测新突破！AlignDet：支持各类检测器完全自监督预训练的框架](https://mp.weixin.qq.com/s/t7jlTyUP6UxplpythX0dOw)
  - 微信公众号「我爱计算机视觉」
    - [2023-06-09，[实践]YOLOv5提升10倍推理速度：利用TensorRT 在Jetson NX上的模型部署](https://mp.weixin.qq.com/s/jWZuNKpVM4k5aDe2JmB-Tg)
    - [2025-01-08，开放词汇检测新晋SOTA：地瓜机器人开源DOSOD实时检测算法](https://mp.weixin.qq.com/s/LhodjnA87KrmqXV1ioUIng)
  - 微信公众号「英特尔物联网」
    - [2022-08-11，基于 OpenVINO™️ 2022.1 POT API 实现 YOLOv5 模型 INT8 量化 | 开发者实战](https://mp.weixin.qq.com/s/DTXVXwf_tPxwsWbSxBv9Sw)
  - 微信公众号「数据科学与AI」
    - [2023-06-22，Win10环境下OpenVINO部署YOLOv5模型：从理论到实践](https://mp.weixin.qq.com/s/v4y-vjsUrlow5EaP_VrF0A)
  - 微信公众号「郭小喵玩AI」
    - [2023-06-22，Win10环境下OpenVINO部署YOLOv5模型：从理论到实践](https://mp.weixin.qq.com/s/v4y-vjsUrlow5EaP_VrF0A)
    - [2023-09-04，超详细 | 使用Yolov8训练自己的数据集](https://mp.weixin.qq.com/s/KdoZnQArI95eWvqHMeqO0A)
  - 微信公众号「郭小喵玩AI」
    - [2023-02-13，如何用OpenVINO™让YOLOv8获得1000+ FPS性能？](https://mp.weixin.qq.com/s/CroC5jiTh6OXGtFUbWLZwQ)
  - 微信公众号「AI视界引擎」
    - [2023-08-20，Fast-BEV的CUDA落地 | 5.9ms即可实现环视BEV 3D检测落地！代码开源](https://mp.weixin.qq.com/s/ypL9_QYcCFjxpdF9CrS2dw)
    - [2024-01-03，Shape-IoU开源 | 同时关注Box形状和尺寸，完美超越SIoU/EIoU/CIoU等，YOLO又有福了](https://mp.weixin.qq.com/s/sDOtseu4icePW2oQObMoWQ)
    - [2024-01-19，YOLOv4与卷积注意力以及ViT结合的进化版本YOLO-Former，精度稳步提升！](https://mp.weixin.qq.com/s/N-5nYylqOTx7tEISJYOuuw)
  - 微信公众号「小白玩转Python」
    - [2023-12-22，基于 YOLOv8 的疲劳状态检测 | 附源码](https://mp.weixin.qq.com/s/L_-Ii5QvnGgJwo5WYSUcVg)
    - [2024-01-22，YOLO-NAS 如何将 YOLO-v8 甩在身后？](https://mp.weixin.qq.com/s/pc7TzlZSULNJwIS-liCdzg)
    - [2024-04-28，小目标检测实战](https://mp.weixin.qq.com/s/42TqNGeaYpoZLBvBmeeAkg)
  - 微信公众号「机器之心」
    - [2024-02-23，目标检测新SOTA：YOLOv9问世，新架构让传统卷积重焕生机](https://mp.weixin.qq.com/s/HFyADfWKkyw0TivsqH6kXA)
  - 微信公众号「码科智能」
    - [2024-01-30，模型部署系列：10x速度提升，YoloV8目标检测模型稀疏化—CPU上超500FPS](https://mp.weixin.qq.com/s/cWRObjaRvL6RgabSdSxVBQ)
    - [2024-02-19，基于YOLO-World+EfficientSAM的零样本目标检测与实例分割Demo](https://mp.weixin.qq.com/s/u4QBbOeNR48aF9YHWdCQsw)
    - [2024-02-23，YOLOv9来了! 抛开损失函数和网络结构，换个可编程梯度信息角度继续升级，目标检测新SOTA！](https://mp.weixin.qq.com/s/TAv_GY3d-tPOX9fKZNBwig)
  - 微信公众号「自动驾驶Daily」
    - [2024-02-23，YOLOv9终于来了！远超现有实时目标检测器！使用PGI学你想学！](https://mp.weixin.qq.com/s/1i76NbtC5DD1lPMIMa9f8w)
    - [2024-05-25，YOLOv10来啦！真正实时端到端目标检测](https://mp.weixin.qq.com/s/xxgvub-Y4RJLjbpY6YNxCQ)
  - 微信公众号「3D视觉工坊」
    - [2024-02-23，YOLOv9震撼来袭！使用可编程梯度信息学习你想学习的内容！](https://mp.weixin.qq.com/s/Fbd-jarVO4LyjlhdxgmnsA)
    - [2024-06-18，YOLO跌落神坛？Mamba YOLO干翻YOLO系列模型！](https://mp.weixin.qq.com/s/MeFXqAyU_OAGnh7qEIb3yQ)
  - 微信公众号「DeepDriving」
    - [2023-07-21，AI模型部署 | TensorRT模型INT8量化的Python实现](https://mp.weixin.qq.com/s/IQTCUs8CcfgHxJCyV6cm3w)
    - [2024-05-29，YOLOv10来啦！ONNX模型部署和性能对比了解一下](https://mp.weixin.qq.com/s/w0Ss9vcseNCEoK2UWugCNw)
  - 微信公众号「CSharp与边缘模型部署」
    - [2024-06-04，使用 TensorRT C++ API 调用GPU加速部署 YOLOv10 实现 500FPS 推理速度——快到飞起！！](https://mp.weixin.qq.com/s/yijeZtkRhbQxuSE1AsyUhA)
  - 微信公众号「BestSongC」
    - [2024-05-24，基于YOLO系列算法（YOLOv5、YOLOv6、YOLOv8以及YOLOv9）和Streamlit框架的行人头盔检测系统](https://mp.weixin.qq.com/s/STAVjII8kAk3MMPbB9vJfQ)
    - [2024-05-29，基于YOLO系列算法YOLOv5、YOLOv6、YOLOv8以及YOLOv9和Streamlit框架的工人头盔和安全背心检测系统](https://mp.weixin.qq.com/s/Cuhwf2exVWFmoyZPQE_HmQ)
    - [2024-05-30，基于YOLO系列算法和Streamlit框架的六类水果目标检测系统](https://mp.weixin.qq.com/s/ZIH1afBpKBa5DgvtHZU1Vg)
    - [2024-06-11，基于YOLO系列算法（YOLOv5、YOLOv6、YOLOv8)以及YOLOv9）和Streamlit框架的五类动物目标检测系统](https://mp.weixin.qq.com/s/cEhgZYp7rUBFz2BukacQQg)
    - [2024-08-18，基于YOLO系列算法和Streamlit框架的车载摄像头下车辆检测系统](https://mp.weixin.qq.com/s/zPNGWQGNWDaMJHjxzlhRGA)
  - 微信公众号「人工智能学习指南」
    - [2024-05-28，用自己的数据集实测YOLOv10效果！](https://mp.weixin.qq.com/s/JlGvYGvPa5NyxjEXHLO6uA)
  - 微信公众号「跨模态AGI」
    - [2024-06-12，YOLO-NAS：开启实时目标检测新纪元](https://mp.weixin.qq.com/s/ASahqSAHoMFvRvBlnq5OzQ)
    - [2024-07-02，YOLOv10：实时目标检测的新星，引领AI视觉识别新纪元](https://mp.weixin.qq.com/s/JMPBJfMhUHg0472javPlpg)
    - [2024-07-05，揭秘YOLO-World：颠覆传统，开启实时开放词汇检测新时代](https://mp.weixin.qq.com/s/WGMNf4u8bA-t534avapJQw)
  - 微信公众号「魔方AI空间」
    - [2024-05-26，CV再放大招 | YOLOv10：毫秒级实时端到端目标检测开源模型](https://mp.weixin.qq.com/s/yQlkvlYnCz1H3JWTXCKc_A)
    - [2024-07-03，2万字长文｜YOLOv10的起源：YOLO系列的十年全面综述【YOLOv1-YOLOv10】(建议收藏)](https://mp.weixin.qq.com/s/1DYhy-flED1HwUX8YCQUPg)
  - 微信公众号「槿墨AI」
    - [2024-06-05，清华接棒YOLOv10开源，卷出毫秒级实时检测！](https://mp.weixin.qq.com/s/2DkhzmEllF5tom9FWHPz3g)
    - [2024-06-12，【超全解读】Drone-YOLO：无人机图像中的实时目标检测](https://mp.weixin.qq.com/s/XQh4MxPwfsWzDnUoiW4jww)
  - 微信公众号「计算机视觉工坊」
    - [2024-06-21，目标检测的极限在哪里？LW-DETR：干翻YOLOv10！](https://mp.weixin.qq.com/s/64HnNUs7r133hTFsmgWpEA)
  - 微信公众号「遥感与深度学习」
    - [2024-06-28，论文赏读 | 结合YOLOv9和Mamba的遥感小目标检测](https://mp.weixin.qq.com/s/FqFDS2Ih0uA9nuWMpbBDEA)
    - [2024-07-11，论文赏读 | Mamba YOLO: 基于SSM的YOLO 用于目标检测](https://mp.weixin.qq.com/s/Td-hwr-4UkIUheF7RJAi7Q)
  - 微信公众号「算法美食屋」
    - [2024-06-08，30分钟吃掉pytorch转onnx及推理](https://mp.weixin.qq.com/s/A1TCBqRJxXWzZKG1_KauMA)
  - 微信公众号「人工智能学起来」
    - [2024-06-25，小目标检测重大进展！速度提升10倍，GPU内存占用少73.4％](https://mp.weixin.qq.com/s/xbUKj3mHOyou5KpCi-04xw)
  - 微信公众号「柴火创客空间」
    - [2023-04-07，边缘计算 | 英伟达Jetson设备上的YOLOv8性能基准测试](https://mp.weixin.qq.com/s/uzvWMoMndwPmyLyDMnDqOQ)
  - 微信公众号「小小cv笔记」
    - [2024-08-12，微小目标检测中基于相似距离的标签分配(arxiv2024）](https://mp.weixin.qq.com/s/0wOmtfkQNt9VpdlOPHgnkA)
  - 微信公众号「阿旭算法与机器学习」
    - [2024-06-28，【YOLOv8模型onnx部署详解】YOLOv8模型转onnx格式并使用onnxruntime 进行推理部署](https://mp.weixin.qq.com/s/GUmql-aIgiFuJ9ll6dFucg)
    - [2024-10-14，YOLOv11与YOLOv8详细对比分析：mAP、Speed、Params、FLOPs](https://mp.weixin.qq.com/s/3ZkVmxpIcB036mAvvYWbow)
    - [2024-10-29，YOLO发展历程以及YOLOv8详解:基本架构、创新点与应用领域](https://mp.weixin.qq.com/s/K-kvKCl_yNclL8qTOrgCFA)
    - [2024-11-19，【模型级联】YOLO-World与SAM2通过文本实现指定目标的零样本分割](https://mp.weixin.qq.com/s/cnpmKr04E1imBBnmx6VTQw)
    - [2024-11-23，超详细！YOLO11模型架构详解、性能对比](https://mp.weixin.qq.com/s/gnoknU8iBjfbLo77vIbasw)
    - [2024-11-24，【深度好文】目标检测技术深度剖析：发展历程、关键技术、常用目标检测算法说明及应用](https://mp.weixin.qq.com/s/-1q0SMdUkklGu7PsrOKpGQ)
    - [2024-12-02，【实战】使用GroundingDino实现零样本自动标注【附源码】](https://mp.weixin.qq.com/s/dH5wFyOhevz37Lt4frVp0w)
    - [2024-12-04，【实战教程】小目标检测利器：使用YOLOv8和SAHI进行视频检测，检测效果真心不错](https://mp.weixin.qq.com/s/KTL-NeFO-eVmSm2RaLxYsw)
    - [2024-12-07，【实战教程】使用YOLOv8 OBB进行旋转框目标检测的数据集定义与训练【附源码】](https://mp.weixin.qq.com/s/LOD1xCKY08HVraxM-UDxvQ)
  - 微信公众号「人工智能与图像处理」
    - [2023-05-26，目标检测算法-YOLOV5解析（附论文与源码）](https://mp.weixin.qq.com/s/lfulLTp5SDrpim7nU1ZebA)
    - [2023-05-27，目标检测算法-YOLOV6解析（附论文与源码）](https://mp.weixin.qq.com/s/bG8KkDhs0ex8QZYS6QO5NA)
    - [2023-05-28，目标检测算法-YOLOV7解析（附论文与源码）](https://mp.weixin.qq.com/s/58XnV1Dy-1gc1ZYuY1XsVQ)
    - [2023-05-29，目标检测算法-YOLOV8解析（附论文和源码）](https://mp.weixin.qq.com/s/QwQhpEFX4Pxfik7PNOpwIA)
    - [2024-04-13，目标检测算法-YOLOV9解析（附论文和源码）](https://mp.weixin.qq.com/s/u8x6ePRmWV6z_FFnGUfUYA)
    - [2024-10-28，模型轻量化之模型剪枝-Pruning](https://mp.weixin.qq.com/s/3fffqlYLit30dI34TRZ5dw)
  - 微信公众号「地瓜机器人」
    - [2023-12-28，技术敲黑板 | 基于地平线RDK X3高效部署YOLOv5](https://mp.weixin.qq.com/s/IroAN_R7IvIxKHw8i-_1XQ)
    - [2024-06-27，技术敲黑板 | YOLOv8目标检测算法在地平线RDK X3上高效部署](https://mp.weixin.qq.com/s/zq4wLfEP3k5cns7xK4iSOg)
  - 微信公众号「深度AI视野」
    - [2025-01-07，Yolo11框架解析与代码重构—开篇](https://mp.weixin.qq.com/s/jYPJ5JsJL0LWSlXMkvzBtA)



  - 微信公众号「PandaCVer」
    - [2022-11-01, 目标检测算法——行人检测&人群计数数据集汇总(附下载链接)](https://mp.weixin.qq.com/s/8eDJ86rPA-0cWnLQKHxfjw)
    - [2022-11-21, 目标检测算法——工业缺陷数据集汇总1（附下载链接）](https://mp.weixin.qq.com/s/oRmPDF1YhIqYYdrgU7sTUQ)
    - [2022-12-01, 目标检测算法——图像分类开源数据集汇总（附下载链接）](https://mp.weixin.qq.com/s/9tGzWDAxp--42ofmKLlJRg)
  - 微信公众号「自动驾驶之心」
    - [2023-03-27, 目标跟踪方向开源数据集资源汇总](https://mp.weixin.qq.com/s/dCwtc-DI0KaPB4meJqewwA)
    - [2023-04-12, 包罗万象！V3Det：1.3W类全新目标检测数据集（港中文&上海AI Lab）](https://mp.weixin.qq.com/s/A-4ze7B3yQ-AYCe0DgHv-A)
  - 微信公众号「整数智能AI研究院」
    - [2022-03-10, 最全自动驾驶数据集分享系列一｜目标检测数据集（1/3）](https://mp.weixin.qq.com/s/eoMa1eUXPaZBlHeZReR77A)
    - [2022-03-21, 最全自动驾驶数据集分享系列一｜目标检测数据集（2/3）](https://mp.weixin.qq.com/s/nJFG6GHw60pRODoEKWj3bg)
    - [2022-04-24, 最全自动驾驶数据集分享系列一｜目标检测数据集（3/3）](https://mp.weixin.qq.com/s/r9d7NmcA3dymKRUhWoIPzw)




## Videos

  - bilibili「我是傅傅猪」
    - [2022-12-14，自制深度学习推理框架](https://www.bilibili.com/video/BV1HV4y1A7H8)
    - [2023-06-02，从零自制深度学习推理框架](https://www.bilibili.com/video/BV118411f7yM/)



## Star History

![Star History Chart](https://api.star-history.com/svg?repos=coderonion/awesome-yolo-object-detection&type=Date)