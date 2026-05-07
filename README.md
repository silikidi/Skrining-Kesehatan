# Skrining-Kesehatan
### Digital Health Screening Tools for Healthcare Facilities (Faskes)

[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://unlicense.org/)

**[Skrining-Kesehatan](https://github.com/silikidi/Skrining-Kesehatan)** adalah repositori yang menyediakan kumpulan formulir skrining kesehatan medis dan jiwa berbasis web (HTML). Alat ini dirancang khusus untuk diintegrasikan ke dalam website Fasilitas Kesehatan (Faskes) guna mempermudah deteksi dini kondisi kesehatan pasien secara mandiri dan digital.

---

## 📋 Daftar Alat Skrining

Repositori ini mencakup berbagai instrumen validasi internasional yang telah diterjemahkan dan disesuaikan:

### 🧠 Kesehatan Jiwa & Psikologi
* **[DASS-21](dass21.html):** *Depression, Anxiety, and Stress Scale* (21 item).
* **[PHQ-9](phq9.html):** *Patient Health Questionnaire* untuk skrining depresi.
* **[GAD-7](gad7.html):** *Generalized Anxiety Disorder* untuk mengukur tingkat kecemasan.
* **[SRQ-20](srq20.html):** *Self-Reporting Questionnaire* dari WHO untuk masalah mental emosional.
* **[EPDS](epds.html):** *Edinburgh Postnatal Depression Scale* untuk depresi pasca melahirkan.
* **[OLBI-16](olbi16.html):** *Oldenburg Burnout Inventory* untuk mengukur tingkat kelelahan kerja.

### 🩺 Kesehatan Fisik & Medis
* **[BMI Calculator](bmi.html):** Kalkulator Indeks Massa Tubuh.
* **[FINDRISC](findrisc.html):** *Finnish Diabetes Risk Score* untuk deteksi risiko Diabetes Tipe 2.
* **[STOP-BANG](stop-bang.html):** Skrining untuk *Obstructive Sleep Apnea* (gangguan tidur).
* **[Cardiovascular Risk (CVS)](cvs.html):** Estimasi risiko penyakit jantung dan pembuluh darah.
* **[Breast Cancer Screening](kanker-payudara.html):** Deteksi dini risiko kanker payudara.
* **[Prostate Cancer Screening](kanker-prostat.html):** Deteksi dini risiko kanker prostat.

### 🗓️ Kesehatan Reproduksi & Lainnya
* **[Kalkulator Masa Subur](kalkulator-masa-subur.html):** Membantu perencanaan kehamilan.
* **[Kegawatdaruratan](darurat.html):** Panduan cepat kondisi darurat medis.

---

## 🚀 Fitur Utama

* **Responsive Design:** Tampilan optimal baik di desktop maupun perangkat mobile.
* **Ready-to-Use:** File HTML mandiri yang mudah diunggah ke server web manapun.
* **Privacy-Focused:** Kalkulasi dilakukan di sisi klien (*client-side*), menjaga privasi data input pengguna.
* **Clean Code:** Menggunakan struktur yang ringan dengan dependensi minimal.

---

## 🛠️ Cara Penggunaan

1.  **Clone Repositori:**
    ```bash
    git clone [https://github.com/silikidi/Skrining-Kesehatan.git](https://github.com/silikidi/Skrining-Kesehatan.git)
    ```
2.  **Integrasi:**
    Anda dapat menggunakan `<iframe>` untuk memasukkan formulir spesifik ke dalam halaman website Faskes Anda:
    ```html
    <iframe src="path/to/dass21.html" width="100%" height="600px" frameborder="0"></iframe>
    ```
3.  **Kustomisasi:**
    Sesuaikan file CSS di folder `aset` atau `dist` untuk menyelaraskan tema warna dengan brand faskes Anda.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **Unlicense** - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini tanpa batasan.

## 🤝 Kontribusi & Kontak
* [Support Donasi](https://saweria.co/sukmabudi)
* [gmailme](mailto:sukmasibudi@gmail.com)

---
*Dibuat dengan ❤️ untuk mendukung transformasi digital kesehatan di Indonesia.*
