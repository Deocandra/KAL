---
title: Transformasi rotasi pada bidang

---

# pembuktian transformasi rotasi bidang
Transformasi rotasi pada bidang dinyatakan oleh matriks:

$A = \begin{bmatrix} 
\cos \theta & -\sin \theta \\ 
\sin \theta & \cos \theta 
\end{bmatrix}$

Misalkan vektor $v = (x, y)$ dalam koordinat polar ditulis sebagai:

$v = (x, y) = (r \cos \alpha, r \sin \alpha)$

dengan:
- $r$ = panjang vektor $v$
- $\alpha$ = sudut antara vektor $v$ dan sumbu-x

Lalu, terapkan transformasi:

$A \cdot v = \begin{bmatrix} 
\cos \theta & -\sin \theta \\ 
\sin \theta & \cos \theta 
\end{bmatrix} 
\begin{bmatrix} 
r \cos \alpha \\ 
r \sin \alpha 
\end{bmatrix}$

$= r \cdot \begin{bmatrix} 
\cos \theta \cos \alpha - \sin \theta \sin \alpha \\ 
\sin \theta \cos \alpha + \cos \theta \sin \alpha 
\end{bmatrix}$

Gunakan identitas trigonometri:

$\cos(\alpha + \theta) = \cos \alpha \cos \theta - \sin \alpha \sin \theta$

$\sin(\alpha + \theta) = \sin \alpha \cos \theta + \cos \alpha \sin \theta$

Sehingga:

$A \cdot v = r \cdot \begin{bmatrix} 
\cos(\alpha + \theta) \\ 
\sin(\alpha + \theta) 
\end{bmatrix}$

Artinya, hasil transformasi adalah vektor dengan panjang tetap $r$ dan sudut bertambah $\theta$ terhadap sumbu-x.

**Kesimpulan:**

Transformasi dengan matriks $A$ adalah rotasi berlawanan arah jarum jam sebesar $\theta$ terhadap titik asal.
