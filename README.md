# UAP-Deployment

1. DATASET
Dataset UAP berisi 20 gambar warna berukuran 32x32 piksel, dibagi dalam 10 kelas. Ada 50.000 gambar untuk latihan dan 10.000 gambar untuk pengujian. Dataset ini dikumpulkan oleh Dignifo.

2. Deep Learning - CNN
Pertama, data dinormalisasi dan dibuat dalam bentuk kategori. Untuk meningkatkan data, kita menggunakan ImageDataGenerator. Arsitektur CNN diperlihatkan di bawah. Beberapa perubahan telah dilakukan, termasuk peningkatan kompleksitas model. Optimizer yang digunakan adalah Adam dengan parameter default. Callbacks ReduceLROnPlateau dan EarlyStopping ditambahkan untuk mencegah overfitting dan overtraining.

3. FLASK
Flask adalah framework web sederhana yang ditulis dalam bahasa Python. Dengan Flask, Anda bisa memuat gambar dari perangkat lokal atau URL. Hasil prediksi 3 teratas dari gambar yang dimuat beserta persentasenya akan ditampilkan pada halaman terpisah.

4. Cara Menjalankan
Clone repository ini dengan perintah: git clone https://github.com/dignifonauval/UAP-Deployment.git

Install dependensi proyek dengan perintah: pip install -r requirements.txt

Jalankan app.py. Atau jika Anda mau, jalankan file .ipynb untuk membuat model Anda sendiri.
