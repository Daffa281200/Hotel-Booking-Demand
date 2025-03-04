# Hotel Booking Demand

## Dibuat oleh: Daffa Dzaky Naufal

---

## Latar Belakang Masalah
**Konteks:**
Industri hotel menghadapi tantangan konstan dalam mengelola pembatalan, yang dapat berdampak signifikan terhadap pendapatan dan operasional. Dengan menganalisis data pemesanan, hotel dapat mengidentifikasi pola yang berkontribusi terhadap pembatalan dan membuat keputusan berbasis data untuk meminimalkannya. 

Kumpulan data ini berisi informasi pemesanan untuk sebuah hotel di Portugal dan mencakup rincian tentang:
- Pemesanan
- Perilaku pelanggan
- Pembatalan

**Target:**
- 0 : Tidak membatalkan *booking*
- 1 : Membatalkan *booking*

---

## Permasalahan
Hotel mengalami tingkat pembatalan pemesanan yang tinggi, menyebabkan:
- Kerugian finansial
- Sumber daya yang kurang dimanfaatkan
- Inefisiensi operasional

Penting untuk memahami faktor-faktor yang berkontribusi terhadap pembatalan dan mengidentifikasi pelanggan yang cenderung membatalkan pemesanan mereka.

---

## Tujuan
1. **Prediksi Pembatalan:**
   Membangun model prediksi untuk menentukan apakah pemesanan akan dibatalkan berdasarkan pelanggan dan fitur pemesanan.

2. **Analisis Faktor Utama:**
   Mengidentifikasi faktor-faktor utama yang memengaruhi pembatalan, untuk:
   - Mengurangi tingkat pembatalan
   - Meningkatkan perencanaan operasional
   - Meningkatkan pengalaman pelanggan

---

## Pendekatan Proyek
1. **Pemahaman Bisnis:**
   - Menjelaskan permasalahan dan tujuan utama.

2. **Eksplorasi Data:**
   - Menganalisis dataset untuk memahami pola dan anomali.

3. **Pra-pemrosesan Data:**
   - Menangani data yang hilang.
   - Menangani outlier.
   - Melakukan rekayasa fitur.
   - Encoding fitur kategorikal.
   - Normalisasi fitur numerik.

4. **Pengembangan Model:**
   - Membandingkan beberapa algoritma *machine learning*.
   - Memilih model terbaik berdasarkan metrik evaluasi.

5. **Evaluasi:**
   - Menilai performa model menggunakan metrik recall.

6. **Penyampaian Wawasan:**
   - Visualisasi dan interpretasi hasil analisis.

---

## Tools dan Teknologi
- **Bahasa Pemrograman:** Python
- **Perpustakaan Utama:**
  - Analisis Data: Pandas, NumPy
  - Visualisasi: Matplotlib, Seaborn, SweetViz, D-Tale
  - *Machine Learning*: Scikit-learn, Imbalanced-learn, Category_encoders, XGBoost, Hyperopt
- **Platform:** Jupyter Notebook

---

## Cara Menjalankan
### Prasyarat
Pastikan Anda memiliki Python 3.12 dan instal perpustakaan berikut:
```bash
pip install pandas numpy matplotlib seaborn sweetviz dtale scikit-learn imblearn category_encoders xgboost hyperopt
```

### Langkah-Langkah
1. Kloning repositori:
   ```bash
   git clone <repository-url>
   ```
2. Buka Jupyter Notebook:
   ```bash
   jupyter notebook Hotel\ Booking\ Demand.ipynb
   ```
3. Ikuti langkah-langkah dalam notebook untuk menjalankan analisis.

---

## Hasil dan Wawasan
Model prediksi yang dikembangkan mampu mencapai tingkat akurasi sebesar **81.47%**. Wawasan utama meliputi:
- **Wawasan 1:** Faktor utama yang memengaruhi pembatalan adalah deposit_type
- **Wawasan 2:** Pelanggan dengan karakteristik tertentu memiliki probabilitas pembatalan yang lebih tinggi.

---

## Rencana Pengembangan
- Mengeksplorasi fitur tambahan, algoritma yang berbeda, dan resampling baru untuk meningkatkan akurasi model.
- Menganalisis data-data yang misprediksi untuk mengidentifikasi area perbaikan model.

---

## Streamlit
Model dapat dicoba melalui [link](https://hotel-booking-demand-by-daffa.streamlit.app/) berikut.

## Note Tambahan
Untuk memastikan agar EDA dapat ditampilkan, download file **Hotel Booking Cancellation Prediction.ipynb** dan jalankan di Jupyter Notebook.

---

## Lisensi
Proyek ini dilisensikan di bawah MIT License.

