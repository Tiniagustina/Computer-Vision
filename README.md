# Computer-Vision
# UTS Computer Vision: EMNIST Character Classification

Repository ini berisi *source code* Machine Learning Pipeline untuk mengklasifikasikan karakter tulisan tangan (huruf) dari dataset EMNIST (Extended MNIST), sebagai pemenuhan tugas Ujian Tengah Semester mata kuliah RE 604 Computer Vision.

## Identitas Mahasiswa
* **Nama:** Tini Agustina
* **NIM:** [Isi NIM kamu di sini]
* **Kelas:** Robotika B (Semester 6)
* **Program Studi:** D4 Teknik Robotika
* **Politeknik Negeri Batam**

## Alur Pemrosesan (Machine Learning Pipeline)
1. **Data Preparation:** Menggunakan 2.600 sampel data seimbang dari dataset EMNIST Letters (100 sampel per kelas huruf A-Z).
2. **Feature Extraction:** Menggunakan algoritma **HOG (Histogram of Oriented Gradients)** untuk mengekstraksi fitur visual karakter.
3. **Classification & Tuning:** Menggunakan **Support Vector Machine (SVM)** dengan optimasi hyperparameter melalui teknik **Grid Search** (K-Fold Cross Validation).
4. **Evaluation:** Mengukur performa model dengan metrik *Accuracy, Precision, Recall, F1-score*, serta *Confusion Matrix*.

## Cara Menjalankan Kode (How to Run)
Dikarenakan ukuran file dataset terlalu besar untuk di-unggah ke GitHub (>100MB), silakan ikuti langkah berikut untuk menjalankan kode:
1. Unduh dataset EMNIST berformat CSV melalui Kaggle: [EMNIST Dataset](https://www.kaggle.com/datasets/crawford/emnist/data)
2. Ekstrak file dan ambil file bernama `emnist-letters-train.csv`.
3. Letakkan file `emnist-letters-train.csv` tersebut di dalam folder (direktori) yang sama dengan file `midterm_cv.ipynb`.
4. Jalankan file Jupyter Notebook (`midterm_cv.ipynb`) secara berurutan.

## Link Video Penjelasan
Penjelasan lengkap mengenai *source code*, pemrosesan data, parameter HOG & SVM, serta hasil evaluasi dapat dilihat pada video presentasi berikut:
**[Nanti ganti tulisan ini dengan Link YouTube kamu]**
