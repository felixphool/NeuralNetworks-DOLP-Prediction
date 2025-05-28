# 🌽 DOLP Estimation for Corn Fields using LSTM + CNN

This project focuses on estimating the Degree of Linear Polarization (DOLP) in corn fields using real-time image analysis powered by deep learning techniques. By combining Convolutional Neural Networks (CNNs) for spatial feature extraction and Long Short-Term Memory (LSTM) networks for temporal pattern recognition, the system predicts DOLP from sequences of RGB images.

---

## 🧠 Why This Project?

Polarization cues can reveal subtle information about plant health and stress. This project explores how deep learning can be applied to agricultural imaging to support real-time crop monitoring and precision farming decisions — starting with corn fields.

---

## 🛠️ Tech Stack

- **Python**
- **NumPy**, **OpenCV**, **Matplotlib**, **scikit-image**
- **CNN** for spatial image feature extraction
- **LSTM** for temporal sequence modeling
- **Jupyter Notebook** for experimentation

---

## 📊 Dataset

RGB images captured over time from a corn field, processed to extract polarization-related data. The model is trained to recognize how DOLP changes based on visual cues in the image sequences.

---

## 🚀 How It Works

1. Load and preprocess image sequences from corn fields.
2. Extract spatial features using a CNN.
3. Feed the CNN outputs into an LSTM to learn temporal dependencies.
4. Predict the Degree of Linear Polarization (DOLP) in real time.

---

## 📁 Project Structure
ProjF2_ProjF.ipynb # Main Jupyter notebook
Data 2020/ # Folder with RGB input images
model/ # Trained model and weights 


---

## 📌 Future Work

- Incorporate multi-spectral and polarization-specific input.
- Improve robustness under varying lighting conditions.
- Expand to other crops and field types.

---

## 🙌 Acknowledgements

This project was developed as part of a coursework assignment for the Neural Networks and Deep Learning course under Dr. Edgar Lobaton and under the guidance of Dr. Michael Kudenov. Huge thanks to the instructors and peers for guidance and dataset support.

---


