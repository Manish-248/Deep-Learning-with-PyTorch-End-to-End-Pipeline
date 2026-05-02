# 🧠 Deep Learning with PyTorch: End-to-End Pipeline

## 📌 Overview

This project demonstrates a complete deep learning workflow using **PyTorch**, covering everything from data preprocessing to model training, evaluation, and persistence.

The goal of this notebook is to showcase practical implementation skills in building and deploying neural networks using industry-standard practices.

---

## 🚀 Key Highlights

* ✅ Real-world dataset (Iris Dataset)
* ✅ Data preprocessing & normalization
* ✅ Train/Test split strategy
* ✅ PyTorch DataLoader for batching
* ✅ Custom Neural Network architecture
* ✅ Training loop with backpropagation
* ✅ Model evaluation (accuracy)
* ✅ Visualization of training performance
* ✅ Model saving & loading (deployment-ready)

---

## 🧱 Project Structure

```
📦 PyTorch-Deep-Learning
 ┣ 📜 notebook_2_pytorch.ipynb
 ┣ 📜 model.pth
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
```

---

## 📊 Dataset

* **Dataset Used:** Iris Dataset
* **Features:**

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* **Target:** Flower Species (3 classes)

---

## 🧠 Model Architecture

The neural network consists of:

* Input Layer (4 features)
* Hidden Layer 1 (16 neurons, ReLU)
* Hidden Layer 2 (8 neurons, ReLU)
* Output Layer (3 classes)

---

## ⚙️ Training Details

* Loss Function: CrossEntropyLoss
* Optimizer: Adam
* Learning Rate: 0.01
* Epochs: 50

---

## 📈 Results

* Training completed successfully
* Model achieves high accuracy on test data
* Loss decreases steadily across epochs

---

## 📊 Visualization

The notebook includes:

* Training Loss Curve
* Model performance evaluation

---

## 💾 Model Persistence

The trained model is saved using:

```python
torch.save(model.state_dict(), "model.pth")
```

And can be loaded using:

```python
model.load_state_dict(torch.load("model.pth"))
```

---

## 🛠️ Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📌 Why This Project Matters

This project demonstrates:

* Practical deep learning implementation
* Understanding of neural networks and optimization
* Ability to build reproducible ML pipelines
* Clean and production-ready coding practices

---

## 🔮 Future Improvements

* Add validation loop
* Implement early stopping
* Hyperparameter tuning
* Confusion matrix & classification report
* Deploy model using API (Flask/FastAPI)

---

## 👨‍💻 Author

**Manish Chandra**

---

## ⭐ If you like this project

Feel free to ⭐ the repository and connect!
