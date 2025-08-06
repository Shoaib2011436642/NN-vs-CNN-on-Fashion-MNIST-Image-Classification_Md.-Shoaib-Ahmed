# NN vs CNN on Fashion MNIST Image Classification

This project compares the performance of a basic Neural Network (NN) and a Convolutional Neural Network (CNN) on the Fashion MNIST dataset. It aims to demonstrate the impact of architecture choice on model accuracy and generalization in image classification tasks.

## Objective
To investigate how different deep learning architectures (feedforward NN vs CNN) perform when classifying clothing item images. The goal is to understand the advantages of spatial feature extraction through convolutions compared to dense-layer-only networks.

## Real-World Importance
Fashion MNIST simulates a real-world scenario of classifying clothing and accessories — relevant to e-commerce, inventory management, and retail automation. The experiment demonstrates how CNNs, being spatially aware, outperform simple NNs for visual recognition tasks.

## 🛠Libraries Used
- `TensorFlow` / `Keras` – To build both NN and CNN architectures.
- `Matplotlib`, `Seaborn` – For visualizing accuracy, loss, and confusion matrix.
- `Sklearn` – For precision, recall, and F1 score evaluation.

## Models & Techniques
- **Basic Neural Network**:
  - Flattened input fed into dense layers with dropout.
  - Decent accuracy but limited in capturing spatial features.
  
- **Convolutional Neural Network (CNN)**:
  - Stack of Conv2D + MaxPooling layers followed by dense layers.
  - Better performance due to feature extraction and spatial understanding.
  
- Both models trained with `categorical_crossentropy` loss and `Adam` optimizer.

## Expected Results
CNN is expected to significantly outperform the dense-only NN, especially on unseen validation data. The accuracy gap clearly reflects the CNN’s superior ability to generalize image-based patterns.

---

## Author

**Md. Shoaib Ahmed Afif**   
 B.Sc. in CSE – North South University  
 [LinkedIn](https://www.linkedin.com/in/md-shoaib-ahmed-133562207/)
