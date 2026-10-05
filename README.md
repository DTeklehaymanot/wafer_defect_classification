# wafer_defect_classification

# GPU-Accelerated Wafer Defect Classification

## Overview
This project aims to classify semiconductor wafer-map defect patterns
by fine-tuning a pretrained ResNet-18 model using PyTorch.

The project will evaluate classification performance and compare
CPU and NVIDIA GPU execution speed using CUDA.

It analyzes existing wafer-test maps; it does not physically test wafers.

## Dataset
The project uses the **WM-811K Wafer Map Dataset** from Kaggle.

Dataset files will be stored separately from this repository.

## Goals
- Inspect and preprocess wafer maps and their labels.
- Create separate training, validation, and test sets.
- Fine-tune a pretrained ResNet-18 model.
- Evaluate accuracy, macro F1, precision, and recall.
- Analyze classification errors using a confusion matrix.
- Compare CPU and NVIDIA GPU performance using equivalent workloads.

## Tools
- **Python:** Programming language.
- **NumPy and pandas:** Data preparation and inspection.
- **Matplotlib:** Wafer-map displays and result visualizations.
- **PyTorch and torchvision:** Model development and training.
- **scikit-learn:** Data splitting and evaluation.
- **CUDA:** NVIDIA GPU computation.
- **Google Colab:** Notebook execution.
- **Git and GitHub:** Version control and documentation.

### Planned Extensions
- Export the trained model to ONNX.
- Explore TensorRT for faster GPU inference.
- Profile execution to investigate performance bottlenecks.
