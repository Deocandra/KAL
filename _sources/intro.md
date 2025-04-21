---
title: Sistem Persamaan linier

---

# Sistem Persamaan linier

## Definisi Sistem Persamaan Linier
kumpulan dari dua atau lebih persamaan linier yang melibatkan variabel-variabel yang sama. Tujuan dari sistem persamaan linier adalah untuk menemukan nilai-nilai dari variabel-variabel tersebut yang memenuhi semua persamaan dalam sistem secara bersamaan.

Definisi Formal
Secara matematis, sistem persamaan linier dapat ditulis sebagai berikut:


$$
\begin{cases}
a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1 \\
a_{21}x_1 + a_{22}x_2 + \dots + a_{2n}x_n = b_2 \\
\vdots \\
a_{m1}x_1 + a_{m2}x_2 + \dots + a_{mn}x_n = b_m
\end{cases}
$$



Di mana:
- **$x_1,x_2, . . .,x_n$** adalah variabel-variabel yang tidak diketahui (unknowns).
- **$a_{ij}$** adalah koefisien dari variabel $X_j$ dalam persamaan ke-i.
- **$b_i$** adalah konstanta dalam persamaan ke-i.
- **$m$** adalah jumlah persamaan.
- **$n$** adalah jumlah variabel.

## Solusi Persamaan Linier
solusi dari sistem persamaan linier dapat ditemukan dengan berbagai metode, di antaranya:
### Eliminasi
Metode eliminasi merupakan salah satu teknik untuk menyelesaikan sistem persamaan linear. Dalam metode ini, persamaan-persamaan tersebut dijumlahkan atau dikurangkan untuk memperoleh persamaan dengan satu variabel. Jika koefisien salah satu variabel sama, dan tanda koefisiennya berlawanan, persamaan dapat dijumlahkan untuk mengeliminasi variabel. Demikian pula, jika koefisien salah satu variabel sama, dan tanda koefisiennya sama, persamaan dapat dikurangkan untuk memperoleh persamaan dengan satu variabel.

Langkah-Langkah Metode Eliminasi
Langkah 1: Pertama, kalikan kedua persamaan yang diberikan dengan beberapa konstanta bukan nol yang sesuai untuk membuat koefisien salah satu variabel (baik x maupun y) sama secara numerik.
Langkah 2:  Setelah itu, tambahkan atau kurangi satu persamaan dari persamaan lainnya sedemikian rupa sehingga satu variabel tereliminasi. Sekarang, jika Anda memperoleh persamaan dalam satu variabel, lanjutkan ke Langkah 3. Jika tidak;

Jika kita memperoleh pernyataan benar yang tidak menyertakan variabel apa pun, maka pasangan persamaan asli mempunyai solusi tak terhingga banyaknya.
Jika kita memperoleh pernyataan salah yang tidak menyertakan variabel apa pun, maka pasangan persamaan asli tidak mempunyai solusi, yaitu tidak konsisten.
Langkah 3: Selesaikan persamaan dalam satu variabel (x atau y) untuk mendapatkan nilainya.
Langkah 4: Substitusikan nilai ini ke salah satu persamaan yang diberikan untuk mendapatkan nilai variabel lain.

Contoh :
Jumlah bilangan dua digit dan bilangan yang diperoleh dengan membalik digitnya adalah 88. Jika digit bilangan tersebut berbeda 2, carilah bilangan tersebut. Berapa banyak bilangan tersebut?

Larutan:

Biarkan angka puluhan dan angka satuan pada bilangan pertama masing-masing adalah x dan y.

Jadi, angka pertama = 10x + y

Setelah angka-angka tersebut dibalik, angka kedua akan menjadi = x + 10y

Sesuai dengan pernyataan yang diberikan;

(10x + y) + (10y + x) = 88

11x + 11y = 88

11(x+y) = 88

Tentukan nilai x+y=8 ……….(1)

Diberikan pula, selisih antara kedua angka tersebut sama dengan 2. Oleh karena itu;

Tentukan x-y = 2 ………..(2)

atau

Persamaan y-x = 2 …………(3)

Jika kita perhatikan persamaan 1 dan 2, maka dengan metode eliminasi kita peroleh,

x = 5 dan y = 3

Jadi, jumlahnya adalah 53.

Jika kita perhatikan persamaan 1 dan 3, maka dengan metode eliminasi kita peroleh,

x = 3 dan y = 5

Jadi, jumlahnya adalah 35.

Jadi, ada dua angka tersebut, 53 dan 35.


### Eliminasi Gaus
Eliminasi Gauss adalah metode yang digunakan untuk menyederhanakan sistem persamaan linier ke dalam bentuk eselon baris. Langkah-langkahnya adalah:
1. Susun sistem persamaan dalam bentuk matriks augmented.
2. Gunakan operasi baris elementer untuk mengubah matriks ke bentuk eselon baris.
3. Dari bentuk eselon baris, gunakan substitusi balik untuk menemukan nilai variabel.

contoh:

$\begin{bmatrix} 
1 & 1 & | 5 \\ 
4 & -1 & | 1
\end{bmatrix}$

1. kita bisa membagi baris pertama dengan 2: $R_1 \rightarrow \frac{R_1}{2}$:

   $\begin{bmatrix} 
   1 & 0.5 & | 2.5 \\ 
   4 & -1 & | 1
   \end{bmatrix}$
   
2. untuk baris 2, kurangkan 4 x $R_1$ dari $R_2$:
    $\begin{bmatrix} 
   1 & 0.5 & | 2.5 \\ 
   0 & -3 & | -9
   \end{bmatrix}$
   
3. substitusi mundur (black subtitution) sekarang kita selesaikan sistem dari bawah ke atas
   
    1.persamaan 2
    $-3y = -9$
    $y = \frac {-9}{-3} =3$
    2.persamaan 1
    $x + 0.5y = 2.5$
    substitusi $y = 3$
    $x + 0.5(3) = 2.5$
    $x + 1.5 = 2.5$
    $x = 2.5 - 1.5 = 1$
    Sehingga diperoleh **$x = 1$ dan $y = 3$**
### Solusi Grafik
metode ini menyelesaikan masalah dengan menentukan titik perpotongan du garis lurus yang merupakan tampilan dari kedua persamaan linier dua variabel.
berikut adalah langkah-lagkah penyelesaian SPLDV dengan metode grafik:
1. tentukan titik potong salah satu persamaan linier dengan sumbu X atau sumbu Y.
2. hubungkan kedua titik potong dengan menggunakan garis lurus.
3. lakukan langkah 1 dan 2 untuk persamaan lain pada SPLDV.
4. jika kedua titik berpotongan di (x,y) = (x1, y1), penyelesaian SPLDV adalah x=x1 dan y=y1.
5. jika kedua tidak berpotongan, SPLDV tidak memiliki penyelesaian.

$\begin{cases}
4x + 5y = 40\\
x + 2y = 14
\end{cases}$



<iframe scrolling="no" title="Graphing Assignment Feb 23, 2025" src="https://www.geogebra.org/material/iframe/id/begbedhq/width/526/height/682/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="526px" height="682px" style="border:0px;"> </iframe>