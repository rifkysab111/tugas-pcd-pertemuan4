# tugas-pcd-pertemuan4
1. Mengubah citra berwarna (3 channel) menjadi citra keabuan (1 channel) menggunakan pembobotan nilai intensitas warna merah, hijau, dan biru berdasarkan tingkat sensitivitas mata manusia.
2. Memetakan intensitas piksel menjadi hanya dua nilai ekstrem (0 untuk hitam, 255 untuk putih) berdasarkan nilai ambang batas (threshold) tertentu, umumnya digunakan untuk memisahkan objek (foreground) dari latar belakang (background).
3. Mengurangi kedalaman bit citra dari standar 8-bit (255 tingkat keabuan) menjadi lebih rendah dengan cara membuang Least Significant Bits (LSB). Tujuannya untuk kompresi data warna, yang menghasilkan efek gradasi kasar (posterization).
4. Operasi penjumlahan atau pengurangan nilai skalar pada piksel untuk menggeser tingkat cahaya citra secara keseluruhan menjadi lebih terang atau lebih gelap (menggeser grafik histogram ke kiri/kanan).
5. Operasi perkalian nilai skalar pada piksel untuk merenggangkan atau menyempitkan jarak antara piksel paling gelap dan paling terang, sehingga detail visual gambar menjadi lebih tajam.
6. Representasi grafik statistik yang menunjukkan sebaran atau distribusi frekuensi kemunculan setiap tingkat intensitas piksel (0 hingga 255) di dalam sebuah citra digital.
7. Teknik perbaikan citra otomatis yang meratakan dan melebarkan distribusi nilai intensitas piksel yang semula menumpuk di area tertentu. Hal ini memaksimalkan rentang dinamis citra sehingga detail yang gelap atau terlalu terang menjadi lebih jelas.

