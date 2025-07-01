# Vision Transformer (ViT) Project

This project explores the use of **Vision Transformers (ViT)** for image classification tasks. Inspired by the Transformer architecture used in NLP, ViT applies self-attention mechanisms directly to image patches — enabling powerful performance in visual tasks.

---

## 📁 Project Structure

```
VIT-Project/
│
├── Apple/              # Apple dataset, Code, Accuracy Result 
├── corn/               # Corn dataset, Code, Accuracy Result 
├── grape/              # Grape dataset, Code, Accuracy Result 
├── FlowChart.png       # Model flowchart
├── output 1-4.png      # Output visualizations
└── README.md           # Project documentation
```

---

## 🚀 Features

- ✅ Vision Transformer implementation from scratch
- 📊 Classification for multiple fruit types (Apple, Corn, Grape)
- 🔍 Attention visualization & output predictions
- 📈 Custom dataset support and evaluation metrics
- 🧠 Built for explainability and modular experimentation

---

## 🛠️ Tech Stack

- Python
- PyTorch / TensorFlow (specify based on your code)
- OpenCV / PIL
- NumPy / Pandas
- Matplotlib / Seaborn

---

## 🧪 Dataset

The project uses custom or publicly available datasets for:
- 🍎 Apple Leaf Disease Classification
- 🌽 Corn Leaf Disease Detection
- 🍇 Grape Leaf Disease Identification

> You can replace or expand the dataset by dropping new images into the respective folders.

---

## 🧠 Model Overview

![Flowchart](./FlowChart.png)

---

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Akil-M/Projects.git
   cd Projects/VIT-Project
   ```

2. (Optional) Set up a virtual environment:
   ```bash
   python -m venv vit-env
   source vit-env/bin/activate  # or vit-env\Scripts\activate on Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the training script:
   ```bash
   python train.py
   ```

---

## 🔍 Results

| Class        | Accuracy (%) |
|--------------|--------------|
| Apple        | 99.5         |
| Corn         | 99.3         |
| Grape        | 99.1         |

> *These are example values — update them with your actual results!*

---

## 📬 Contact

Created with ❤️ by **Akil M**  
📧 akilmasiv@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/akil-m-343359254)

---
