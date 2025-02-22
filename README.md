# Customers Lifetime Values (CLV) Predictive pada Perusahaan Asuransi Mobil

**Business Problem Understanding**

**Context**

Customer Lifetime Value (CLV) adalah ukuran seberapa bernilai seorang pelanggan bagi sebuah perusahaan. Dari nilai ini, perusahaan dapat menentukan berapa banyak keuntungan yang diperoleh dari satu pelanggan serta biaya yang dikeluarkan untuk mendapatkan atau mempertahankan pelanggan baru. Angka ini sangat penting bagi perusahaan yang ingin menargetkan pemasaran secara efektif kepada pelanggan yang bernilai serta memahami bagaimana perubahan pelanggan perusahaan di masa depan.

**Problem Statement**

Di tengah persaingan yang semakin ketat dalam industri asuransi, perusahaan perlu menerapkan strategi yang efektif untuk mempertahankan loyalitas pelanggan. Salah satu tantangan utama adalah mengidentifikasi pelanggan dengan nilai tinggi dan memahami pola perilaku mereka agar dapat meningkatkan pengalaman pengguna.

**Goals**

Berdasarkan permasalahan tersebut, perusahaan asuransi membutuhkan alat yang mampu memprediksi Customer Lifetime Value (CLV). Dengan adanya prediksi CLV yang akurat, perusahaan dapat merancang strategi pemasaran yang lebih efektif, mengalokasikan sumber daya dengan lebih efisien, serta meningkatkan retensi pelanggan.

**Analytic Approach**

- Pendekatan analitis yang digunakan dalam proyek ini melibatkan eksplorasi data untuk menemukan pola yang dapat membedakan karakteristik pelanggan berdasarkan fitur yang tersedia. 
- Model yang akan dikembangkan adalah model regresi, yang dirancang untuk membantu perusahaan dalam memprediksi nilai CLV pelanggan dengan akurat.

**Metric Evaluation**

Evaluasi kinerja model akan dilakukan menggunakan metrik berikut:
1. Root Mean Squared Error (RMSE)
- MSE mengukur seberapa jauh prediksi dari nilai aktual, dengan penalti lebih besar untuk error yang lebih besar.
- Nilai lebih kecil lebih baik, karena menunjukkan prediksi lebih dekat ke nilai aktual.

2. Mean Absolute Error (MAE)
- MAE mengukur rata-rata perbedaan absolut antara prediksi dan nilai aktual.
- Lebih kecil lebih baik, karena berarti rata-rata kesalahan prediksi lebih rendah.
  
3. Mean Absolute Percentage Error (MAPE)
- MAPE mengukur kesalahan dalam bentuk persentase terhadap nilai aktual.
- Semakin kecil semakin baik, karena menunjukkan prediksi lebih akurat dalam skala relatif.

**Conclusion**

1. Fitur yang paling berpengaruh terhadap Customer Lifetime Value (CLV) adalah Number of Policies.
2. Random Forest Regressor terbukti sebagai model terbaik, dengan nilai evaluasi sebagai berikut:
- RMSE: 3,317
- MAE: 1,455
- MAPE: 11%

3. Dengan MAPE sebesar 11%, model memiliki kinerja yang baik dalam prediksi, karena kesalahan rata-rata persentase absolut berada di bawah 20%, sesuai dengan standar yang dikemukakan oleh Lewis (1992).

**Recomendation**
- Karena Number of Policies adalah faktor paling berpengaruh terhadap CLV, strategi peningkatan jumlah polis per pelanggan dapat diterapkan.
- Menambahkan fitur-fitur baru yang bisa membantu meningkatkan performa model prediksi dan memahami lebih dalam faktor-faktor yang memengaruhi CLV






