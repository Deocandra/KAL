## penyelesaian sistem persamaan linier persaman linier
### operasi baris elementer
### eliminasi gaus
contoh soal 1

$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3-x_2&=2
\end{array}
$$

penyelesaian 

 $\begin{bmatrix} 
   1 & 2 & 3 & | 6 \\ 
    2 & 4 & 6 & | 12\\
   0 & 1 & 1 & | 2
   \end{bmatrix}$
   
   baris pertama kali -2 lalu kurangi baris kedua dengan hasil tersebut
   $\begin{bmatrix} 
   1 & 2 & 3 & | 6 \\ 
    0 & 0 & 0 & | 0\\
   0 & 1 & 1 & | 2
   \end{bmatrix}$

contoh soal 2

$$
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+x_3&=5\\
x_1+2x_2&=3
\end{array}
$$

contoh soal 3

$$
\begin{array}{cc}
2x_1+2x_2&=4\\
x_1+x_2&=2
\end{array}
$$

 penyelesaian 
 
 $\begin{bmatrix} 
   2 & 2 & | 4 \\ 
    1& 1 & | 2
   \end{bmatrix}$
   
   kalikan baris kedua dengan 2
   
$\begin{bmatrix} 
   2 & 2 & | 4 \\ 
    2& 2 & | 4
   \end{bmatrix}$
   
   baris kedua dikurangi baris ke 1

$\begin{bmatrix} 
   2 & 2 & | 4 \\ 
    0& 0 & | 0
   \end{bmatrix}$
   
   nyatakan $x_2$ sebagai variabel bebas:

   $x_1 = 4 - x_2$
   
   kesimpulan :

   $(x_1 , x_2) = (4 - x_2,x_2) untu semua x_2 sampai R$
contoh soal 4

$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+x_3&=6
\end{array}
$$

penyelesaian

$\begin{bmatrix} 
   1 & 1 & 0& | 4 \\ 
    1& 0 & 1&| 0
   \end{bmatrix}$
   