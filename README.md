# 🧠 Image Forgery Detection Based on Fusion of Lightweight Deep Learning Models (2023)

A **Tkinter-based desktop application** for detecting image forgeries using a **fusion of lightweight deep learning models** (SqueezeNet, ShuffleNet, and MobileNetV2). The project integrates traditional feature extraction (SIFT) and modern CNN-based fusion for enhanced accuracy, enabling users to visualize results, generate metrics, and compare model performance.

---

## 🔧 Technologies Used

* **Programming Language:** Python 3.x
* **GUI Framework:** Tkinter
* **Deep Learning:** TensorFlow, Keras
* **Machine Learning:** Scikit-learn, SVM
* **Computer Vision:** OpenCV, SIFT
* **Visualization:** Matplotlib, Seaborn
* **Dataset:** MICC-F220 Forgery Dataset

---

## ✅ Features

* Graphical User Interface built using **Tkinter**
* Upload and preprocess the **MICC-F220 dataset**
* Load pre-trained **SqueezeNet**, **ShuffleNet**, and **MobileNetV2** models
* Generate a **fusion model** by merging features from all CNNs
* Evaluate performance using **Precision, Recall, F1-Score, and Accuracy**
* Compare models with **Accuracy Graphs and Performance Tables**
* Baseline comparison with **SIFT + SVM model**
* Predict and visualize forgery detection results for test images

---

## 🧩 Workflow

1. **Upload Dataset:** Select the MICC-F220 dataset directory.
2. **Preprocess Data:** Normalize images and visualize a sample.
3. **Load Fusion Models:** Import pre-trained SqueezeNet, ShuffleNet, and MobileNet weights.
4. **Fine-Tune with SVM:** Extract deep features and classify them using SVM.
5. **Run Baseline Model:** Compare performance with traditional SIFT + SVM.
6. **Visualize Results:** Display confusion matrices, accuracy graphs, and HTML-based performance tables.
7. **Predict:** Test a single image to identify whether it’s forged or authentic.

---

## 🧠 Model Fusion

* **SqueezeNet:** Efficient CNN with high accuracy in lightweight form.
* **ShuffleNet:** Optimized for mobile and embedded applications.
* **MobileNetV2:** Feature-rich CNN with inverted residuals.

Features from all three models are extracted and concatenated, forming a **fine-tuned feature map**. This fused feature set is passed to an **SVM classifier** for final prediction.

---

## 📊 Evaluation Metrics

* **Precision**
* **Recall**
* **F1-Score**
* **Accuracy**

Each model’s metrics are stored and visualized in comparison graphs and confusion matrices.

---

## 📈 Output Visualizations

* Confusion matrices for SqueezeNet, ShuffleNet, MobileNet, Fusion Model, and SIFT-SVM.
* Accuracy comparison bar chart using **Matplotlib + Seaborn**.
* Performance summary displayed in an auto-generated **HTML table**.

---

## 🧩 How to Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/kvvr0076/Image-Forgery-Detection-project.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Ensure model files exist in the **model/** folder:

   * squeezenet_model.json / squeezenet_weights.h5
   * shufflenet_model.json / shufflenet_weights.h5
   * mobilenet_model.json / mobilenet_weights.h5
   * X.txt.npy / Y.txt.npy
4. Run the main program:

   ```bash
   python main.py
   ```
5. The GUI will open — follow the workflow buttons to perform forgery detection.

---

## 🪄 Example Outputs

| Algorithm          | Accuracy (%) | Precision | Recall | F1-Score |
| ------------------ | ------------ | --------- | ------ | -------- |
| SqueezeNet         | 93.2         | 91.8      | 92.5   | 92.1     |
| ShuffleNet         | 94.5         | 93.7      | 94.1   | 93.9     |
| MobileNetV2        | 95.6         | 94.9      | 95.3   | 95.1     |
| Fusion Model (SVM) | 97.8         | 97.1      | 97.4   | 97.3     |
| SIFT + SVM         | 88.3         | 86.9      | 87.4   | 87.1     |

---

## ☁️ Future Enhancements

* Add **real-time forgery detection** via webcam or image upload.
* Integrate **Grad-CAM heatmaps** for tamper region visualization.
* Deploy GUI as a **Streamlit Web Application**.
* Extend fusion models with **Vision Transformers (ViT)**.

---

## 🧑‍💻 Author

**Vishnuvardhan Reddy Komatireddy**
📅 Year: 2023
🔗 GitHub: [https://github.com/kvvr0076](https://github.com/kvvr0076)

---

**Live Repository:** [https://github.com/kvvr0076/Image-Forgery-Detection-project](https://github.com/kvvr0076/Image-Forgery-Detection-project)
