# Object and Sub-Object Detection using Faster R-CNN

This project demonstrates real-time object and sub-object detection using a pre-trained Faster R-CNN model from PyTorch's `torchvision` library. The system processes video streams or webcam input to detect objects, draw bounding boxes, and generate JSON outputs.

---

## Features
- **Real-Time Object Detection**: Detects objects in video streams or webcam feeds with bounding boxes and confidence scores.
- **Hierarchical JSON Output**: Generates structured JSON output with object and sub-object information.
- **Customizable Thresholds**: Filters detections based on confidence thresholds.
- **Frame Processing Benchmark**: Displays frames per second (FPS) for performance monitoring.

---

## Prerequisites

Before running the project, ensure the following libraries are installed:

```bash
pip install opencv-python torch torchvision
