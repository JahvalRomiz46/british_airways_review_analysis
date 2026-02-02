# British Airways Review Analysis
## Executive Summary
Proyek ini bertujuan untuk menganalisis data review pelanggan British Airways untuk mengidentifikasi trend dalam layanan operasional yang diberikan. Dengan memanfaatkan data review pelanggan dari tahun 2016-2023, dashboard ini menyediakan actionable insights bagi stakeholders untuk meningkatkan retensi pelanggan melalui standarisasi kualitas layanan di berbagai armada dan wilayah.

---

## Business Problem
Fluktuasi tingkat kepuasan pelanggan yang drastis dengan skor rating terendah ada di 1.0/10. Ini menunjukkan adanya inkonsistensi layanan yang berisiko pada reputasi brand. Manajemen membutuhkan alat pemantauan yang mampu membedah kinerja berdasarkan armada pesawat, geografi, dan tren waktu untuk menentukan prioritas perbaikan layanan 

---

## Dashboard
[Klik di sini untuk akses dashboardnya di Tableau Public](https://public.tableau.com/views/AirwaysReviewDashboard_17634490901250/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
<img src="Dashboard Image.png" alt="British Airways Review Dashboard" width="1000">

---

## Key Insights & Findings
- Service Volatility: Data menunjukkan volatilitas tinggi dengan penurunan paling signifikan terjadi pada Juni 2020 dan awal 2021. Hal ini mengindikasikan kegagalan adaptasi layanan pada periode krisis atau transisi operasional.
- Fleet Performance Excellence: Pesawat Boeing 747-400 mencatatkan rating tertinggi dengan skor 4.7, menunjukkan konfigurasi atau standar layanan pada armada ini adalah yang paling disukai pelanggan.
- High-Volume Friction: Armada A320 memiliki volume ulasan tertinggi dengan jumlah 263 ulasan, namun dengan rating yang moderat di 4.3. Ini adalah area kritis di mana peningkatan kecil dalam kualitas layanan akan berdampak pada jumlah pelanggan terbesar.
- Emerging Markets Potential: Wilayah Czechia, Hungary, dan Turkey menunjukkan tingkat kepuasan tertinggi (skor 8.0 - 9.5). Ini memberikan peluang strategis bagi Business Analyst untuk memperkuat branding dan frekuensi penerbangan di rute-rute tersebut.

---

## Business Recomendations
1) Standardisasi Layanan: Melakukan audit internal pada rute/periode dengan rating rendah untuk menyelaraskan kualitas layanan dengan standar armada Boeing 747-400.
2) Operational Recovery Plan: Mengembangkan strategi dengan standard yang lebih baik untuk menjaga customer experience tetap stabil pada periode peak season atau mungkin ketika krisis untuk menghindari penurunan rating drastis seperti sebelumnya.
3) Customer Feedback Loop: Memberbaiki fasilitas pada armada A320 untuk meningkatkan kepuasan pada segmen pasar dengan volume terbesar.

---

## Workflow & Toolstack
Dalam membangun solusi ini, saya menerapkan metodologi analisis data end-to-end seperti:
- Data Preparation: Melakukan data grouping pada kategori pesawat untuk mempermudah analisis dan mengurangi noise pada visualisasi.
- Advanced Analytics (Tableau):
  - Dynamic Metrics: Mengimplementasikan Custom Parameters dan Calculated Fields menggunakan logika CASE WHEN untuk memungkinkan user mengganti KPI secara instan.
  - Geospatial Analysis: Menggunakan Map Charts untuk memetakan distribusi kepuasan global secara intuitif.
- Time-Series Tracking: Membangun analisis tren untuk mengidentifikasi pola musiman dan anomali performa bulanan.
- UI/UX Design: Menerapkan prinsip desain minimalis untuk memastikan stakeholder dapat menarik kesimpulan dalam waktu singkat karna minimnya distraksi yang tidak diperlukan.
