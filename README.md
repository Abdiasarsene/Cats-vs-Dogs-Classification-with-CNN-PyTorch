# 🐾 Cats vs Dogs Classification with CNN (PyTorch)
This project implements a **Convolutional Neural Network (CNN)** to classify images into two categories: **Cat** or **Dog**.  
It is designed as a beginner-friendly deep learning project, covering the essential steps of the machine learning pipeline.

---

### Validation
The script will display **loss** and **accuracy** on the validation set after each epoch.

---

## 📊 Results
Example training run (5 epochs):

```
Epoch 1, Loss: 0.6090
Epoch 2, Loss: 0.5071
Epoch 3, Loss: 0.8904
Epoch 4, Loss: 0.6948
Epoch 5, Loss: 0.3565

Validation Accuracy: 73.55%
```

👉 The loss generally decreases across epochs, and the validation accuracy reaches over **73%**, showing that the CNN successfully learns to distinguish cats from dogs.

---

## 🔮 Possible Improvements
- Add a third class `"Other"` to handle out-of-domain images.  
- Use **pre-trained models** (ResNet, EfficientNet) for transfer learning.  
- Implement a **learning rate scheduler** for better convergence.  
- Apply **data augmentation** to improve robustness.  

