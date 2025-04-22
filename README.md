# 🧠 Computer Vision Case Study – PCA, SIFT, and HOG for Object Recognition

This repository contains the final submission for my Computer Vision case study project. The objective of this study was to evaluate and compare three popular feature extraction techniques — **Principal Component Analysis (PCA)**, **Scale-Invariant Feature Transform (SIFT)**, and **Histogram of Oriented Gradients (HOG)** — for object recognition using the COIL-20 dataset.

---

## 📁 Contents

- 📄 `CVPR_CaseStudy.pdf` — Complete case study report including abstract, methods, results, discussion, and references.
- 📓 `CVPR_CaseStudy.ipynb` — Python notebook (Colab-ready) implementing PCA, SIFT, and HOG pipelines with KNN classifier.
---

## 📌 Highlights

- Dataset: [COIL-20](http://www.cs.columbia.edu/CAVE/software/softlib/coil-20.php)
- Classifier: K-Nearest Neighbors (KNN)
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC Curve
- Tools Used: Python, OpenCV, Scikit-learn, Matplotlib, Seaborn, Scikit-image

---

## 🧠 Summary of Findings

- **PCA + KNN** achieved the highest classification accuracy of **98.96%**
- **HOG + KNN** followed closely with **98.26%**
- **SIFT + KNN** performed slightly lower at **87.5%**
- PCA proved highly effective due to its global variance-based feature reduction
- HOG was robust for edge-based features; SIFT underperformed due to BoVW limitations

---

## ✅ How to Use

You can open the `.ipynb` notebook using [Google Colab](https://colab.research.google.com/) and run the entire pipeline step-by-step.

---

## 📧 Contact

For any queries or suggestions, feel free to reach out via GitHub or email.
