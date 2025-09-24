# 🩻 Chest X-ray Image Classification

This project focuses on developing a **multi-label image classification model** to predict pathological conditions from frontal chest X-ray images. It leverages deep learning to provide accurate predictions that can assist clinicians in diagnosing various diseases.

---

## 🚀 Overview

- Uses the **ChestX-ray8 dataset**, which contains 108,948 images from 32,717 patients.  
- Each image comes with multiple text-mined labels, enabling classification of **14 disease categories**.  
- Goal: Build a robust classifier to detect multiple conditions simultaneously.

---

## 📊 Workflow

1. **Data Acquisition & Preprocessing**  
   - Resize images to a fixed input size.  
   - Normalize pixel values.  
   - Apply augmentation (rotation, flips, shifts).  

2. **Feature Extraction**  
   - Convolutional Neural Networks (CNNs) for hierarchical feature learning.  

3. **Model Architecture**  
   - Multi-label classification network.  
   - Dense layers with sigmoid activations for multiple outputs.  

4. **Training**  
   - Optimizer: Adam / RMSProp.  
   - Loss: Binary Cross Entropy.  
   - Evaluation metrics: Accuracy, Precision, Recall, AUC.  

5. **Evaluation**  
   - Measure performance on validation/test sets.  
   - Visualize ROC curves and confusion matrices.  

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy, Pandas, Matplotlib**
- **Scikit-learn**

---

## 📂 Project Structure

\`\`\`
Chest-X-ray-Image-Classification/
│── data/                # Dataset (ChestX-ray8 or sample subset)
│── models/              # Saved models / weights
│── notebooks/           # Training & evaluation notebooks
│── utils/               # Helper functions (preprocessing, plotting)
│── chest.html           # Project page (Pinterest-style)
│── chest.css            # Stylesheet
│── README.md            # Project documentation
\`\`\`

---

## 📈 Results

- Achieved high performance in predicting multiple disease categories.  
- Metrics reported: **Accuracy, AUC, Precision, Recall, F1-score**.  
- Visualization of predictions and label distributions included in notebooks.  

---

## 📸 Demo Screenshot

![Chest X-ray Example](assets/chest_xray.png)

---

## 🔗 Links

- **GitHub Repo:** [Chest-X-ray-Image-Classification](https://github.com/kru2710shna/Chest-X-ray-Image-Classification)

---

## 🤝 Contributing

Contributions are welcome!  
1. Fork the repository.  
2. Create a new branch (\`feature-xyz\`).  
3. Commit your changes.  
4. Open a Pull Request.  

---

## 📜 License

This project is licensed under the **MIT License**.
