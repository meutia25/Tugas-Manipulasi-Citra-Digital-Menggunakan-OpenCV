# Manipulasi Citra Digital Menggunakan OpenCV

## Nama Mahasiswa

Meutia Mirah Asih

## Deskripsi Singkat Project

Project ini merupakan implementasi berbagai teknik manipulasi citra digital menggunakan Python dan OpenCV. Eksperimen yang dilakukan meliputi pembacaan citra, konversi warna dari BGR ke RGB, resize citra, image blending, image negative, transformasi logaritmik, dan transformasi gamma. Setiap teknik dianalisis untuk memahami pengaruhnya terhadap nilai pixel, brightness, contrast, dan kualitas visual citra.

## Citra yang Digunakan

1. image1.jpg (Citra Anjing)
2. image2.jpg (Citra Kucing)

## Library yang Digunakan

* OpenCV
* NumPy
* Matplotlib

## Cara Menjalankan Notebook

1. Buka Google Colab atau Jupyter Notebook.
2. Upload file `image_manipulation.ipynb`.
3. Upload file `image1.jpg` dan `image2.jpg`.
4. Jalankan seluruh cell secara berurutan.
5. Amati hasil visualisasi dan analisis yang dihasilkan.

## Struktur Folder Project

manipulasi-citra-digital/

├── notebook/

│   └── image_manipulation.ipynb

├── images/

│   ├── image1.jpg

│   └── image2.jpg

├── report/

│   └── laporan.pdf

├── README.md

└── requirements.txt

## Ringkasan Hasil Eksperimen

* Konversi BGR ke RGB berhasil menampilkan warna citra dengan benar.
* Resize digunakan untuk menyamakan ukuran citra sebelum proses blending.
* Image blending menghasilkan citra gabungan dengan tingkat dominasi yang bergantung pada bobot yang digunakan.
* Image negative membalik intensitas pixel sehingga menghasilkan tampilan warna yang berlawanan dengan citra asli.
* Transformasi logaritmik meningkatkan detail pada area gelap.
* Transformasi gamma dapat digunakan untuk mencerahkan maupun menggelapkan citra sesuai nilai gamma yang dipilih.

## Kesimpulan Singkat

Berdasarkan eksperimen yang dilakukan, setiap teknik manipulasi citra memiliki fungsi yang berbeda. Image blending digunakan untuk menggabungkan citra, image negative digunakan untuk membalik intensitas pixel, transformasi logaritmik digunakan untuk meningkatkan detail pada area gelap, sedangkan transformasi gamma digunakan untuk mengatur tingkat kecerahan citra secara fleksibel. Pemilihan teknik yang tepat sangat penting untuk memperoleh hasil pengolahan citra yang optimal.
