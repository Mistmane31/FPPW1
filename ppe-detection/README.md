_______________________________________________

PPE Detection System for Workplace Safety
_______________________________________________

Project Overview

This project develops an AI-based system that can detect Personal Protective Equipment (PPE) such as hard hats, safety vests, and masks in workplace images. The goal is to improve workplace safety by automatically identifying whether workers are properly equipped with required safety gear.

The system uses deep learning and computer vision techniques to detect PPE in images or employ a real-time detection via a webcam. The core model will be an object detection model (YOLOv8) trained on labeled datasets containing construction site images. The project also integrates NLP and reinforcement learning components.

_______________________________________________

Objectives:

- Develop an object detection model capable of identifying PPE in workplace images.

- Evaluate the system using standard detection metrics such as mAP@0.5 and Precision-Recall curves.

- Integrate a CNN-based vision model, an NLP component, and a reinforcement learning component.

- Analyze ethical considerations related to workplace surveillance and privacy.

_______________________________________________

Project Components:

Computer Vision (CNN)
A YOLO-based object detection model will be trained to detect PPE items including:
- Hard hats
- Safety vests
- Masks

Natural Language Processing (NLP)
An NLP module may be used to:
- Generate text descriptions or safety reports from detection results.

Reinforcement Learning (RL)
A reinforcement learning agent may be used to:
- Optimize system decisions such as alert thresholds or detection policies.

_______________________________________________

Dataset

The dataset will be sourced from public PPE detection datasets available on platforms such as Kaggle or Roboflow. These datasets contain labeled images of workers with annotations for PPE items.

The dataset will be divided into:
- Training set
- Validation set
- Test set

Preprocessing steps may include image resizing, normalization, and data augmentation.

_______________________________________________

Repository Structure

project-root/
│
├── README.md
├── requirements.txt
│
├── data/
├── src/
├── notebooks/
├── experiments/
└── docs/

_______________________________________________

Week 1 Progress

- Project proposal document
- Repository structure initialized
- Dataset sources identified
- Model approach planned

Team Members:

- Arcuino, Shan Harvey H.
- De Leon, Kim Alyson R.
- Palma, Jasmine Rose A.
- Ruiz, Eina Loux M.

_______________________________________________

Ethical Considerations

This project considers potential ethical issues including:
- Worker privacy concerns
- Responsible use of surveillance technologies
- Minimization of personal data collection

The system is intended for research and educational purposes only.
