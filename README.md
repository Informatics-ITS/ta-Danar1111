# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Danar Sodik Priyambodo  
**NRP**: 5025211145  
**Judul TA**: Sistem Deteksi Postur Duduk Ergonomis Menggunakan Pose Estimation dan Support Vector Machine  
**Dosen Pembimbing**: Ir. Adhatus Solichah Ahmadiyah, S.Kom., M.Sc.  

---

## 📺 Demo Aplikasi  

[![Demo Aplikasi](https://i.ytimg.com/vi/zIfRMTxRaIs/maxresdefault.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)  
*Klik gambar di atas untuk menonton demo*

---

## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
- Daftar dependensi:
  - Ubuntu versi 20.04
  - NVIDIA CUDA minimum versi 11.8.0, maksimum versi 12.8
  - Docker Image versi pengembangan (devel) : nvidia/cuda:11.8.0-devel-ubuntu20.04
  - cuDNN versi 8.3.3.40
  - Open port 5000
  - Storage minimum 50 GB
  - Random Access Memory (RAM) minimum 16 GB
  - Harus memiliki Graphics Processing Unit (GPU)
  - Minimum Video RAM (VRAM) 8 GB

### Langkah-langkah  
1. **Instalasi dan deploy**  
   ```bash
   source <(curl -s https://raw.githubusercontent.com/Informatics-ITS/ta-Danar1111/main/install.sh)
   ```
2. Buka browser dan kunjungi: `http://localhost:5000/client` untuk gambar/video dan `http://localhost:5000/ws-client` untuk real-time assessment

---

## 📚 Dokumentasi Tambahan

- [![User Manual]](docs/UserManual.pdf)
- [![Diagram Arsitektur]](docs/arsitektur.png)
- [![Dataset]](docs/dataset_rula_reba.csv)

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: priyambodo02@gmail.com
- Pembimbing Utama: adhatus@if.its.ac.id
