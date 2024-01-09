# Alzheimer's Disease Classification with CNN and Self-Attention

This repository contains a Convolutional Neural Network (CNN) based model for classifying brain MRI images into categories of Alzheimer's Disease (AD), Cognitive Normal (CN), and Mild Cognitive Impairment (MCI). The model is enhanced with a self-attention mechanism to improve overall performance.

## Dataset
The dataset used for training and evaluation is the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset. It includes brain MRI images corresponding to AD, CN, and MCI.

## Dependencies
Make sure you have the following libraries installed before running the code:
- scikit-learn
- TensorFlow
- Keras

You can install them using the following:
```bash
pip install scikit-learn tensorflow keras
```


## Model Architecture
The CNN architecture includes convolutional layers for feature extraction, pooling layers for down-sampling, and dense layers for classification. Self-attention mechanisms are incorporated to enhance the model's ability to focus on relevant image regions.

Feel free to experiment with different architectures and hyperparameters to optimize the model for your specific use case.

## Acknowledgments
- The ADNI dataset is acknowledged for providing the valuable data for this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
