# Data Analysis SaaS Amazon 📊
*Oleh: Darrell Lokadeva Lim*

## 📖 Gambaran Umum
Repositori ini berisi Jupyter Notebook untuk proyek *capstone* "Data Analysis SaaS Amazon". Proyek ini menganalisis dampak dari strategi pemberian diskon promosi terhadap profitabilitas bisnis *Software as a Service* (SaaS) Amazon.

## 🎯 Latar Belakang & Pernyataan Masalah
Amazon, sebagai perusahaan teknologi yang menyediakan layanan *Software as a Service* (SaaS), memiliki basis data penjualan berskala global. Dalam upaya mempertahankan keberlanjutan bisnis dan pertumbuhan perusahaan, Amazon harus memastikan bahwa tingkat profitabilitas secara keseluruhan tetap positif. Salah satu strategi pemasaran dan penjualan yang sering diterapkan oleh perusahaan adalah dengan memberikan diskon. Namun, strategi pemberian diskon ini seringkali menjadi pisau bermata dua; di satu sisi dapat menaikkan volume penjualan, namun di sisi lain berisiko menggerus profit jika tidak dilakukan dengan tepat.

**Pernyataan Masalah:**
Perusahaan menemukan beberapa anomali saat melakukan pengulikan data, di mana beberapa transaksi yang diberi diskon justru malah merugi. Selain itu, perusahaan masih belum mengetahui seberapa parah tingkat diskon tersebut sehingga bisa merusak keuntungan perusahaan. 

**Tujuan Analisis:**
Untuk mengetahui **seberapa besar pengaruh pemberian diskon terhadap profitabilitas**, serta memberikan rekomendasi strategis berbasis data untuk mengoptimalkan strategi harga dan promosi di masa mendatang.

## 💡 Rekomendasi & Wawasan Strategis
Berdasarkan hasil analisis data, berikut adalah langkah-langkah strategis yang direkomendasikan untuk meminimalisir transaksi yang merugi dan mengembalikan margin keuntungan yang sehat:

1. **Ubah Strategi Pertumbuhan pada Segmen SMB:**
   - Hindari memaksakan *growth hacking* dengan cara membakar uang melalui potongan harga kasar di segmen SMB (*Small and Medium Business*).
   - Strategi bisa dialihkan ke program lain yang tidak memberatkan *profit*, seperti penambahan *Value-added Services* (bundling sistem, masa uji coba lebih lama, atau prioritas layanan).

2. **Bekukan Diskon pada Produk yang Rentan:**
   - Melakukan pembekuan program diskon pada produk-produk yang rentan (*Top 5 Loss Products*).

3. **Evaluasi Ulang Struktur Biaya & Harga Dasar:**
   - Sangat disarankan untuk mengevaluasi ulang struktur biaya harian (HPP infrastruktur *SaaS*) dari produk tersebut, terutama pada produk *Contact Matcher* dan 4 produk rentan lainnya.
   - Pertimbangkan untuk melakukan *re-pricing* (kenaikan harga dasar) untuk menyelamatkan kelayakan operasionalnya ke depan.

Dengan menerapkan strategi pembatasan diskon yang lebih ketat dan merevisi kembali penetapan harga pada segmen dan lini produk paling rentan, kita harap langkah ini bisa membantu perusahaan meminimalisir transaksi yang merugi, menyelamatkan margin, dan mendorong tingkat profitabilitas yang sehat secara keseluruhan di kuartal berikutnya.

## 🛠️ Tech Stack & Metodologi
- **Bahasa:** Python 3
- **Lingkungan:** Jupyter Notebook
- **Fokus Utama:** *Data Cleaning*, *Exploratory Data Analysis* (EDA), Analisis Dampak Profitabilitas, dan Rekomendasi Strategi Bisnis.
