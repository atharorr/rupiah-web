# NOTICE

Hak cipta (c) 2026 Khanza Atha Aulyan, Rahma Auliya Safira, Elysa Putri Heksa C, dan Rizal Alfarizi.

**RupiahLens**: Penerapan Transfer Learning (YOLOv8) untuk Deteksi dan Klasifikasi Nominal Rupiah dengan Output Suara sebagai Alat Bantu Tunanetra.

Proyek mata kuliah Computer Vision, Program Studi Teknik Informatika, Fakultas Teknik, Universitas Wahid Hasyim Semarang.

Lambang Universitas Wahid Hasyim pada situs ini hanya menunjukkan asal proyek perkuliahan dan merupakan milik universitas tersebut. Logo RupiahLens adalah karya tim pengembang.

## Lisensi proyek

Proyek ini dirilis di bawah **GNU Affero General Public License v3.0 (AGPL-3.0)**. Teks lengkap lisensi ada di berkas `LICENSE`.

Alasannya: model deteksi (`best_v4*.onnx`) dilatih ulang dari bobot Ultralytics YOLOv8 (`yolov8n.pt`) yang berlisensi AGPL-3.0, sehingga proyek yang memakainya mengikuti ketentuan yang sama. Kode sumber halaman web dan model tersedia di repository ini.

## Komponen pihak ketiga

| Komponen | Pemilik / Sumber | Lisensi |
|---|---|---|
| YOLOv8 (model dasar dan pustaka pelatihan) | Ultralytics | AGPL-3.0 |
| Dataset `dataset_rupiah-jsets5` (workspace `st-and`, Roboflow Universe) | Pembuat dataset di Roboflow Universe | CC BY 4.0 |
| ONNX Runtime Web (mesin inferensi di browser) | Microsoft | MIT |

Dataset dipakai sesuai ketentuan CC BY 4.0 dengan mencantumkan atribusi di atas. Model dilatih ulang (fine-tuning) dari data tersebut untuk kebutuhan proyek ini.

## Penafian

RupiahLens adalah prototipe akademik. Sistem ini belum diuji oleh pengguna tunanetra dan bukan alat bantu bersertifikat. Akurasi dipengaruhi cahaya, kondisi uang, dan kamera. Jangan dijadikan satu-satunya alat untuk transaksi penting.
