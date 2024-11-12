Notebook ini menggunakan Transfer Learning dengan model DenseNet121 untuk mengklasifikasikan digit tulisan tangan dari dataset MNIST. Tahapan utama meliputi:
1. Modifikasi Model: Menyesuaikan DenseNet121 agar sesuai dengan 10 kelas MNIST.
2. Latihan Model: Melatih model dengan semua lapisan aktif, lalu mengevaluasi performa.
3. Pembekuan Lapisan: Menguji performa dengan membekukan beberapa bagian lapisan model (denseblock1 dan denseblock2) dan melatih ulang.
4. Bonus Model: Mengulangi langkah di atas dengan model ResNet dan Vision Transformer.


Tujuan utama adalah untuk mengevaluasi pengaruh Transfer Learning dan pembekuan lapisan pada klasifikasi digit.
