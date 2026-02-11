# # 🎵 RHYTMIA — Semantic Music Explorer

RHYTMIA adalah aplikasi web berbasis **Semantic Web** yang digunakan untuk melakukan pencarian informasi musisi dan band secara semantik dengan memanfaatkan **Linked Open Data** dari DBpedia.

Proyek ini dikembangkan sebagai **Tugas Mandiri (Case Study)** pada mata kuliah **Semantic Web (CPMK 4)**.

---

## 👤 Identitas Mahasiswa
- **Nama:** Gabriela Anastasia Tetelepta  
- **NIM:** 230101099  
- **Dosen Pengampu:** Fadli H. Wattiheluw, S.Kom., M.Kom  

---

## 📝 Deskripsi Proyek
RHYTMIA dirancang untuk menampilkan informasi band dan musisi tanpa menggunakan database lokal maupun penyimpanan data konvensional. Seluruh data diambil secara langsung dari **DBpedia Knowledge Graph** melalui mekanisme **SPARQL Query**.

Dengan pendekatan ini, data yang ditampilkan bersifat dinamis, terstruktur, serta mengikuti konsep web semantik yang memungkinkan integrasi data lintas sumber.

---

## 🚀 Fitur Aplikasi
- Pencarian band atau musisi secara real-time
- Akses langsung ke DBpedia SPARQL Endpoint
- Penyaringan data berbasis ontologi semantik
- Tampilan informasi musisi/band yang terstruktur

Informasi yang ditampilkan meliputi:
- Nama musisi atau band
- Deskripsi singkat (abstract)
- Genre musik
- Kota asal
- Tahun mulai aktif
- Gambar (jika tersedia)

---

## 🛠️ Teknologi yang Digunakan
- **Sumber Data:** DBpedia Knowledge Graph  
- **Bahasa Query:** SPARQL  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Ontologi:** DBpedia Ontology (`dbo`)  

---

## 🧠 Konsep Semantic Web
Konsep Semantic Web yang diterapkan dalam aplikasi RHYTMIA antara lain:
- Linked Open Data (LOD)
- Resource Description Framework (RDF)
- SPARQL Query Language
- DBpedia Ontology

Ontologi utama yang digunakan:
- `dbo:Band`
- `dbo:MusicalArtist`
- `dbo:genre`
- `dbo:hometown`
- `dbo:activeYearsStartYear`
- `dbo:abstract`
- `dbo:thumbnail`

---

## 📸 Dokumentasi Aplikasi
### Landing Page
<img width="1919" height="875" alt="image" src="https://github.com/user-attachments/assets/64161142-1541-4f5a-a0ec-a86d5cc810d6" />
### Pencarian Band Coldplay
<img width="1919" height="874" alt="image" src="https://github.com/user-attachments/assets/cba8079a-221a-4367-b7e8-08f09000e783" />
### Pencarian Band Linkin Park
<img width="1919" height="869" alt="image" src="https://github.com/user-attachments/assets/53197a1c-4f61-4475-8085-80351be3801e" />
### Pencarian Band Queen 
<img width="1919" height="866" alt="image" src="https://github.com/user-attachments/assets/c0648e34-21f1-460f-8bc3-0742283f659c" />







### Hasil Pencarian
- Band Queen  
- Band Coldplay  
- Band Linkin Park  

---

## 📌 Catatan
Aplikasi ini sepenuhnya memanfaatkan data terbuka dari DBpedia dan tidak menyimpan data pengguna maupun data hasil pencarian secara lokal.
