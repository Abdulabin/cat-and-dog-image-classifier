# 🐱 Cat vs. Dog Classifier: CNN Power

Build a high-accuracy image recognition tool that knows the difference between a feline and a canine. This project uses **Deep Learning** and **Data Augmentation** to turn a small dataset into a robust, "smart" model.

---

## 🚀 Why This Matters

Training AI usually requires thousands of images. Without them, the model **overfits** (it memorizes the training photos but fails on new ones).

**The Solution:** This project uses "Data Augmentation" to flip, zoom, and twist images, teaching the AI to recognize the *animal*, not just the *photo*.

---

## Tech Stack

* **Language:** Python
* **Deep Learning:** TensorFlow & Keras
* **Math & Charts:** NumPy & Matplotlib

---

### how the model learns over time

![alt text](images/image.png)
---

## Getting Started

### 1. Setup

```bash
pip install -r requirements.txt

```

### 2. Data Prep

1. Grab the dataset from [Kaggle](https://www.kaggle.com/datasets/sanchitnamdeo/catvsdog).
2. Organize your folders like this:
* `training_data/` (for learning)
* `test_data/` (for final exams)



### 3. Run It

| Step | File | Purpose |
| --- | --- | --- |
| **01** | `data_augmentation.ipynb` | Transforms your images to boost variety. |
| **02** | `cnn_cat_dog_classification.ipynb` | Trains the "brain" and tests its accuracy. |

---
