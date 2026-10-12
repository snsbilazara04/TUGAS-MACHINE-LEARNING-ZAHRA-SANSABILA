# Praktikum Machine Learning: Prediksi Performance Index Mahasiswa

Repositori ini berisi proyek analisis data yang bertujuan untuk mengetahui hubungan antara kebiasaan belajar, durasi belajar, dan prestasi akademik mahasiswa. Analisis dilakukan dengan memanfaatkan data yang tersedia untuk melihat pola serta faktor-faktor yang berpotensi berkaitan dengan hasil belajar.

Proyek ini dibuat untuk memenuhi tugas praktikum mata kuliah Machine Learning.

# 👤 Identitas Praktikan

Nama: Zahra Sansabila

NIM: 241011400701

Kelas: 05TPLP018

Mata Kuliah: Machine Learning

Repositori ini berisi proyek analisis data yang bertujuan untuk mengetahui hubungan antara kebiasaan belajar, durasi belajar, dan prestasi akademik mahasiswa. Analisis dilakukan dengan memanfaatkan data yang tersedia untuk melihat pola serta faktor-faktor yang berpotensi berkaitan dengan hasil belajar.

Proyek ini dibuat untuk memenuhi tugas praktikum mata kuliah Machine Learning.


Dosen Pengampu: Asep Erlan Maulana S.kom., M.Kom

# 🧰 Teknologi dan Library

1. Teknologi dan library yang digunakan dalam proyek ini adalah:

2. Python — bahasa pemrograman untuk pengolahan dan analisis data.

3. Pandas — mengelola dan memanipulasi dataset.

4. NumPy — melakukan operasi numerik.

5. Matplotlib — membuat visualisasi data.

6. Seaborn — membantu menampilkan grafik statistik.

7. Scikit-learn — membangun, melatih, dan mengevaluasi model machine learning.

8. Joblib dan Pickle — menyimpan model hasil pelatihan.

🧰 Teknologi dan Library

Teknologi dan library yang digunakan dalam proyek ini adalah:

Python — bahasa pemrograman untuk pengolahan dan analisis data.

Pandas — mengelola dan memanipulasi dataset.

NumPy — melakukan operasi numerik.

Matplotlib — membuat visualisasi data.

Seaborn — membantu menampilkan grafik statistik.

Scikit-learn — membangun, melatih, dan mengevaluasi model machine learning.

Joblib dan Pickle — menyimpan model hasil pelatihan.

# 📂 Dataset

Pada praktikum kali ini menggunakan beberapa file CSV sebagai sumber data:
Notebook menggunakan beberapa file CSV sebagai sumber data:

train_input.csv - Data yang digunakan dalam proses pelatihan.

train_label.csv - File label yang dibaca oleh notebook.

test_input.csv - Data untuk menghasilkan prediksi.

order.csv - File pendukung yang dibaca pada awal notebook.

# Variabel yang Digunakan

Beberapa variabel yang terdapat dalam dataset meliputi:

Hours Studied — jumlah waktu yang digunakan untuk belajar.

Previous Scores — nilai yang diperoleh sebelumnya.

Sleep Hours — jumlah jam tidur.

Sample Question Papers Practiced — jumlah latihan soal yang dikerjakan.

Extracurricular Activities — informasi aktivitas ekstrakurikuler.

Performance Index — variabel target yang diprediksi.

# ⚙️ Tahapan Pengerjaan

# 1. Import Library
Mengimpor library Python yang dibutuhkan untuk pengolahan data, visualisasi, preprocessing, pemodelan, dan evaluasi.

<img width="701" height="95" alt="image" src="https://github.com/user-attachments/assets/970b323f-f21e-4074-bd81-4ff2b0e75eec" />

# 2. Membaca Dataset

Memuat file CSV menggunakan Pandas, kemudian menampilkan beberapa baris awal untuk memahami struktur data.

<img width="601" height="259" alt="image" src="https://github.com/user-attachments/assets/4782da0c-313e-4b04-a526-f2733d5d70d9" />

Output:

<img width="522" height="410" alt="image" src="https://github.com/user-attachments/assets/db3c21bb-d867-4876-b806-54e0d86abf08" />

# 3. Eksplorasi Data

Melakukan pemeriksaan terhadap ukuran dataset, tipe data, dan statistik deskriptif.

# Ukuran Dataset

<img width="260" height="50" alt="image" src="https://github.com/user-attachments/assets/d8adfd0d-911f-4fa3-b683-096566d3e189" />

Output:

<img width="137" height="44" alt="image" src="https://github.com/user-attachments/assets/bc20c0b8-2ffa-4cbf-add5-5e56a7ce3ca9" />

# Tipe Data 

<img width="203" height="30" alt="image" src="https://github.com/user-attachments/assets/4ab90df6-8bf5-4f3e-8b43-bcf1d6b71731" />

Output:

<img width="240" height="122" alt="image" src="https://github.com/user-attachments/assets/77f00fae-dff0-4735-837e-48dd1b0f55be" />

# Statistik deskriptif

<img width="182" height="32" alt="image" src="https://github.com/user-attachments/assets/fe542670-14e6-4e67-9ca6-32d965859c4b" />

Output:

<img width="544" height="191" alt="image" src="https://github.com/user-attachments/assets/c9237442-1712-4345-b32f-9ca8792b606e" />

# 4. Pembersihan Data

Memeriksa nilai kosong (missing values), menghapus data duplikat, serta mengidentifikasi dan menangani pencilan (outlier) menggunakan metode Interquartile Range (IQR) pada fitur numerik.

# Missing values

<img width="239" height="83" alt="image" src="https://github.com/user-attachments/assets/919fa710-4484-4568-ad1f-0672856303d5" />

Output:

<img width="181" height="107" alt="image" src="https://github.com/user-attachments/assets/eabfe663-7295-4b0c-b29d-34ca4a058352" />

# Menghapus data duplikat

<img width="586" height="301" alt="image" src="https://github.com/user-attachments/assets/a2c1f848-63e4-487d-9fbd-cf6e8c8fdcff" />


# Mengidentifikasi dan menangani pencilan outlier menggunakan metode IQR 

<img width="510" height="389" alt="image" src="https://github.com/user-attachments/assets/fe7a8be8-0c17-4e5e-9453-fb5c8c36cb44" />

<img width="367" height="265" alt="image" src="https://github.com/user-attachments/assets/f540a8dd-bd31-4ca7-a1b6-318cce482d98" />

<img width="433" height="195" alt="image" src="https://github.com/user-attachments/assets/6a88b5a6-ceaf-43ae-b052-3285d9f368b3" />

# 5. Visualisasi Data

Menggunakan histogram, box plot, dan heatmap korelasi untuk membantu memahami distribusi data dan hubungan antarvariabel.

<img width="515" height="347" alt="image" src="https://github.com/user-attachments/assets/bf67eaed-e5c4-484c-ae13-7fa1b6468d77" />

Output:
 
<img width="545" height="313" alt="image" src="https://github.com/user-attachments/assets/c50677a3-38e7-4b77-ac29-1264b8f16618" />

# Visualisasi Distribusi

<img width="367" height="187" alt="image" src="https://github.com/user-attachments/assets/dd6ab04c-9c1e-4691-b9b9-f44e2a8879f8" />

Output:

<img width="554" height="294" alt="image" src="https://github.com/user-attachments/assets/f1ff350e-a29d-49dc-bba1-0d54fa379180" />

# Distribusi Performance Index

<img width="322" height="146" alt="image" src="https://github.com/user-attachments/assets/59553c7c-a31a-4abe-b0ce-f59f164dcc01" />

Output:

<img width="463" height="235" alt="image" src="https://github.com/user-attachments/assets/5c31cb58-0881-4244-9b86-9dfd940e9e5c" />

# 6. Preprocessing Data

Melakukan pengolahan fitur kategorikal menggunakan teknik encoding, serta mempersiapkan data agar dapat digunakan oleh algoritma machine learning.

# Melakukan One-Hot Encoding

<img width="334" height="114" alt="image" src="https://github.com/user-attachments/assets/9d535ebd-e9e7-4526-b96d-f9551195bcb8" />

<img width="544" height="119" alt="image" src="https://github.com/user-attachments/assets/52ae570a-dfce-4f83-92fd-2f5719677049" />

<img width="599" height="417" alt="image" src="https://github.com/user-attachments/assets/b96ad561-0705-411c-8cd3-663bae4be30e" />

<img width="595" height="416" alt="image" src="https://github.com/user-attachments/assets/8bccc9fd-2090-467a-97c1-b3d817b36ea6" />

<img width="595" height="415" alt="image" src="https://github.com/user-attachments/assets/fdfe6872-7de2-403a-aa01-7b4ad85ffa5b" />

<img width="599" height="418" alt="image" src="https://github.com/user-attachments/assets/6bdd5b5c-1ccf-4c54-b68d-91b1dac8a24c" />

<img width="599" height="419" alt="image" src="https://github.com/user-attachments/assets/fed78bf1-84a9-4eb6-8dbd-16cf4cec26a6" />

<img width="593" height="414" alt="image" src="https://github.com/user-attachments/assets/aa820405-7c1e-44f2-b0b4-d4ff0713293f" />

# 7. Pemisahan Fitur dan Target

Memisahkan variabel input sebagai fitur (X) dan Performance Index sebagai target (y). Kolom ID dan kolom target tidak dimasukkan ke dalam fitur model.

<img width="490" height="180" alt="image" src="https://github.com/user-attachments/assets/a100faa7-65f0-4590-840e-c28d4b41475d" />

# 8. Pembagian Data

Membagi data menjadi data latih dan data pengujian dengan proporsi 80:20 untuk proses pelatihan dan evaluasi.

<img width="328" height="255" alt="image" src="https://github.com/user-attachments/assets/b3292e9a-5ad4-44f5-b8c2-0085351c9c72" />

# 9. Standardisasi Data

Menggunakan StandardScaler untuk menstandarkan fitur numerik. Scaler dilatih menggunakan data latih, kemudian diterapkan pada data pengujian.

<img width="438" height="362" alt="Screenshot 2026-10-12 193702" src="https://github.com/user-attachments/assets/5c813fd0-2ada-4213-893e-b6db8a761d61" />


# 10. Pelatihan Model

Melatih dan membandingkan tiga algoritma machine learning, yaitu:

# Least Angle Regression (LARS)

<img width="302" height="158" alt="image" src="https://github.com/user-attachments/assets/3fedc2ec-5de6-4d21-b8c4-fe4dd65d6f5d" />


# Linear Regression

<img width="316" height="136" alt="image" src="https://github.com/user-attachments/assets/ca93feca-8fac-4c7a-b667-b01b5330dc3b" />


# Gradient Boosting Regressor

<img width="331" height="159" alt="image" src="https://github.com/user-attachments/assets/896ae99c-1231-4b96-9f7a-047ea847801d" />

<img width="503" height="415" alt="image" src="https://github.com/user-attachments/assets/cd1d76d7-bd39-4b30-a5b1-234ed4aadc20" />

<img width="488" height="344" alt="image" src="https://github.com/user-attachments/assets/5de9ddf5-7be9-40dd-afcd-59e2b78565ae" />

<img width="359" height="362" alt="image" src="https://github.com/user-attachments/assets/c153a2c9-951c-44bd-beea-117b7f91b0bc" />

# 11. Evaluasi Model.

Mengevaluasi hasil prediksi setiap model menggunakan Mean Absolute Error (MAE), Mean Squared Error (MSE), dan koefisien determinasi (R²).

<img width="596" height="401" alt="image" src="https://github.com/user-attachments/assets/9c835f56-3eca-4a36-b6b6-26a526c4e3af" />

<img width="596" height="410" alt="image" src="https://github.com/user-attachments/assets/0cb7ea77-a22e-4634-8a2b-5dcdca28a233" />

<img width="595" height="413" alt="image" src="https://github.com/user-attachments/assets/545a3759-4323-471a-8337-7fa7e2a3b05c" />

<img width="575" height="243" alt="image" src="https://github.com/user-attachments/assets/290c0919-1e85-4007-a12c-684acf6df431" />

# 12. Penyimpanan Model dan Prediksi

Menyimpan model Gradient Boosting Regressor dan scaler, kemudian menghasilkan prediksi pada data uji serta menyimpannya ke dalam file CSV.

<img width="386" height="407" alt="image" src="https://github.com/user-attachments/assets/c96b758a-a25d-4b61-bc8e-8e6cd8711f7b" />

<img width="590" height="410" alt="image" src="https://github.com/user-attachments/assets/5283ff5a-5de7-4ca9-bb59-03c5aa3f4565" />

<img width="650" height="413" alt="image" src="https://github.com/user-attachments/assets/e1dd8622-4a44-4044-a65c-66a9ceb98fe9" />


