# Submission Proyek Klasifikasi Gambar

## Deskripsi
Proyek ini merupakan submission untuk proyek **Klasifikasi Gambar** di platform Dicoding. Dalam proyek ini, saya menggunakan dataset **The Simpsons Characters** dari Kaggle untuk membangun model klasifikasi gambar yang dapat mengklasifikasikan gambar-gambar karakter dari serial TV **The Simpsons**.

Model ini menggunakan arsitektur CNN (Convolutional Neural Network) dengan layer **Conv2D** dan **Pooling**. Dataset dibagi menjadi 80% untuk data latih dan 20% untuk data uji, dan model harus mencapai akurasi minimal 85% di kedua set data.

## Fitur
- **Dataset:** The Simpsons Characters dari Kaggle.
- **Model:** Menggunakan CNN dengan layer Conv2D dan Pooling.
- **Akualitas Model:** Minimal 85% akurasi pada data latih dan data uji.
- **Format Model:** Disimpan dalam format **SavedModel**, **TF-Lite**, dan **TFJS**.

## Struktur Proyek
- `data/` - Folder berisi dataset gambar.
- `model/` - Folder berisi model yang sudah dilatih.
- `notebooks/` - Folder berisi notebook untuk eksperimen dan pengolahan data.
- `src/` - Folder berisi skrip untuk melatih dan mengonversi model.
- `README.md` - File ini.

## Persiapan Lingkungan
Untuk menjalankan proyek ini, pastikan kamu sudah menginstal **Python 3.x** dan beberapa library berikut:

- TensorFlow
- NumPy
- Matplotlib
- Pandas
- OpenCV

Install dependencies dengan menjalankan:

```bash
pip install -r requirements.txt
