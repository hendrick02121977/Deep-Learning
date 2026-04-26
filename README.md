# 🧠 Materi Kuliah Deep Learning

Repositori ini berisi materi kuliah **Deep Learning** yang dikembangkan menggunakan **Google Colab**. Setiap topik tersedia dalam bentuk Jupyter Notebook interaktif yang dapat langsung dijalankan di Google Colab tanpa instalasi tambahan.

---

## 📚 Daftar Materi

| # | Topik | Buka di Colab | Deskripsi |
|---|-------|---------------|-----------|
| 1 | **Pengantar Deep Learning** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hendrick02121977/Deep-Learning/blob/main/notebooks/01_Pengantar_Deep_Learning.ipynb) | AI vs ML vs DL, sejarah, neuron buatan, fungsi aktivasi, implementasi NN dari scratch |
| 2 | **Neural Networks & Backpropagation** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hendrick02121977/Deep-Learning/blob/main/notebooks/02_Neural_Networks_dan_Backpropagation.ipynb) | Forward propagation, loss functions, gradient descent, backpropagation, optimizer (SGD/Adam/RMSprop), regularisasi |
| 3 | **Convolutional Neural Networks (CNN)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hendrick02121977/Deep-Learning/blob/main/notebooks/03_Convolutional_Neural_Networks.ipynb) | Operasi konvolusi, pooling, arsitektur CNN, klasifikasi CIFAR-10, visualisasi feature maps, transfer learning |
| 4 | **RNN dan LSTM** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hendrick02121977/Deep-Learning/blob/main/notebooks/04_RNN_dan_LSTM.ipynb) | Recurrent NN, vanishing gradient, LSTM, GRU, prediksi time series, analisis sentimen |
| 5 | **Transfer Learning** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hendrick02121977/Deep-Learning/blob/main/notebooks/05_Transfer_Learning.ipynb) | Feature extraction, fine-tuning, MobileNetV2, perbandingan pretrained models, best practices |

---

## 🎯 Tujuan Pembelajaran

Setelah mengikuti seluruh materi ini, mahasiswa diharapkan mampu:

- ✅ Memahami konsep dasar dan arsitektur Deep Learning
- ✅ Mengimplementasikan Neural Network dari scratch menggunakan NumPy
- ✅ Membangun dan melatih model Deep Learning menggunakan TensorFlow/Keras
- ✅ Memahami dan menerapkan CNN untuk tugas Computer Vision
- ✅ Memahami dan menerapkan RNN/LSTM untuk data sekuensial
- ✅ Menerapkan Transfer Learning untuk dataset terbatas
- ✅ Mengevaluasi dan melakukan debugging model Deep Learning

---

## 🛠️ Cara Menggunakan

### Opsi 1: Google Colab (Direkomendasikan)
Klik badge **"Open in Colab"** pada tabel di atas. Tidak perlu instalasi apapun!

### Opsi 2: Jalankan Lokal
```bash
# Clone repositori
git clone https://github.com/hendrick02121977/Deep-Learning.git
cd Deep-Learning

# Install dependensi
pip install tensorflow numpy matplotlib scikit-learn seaborn pandas

# Jalankan Jupyter
jupyter notebook notebooks/
```

---

## 📋 Prasyarat

- Pengetahuan dasar **Python** (variabel, fungsi, list, numpy)
- Pengetahuan dasar **Aljabar Linear** (matriks, vektor, dot product)
- Pengetahuan dasar **Kalkulus** (turunan/gradien)
- **Akun Google** untuk menggunakan Google Colab

---

## 📦 Dependensi

| Library | Versi | Kegunaan |
|---------|-------|----------|
| TensorFlow | ≥ 2.10 | Framework Deep Learning utama |
| Keras | (bundled) | High-level API untuk building model |
| NumPy | ≥ 1.21 | Komputasi numerik |
| Matplotlib | ≥ 3.5 | Visualisasi data |
| Scikit-learn | ≥ 1.0 | Preprocessing dan evaluasi |
| Seaborn | ≥ 0.11 | Visualisasi statistik |

> Semua library sudah tersedia di Google Colab secara default.

---

## 📖 Referensi

- [Deep Learning Book](https://www.deeplearningbook.org/) - Goodfellow, Bengio & Courville
- [TensorFlow Documentation](https://www.tensorflow.org/tutorials)
- [Keras Documentation](https://keras.io/guides/)
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) - Michael Nielsen
- [CS231n: Convolutional Neural Networks](http://cs231n.stanford.edu/) - Stanford University

---

## 📝 Lisensi

Materi ini tersedia di bawah lisensi [MIT](LICENSE).
