# 🌾 Rice Leaf Disease Detection using CNN & U-Net

An AI-powered rice leaf disease detection system developed using **Convolutional Neural Networks (CNNs)** and **U-Net segmentation** for accurate and real-time identification of rice leaf diseases.

This project was developed as a Mini Project for the Department of Computer Science & Engineering, RV Institute of Technology and Management (VTU).

---

# 📌 Project Overview

Rice diseases significantly reduce crop productivity and quality. Traditional disease detection methods rely on manual inspection, which can be:
- time-consuming,
- inconsistent,
- and dependent on agricultural expertise.

This project automates rice disease detection using Deep Learning and Computer Vision techniques.

The system:
- segments infected regions using U-Net,
- analyzes lesion patterns,
- classifies diseases using CNN,
- and displays results through a Streamlit/Python-based interface.

---

# 🧠 Features

✅ Rice leaf disease classification  
✅ U-Net lesion segmentation  
✅ Narrow Brown Spot detection using rule-based logic  
✅ Bounding box visualization  
✅ Real-time prediction  
✅ Deep learning-based image analysis  

---

# 🦠 Diseases Detected

The system can identify:

- Bacterial Leaf Blight
- Leaf Blast
- Leaf Scald
- Heath Blast
- Narrow Brown Spot
- Healthy Leaf

---

# 🛠️ Technologies Used

## Languages & Frameworks
- Python
- TensorFlow
- Keras
- OpenCV

## Libraries
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Pillow

## Development Tools
- Jupyter Notebook
- Streamlit
- VS Code

---

# 📂 Project Structure

```bash
Rice-Leaf-Disease-Detection/
│
├── rice.py
├── Rice_Disease.ipynb
├── U_Net.ipynb
├── test_images/
├── README.md
└── requirements.txt
```

---

# 🤖 Model Files

Due to GitHub file size limitations, the trained model files are hosted on Google Drive.

## Download Models

### CNN Classification Model
https://drive.google.com/file/d/1mYhQybTDTmaNX6hUUtFsEzS-vd0AUNqk/view?usp=drive_link

### U-Net Segmentation Model
https://drive.google.com/file/d/1QpljoJJxm3sV-GTKart0eA4QpXRaQ3AG/view?usp=sharing


After downloading:
- place `rice_cnn.h5`
- and `unet80.h5`

inside the project root folder.

---

# 🚀 Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/rice-leaf-disease-detection.git
cd rice-leaf-disease-detection
```

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 3️⃣ Download Model Files

Download:
- `rice_cnn.h5`
- `unet80.h5`

from the Google Drive links above.

Place them in the main project directory.

---

# ▶️ Run the Project

```bash
python rice.py
```

---

# 🧪 Model Information

## U-Net Segmentation
Used for:
- lesion localization,
- infected region extraction,
- mask generation.

### Performance
- Dice Score: **0.86**
- IoU Score: **0.74**
- Pixel Accuracy: **99%**

---

## CNN Classification
Used for:
- disease classification,
- feature extraction,
- real-time prediction.

### Performance
Overall accuracy achieved:
- **85% – 88%**

---

# 📊 Dataset

The dataset contains rice leaf images categorized into:
- diseased leaves,
- healthy leaves,
- segmented lesion masks.

Dataset sources:
- Kaggle
- Field-captured images
- Agricultural research datasets

---

# 🔄 Data Augmentation

Applied augmentation techniques:
- Rotation
- Flipping
- Zooming
- Brightness adjustment
- Random cropping

---

# 📸 Output Features

The system provides:
- segmented lesion masks,
- disease prediction labels,
- contour detection,
- bounding box visualization.

---

# 🌱 Future Improvements

- Mobile application deployment
- Cloud hosting
- Real-time camera detection
- Multi-crop disease detection
- IoT integration for smart farming

---

# 👨‍💻 Team Members

- VINAYAK ARUN NAIK
- SAMEEKSHA UDAY NAIK

---

# 🎓 Institution

Department of Computer Science & Engineering  
RV Institute of Technology and Management  
Visvesvaraya Technological University (VTU)

---

# 📜 License

This project is developed for academic and educational purposes.

---

# 🙏 Acknowledgement

We sincerely thank our guide Mrs. Padmasree N and the Department of CSE, RVITM, for their continuous support and guidance throughout the project.
