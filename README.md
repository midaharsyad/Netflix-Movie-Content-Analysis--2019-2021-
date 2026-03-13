# 🎬 Netflix Movie Content Analysis (2019–2021)

## 📌 Project Overview
Netflix merupakan salah satu platform streaming dan hiburan digital terbesar di dunia. Film menjadi salah satu jenis konten utama yang tersedia di platform ini.

Proyek ini bertujuan untuk menganalisis konten film Netflix pada periode **2019 hingga 2021** guna memahami tren penambahan film, mengidentifikasi genre dan negara yang dominan, serta memberikan **rekomendasi berbasis data** untuk mendukung pertumbuhan konten di masa mendatang.

Dataset yang digunakan dalam analisis ini terdiri dari **3.276 data film**.

---

# ❓ Business Problem

Pada periode yang diamati, jumlah film yang ditambahkan ke Netflix mengalami penurunan:

- **2019 → 2020:** -8.81%  
- **2020 → 2021:** -36.67%

Penurunan ini menimbulkan pertanyaan bisnis berikut:

**Bagaimana Netflix dapat meningkatkan pertumbuhan konten film dari -36.67% menjadi -27.86% pada tahun berikutnya?**

---

# 🎯 Project Objectives

- Menganalisis **tren pertumbuhan konten film di Netflix**
- Mengidentifikasi **negara yang paling banyak berkontribusi terhadap konten film**
- Menganalisis **genre film yang paling dominan**
- Mengidentifikasi **sutradara yang paling banyak memproduksi film**
- Memberikan **rekomendasi berbasis data** untuk meningkatkan pertumbuhan konten film

---

# 📂 Dataset Description

Dataset berisi informasi mengenai film yang tersedia di Netflix dengan atribut sebagai berikut:

| Kolom | Deskripsi |
|------|------|
| show_id | Identitas unik setiap film |
| type | Jenis konten (Film atau TV Show) |
| title | Judul film |
| director | Nama sutradara film |
| cast | Daftar aktor yang bermain dalam film |
| country | Negara produksi |
| date_added | Tanggal film ditambahkan ke Netflix |
| years_added | Tahun film ditambahkan |
| release_year | Tahun rilis film |
| rating | Klasifikasi usia penonton |
| duration | Durasi film |
| listed_in | Kategori genre film |
| description | Deskripsi singkat film |

---

# 🧹 Data Cleaning

Sebelum melakukan analisis, dilakukan beberapa tahapan pembersihan data agar dataset siap digunakan:

- Menghapus data duplikat berdasarkan kolom **show_id**
- Menangani nilai yang hilang pada kolom **country** dan **director**
- Memformat variabel data seperti mengubah **date_added** menjadi format tanggal dan mengekstrak **years_added**
- Memisahkan kolom dengan beberapa nilai seperti **country** dan **listed_in** untuk analisis yang lebih detail

---

# 🔍 Data Analysis Workflow

Proyek ini mengikuti tahapan analisis data sebagai berikut:

1. **Business Understanding**  
Memahami permasalahan terkait penurunan pertumbuhan konten film.

2. **Data Understanding**  
Memahami struktur dataset dan variabel yang tersedia.

3. **Data Preparation**  
Melakukan pembersihan dan transformasi data.

4. **Exploratory Data Analysis (EDA)**  
Menganalisis pola pertumbuhan film, negara, genre, dan sutradara.

5. **Visualization & Insight Extraction**  
Membuat visualisasi untuk mendapatkan insight dari data.

---

# 📊 Key Analysis Metrics

- ### Pertumbuhan Konten Film per Tahun
  Menganalisis jumlah film yang ditambahkan ke Netflix setiap tahun.

- ### Pertumbuhan Konten Film Berdasarkan Negara
  Mengidentifikasi negara yang paling banyak menyumbang film ke Netflix.

- ### Distribusi Genre Film
  Menganalisis genre film yang paling banyak tersedia di Netflix.

- ### Kontribusi Sutradara
  Mengidentifikasi sutradara yang paling banyak memproduksi film di Netflix.

---

# 💡 Key Insights

- ### Kontribusi Negara
  **Amerika Serikat** merupakan negara dengan kontribusi film terbanyak yaitu **1.676 film**, diikuti oleh **India**. Negara lain memberikan kontribusi yang jauh lebih sedikit.

- ### Distribusi Genre
  Genre film yang paling dominan di Netflix adalah:
  - Drama
  - Film Internasional
  - Komedi

- ### Genre Dominan di Amerika Serikat
  Genre yang paling banyak diproduksi di Amerika Serikat antara lain:
  - Drama
  - Komedi
  - Action & Adventure
  - Children & Family Movies
  - Independent Movies

- ### Kontribusi Sutradara
  Sutradara dengan jumlah film terbanyak adalah **Cathy Garcia-Molina** dengan **13 film**, sementara **Robert Rodriguez** berada di peringkat kelima dengan **8 film**.

---

# 🧾 Conclusion

Hasil analisis menunjukkan bahwa penurunan penambahan film di Netflix dipengaruhi oleh **konsentrasi produksi konten yang hanya berasal dari beberapa negara dan genre tertentu**. Sebagian besar film berasal dari **Amerika Serikat dan India**, sementara negara lain memiliki kontribusi yang relatif kecil.

Hal ini menunjukkan adanya peluang bagi Netflix untuk memperluas produksi konten ke lebih banyak negara serta meningkatkan keberagaman genre film.

---

# 🚀 Recommendations

- ### Memperluas Produksi Film ke Lebih Banyak Negara
  Mendorong produksi film dari negara yang kontribusinya masih rendah untuk meningkatkan keberagaman konten global.

- ### Diversifikasi Genre Film
  Menambah variasi genre film dapat membantu menarik lebih banyak segmen penonton.

- ### Kolaborasi dengan Sutradara Berpengalaman
  Bekerja sama dengan sutradara berpengalaman dapat membantu menghasilkan film berkualitas tinggi dan meningkatkan daya saing Netflix.

---

# 🛠 Tools & Technologies

The analysis was conducted using:

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
