
```markdown
# Analisis Sebaran Titik Api (Hotspot) dan Fire Radiative Power (FRP) Karhutla di Indonesia

Proyek analisis data spasial dan statistik mengenai kebakaran hutan dan lahan (Karhutla) di Indonesia menggunakan data satelit VIIRS (SNPP / NOAA-20) dari **NASA FIRMS** (*Fire Information for Resource Management System*).

---

## 📋 Deskripsi Proyek
Kebakaran hutan dan lahan (Karhutla) merupakan isu lingkungan krusial di Indonesia. Proyek ini bertujuan untuk:
1. Memetakan sebaran geografis titik panas (*hotspot*) di seluruh wilayah Indonesia.
2. Menganalisis distribusi intensitas radiasi panas menggunakan metrik **Fire Radiative Power (FRP)** dalam satuan Megawatt (MW).
3. Mengklasifikasikan tingkat risiko dan kepercayaan (*confidence level*: Low, Nominal, dan High) untuk mengidentifikasi area prioritas mitigasi.

---

## 📁 Struktur Repositori

```text
analisis-karhutla-indonesia/
├── data/
│   ├── fire_archive_SV-C2_839983.csv    # Dataset historis titik api VIIRS
│   └── Readme.txt                       # Keterangan metadata dari NASA FIRMS
├── docs/
│   └── Laporan_Komprehensif_Terintegrasi_FRP_Indonesia.pdf  # Laporan lengkap hasil analisis
├── notebooks/
│   └── analisis_karhutla.ipynb          # Kode Python pembersihan data, EDA, dan pemetaan spasial
├── output/
│   ├── peta_hotspot_indonesia.png
│   ├── peta_hotspot_level_h.png
│   ├── peta_hotspot_level_n.png
│   ├── peta_sebaran_level_frp.png
│   ├── peta_sebaran_titik_api_per_level.png
│   └── statistik_hotspot_frp.png
├── .gitignore
└── README.md

```

---

## 📊 Hasil Visualisasi Utama

### 1. Peta Sebaran Hotspot Indonesia & Level FRP

### 2. Statistik Hotspot & Intensitas FRP

*(Seluruh hasil visualisasi lainnya beserta pembahasan mendalam dapat dilihat pada folder `output/` dan dokumen `docs/Laporan_Komprehensif_Terintegrasi_FRP_Indonesia.pdf`)*

---

## 🛠️ Teknologi & Library yang Digunakan

* **Bahasa Pemrograman:** Python 3
* **Manipulasi & Analisis Data:** `pandas`, `numpy`
* **Analisis & Pemetaan Spasial:** `geopandas`, `shapely`
* **Visualisasi Data:** `matplotlib`, `seaborn`

---

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori ini:**
```bash
git clone [https://github.com/roni-k27/analisis-karhutla-indonesia.git](https://github.com/USERNAME_ANDA/analisis-karhutla-indonesia.git)
cd analisis-karhutla-indonesia

```


2. **Instal library yang dibutuhkan:**
```bash
pip install pandas numpy geopandas matplotlib seaborn jupyter

```


3. **Konfigurasi API Key (Opsional):**
Jika Anda ingin menarik data terbaru secara langsung dari NASA FIRMS API, daftar gratis di [NASA FIRMS API](https://firms.modaps.eosdis.nasa.gov/api/), lalu buat file `api_key.txt` di direktori utama dan tempelkan kunci API Anda di dalamnya *(file ini otomatis diabaikan oleh `.gitignore`)*.
4. **Jalankan Notebook:**
Buka file `notebooks/analisis_karhutla.ipynb` menggunakan Jupyter Notebook, VS Code, atau Google Colab.

---

## 📄 Sumber Data

* Dataset diperoleh dari **NASA Fire Information for Resource Management System (FIRMS)** — *VIIRS 375m / S-NPP & NOAA-20*.

---

## 👤 Penulis

* **Roni Kurniawan** (NIM: 52250020) — Program Studi Sains Data, Institut Teknologi dan Sains Bandung (ITSB)

```

