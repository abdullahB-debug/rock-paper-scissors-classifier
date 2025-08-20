# Rock–Paper–Scissors CNN Classifier ✊✋✌️

This project implements a **Convolutional Neural Network (CNN)** in **Python (PyTorch)** to classify images of **rock, paper, and scissors** hand gestures.  
It demonstrates preprocessing, data augmentation, model training, evaluation, and comparison with transfer learning (MobileNetV2).

---

## 📌 Project Overview
- Built and trained a CNN from scratch for 3-class image classification.
- Applied **data augmentation** (flips, rotations, normalization) to improve generalization.
- Compared performance against a **MobileNetV2 transfer learning model**.
- Evaluated using **accuracy curves, confusion matrices, and sample predictions**.
- Designed for reproducibility (seeded runs, modular notebook).

---

## 📂 Repository Structure
```
rock-paper-scissors-classifier/
 ├─ Data/                # dataset folder (not included in repo)
 │   └─ README.md        # explains how to download dataset from Kaggle
 ├─ results/             # saved plots (confusion matrix, accuracy curves, etc.)
 ├─ .gitignore
 ├─ LICENSE
 ├─ README.md
 ├─ requirements.txt
 └─ rock_paper_scissors_cnn.ipynb   # main notebook
```

---

## 📊 Results
- **Custom CNN:** ~82% accuracy on test set  
- **MobileNetV2 Transfer Learning:** ~95% accuracy (higher stability across datasets)  
- Common misclassifications: blurred images or low-light hand gestures  
- Key plots are available in `/results/`:
  - Training vs validation accuracy curve
  - Confusion matrix
  - Sample predictions

---

## 🚀 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/abdullahB-debug/rock-paper-scissors-classifier.git
   cd rock-paper-scissors-classifier
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the dataset**
   - Download the dataset from Kaggle:  
     https://www.kaggle.com/datasets/alexandredj/rock-paper-scissors-dataset
   - Follow instructions in [`Data/README.md`](Data/README.md) to set up the folder structure.

4. **Run the notebook**
   ```bash
   jupyter notebook rock_paper_scissors_cnn.ipynb
   ```

---

## 🛠 Tech Stack
- Python 3.x  
- PyTorch & Torchvision  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- scikit-learn  

---

## 📜 License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🙌 Acknowledgements
- **Dataset:** [Rock–Paper–Scissors Dataset on Kaggle](https://www.kaggle.com/datasets/alexandredj/rock-paper-scissors-dataset) by *Alexandre Dj*.  
- Thanks to the PyTorch and Kaggle communities for resources and tutorials.
