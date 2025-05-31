# Restaurant-Cuisine-rating-for-EDA

#Questions KPis
- How is the distribution of food, service and overall ratings?



Distribusi Rating
"Bagaimana distribusi rating makanan, layanan, dan keseluruhan? Apakah ada perbedaan signifikan antara ketiganya?"
Analisis: Gunakan histogram (matplotlib/seaborn) dan uji statistik seperti ANOVA.

Pengaruh Demografi
"Apakah rating (makanan/layanan/keseluruhan) berbeda signifikan berdasarkan jenis kelamin, status pernikahan, atau lokasi restoran?"
Analisis: Boxplot grouping dan uji t-test/chi-square.

Kebiasaan Konsumen
"Apakah pelanggan yang merokok atau minum alkohol cenderung memberikan rating yang lebih tinggi/rendah?"
Analisis: Crosstab (pandas) dan heatmap (seaborn).

Korelasi Pengeluaran-Rating
"Apakah ada korelasi antara jumlah uang yang dihabiskan dengan rating yang diberikan?"
Analisis: Scatter plot + korelasi Pearson/Spearman.

Segmentasi Usia
"Bagaimana rating berubah berdasarkan kelompok usia (generasi) pelanggan?"
Analisis: Kategorisasi tahun lahir (misal: Gen Z, Milenial), lalu groupby + line plot.

Prediksi Rating
"Faktor mana (lokasi, pengeluaran, kebiasaan, dll) yang paling berpengaruh terhadap rating keseluruhan?"
Analisis: Regresi linear/klasifikasi (scikit-learn) atau feature importance.
