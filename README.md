
# 📚 Datakuliah

Repositori ini berisi kumpulan data dan file pendukung untuk berbagai macam mata kuliah di bidang **Ilmu Komputer** dan terkait. Tujuannya adalah menyediakan sumber belajar yang terstruktur, mudah diakses, dan dapat digunakan untuk praktikum, penelitian, maupun eksplorasi mandiri.

---

## 📂 Struktur Direktori

- **CC_GENERAL.csv**  
  Dataset transaksi kartu kredit untuk analisis *clustering* dan *machine learning*.

- **bank.csv**  
  Data nasabah bank untuk studi *classification* dan *predictive modeling*.

- **citation_network.csv**  
  Jaringan sitasi untuk analisis graf dan *network science*.

- **facebook_combined.txt.gz**  
  Data graf jejaring sosial Facebook (compressed).

- **friend_of_friend_relationships.txt**  
  Relasi *friend-of-friend* untuk eksplorasi algoritma graf.

- **lastfm_asia_edges.csv**  
  Data interaksi musik dari Last.fm Asia.

- **nietzsche-ID.txt**  
  Teks filsafat Nietzsche dalam bahasa Indonesia untuk analisis NLP.

- **pricerunner_aggregate.csv**  
  Data agregat harga untuk studi *recommender systems*.

- **recommender.txt**  
  Dataset sederhana untuk sistem rekomendasi.

- **simulation.py**  
  Script Python untuk simulasi data/algoritma.

- **test_data_master_vokal.zip**  
  Data uji untuk pengolahan vokal.

- **twitter_combined.txt.gz**  
  Dataset jejaring sosial Twitter (compressed).

---

## 🚀 Cara Penggunaan

1. **Clone repositori ini**  
   ```bash
   git clone https://github.com/hyulianton/datakuliah.git
   cd datakuliah
   ```

2. **Eksplorasi dataset**  
   Gunakan Python, R, atau tools lain untuk membaca file CSV/TXT.  
   Contoh dengan Python:
   ```python
   import pandas as pd
   df = pd.read_csv("bank.csv")
   print(df.head())
   ```

3. **Jalankan simulasi**  
   ```bash
   python simulation.py
   ```

---

## 🎯 Tujuan

- Menyediakan **dataset nyata** untuk mendukung pembelajaran berbagai mata kuliah (Big Data, AI, Jejaring Sosial, NLP, dll.).
- Mempermudah mahasiswa dalam melakukan **praktikum dan penelitian**.
- Menjadi **sumber terbuka** yang dapat dikembangkan lebih lanjut.

---

## 🛠️ Teknologi

- Bahasa: **Python**
- Tools: Pandas, NetworkX, scikit-learn (disarankan)

---

## 🤝 Kontribusi

Silakan *fork* repositori ini dan ajukan *pull request* jika ingin menambahkan dataset atau perbaikan.

---

## 📜 Lisensi

Repositori ini bersifat **open educational resource**. Gunakan untuk keperluan akademik dan penelitian.  
Mohon cantumkan atribusi jika menggunakan data ini dalam publikasi.

---

## 👨‍🏫 Tentang

Repositori ini dikelola oleh **Heribertus Yulianton**, dosen senior di bidang **Cloud Computing, Big Data, dan AI** di Universitas Stikubank Semarang.  
Fokus utama: menjembatani teknologi, teologi, dan kehidupan praktis melalui sumber belajar yang terstruktur.
