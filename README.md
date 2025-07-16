# Analisis Respon Publik Terhadap Shin Tae Yong 🇰🇷⚽

Proyek ini menganalisis interaksi publik terhadap pelatih Timnas Indonesia, **Shin Tae Yong**, berdasarkan data Twitter. Visualisasi dibuat dalam bentuk graph network untuk melihat pengaruh dan hubungan antar akun.

---

## 📊 Fitur Analisis
- ✔️ Visualisasi interaksi pengguna (source → target)
- ✔️ Analisis centrality:
  - Degree Centrality
  - Betweenness Centrality
  - Closeness Centrality
- ✔️ Ekspor hasil graph ke format `.gexf` (bisa dibuka di Gephi)
- ✔️ Dataset real-world dalam format `CSV`

---

## 📁 Struktur File

| File | Deskripsi |
|------|-----------|
| `analisis_respon_publik_shin_tae_yong.py` | Script utama Python untuk analisis |
| `source_target.csv` | Dataset interaksi pengguna Twitter |
| `graph_fans_shin_tae_yong.gexf` | Output graph untuk Gephi |
| `requirements.txt` | Daftar library Python yang digunakan |

---

## 💻 Cara Menjalankan

1. **Clone repo** ini:
```bash
git clone https://github.com/Radityaprama/Analisis-Respon-Publik-ShinTaeYong.git
cd Analisis-Respon-Publik-ShinTaeYong
