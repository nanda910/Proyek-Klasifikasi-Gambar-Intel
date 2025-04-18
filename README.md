# Proyek-Klasifikasi-Gambar-Intel

# 🧠 Intel Image Classification with CNN

Klasifikasi citra menggunakan Convolutional Neural Network (CNN) pada dataset **Intel Image Classification** dari Kaggle. Proyek ini mengeksplorasi preprocessing, augmentasi, pelatihan model CNN, dan ekspor model ke format `SavedModel`, `TFLite`, dan `TensorFlow.js`.

---

## 📁 Dataset

Dataset diambil dari Kaggle:  
[Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

Dataset berisi 6 kelas citra alam:
- 🌇 Buildings  
- 🌲 Forest  
- ❄️ Glacier  
- 🏔️ Mountain  
- 🌊 Sea  
- 🛣️ Street

---

## 🧪 Arsitektur Model

Model CNN terdiri dari:
- 3 buah **Conv2D layer** dengan `ReLU`, `BatchNormalization`, dan `MaxPooling`
- Fully connected layer sebanyak 2 lapis
- Dropout untuk regularisasi
- Aktivasi akhir: `softmax`

Cara Menjalankan
1. Instal requirements.txt
2. Jalankan Script Utama "Dewangga_Megananda_Klasifikasi_Gambar_intel.ipynb"
