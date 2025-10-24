[Mental_Health.ipynb](https://github.com/user-attachments/files/23122637/Mental_Health.ipynb)[README.md](https://github.com/user-attachments/files/23122598/README.md)[README.md](https://github.com/user-attachments/files/23122341/README.md)# 🧠 Capstone Project: Analisis Stres dan Depresi pada Mahasiswa & Pekerja Muda

**Author:** Yuditchern Makawimbang  
**Tanggal:** Oktober 2025  
**Platform:** IBM x Hacktiv8 Capstone (AI for Data Analytics Track)

---

## 📘 Deskripsi Proyek

Proyek ini bertujuan untuk **mendeteksi indikasi stres dan depresi** dalam teks publik yang menggambarkan pengalaman mahasiswa dan pekerja muda.  
Analisis dilakukan menggunakan pendekatan **Natural Language Processing (NLP)** sederhana dengan bantuan **AI (LLM Granite via Replicate)** untuk mengidentifikasi pola dan topik dominan seperti tekanan akademik, lingkungan kerja, dan keseimbangan hidup.

> _This project analyzes public text data to detect early signs of stress and depression among students and young professionals using rule-based NLP and optional AI model inference (Granite via Replicate)._  

---

## 📊 Dataset

| Sumber | Deskripsi |
|--------|------------|
| [💬 Suicide & Depression Dataset (Kaggle)](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch) | Dataset berisi posting teks dari forum dukungan depresi. |
| [🎓 Student Mental Health Survey (Kaggle)](https://www.kaggle.com/datasets/abhijeetdahatonde/student-mental-health-survey) | Data survei terkait kesehatan mental mahasiswa. |

---

## ⚙️ Metodologi

1. **Data Cleaning** – menghapus simbol, tautan, dan huruf kapital.  
2. **Top-K Keyword Detection (Rule-Based)** – mengekstrak kata-kata terkait stres, depresi, tugas, kerja, dan tidur.  
3. **(Opsional) LLM Granite Analysis** – memanfaatkan model AI untuk klasifikasi dan insight tambahan.  
4. **Visualization & Summary** – menghasilkan grafik distribusi kata dan insight kualitatif.  

---

## 🧪 Hasil & Temuan Utama

- Sekitar **40% teks** mengandung kata yang berhubungan dengan stres atau depresi.  
- Topik dominan:
  - 📚 Tugas & tekanan akademik  
  - 💼 Beban kerja & atasan  
  - 💤 Gangguan tidur & kelelahan  
- Insight:
  - Dukungan sosial dan edukasi manajemen stres efektif menurunkan beban psikologis.

---

## 💡 Rekomendasi

- Implementasi program **dukungan kesehatan mental kampus & kantor**.  
- Pemanfaatan model AI untuk **analisis sentimen otomatis** dalam survei.  
- Edukasi berkelanjutan mengenai **self-care dan keseimbangan hidup**.

---

## 🧰 Cara Menjalankan di Google Colab

1. Upload dataset atau file `kaggle.json` untuk auto-download dataset dari Kaggle.  
2. (Opsional) Isi `REPLICATE_API_TOKEN` jika ingin menjalankan analisis dengan LLM.  
3. Jalankan seluruh cell dari atas ke bawah.  
4. Output otomatis:  
   - `Capstone_MentalHealth_Slides.pptx' [Capstone_MentalHealth_Slides.pptx](https://github.com/user-attachments/files/23122332/Capstone_MentalHealth_Slides.pptx'
   - `README.md`
   - `Mental_health.ipynb`[Uploading Mental_Health.ipynb…]

     

---

## 🪩 Output Files

| File | Deskripsi |
|------|------------|
| `Capstone_MentalHealth_Slides.pptx` | Slide presentasi berisi latar belakang, metode, hasil, dan kesimpulan. |
| `README.md` | Dokumen deskripsi proyek. |
| `analysis_plot.png` | Grafik distribusi keyword atau hasil analisis. |

---

## 🧭 Etika & Catatan

> Proyek ini hanya untuk tujuan edukasi dan kesadaran kesehatan mental.  
> Tidak ditujukan untuk diagnosis medis atau keputusan profesional apa pun.  
> Data yang digunakan bersumber dari dataset publik tanpa informasi pribadi.

---

## 💬 Kontak

Jika ingin berdiskusi atau kolaborasi:  
📧 **makawimbangyuditchern@gmail.com**

---

**© 2025 Yuditchern Makawimbang**  
_Made with 💙 using Google Colab, Pandas, Matplotlib, and IBM Granite AI_
