# Hacktiv8 Phase 0: Graded Challenge 2

Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada Linear Algebra dan Calculus.

---

By [Rifky Aliffa](https://github.com/Penzragon)

## Dataset

![Image](https://cdn.cnn.com/cnnnext/dam/assets/201030094143-stock-rhodesian-ridgeback-exlarge-169.jpg)

Dataset yang digunakan adalah gambar seekor anjing rhodesian ridgeback yang berukuran 438 x 780 pixels. Gambar dapat diunduh dari [sini](https://cdn.cnn.com/cnnnext/dam/assets/201030094143-stock-rhodesian-ridgeback-exlarge-169.jpg).

## Objective

Dari sebuah gambar, gunakan konsep gradien untuk mendeteksi edge pada gambar dan lakukan operasi perkalian matriks pada gambar. Dengan langkah-langkah sebagai berikut:

1. Hitung vektor gradien (turunan parsial) masing-masing pixel untuk masing-masing sumbu x dan y dengan rumus:

   $$\frac{\partial I}{\partial x},\frac{\partial I}{\partial y}$$

2. Hitung gradient magnitude tiap pixel dengan rumus:

   $$\sqrt{(\frac{\partial I}{\partial x})^{2} + (\frac{\partial I}{\partial y})^{2}}$$

3. Jika nilai magnitude melebihi angka threshold, maka edge terdeteksi (Biasanya threshold ~ 30).
4. Untuk operasi matriks, buat matriks dengan nilai apapun yang bersesuaian dengan ukuran gambar dan sesuai dengan aturan perkalian matriks.
