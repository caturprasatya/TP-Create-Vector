
# Visualisasi Medan Vektor

Kode ini digunakan untuk memvisualisasikan dua medan vektor berdasarkan soal matematika yang diberikan. Medan vektor direpresentasikan dalam bentuk panah (arrow plot) menggunakan pustaka **Matplotlib** dan **NumPy**.

## Medan Vektor
1. **Soal (a):**
   \[
   \mathbf{F}(x, y) = x\mathbf{i} + \frac{1}{2}y\mathbf{j}
   \]
   - Komponen \( x \): \( Fx = x \).
   - Komponen \( y \): \( Fy = \frac{1}{2}y \).
   - Pola vektor menunjukkan arah horizontal bergantung pada \( x \), dan arah vertikal bergantung pada \( y \) dengan faktor pengurang \( \frac{1}{2} \).

2. **Soal (b):**
   \[
   \mathbf{F}(x, y) = y\mathbf{i} + (x + y)\mathbf{j}
   \]
   - Komponen \( x \): \( Fx = y \).
   - Komponen \( y \): \( Fy = x + y \).
   - Pola vektor lebih kompleks karena komponen \( y \) tergantung pada penjumlahan \( x \) dan \( y \).

## Fitur Kode
- Membuat grid menggunakan `numpy.meshgrid` untuk mendefinisikan koordinat \( x \) dan \( y \).
- Menggunakan `matplotlib.pyplot.quiver` untuk memplot medan vektor.
- Visualisasi meliputi dua plot terpisah untuk masing-masing medan vektor:
  - Plot pertama untuk soal (a), dengan vektor berwarna biru.
  - Plot kedua untuk soal (b), dengan vektor berwarna merah.
- Sumbu koordinat dan garis grid ditampilkan untuk memberikan konteks visual.

## Cara Menggunakan
1. Pastikan Python 3 terinstal di sistem Anda.
2. Instal pustaka yang diperlukan:
   ```bash
   pip install matplotlib numpy
   ```
3. Salin dan tempel kode Python ke dalam editor JupyterLab atau IDE Python Anda.
4. Jalankan kode untuk menghasilkan dua grafik visualisasi medan vektor.

## Hasil
- Grafik pertama menunjukkan medan vektor dari soal (a).
- Grafik kedua menunjukkan medan vektor dari soal (b).

## Persyaratan
- Python 3.x
- Pustaka:
  - **Matplotlib**: Untuk visualisasi grafik.
  - **NumPy**: Untuk perhitungan numerik dan grid data.