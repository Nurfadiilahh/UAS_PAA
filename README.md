# UAS_PAA
# Untuk melakukan analisis algoritma pengurutan (bubble sort dan insertion sort) dan mengevaluasi kasus terburuk, terbaik, dan rata-rata, kita dapat menggunakan metrik berikut:

1. Worst Case:
   - Bubble Sort: Jumlah perbandingan maksimum terjadi ketika elemen-elemen dalam daftar terurut secara terbalik. Jumlah perbandingan pada kasus terburuk adalah (n-1) + (n-2) + ... + 1 = n*(n-1)/2, di mana n adalah jumlah elemen dalam daftar.
   - Insertion Sort: Jumlah perbandingan maksimum terjadi ketika elemen-elemen dalam daftar terurut secara terbalik. Jumlah perbandingan pada kasus terburuk adalah (n-1) + (n-2) + ... + 1 = n*(n-1)/2, di mana n adalah jumlah elemen dalam daftar.

2. Best Case:
   - Bubble Sort: Jumlah perbandingan minimum terjadi ketika elemen-elemen dalam daftar sudah terurut secara terurut. Jumlah perbandingan pada kasus terbaik adalah n-1, di mana n adalah jumlah elemen dalam daftar.
   - Insertion Sort: Jumlah perbandingan minimum terjadi ketika elemen-elemen dalam daftar sudah terurut secara terurut. Jumlah perbandingan pada kasus terbaik adalah n-1, di mana n adalah jumlah elemen dalam daftar.

3. Average Case:
   - Bubble Sort: Jumlah perbandingan rata-rata pada bubble sort dapat dianggap sama dengan jumlah perbandingan pada kasus terburuk, yaitu n*(n-1)/2, karena bubble sort melakukan perbandingan pada setiap pasangan elemen yang berdekatan, terlepas dari urutan sebelumnya.
   - Insertion Sort: Jumlah perbandingan rata-rata pada insertion sort dapat dianggap sama dengan jumlah perbandingan pada kasus terburuk, yaitu n*(n-1)/2, karena pada kasus rata-rata, elemen-elemen yang akan diurutkan secara acak akan memiliki probabilitas yang sama untuk setiap posisi.

Dalam kode yang diberikan, metode pengurutan dipilih oleh pengguna dan kode mengevaluasi metode pengurutan tersebut dalam kasus terburuk, terbaik, dan rata-rata menggunakan list yang sama pada setiap iterasi.

Jadi, dalam kasus ini, analisis algoritma pengurutan (bubble sort dan insertion sort) memberikan hasil berikut:
- Worst case: n*(n-1)/2 perbandingan
- Best case: n-1 perbandingan
- Average case: n*(n-1)/2 perbandingan

Kode tersebut juga menghasilkan output yang mencetak hasil perbandingan dalam iterasi pertama dan terakhir dari metode pengurutan yang digunakan, serta mencetak waktu komputasi untuk setiap metode pengurutan.

Harap dicatat bahwa analisis yang diberikan hanya berlaku untuk kasus pengurutan list yang sama pada setiap iterasi. Jika list yang diurutkan berbeda pada setiap iterasi, analisis tersebut tidak lagi berlaku.



# Berikut adalah analisis algoritma untuk evaluasi kasus terbaik (best case), kasus terburuk (worst case), dan kasus rata-rata (average case) untuk kedua algoritma TSP dan Dijkstra:

*Analisis Algoritma TSP:*

a. Worst Case:
   - Pada worst case, kita harus mengunjungi setiap simpul tepat satu kali.
   - Jumlah node: N
   - Jumlah iterasi: N - 1 (karena simpul awal sudah dikunjungi)
   - Jumlah total perbandingan: N - 1
   - Waktu Komputasi: O(N)

b. Best Case:
   - Pada best case, simpul awal langsung terhubung ke simpul dengan bobot terendah.
   - Jumlah node: N
   - Jumlah iterasi: 1
   - Jumlah total perbandingan: 1
   - Waktu Komputasi: O(1)

c. Average Case:
   - Pada kasus rata-rata, kita akan melakukan serangkaian uji coba dengan grafik acak untuk mendapatkan rata-rata bobot dan waktu komputasi.
   - Jumlah node: N
   - Jumlah iterasi: N - 1 (karena simpul awal sudah dikunjungi)
   - Jumlah total perbandingan: Bervariasi, tergantung pada struktur grafik yang dihasilkan
   - Waktu Komputasi: Bervariasi, tergantung pada struktur grafik yang dihasilkan

*Analisis Algoritma Dijkstra:*

a. Worst Case:
   - Pada worst case, semua simpul harus dikunjungi untuk mencapai simpul akhir.
   - Jumlah node: N
   - Jumlah total perbandingan: N^2
   - Waktu Komputasi: O(N^2)

b. Best Case:
   - Pada best case, simpul awal langsung terhubung ke simpul akhir.
   - Jumlah node: N
   - Jumlah total perbandingan: N
   - Waktu Komputasi: O(N)

c. Average Case:
   - Pada kasus rata-rata, kita akan melakukan serangkaian uji coba dengan grafik acak untuk mendapatkan rata-rata bobot dan waktu komputasi.
   - Jumlah node: N
   - Jumlah total perbandingan: Bervariasi, tergantung pada struktur grafik yang dihasilkan
   - Waktu Komputasi: Bervariasi, tergantung pada struktur grafik yang dihasilkan

# NUR FADILLAH_F55121047
# Kelas : B
