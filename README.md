# Deteksi Kematangan Tomat Menggunakan Histogram HSV

Proyek ini bertujuan untuk mengklasifikasikan tingkat kematangan tomat menggunakan metode analisis warna berdasarkan histogram HSV. Gambar tomat dikategorikan ke dalam tiga kelas: **Hijau**, **Campur**, dan **Merah**.

## 📦 Struktur Dataset

Letakkan gambar tomat dalam folder `dataset_tomat/` dengan nama:
- `hijau.bmp` - untuk tomat hijau
- `campur.bmp` - untuk tomat setengah matang
- `merah.bmp` - untuk tomat matang
- `uji-<warna>.bmp` - gambar uji (misal: `uji-merah.bmp`)

## 🚀 Cara Kerja

1. **Konversi RGB ke HSV** dilakukan secara manual.
2. **Histogram HSV** dihitung untuk setiap gambar.
3. Histogram-histogram dilatih dan dibandingkan terhadap gambar uji.
4. Gambar uji diklasifikasikan ke kategori yang paling dekat secara histogram.

## 🛠️ Instalasi dan Menjalankan

Pastikan Python dan pustaka berikut sudah terinstal:
```bash
pip install numpy opencv-python matplotlib
```

## 📩 Hubungi
email: widiarrohman1234@gmail.com