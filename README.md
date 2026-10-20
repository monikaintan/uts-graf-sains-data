# uts-graf-sains-data
UTS Graf Sains Data - RetailRocket Recommendation System

# UTS Graf Sains Data

## Deskripsi Proyek
Proyek ini menerapkan konsep graf untuk menganalisis interaksi pengguna dan barang menggunakan dataset RetailRocket serta membangun sistem rekomendasi barang berbasis kemiripan pengguna.

## Tujuan
- Memodelkan interaksi pengguna dan barang dalam graf.
- Membentuk User-Item Matrix.
- Menghitung kemiripan pengguna menggunakan cosine similarity.
- Menghasilkan rekomendasi menggunakan K-Nearest Neighbors (KNN) dengan k = 5.
- Mengevaluasi rekomendasi menggunakan data periode P2.

## Struktur Proyek
- `UTS_Graf_Sains_Data.ipynb`: notebook analisis, visualisasi, rekomendasi, dan evaluasi.
- `data/processed/events_P1.csv`: data interaksi periode P1.
- `data/processed/events_P2.csv`: data interaksi periode P2.

## Metode
1. Pemodelan graf pengguna dan barang.
2. Pembentukan User-Item Matrix.
3. Perhitungan cosine similarity.
4. Pencarian lima tetangga terdekat.
5. Pemeringkatan kandidat barang dan pembuatan rekomendasi.
6. Evaluasi dengan Hit@5 dan NDCG@5.

## Hasil Evaluasi
Evaluasi dilakukan terhadap 50 pengguna. Pada sampel pengujian ini, rata-rata Hit@5 dan NDCG@5 adalah 0.0. Hasil tersebut menunjukkan bahwa rekomendasi yang dihasilkan belum cocok dengan interaksi aktual pengguna pada periode P2.

## Cara Menjalankan
Buka `UTS_Graf_Sains_Data.ipynb` menggunakan Jupyter Notebook atau JupyterLab. Pastikan dependensi Python dan lokasi dataset sesuai dengan yang digunakan dalam notebook.
