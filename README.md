# 🖼️ Image Forgery Detection using Machine Learning (2023)

A computer vision and machine learning project developed in **2023** to detect tampered or forged images using feature extraction and classification techniques. The project identifies image manipulations such as copy-move, splicing, and resampling using advanced digital image forensics methods.

---

## 🔧 Technologies Used

* **Language:** Python 3.x
* **Libraries:** OpenCV, NumPy, Scikit-learn, Matplotlib, TensorFlow/Keras (optional for deep learning)
* **Techniques:** Feature Extraction, PCA, CNN (optional), Machine Learning Classifiers
* **IDE:** Jupyter Notebook / PyCharm
* **Version Control:** Git & GitHub

---

## ✅ Features

* Detects manipulated or tampered regions in digital images
* Uses **Copy-Move Forgery Detection (CMFD)** and **Splicing Detection** algorithms
* Extracts key features like color, texture, and edge details for analysis
* Employs **ML classifiers** such as SVM, Logistic Regression, and Random Forest for forgery classification
* Visualizes forged regions and authenticity probability
* Can be extended with **CNN-based models** for deep feature extraction

---

## 📊 Workflow

1. **Data Collection:** Load dataset of real and forged images
2. **Preprocessing:** Resize, normalize, and convert images to grayscale if required
3. **Feature Extraction:** Use ORB/SIFT/SURF or deep features from CNN
4. **Training:** Train ML classifiers on extracted features
5. **Detection:** Predict whether an image is forged or authentic
6. **Visualization:** Highlight manipulated areas and display confidence levels

---

## 🧠 Algorithms & Concepts

* **SIFT (Scale-Invariant Feature Transform)** for keypoint detection
* **ORB (Oriented FAST and Rotated BRIEF)** for efficient feature matching
* **PCA** for dimensionality reduction
* **SVM / Random Forest / Logistic Regression** for classification
* **CNN (optional)** for deep learning-based forgery detection

---

## 🧩 How to Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/kvvr0076/Image-Forgery-Detection-project.git
   ```
2. Navigate to the project folder:

   ```bash
   cd Image-Forgery-Detection-project
   ```
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Image_Forgery_Detection.ipynb
   ```

   or execute the script:

   ```bash
   python image_forgery_detection.py
   ```

---

## 📈 Results

* Detected forged regions highlighted on test images
* Achieved high classification accuracy using SVM and Random Forest models
* Successfully differentiated between authentic and tampered images

---

## 🪄 Example Output

| Image       | Status    | Confidence |
| ----------- | --------- | ---------- |
| car1.jpg    | Authentic | 98.4%      |
| car2.jpg    | Forged    | 92.7%      |
| nature1.jpg | Authentic | 97.3%      |

---

## ☁️ Future Enhancements

* Integration with **Deep Learning CNN models** for higher accuracy
* Deploying as a **Streamlit web app** for real-time image upload and detection
* Expanding dataset for general image forgery detection
* Adding localization heatmaps using **Grad-CAM** for deep models

---

## 🧑‍💻 Author

**Vishnuvardhan Reddy Komatireddy**
📅 Year: 2023
🔗 GitHub: [https://github.com/kvvr0076](https://github.com/kvvr0076)

---

**Live Repository:** [https://github.com/kvvr0076/Image-Forgery-Detection-project](https://github.com/kvvr0076/Image-Forgery-Detection-project)
