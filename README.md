# Lung Cancer Classification Project

This project implements deep learning models for classifying lung cancer cases from CT scan images using various architectures including EfficientNet, ResNet50, VGG-16, and others.

## Dataset

The dataset comes from the Iraq-Oncology Teaching Hospital/National Center for Cancer Diseases (IQ-OTH/NCCD) containing 1190 CT scan images of 110 cases classified into three categories:
- Normal (55 cases)
- Benign (15 cases)
- Malignant (40 cases)

## Models Implemented

- EfficientNet
- ResNet50
- VGG-16
- VGG-19
- ResNeXt101
- Custom architectures

## Requirements

```
pip install datasets transformers tensorflow numpy matplotlib opencv-python scikit-learn
```

## Usage

1. Clone this repository
2. Install dependencies
3. Run the Jupyter notebooks for each model:
   - `EfficientNet/EfficientNet.ipynb`
   - `Resnet50/resnet50.ipynb`
   - `VGG16/VGG16.ipynb`
   - etc.

## Results

Model performance metrics and training results are stored in the `.h5` files for each model.

## License

This project is for research purposes only.