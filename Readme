# Real-Time Gun Detection System Using YOLOv9 and Node MCU Hardware Integration

![Project Banner](https://www.researchgate.net/publication/370148091/figure/fig1/AS:11431281156625554@1683565238613/Demonstration-of-automated-weapon-detection-using-CCTV-camera.jpg)

## Introduction
This project presents a real-time gun detection system using the YOLOv9 deep learning model, integrated with a NodeMCU ESP8266 microcontroller. By leveraging the power of advanced machine learning, it aims to deliver immediate and automated responses to detected firearms in various settings. The system combines high detection accuracy with immediate alerting via LED lights and buzzers, offering a robust solution to enhance public safety.

### Objectives
- Improve firearm detection accuracy using YOLOv9 trained on an annotated dataset.
- Reduce detection-to-alert response time through NodeMCU hardware integration.
- Ensure system performance in real-world scenarios, minimizing false positives.
- Highlight the utility of integrating object detection technologies with embedded systems for security.

## System Architecture
### Software Components
- **YOLOv9**: Detects firearms with high precision in video frames.
- **OpenCV**: Captures and processes video feeds in real time.
- **Python**: Manages object detection and communication with NodeMCU.

### Hardware Components
- **NodeMCU ESP8266**: Microcontroller acting as a server for receiving detection alerts.
- **LED Light & Buzzer**: Provide immediate physical alerts upon firearm detection.

### Workflow
1. **Video Capture**: OpenCV captures a live video stream.
2. **Object Detection**: YOLOv9 processes each frame and identifies firearms.
3. **Alert Trigger**: If a firearm is detected, the system sends an HTTP request to the NodeMCU.
4. **Physical Alert**: The NodeMCU triggers a LED and buzzer response to alert of the detection.

![System Workflow](path-to-your-workflow-diagram)

## Results
- **Precision/Recall/F1 Score**: The system achieved a peak F1 score of 0.97, precision of 0.981, and recall of 0.956.
- **Mean Average Precision**: mAP@0.5 was 0.987, and mAP@0.5:0.95 was 0.885.
- **Training Losses**: Consistent reduction in training and validation losses indicates robust model generalization.

![Performance Graphs](path-to-your-performance-graphs)

## Future Work
- **Dataset Expansion**: Include diverse environments and firearm types to improve model robustness.
- **Real-World Testing**: Validate performance in public spaces and controlled environments.
- **Integration with Surveillance**: Seamless integration with existing security systems via plugins/APIs.
- **Advanced Alerts**: Integrate mobile notifications and facial recognition for law enforcement alerts.
- **Edge Computing**: Deploy model on edge devices to reduce latency and bandwidth usage.
