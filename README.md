# CNN-with-CIFAR-10
This project uses a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 data set into 10 object classes. The model is optimized for high accuracy (~90%), efficiency, and readability with precise evaluation metrics such as confusion matrix, accuracy/loss plots, and classification report.
Requirements
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

Dataset
- This project uses the **CIFAR-10 dataset**, which contains 60,000 32x32 color images in 10 classes (e.g., airplane, car, bird, cat, etc.).
- The dataset is split into:
  - **50,000 training images**
  - **10,000 testing images**

Preprocessing
- **Normalization:** Pixel values are scaled to the range [0, 1].
- **One-hot encoding:** Labels are converted to one-hot vectors.
- **Optional augmentation:** Random flips and rotations to improve model generalization.

---

Workflow
1. **Load Dataset** – Using `tensorflow.keras.datasets` or custom dataset loading.
2. **Preprocess Data** – Normalize images, encode labels, and optionally augment data.
3. **Build CNN Model** – Convolution + ReLU + MaxPooling layers, followed by Dense layers.
4. **Compile Model** – Optimizer: Adam, Loss: Categorical Crossentropy, Metrics: Accuracy.
5. **Train Model** – Train on the training set and validate on test data.
6. **Evaluate Model** – Evaluate test accuracy and loss.
7. **Visualize Results** – Plot training/validation accuracy and loss, display sample predictions.

**RESULT**
<img width="1184" height="541" alt="image" src="https://github.com/user-attachments/assets/fd2daae5-d08c-4822-9ed8-9acb0bdc42f3" />
<img width="814" height="652" alt="image" src="https://github.com/user-attachments/assets/cf584056-35ae-45b4-889f-723b3179e306" />
<img width="561" height="392" alt="image" src="https://github.com/user-attachments/assets/41f9afe3-4e71-49a0-9c23-a4cf11be194b" />


