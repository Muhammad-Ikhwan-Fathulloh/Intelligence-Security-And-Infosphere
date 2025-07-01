## 1. Alur dan Proses SIGINT dan IMINT

### Alur SIGINT

1. Pengumpulan data ulasan produk dari sumber komunikasi publik (dataset Amazon Reviews).
2. Pra-pemrosesan data: Membersihkan dan sampling data untuk efisiensi.
3. Analisis sentimen menggunakan model *Transformer Pre-trained Sentiment Analysis*.
4. Visualisasi hasil analisis sentimen dan rating.

### Alur IMINT

1. Simulasi data keramaian pengunjung di beberapa lokasi strategis (Mall A, Mall B, Pasar C).
2. Pengamatan dan pencatatan total pengunjung per lokasi.
3. Visualisasi total pengunjung untuk mengetahui pusat minat konsumen.

---

## Ilustrasi Hasil Visualisasi

### Distribusi Sentimen Total (SIGINT)

![Distribusi Sentimen](download%20\(31\).png)
**Positif:** 2021, **Negatif:** 983

### Distribusi Rating Total (SIGINT)

![Distribusi Rating](download%20\(32\).png)
**Rating 1:** 304, **Rating 2:** 189, **Rating 3:** 231, **Rating 4:** 406, **Rating 5:** 1874

### Rata-rata Helpfulness Ratio per Bulan (SIGINT)

![Helpfulness Ratio](download%20\(33\).png)

### Total Visitor per Location (IMINT)

![Visitor IMINT](download%20\(34\).png)
**Mall A:** 26,922, **Mall B:** 28,278, **Pasar C:** 27,942

---

## 2. Pengambilan Keputusan dan Simulasi

* **SIGINT:** Data sentimen menunjukkan dominasi sentimen positif, memperkuat keyakinan bahwa produk memiliki minat pasar yang kuat. Mayoritas ulasan memiliki skor tinggi.
* **IMINT:** Data pengunjung menunjukkan Mall B menjadi lokasi dengan tingkat kunjungan tertinggi, diikuti oleh Pasar C dan Mall A. Lokasi tersebut diprioritaskan dalam distribusi produk.

> **Kesimpulan:** SIGINT dan IMINT dapat digunakan secara terintegrasi untuk mendukung keputusan produksi dan distribusi.

---

## 3. Potensi Bias dan Strategi Mitigasi

### Potensi Bias

* **SIGINT:** Bias sampling.
* **IMINT:** Bias lokasi.
* **Dunning-Kruger Effect:** Pengambilan kesimpulan terlalu dini dari data terbatas.

### Strategi Mitigasi

* Triangulasi data (SIGINT, IMINT, OSINT, HUMINT).
* Perluasan cakupan pengumpulan data.
* Analisis multi-periode.
* Validasi lapangan.

---

## 4. Analisis Sentimen dan Bias

### Data Multi-Sumber

![Grafik HUMINT, OSINT, SIGINT](Screenshot%202025-07-01%20181815.png)

### (a) Kesimpulan Sentimen Publik

* **Grafik A - HUMINT:** Mayoritas positif.
* **Grafik B - OSINT:** Fluktuatif.
* **Grafik C - SIGINT:** Topik kebijakan sering dibahas.

### (b) Potensi Bias

* **HUMINT:** Bias responden.
* **OSINT:** Bias algoritma media sosial.
* **SIGINT:** Bias sampling.

### (c) Langkah-Langkah Meminimalisir Bias

* Triangulasi HUMINT, OSINT, SIGINT.
* Pengumpulan data multi-periode.
* Validasi lapangan dan penggunaan metode machine learning.

---

## Eksplorasi Topik Penelitian Lanjutan

Penulis berencana mengeksplorasi topik penelitian lain untuk memperluas wawasan dan kontribusi di bidang ini.

### Dashboard Hasil Analisis

#### HUMINT

![Dashboard HUMINT](Screenshot%202025-07-01%20165904.png)

* **Positif:** 1432
* **Netral:** 374
* **Negatif:** 194

#### OSINT

![Dashboard OSINT](Screenshot%202025-07-01%20165920.png)

* **Positif:** 1348
* **Netral:** 439
* **Negatif:** 213

#### SIGINT

![Dashboard SIGINT](Screenshot%202025-07-01%20165944.png)

* **Positif:** 1438
* **Netral:** 395
* **Negatif:** 167

---

## Referensi Dataset

* [Amazon Fine Food Reviews (HUMINT)](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
* [Sentiment140 (OSINT)](https://www.kaggle.com/datasets/kazanova/sentiment140)
* [SMS Spam Collection Dataset (SIGINT)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## GitHub Repository

[Link GitHub Project](https://github.com/Muhammad-Ikhwan-Fathulloh/Intelligence-Security-And-Infosphere)
