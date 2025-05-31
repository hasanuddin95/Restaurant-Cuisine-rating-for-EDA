# Restaurant-Cuisine-rating-for-EDA

## Questions KPis
- How is the distribution of food, service and overall ratings?
- are rating (food/service/Overall) diferent as signicant base on gender, marital status and location?
- Do customers who tend to smoke or drink alcohol give a bad rating or good rating?
- Is there a correlation between the amount of money spent and the rating given?
- How ratings change based on customer age group (generation)
- Which factors (location, expenses, habits, etc.) have the most influence on the overall rating

## Project Insight
- Service rating and food rating even though they have a large number of rating 5, there are still quite a lot of customers who give a rating of one. This must be a concern because the number is still quite large, as many as 66 customers.
- for the overall rating so far, it shows quite stable results because it is almost evenly distributed, with the highest point being at rating 3.5 as many as 35 people, the average is distributed in the rating range of 2 to 3.5, and also a fairly small rating of 1, only 6 customers.

<img width="557" alt="image" src="https://github.com/user-attachments/assets/45c4c10a-3352-4059-89e5-d1a1d5dff444" />




## Note

- Distribusi Rating
"Bagaimana distribusi rating makanan, layanan, dan keseluruhan? Apakah ada perbedaan signifikan antara ketiganya?"
Analisis: Gunakan histogram (matplotlib/seaborn) dan uji statistik seperti ANOVA.

- Pengaruh Demografi
"Apakah rating (makanan/layanan/keseluruhan) berbeda signifikan berdasarkan jenis kelamin, status pernikahan, atau lokasi restoran?"
Analisis: Boxplot grouping dan uji t-test/chi-square.

- Kebiasaan Konsumen
"Apakah pelanggan yang merokok atau minum alkohol cenderung memberikan rating yang lebih tinggi/rendah?"
Analisis: Crosstab (pandas) dan heatmap (seaborn).

- Korelasi Pengeluaran-Rating
"Apakah ada korelasi antara jumlah uang yang dihabiskan dengan rating yang diberikan?"
Analisis: Scatter plot + korelasi Pearson/Spearman.

- Segmentasi Usia
"Bagaimana rating berubah berdasarkan kelompok usia (generasi) pelanggan?"
Analisis: Kategorisasi tahun lahir (misal: Gen Z, Milenial), lalu groupby + line plot.

- Prediksi Rating
"Faktor mana (lokasi, pengeluaran, kebiasaan, dll) yang paling berpengaruh terhadap rating keseluruhan?"
Analisis: Regresi linear/klasifikasi (scikit-learn) atau feature importance.
