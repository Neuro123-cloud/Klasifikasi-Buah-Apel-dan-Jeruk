🍎🍊 Klasifikasi Citra Buah Apel dan Jeruk Menggunakan Convolutional Neural Network (CNN)
📖 Deskripsi Proyek
Proyek ini bertujuan untuk membangun sistem klasifikasi citra buah apel dan jeruk menggunakan metode Convolutional Neural Network (CNN). Model dikembangkan menggunakan framework TensorFlow dan Keras untuk mengenali karakteristik visual dari masing-masing buah berdasarkan citra digital.

Sistem dilatih menggunakan dataset buah yang terdiri dari gambar apel dan jeruk, kemudian digunakan untuk melakukan prediksi terhadap gambar baru yang belum pernah dilihat sebelumnya. Proyek ini merupakan implementasi konsep Deep Learning pada bidang Computer Vision untuk tugas UAS mata kuliah Kecerdasan Buatan.

🎯 Tujuan
Mengembangkan sistem klasifikasi citra buah berbasis Artificial Intelligence (AI).
Menerapkan metode Convolutional Neural Network (CNN) pada permasalahan klasifikasi citra.
Melatih model untuk membedakan buah apel dan jeruk berdasarkan karakteristik visualnya.
Mengevaluasi performa model menggunakan data validasi dan data uji.
Menjadi media pembelajaran penerapan Deep Learning dalam bidang Computer Vision.

📥 Unduh Dataset (Kaggle)
Dataset yang digunakan pada proyek ini tersedia secara publik di Kaggle dan dapat diunduh melalui tautan berikut:
🔗 Kaggle Dataset: https://www.kaggle.com/datasets/muhriddinmuxiddinov/fruits-and-vegetables-dataset

🎥 Link Demo / Simulasi
Demonstrasi model dapat diakses melalui Google Drive pada tautan berikut:
🔗 Google Drive Demo: https://drive.google.com/drive/folders/1nU4OiG7awBJZBFkoKEnrX22L_zUs3Iy1?usp=sharing

📊 Link Slide Presentasi
Materi presentasi yang menjelaskan latar belakang, metodologi, arsitektur CNN, hasil pengujian, dan kesimpulan dapat diakses melalui tautan berikut:
🔗 Canva Presentasi: https://canva.link/rztb9vizjztoean

🚀 Cara Menjalankan Program
1. Clone Repository
git clone https://github.com/username/Fruit-Classification-CNN.git
cd Fruit-Classification-CNN
2. Unduh Dataset

Unduh dataset melalui tautan Kaggle di atas, kemudian ekstrak sehingga memiliki struktur folder sebagai berikut:

Dataset/
├── Apple/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── Orange/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
3. Install Library

Install seluruh library yang dibutuhkan:

pip install tensorflow
pip install numpy
pip install matplotlib

Atau apabila tersedia file requirements.txt:

pip install -r requirements.txt
4. Menjalankan Program Training

Jalankan program berikut:

python klasifikasi_buah_apel_dan_jeruk.py

Program akan melakukan:

Memuat dataset
Melakukan preprocessing data
Membagi data training dan validation
Melatih model CNN
Menampilkan grafik akurasi
Menyimpan model hasil training

Output model:

fruit_model.h5
5. Menjalankan Prediksi

Siapkan gambar yang ingin diprediksi, kemudian ubah bagian berikut pada program:

img_path = "apel.jpg"

Jalankan bagian prediksi.

Contoh hasil:

Hasil Prediksi : Apel
Tingkat Keyakinan : 97.62%
Probabilitas : [[0.9762 0.0238]]
📈 Hasil

Model CNN berhasil melakukan klasifikasi citra buah apel dan jeruk dengan performa yang sangat baik.

Training Accuracy : 100%
Validation Accuracy : ±99%
Epoch : 10
Optimizer : Adam
Batch Size : 32

Hasil tersebut menunjukkan bahwa model mampu mengenali dan membedakan kedua jenis buah dengan tingkat akurasi yang tinggi.

👨‍💻 Penulis

Muhammad Fadhil Qutrunnada
NIM: 235060307111061

Departemen Teknik Elektro
Fakultas Teknik
Universitas Brawijaya
