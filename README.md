# CBR-Perjudian-PNBPP

## Deskripsi

Proyek ini merupakan implementasi **Case-Based Reasoning (CBR)** untuk mencari kemiripan kasus pada putusan pidana perjudian dari Pengadilan Negeri Balikpapan.

## Dataset

Dataset terdiri dari **44 putusan pidana perjudian** yang diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia dalam format PDF.

## Tahapan Pengerjaan

1. Ekstraksi teks dari dokumen PDF menggunakan PyPDF.
2. Preprocessing teks (cleaning dan normalisasi).
3. Representasi kasus menggunakan TF-IDF.
4. Perhitungan kemiripan menggunakan Cosine Similarity.
5. Retrieval 5 kasus yang paling mirip berdasarkan query.
6. Penyimpanan hasil retrieval dan prediksi ke dalam file CSV.

## Tools dan Library

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* PyPDF
* Matplotlib

## Struktur Repository

```
data/
├── processed/
├── eval/

notebooks/
requirements.txt
README.md
```

## Cara Menjalankan

1. Install dependensi:

   ```
   pip install -r requirements.txt
   ```
2. Buka notebook `CBR_Perjudian_PNBPP.ipynb`.
3. Jalankan setiap sel secara berurutan.
