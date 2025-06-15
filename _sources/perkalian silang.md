---
title: '✍️ Ringkasan Materi: Perkalian Silang (Cross Product)'

---



#  Ringkasan Materi: Perkalian Silang (Cross Product)

Perkalian silang adalah operasi antara dua vektor dalam ruang 3 dimensi yang menghasilkan:

* **Vektor baru** yang **tegak lurus (orthogonal)** terhadap dua vektor asal
* Hasil berupa vektor: \$\vec{u} \times \vec{v}\$

### Rumus Umum Cross Product

Jika:

$$
\vec{u} = \begin{bmatrix} u_1 \\ u_2 \\ u_3 \end{bmatrix}, \quad
\vec{v} = \begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix}
$$

Maka:

$$
\vec{u} \times \vec{v} =
\begin{bmatrix}
u_2 v_3 - u_3 v_2 \\
-(u_1 v_3 - u_3 v_1) \\
u_1 v_2 - u_2 v_1
\end{bmatrix}
$$

### Luas Jajargenjang

$$
\text{Luas} = \|\vec{u} \times \vec{v}\|
$$

### Luas Segitiga

$$
\text{Luas} = \frac{1}{2} \|\vec{AB} \times \vec{AC}\|
$$

---

# ✅ Penyelesaian Soal

### **1. Luas Jajargenjang dari**

$$
\vec{u} = \begin{bmatrix} 1 \\ 2 \end{bmatrix}, \quad
\vec{v} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}
$$

Gunakan determinan matriks 2x2:

$$
\text{Luas} = \left| \begin{vmatrix} 1 & 2 \\ 2 & 1 \end{vmatrix} \right|
= |1 \cdot 1 - 2 \cdot 2| = |-3| = \boxed{3}
$$

---

### **2. Luas Jajargenjang dari**

$$
\vec{u} = \begin{bmatrix} 2 \\ 0 \end{bmatrix}, \quad
\vec{v} = \begin{bmatrix} 0 \\ 3 \end{bmatrix}
$$

$$
\text{Luas} = \left| \begin{vmatrix} 2 & 0 \\ 0 & 3 \end{vmatrix} \right|
= |2 \cdot 3 - 0 \cdot 0| = |6| = \boxed{6}
$$

---

### **3. Luas Segitiga dengan Titik:**

$$
A = (0,0,0), \quad B = (1,3,-1), \quad C = (2,1,1)
$$

#### a. Vektor AB dan AC:

$$
\vec{AB} = B - A = (1,3,-1), \quad \vec{AC} = C - A = (2,1,1)
$$

#### b. Hitung Cross Product:

$$
\vec{AB} \times \vec{AC} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
1 & 3 & -1 \\
2 & 1 & 1
\end{vmatrix}
= \hat{i}(3 \cdot 1 - (-1) \cdot 1) - \hat{j}(1 \cdot 1 - (-1) \cdot 2) + \hat{k}(1 \cdot 1 - 3 \cdot 2)
= \begin{bmatrix} 4 \\ -3 \\ -5 \end{bmatrix}
$$

#### c. Panjang Vektor:

$$
\|\vec{AB} \times \vec{AC}\| = \sqrt{4^2 + (-3)^2 + (-5)^2} = \sqrt{16 + 9 + 25} = \sqrt{50}
$$

#### d. Luas Segitiga:

$$
\text{Luas} = \frac{1}{2} \sqrt{50} = \boxed{\frac{\sqrt{50}}{2} \approx 3.54}
$$

---

### **4. Luas Segitiga dengan Titik:**

$$
A = (5,2,-1), \quad B = (3,6,2), \quad C = (1,0,4)
$$

#### a. Vektor AB dan AC:

$$
\vec{AB} = B - A = (-2,4,3), \quad \vec{AC} = C - A = (-4,-2,5)
$$

#### b. Hitung Cross Product:

$$
\vec{AB} \times \vec{AC} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
-2 & 4 & 3 \\
-4 & -2 & 5
\end{vmatrix}
= \hat{i}(4 \cdot 5 - 3 \cdot (-2)) - \hat{j}((-2)(5) - 3(-4)) + \hat{k}((-2)(-2) - 4(-4))
$$

$$
= \hat{i}(20 + 6) - \hat{j}(-10 + 12) + \hat{k}(4 + 16)
= \begin{bmatrix} 26 \\ -2 \\ 20 \end{bmatrix}
$$

#### c. Panjang Vektor:

$$
\|\vec{AB} \times \vec{AC}\| = \sqrt{26^2 + (-2)^2 + 20^2} = \sqrt{676 + 4 + 400} = \sqrt{1080}
$$

#### d. Luas Segitiga:

$$
\text{Luas} = \frac{1}{2} \sqrt{1080} = \boxed{\frac{\sqrt{1080}}{2} \approx 16.43}
$$
