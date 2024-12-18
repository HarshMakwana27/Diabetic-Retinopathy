
# Diabetic Retinopathy Detection

This project implements a **Convolutional Neural Network (CNN)** to detect **Diabetic Retinopathy** from retinal images. The model aims to classify retinal images into different stages of diabetic retinopathy, leveraging deep learning techniques for accurate medical diagnosis.

## Features

- Preprocessing of retinal images for optimal model input.
- Training a CNN using TensorFlow/Keras for classification.
- Visualization of training metrics and model predictions.
- Evaluation of model performance using accuracy, precision, and recall.

## Dataset

The dataset used in this project consists of retinal images labeled with different levels of diabetic retinopathy. Ensure the dataset is structured as follows:

```
dataset/
├── train/
│   ├── class_0/
│   ├── class_1/
│   ├── ...
├── validation/
│   ├── class_0/
│   ├── class_1/
│   ├── ...
```

Here `class_0`, `class_1`, represents the level of severeness of DR.

## Prerequisites

- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib
- Pandas
- OpenCV

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/diabetic-retinopathy-detection.git
    cd diabetic-retinopathy-detection
    ```

2. Prepare your dataset following the structure mentioned above.

3. Run the notebook:
    ```bash
    jupyter notebook DR.ipynb
    ```

4. Follow the notebook instructions to preprocess data, train the model, and evaluate its performance.

## Key Sections of the Notebook

- **Data Preprocessing**: Standardizes the input images and applies augmentation techniques.
- **Model Building**: Defines a CNN architecture suitable for image classification.
- **Training and Evaluation**: Trains the model and evaluates it using metrics like accuracy and confusion matrix.
- **Predictions**: Demonstrates model predictions on new images.

## Results

The trained model achieves the following performance on the test set:

- **Accuracy**: 79.60000038146973%

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy coding!
