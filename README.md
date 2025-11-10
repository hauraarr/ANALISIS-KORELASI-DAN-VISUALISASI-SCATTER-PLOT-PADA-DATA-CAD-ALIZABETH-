# Analisis Korelasi dan Visualisasi Scatter Plot Dataset CAD Alizabeth

Proyek ini merupakan **Tugas Besar Mata Kuliah Statistika** yang dilakukan menggunakan **Jupyter Notebook (Anaconda)**.  
Tujuan dari proyek ini adalah untuk menganalisis **hubungan antar faktor risiko terhadap penyakit Coronary Artery Disease (CAD)** menggunakan **visualisasi korelasi dan scatter plot**.

---

## Deskripsi Proyek
Dataset **CAD Alizabeth** berisi data pasien dengan beberapa variabel yang berkaitan dengan risiko penyakit jantung koroner, seperti:
- Usia (Age)  
- Hipertensi (HTN)  
- Diabetes Mellitus (DM)  
- Obesitas  
- Status perokok (Ex-Smoker)  
- Riwayat CAD  

Analisis dilakukan untuk melihat **hubungan antar variabel** dengan pendekatan statistik sederhana serta **visualisasi scatter plot** dan **heatmap korelasi** menggunakan Python.

---

## Tujuan Analisis
1. Mengidentifikasi korelasi antar faktor risiko terhadap CAD  
2. Menampilkan hubungan antar variabel melalui **scatter plot**  
3. Menentukan faktor yang memiliki pengaruh paling signifikan terhadap kemungkinan terkena CAD  

---

## Tools dan Library yang Digunakan
- **Jupyter Notebook (Anaconda)**  
- **Python Libraries:**
  - `pandas` → untuk pengolahan data  
  - `matplotlib` & `seaborn` → untuk visualisasi scatter plot & heatmap  
  - `numpy` → untuk perhitungan numerik  

---

## Langkah Analisis
1. Import dataset dan library  
2. Melakukan *data cleaning* (pengecekan nilai kosong dan tipe data)  
3. Menghitung **matriks korelasi** antar variabel  
4. Membuat **heatmap** untuk visualisasi korelasi  
5. Membuat **scatter plot** antar variabel yang berkaitan dengan CAD  
6. Menarik kesimpulan dari hasil visualisasi  

---

## Hasil Analisis
- Ditemukan beberapa variabel dengan korelasi cukup kuat terhadap CAD, terutama **usia**, **hipertensi**, dan **diabetes**.  
- Scatter plot menunjukkan adanya tren positif antara peningkatan usia dan risiko CAD.  
- Variabel **obesitas** dan **status perokok** juga menunjukkan kontribusi terhadap peningkatan risiko, meski tidak sekuat variabel lainnya.  

