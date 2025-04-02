# Multi-Class Animal Recognition

## Overview
This project implements a **multi-class animal recognition model** using deep learning techniques. The model is trained to classify images of different animal species using a convolutional neural network (CNN).

## Dataset
The dataset consists of labeled images of multiple animal species. The dataset is preprocessed and augmented before being fed into the model.

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hemalatha0409/Multi-Class-Animal-Recognition.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Multi-Class-Animal-Recognition
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset Preparation
1. Download the dataset and place it in the `data/` directory.
2. Ensure the dataset is structured properly:
   ```
   data/
   |-- train/
   |   |-- class_1/
   |   |-- class_2/
   |   |-- ...
   |-- test/
   |   |-- class_1/
   |   |-- class_2/
   |   |-- ...
   ```

## Model Training
Run the Jupyter Notebook to train the model:
```bash
jupyter notebook Multi_Class_Animal_Recognition.ipynb
```

## Evaluation
After training, the model is evaluated on test data to compute accuracy, precision, recall, and F1-score.

## Results
The trained model achieves an accuracy of **83.33%** on the test dataset. Sample predictions are visualized using Matplotlib.

## Usage
- Run the model on new images:
  ```python
  from model import predict_animal
  result = predict_animal('path/to/image.jpg')
  print(f'Predicted Class: {result}')
  ```

## Future Improvements
- Train on a larger dataset for better generalization.
- Experiment with different architectures (ResNet, EfficientNet, etc.).
- Implement real-time classification using a webcam.

## Contributors
- **B Hemalatha** - Project Development


