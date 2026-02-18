# ✈️ Aviation Customer Experience & Service Recovery Analysis - British Airways

<img src="Dashboard Image.png" alt="British Airways Review Dashboard" width="1000">

[Akses dashboard di Tableau Public](https://public.tableau.com/views/AirwaysReviewDashboard_17634490901250/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Business Context
Dalam industri penerbangan, *Customer Experience* (CX) adalah kunci utama retensi penumpang. British Airways menghadapi tantangan berat berupa fluktuasi kepuasan pelanggan yang sangat drastis, yang berpotensi merusak reputasi *brand* dan menurunkan tingkat loyalitas penumpang di tengah ketatnya persaingan rute internasional.

Proyek ini bertujuan sebagai simulasi data analyst dalam menganalisis lebih dari 1.300 data ulasan pelanggan (2016-2023) untuk menemukan *root cause* dari sentimen negatif, mengevaluasi standar pelayanan antar-armada, dan memberikan panduan strategis bagi manajemen operasional untuk menstabilkan kualitas layanan.

## Problem Statement & Objectives
Fokus analisis ini adalah mengidentifikasi titik lemah (*pain points*) dalam *customer journey*. Objektif utamanya adalah:
1.  **Service Bottleneck Identification:** Menemukan fasilitas atau layanan spesifik yang paling banyak memicu keluhan.
2.  **Fleet Consistency Audit:** Membandingkan tingkat kepuasan antar-tipe pesawat untuk melihat inkonsistensi fasilitas.
3.  **Trend Monitoring:** Menganalisis stabilitas performa layanan dari waktu ke waktu, terutama di masa transisi operasional.

## Tools & Methodology
-   **Data Preparation:** Tableau (Melakukan *grouping* pada pesawat dengan ulasan < 50 ke dalam kategori "Others" untuk mengurangi *noise* dan memfokuskan analisis pada armada utama).
-   **Data Visualization:** Tableau (Membangun *interactive dashboard* menggunakan *Custom Parameters* dan *Calculated Fields* untuk analisis metrik dinamis).

## Key Insights (Executive Summary)

### 1. Krisis Parah pada "In-Flight Entertainment" & Katering
Meskipun staf kabin bernilai lebih tinggi, fasilitas pendukung adalah kelemahan terbesar maskapai. *Avg. Entertainment* tercatat di angka kritis **1.4/10**, disusul oleh *Food & Beverages* (**2.4**) dan *Value for Money* (**2.8**). Ini membuktikan bahwa pelanggan merasa harga tiket mahal yang mereka bayar tidak sepadan dengan fasilitas makanan dan hiburan.

### 2. Inkonsistensi Kualitas Armada
Terdapat kesenjangan kualitas pengalaman terbang yang nyata antar pesawat. Armada *legacy* Boeing 747-400 adalah yang paling disukai dengan rating 4.7. Sebaliknya, armada Airbus seri A321 memiliki rating terburuk (3.6). Lebih krusial lagi, armada A320 yang memiliki pencatatan volume feedback terbanyak (263 ulasan) hanya mampu memberikan kepuasan moderat di angka 4.3.

### 3. Volatilitas Layanan yang Ekstrem
Grafik tren *Average Overall Rating by Month* menunjukkan pergerakan yang sangat tidak stabil, dengan skor yang sering kali anjlok mendekati angka 1. Hal ini mengindikasikan ketiadaan Standar Operasional Prosedur (SOP) *Customer Service* yang ketat, sehingga kualitas pelayanan sangat bergantung pada "siapa kru yang bertugas" dan "kapan penerbangan terjadi", alih-alih pada standar perusahaan.

## Strategic Recommendations

* **Audit Vendor Katering & Perombakan In-Flight Entertainment:** Manajemen harus segera meninjau ulang kontrak dengan vendor makanan saat ini. Selain itu, diperlukan *Capex* (Capital Expenditure) untuk memperbarui sistem *In-Flight Entertainment* (IFE) yang usang, mengingat skor 1.4 adalah titik terendah dari seluruh layanan operasional.
* **Fokus Retrofit pada Armada A320 & A321:** Karena A320 memiliki volume penumpang tertinggi (terlihat dari jumlah feedback yang lebih banyak), peningkatan kecil pada kursi (*Seat Comfort* saat ini di 2.9) atau fasilitas di armada ini akan berdampak pada peningkatan *Overall Rating* perusahaan.
* **Standardisasi Layanan (SOP):** Lakukan investigasi internal terhadap kru dan konfigurasi pesawat Boeing 747-400 untuk memahami *best practice* yang membuat mereka mendapat rating 4.7. Terapkan standar tersebut atau bahkan yang lebih baik lagi di seluruh lini armada untuk meredam volatilitas grafik bulanan.

## 📂 Repository Structure
-   `/data`: Raw data (csv) keseluruhan dataset.
-   `Airways Review Dashboard.twbx`: File Tableau berisi dashboard interaktif.

---
*Disclaimer: Analisis ini menggunakan dataset publik review pelanggan sebagai simulasi Data Analysis/Business Intelligence.*
