# ANALISISDATAGAJI
Salwa Salsabila Nurman_12030122140232

Tabel 1: Lima Baris Pertama Data
age	salary	height	gender
25	50000	170	pria
30	60000	175	wanita
22	45000	168	pria
35	80000	180	wanita
28	55000	165	pria

Tabel 2: Statistik Deskriptif dari Kolom Numerik
             age        salary      height
count   5.000000      5.000000    5.000000
mean   28.000000  58000.000000  171.600000
std     4.242641  13717.621436    5.123475
min    22.000000  45000.000000  165.000000
25%    25.000000  50000.000000  168.000000
50%    28.000000  55000.000000  170.000000
75%    30.000000  60000.000000  175.000000
max    35.000000  80000.000000  180.000000

Tabel 3 : Jumlah Nilai Unik dalam Setiap Kolom
Column	Unique Values
age        	5
salary    	5
height    	5
gender    	2

INTERPRETASI DATA

Tabel 1: Lima Baris Pertama Data
Tabel ini menunjukkan lima baris pertama dari dataset yang berisi informasi tentang usia (age), gaji (salary), tinggi badan (height), dan jenis kelamin (gender). Berdasarkan tabel ini:

Kita memiliki data dari 5 individu dengan usia berkisar antara 22 hingga 35 tahun.

Gaji berkisar antara 45,000 hingga 80,000.

Tinggi badan berkisar antara 165 cm hingga 180 cm.

Jenis kelamin terdiri dari dua kategori: pria dan wanita.

Tabel 2: Statistik Deskriptif dari Kolom Numerik
Tabel ini memberikan statistik deskriptif dari kolom numerik (age, salary, dan height). Dari tabel ini:

Usia:
Rata-rata usia adalah 28 tahun dengan standar deviasi sekitar 4.24 tahun.
Usia termuda adalah 22 tahun dan tertua adalah 35 tahun.
Kuartil pertama (25%) dan kuartil ketiga (75%) masing-masing adalah 25 tahun dan 30 tahun.

Gaji:
Rata-rata gaji adalah 58,000 dengan standar deviasi sekitar 13,717.
Gaji terendah adalah 45,000 dan tertinggi adalah 80,000.
Kuartil pertama (25%) dan kuartil ketiga (75%) masing-masing adalah 50,000 dan 60,000.

Tinggi Badan:
Rata-rata tinggi badan adalah 171.6 cm dengan standar deviasi sekitar 5.12 cm.
Tinggi badan terendah adalah 165 cm dan tertinggi adalah 180 cm.
Kuartil pertama (25%) dan kuartil ketiga (75%) masing-masing adalah 168 cm dan 175 cm.

Tabel 3: Jumlah Nilai Unik dalam Setiap Kolom

Tabel ini menunjukkan jumlah nilai unik dalam setiap kolom. Dari tabel ini:
Usia, gaji, dan tinggi badan masing-masing memiliki 5 nilai unik, yang berarti setiap individu dalam dataset memiliki usia, gaji, dan tinggi badan yang berbeda.
Jenis kelamin memiliki 2 nilai unik, yaitu "pria" dan "wanita".

VISUALISASI DATA

Berikut adalah visualisasi dari data yang telah dianalisis menggunakan matplotlib:

Scatter Plot: Age vs Salary
Histogram: Distribution of Salary
Box Plot: Distribution of Height
Bar Plot: Count of Gender

PENJELASAN VISUALIASI DATA

1. Scatter Plot: Age vs Salary

Scatter plot ini menunjukkan hubungan antara usia (age) dan gaji (salary). Kita dapat melihat bagaimana gaji cenderung meningkat seiring bertambahnya usia.
Ada beberapa outliers yang bisa jadi menarik untuk diteliti lebih lanjut.

2. Histogram: Distribution of Salary

Histogram ini menunjukkan distribusi gaji dalam dataset. Kita dapat melihat distribusi gaji di antara individu dan menentukan apakah distribusi tersebut mirip dengan distribusi normal atau terdapat skewness.
Rentang gaji bervariasi dari sekitar 45000 hingga 80000.

3. Box Plot: Distribution of Height

Box plot ini menunjukkan distribusi tinggi badan. Dari box plot, kita dapat melihat rentang interkuartil, median, dan outliers (jika ada).
Tinggi badan berkisar antara 165 hingga 180.

4. Bar Plot: Count of Gender

Bar plot ini menunjukkan jumlah individu dalam setiap kategori jenis kelamin. Kita dapat melihat apakah dataset seimbang dalam hal jenis kelamin.
Jumlah pria dan wanita terlihat seimbang dalam contoh data ini.

![Screenshot 2024-06-07 131317](https://github.com/salwasalsabila12/ANALISISDATAGAJI/assets/167194809/108561bb-f2e2-4d1d-830a-65cc30af5fcf)

Kesimpulan :
Berdasarkan data dan interpretasi dari tabel di atas, kita dapat menyimpulkan bahwa dataset ini terdiri dari informasi demografis dasar dari lima individu yang berbeda. Distribusi usia, gaji, dan tinggi badan cukup bervariasi, dengan rentang yang tidak terlalu besar. Jenis kelamin terbagi secara merata antara pria dan wanita. Statistik deskriptif memberikan gambaran umum yang baik tentang karakteristik data dan dapat digunakan untuk analisis lebih lanjut atau pembuatan visualisasi yang lebih mendalam.
