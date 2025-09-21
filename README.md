# Student Stress Level Analysis

Proyek ini menganalisis faktor-faktor yang memengaruhi tingkat stres mahasiswa berdasarkan dataset survei nasional. Analisis menggunakan metode machine learning dengan fokus pada **Random Forest Classifier** untuk memprediksi level stres.

* **Nama File**: StressLevelDataset.csv
* **Jumlah Data**: 1100 baris × 21 kolom
* **Target**: stress_level (3 kelas)
* **Link Dataset**: https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets/data

## Analysis Process
1. Data loading dan eksplorasi awal (EDA)
2. Visualisasi faktor psikologis, akademik, sosial, dan lingkungan
3. Preprocessing: cek missing values, encoding (jika ada variabel kategori), normalisasi
4. Modeling dengan **Random Forest Classifier**
5. Evaluasi model menggunakan confusion matrix & classification report
6. Interpretasi feature importance untuk melihat faktor dominan penyebab stres

## Insights & Findings
* Faktor yang paling memengaruhi stres mahasiswa: `study_load`, `future_career_concerns`, `sleep_quality`, dan `academic_performance`.
* Model Random Forest memiliki akurasi lebih tinggi dibanding Linear Regression (karena target bersifat kategori).
* Kualitas tidur yang buruk + beban studi tinggi = risiko stres berat.

## Conclusion & Recommendation
* Mahasiswa perlu mengatur manajemen waktu belajar & tidur agar tingkat stres terkendali.
* Kampus bisa meningkatkan dukungan akademik & konseling karier.
* Faktor sosial (peer pressure & bullying) juga harus dipantau karena berdampak pada stres jangka panjang.

## AI Support Explanation
Dalam proyek ini, AI digunakan untuk:

* **IBM Granite (WatsonX)** → menjalankan eksperimen machine learning (Random Forest) & interpretasi hasil.
* **Gemini / ChatGPT** → membantu menyusun insight, kesimpulan.
