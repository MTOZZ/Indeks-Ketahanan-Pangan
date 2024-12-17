# :rocket: KETAHANAN PANGAN DI INDONESIA :rocket:
Kondisi terpenuhinya pangan bagi negara dengan perseorangan. Ketahanan pangan diukur dengan **Indeks Ketahanan Pangan**
yang memeiliki peran dalam mengevaluasi capaian ketahanan pangan dan gizi wilayah.

Project ini dibuat untuk menyelesaikan final project [MSIB7] Data Science Track Startup Campus.

Judul: **SINERGI EKONOMI HIJAU UNTUK MEWUJUDKAN KETAHANAN PANGAN BERKELANJUTAN**

---
# :loudspeaker: PROBLEM STATEMENT
meskipun Indonesia memiliki potensi besar dalam sektor pertanian, tantangan dalam keterjangkauan, ketersediaan, pemanfaatan, dan berkelanjutan pangan masih menjadi hambatan utama untuk mewujudkan ketahanan pangan.
Berdasarkan tren IKP (Indek Ketahanan Pangan) di Indonesia dari tahun 2012-2022.
![Tren Indeks Ketahanan Pangan](https://raw.githubusercontent.com/MTOZZ/Indeks-Ketahanan-Pangan/main/Image/TrenIKP.png)
Ketahanan pangan Indonesia mengalami tren penurunan selama 4 tahun terkahir. Hal ini memerlukan evaluasi lebih lanjut
terhadap faktor ekonomi, sosial, lingkungan, dan kebijakan pemerintah, terutama dampak covid-19 yang terjadi.

---
# :man_shrugging: GOALS
- Forecasting,
  Memberikan wawasan starategis bagi pengembang kebijakan yang mendukung keberlanjutan ketahanan pangan nasional.
- Clustering,
  Mengidentifikasi kelompok wilayah agar kebijakan lebih spesifik, efektif, dan sesuai kebutuhan.
- Strategic Policy,
  Memastikan ketahanan pangan yang stabil dan berkelanjutan, dengan memastikan ketersediaan, keterjangkauan, dan pemanfaatan
  pangan yang merata bagi seluruh lapisan masyarakat.

---

# :bar_chart: DATA SET
Dataset utama diambil dari *real dataset* yang bersumber pada https://data-explorer.oecd.org/ dan juga bersumber dari https://fsva.badanpangan.go.id/ .

---

# :chart_with_upwards_trend: DASHBOARD
https://public.tableau.com/app/profile/team.bravo/viz/FinalProject_TeamB-RAVO/Dashboard4?publish=yes .

---

# :file_folder: DATA DICTIONARY
*FORECASTING* & *CLUSTERING*
- AFFORDABILITY: Indeks keterjangkauan pangan, mencerminkan kemampuan masyarakat dalam membeli pangan.
- AVAILABILITY: Indeks ketersediaan pangan, menunjukkan seberapa tersedia pangan di suatu daerah.
- QUALITY AND SAFETY: Indeks kualitas dan keamanan pangan, mengukur mutu serta keamanan pangan yang dikonsumsi.
- SUSTAINABILITY AND ADAPTATION: Indeks keberlanjutan dan adaptasi, menunjukkan keberlanjutan sistem pangan terhadap perubahan lingkungan atau iklim.

---

# :hourglass: EXPLORATORY DATA ANALYSIS (EDA) FORECASTING
Pada tahap ini kami melakukan beberapa tahap yaitu:
- Transformasi Data Karena Time Series membutuhkan kolom tanggal yang proper (berformat YYYY-MM-DD) maka perlu dipastikan apakah kolom tanggal pada data sudah sesuai dengan format tanggal universal. Jika belum maka ubah format tanggal tersebut.
- Plot TimeSeries adalah alat yang sangat berguna untuk analisis data. Biasanya dengan line chart. Dengan memberikan visualisasi yang jelas, akan memungkinkan pengamat untuk mengambil wawasan yang signifikan dari data yang disajikan, yang dapat digunakan untuk pengambilan keputusan yang lebih baik.
![Plot Time Series](https://raw.githubusercontent.com/MTOZZ/Indeks-Ketahanan-Pangan/main/Image/PlotTS.png)
![Plot Time Series](https://raw.githubusercontent.com/MTOZZ/Indeks-Ketahanan-Pangan/main/Image/PlotTS1.png)
![Plot Time Series](https://raw.githubusercontent.com/MTOZZ/Indeks-Ketahanan-Pangan/main/Image/PlotTS2.png)
![Plot Time Series](https://raw.githubusercontent.com/MTOZZ/Indeks-Ketahanan-Pangan/main/Image/PlotTS3.png)
![Plot Time Series](https://raw.githubusercontent.com/MTOZZ/Indeks-Ketahanan-Pangan/main/Image/PlotTS4.png)
- 
