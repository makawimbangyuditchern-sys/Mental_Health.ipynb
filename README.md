# Mental_Health.ipynb
readme_content = f"""# {Mental_Health}

**Author:** {Yuditchern__Makawimbang}  
**Tanggal:** {Oktober_2025}

## Deskripsi
Proyek singkat ini menganalisis teks publik untuk mendeteksi indikasi stres dan depresi di kalangan mahasiswa dan pekerja muda. Metode: pembersihan teks, baseline rule-based (top-k keywords), dan (opsional) prompt-based LLM (IBM Granite via Replicate).

## Dataset 
- Suicide & Depression (Kaggle): https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch  
- Student Mental Health Survey (opsional): https://www.kaggle.com/datasets/abhijeetdahatonde/student-mental-health-survey
## Output
- `Capstone_MentalHealth_Slides.pptx`
- `README.md`
  
## Etika
Hasil bukan untuk diagnosis. Jaga privasi data.
"""
with open("README.md","w",encoding="utf-8") as f:
    f.write(readme_content)
print("README.md dibuat")
