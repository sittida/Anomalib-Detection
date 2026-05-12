# Anomalib-Detection

This project presents a comparative study of anomaly detection models using Anomalib
, focusing on PatchCore and PaDiM.
The workflow includes model evaluation, post-training quantization
, and performance optimization for deployment on edge and resource-constrained devices.

## Overview

- Compare the performance of PatchCore and PaDiM anomaly detection models.
- Evaluate model accuracy using AUROC metrics.
- Apply quantization techniques to optimize inference efficiency.
- Analyze trade-offs between accuracy, latency, and model size.
- Deploy lightweight optimized models suitable for edge-device environments.

## Evaluation Metrics

The models are evaluated using:
- AUROC (Area Under the Receiver Operating Characteristic Curve)
- Inference latency
- Model size reduction
- Memory consumption

## Technologies Used

- PyTorch
- OpenVINO™ Toolkit
- ONNX Runtime
- Anomalib

## Use Cases

- Industrial anomaly detection
- Smart manufacturing systems
- Edge AI deployment
- Low-resource embedded systems
- Real-time inspection applications


## Dataset Structure

```
path/to/mvtec_ad/
└── cable/
    ├── train/
    │   └── good/
    │
    ├── test/
    │   ├── good/
    │   └── crack/
    │
    └── ground_truth/
        └── crack/
```

