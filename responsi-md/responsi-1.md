
# Responsi-1 (4.1--4.3)


## Soal Reponsi-1
1. Tunjukkan atau bantah bahwa himpunan $A=\{ (x,0): x\in \mathbb{R}\}$ yang di lengkapi operasi standar merupakan ruang vektor.

1. Misalkan $U_1$ dan $U_2$ adalah subruang  dari $V$. Buktikan bahwa $U_1 \cap U_2$ juga subruang dari $V$
   
2. Tunjukkan bahwa himpunan fungsi kontinu $\mathbf{f}=f(x)$ pada $[a, b]$ yang memenuhi $$\int_a^b f(x) d x=0$$ adalah subruang dari $C[a, b]$.
   
3. Tunjukkan atau bantah bahwa jika $U_1, U_2$ subruang dari dari $V$, maka $U_1\cup U_2$ juga subruang dari $V$.
   
4. Untuk setiap subhimpunan berikut dari $\mathbf{R}^3$, tentukan apakah itu adalah subruang dari $\mathbf{R}^3$: 

    - $A=\left\{\left(x_1, x_2, x_3\right) \in \mathbf{R}^3: x_1+2 x_2+3 x_3=0\right\}$;

    - $B=\left\{\left(x_1, x_2, x_3\right) \in \mathbf{R}^3: x_1+2 x_2+3 x_3=4\right\}$;

    -  $C=\quad\left\{\left(x_1, x_2, x_3\right) \in \mathbf{R}^3: x_1 x_2 x_3=0\right\}$;

   - $D=\quad\left\{\left(x_1, x_2, x_3\right) \in \mathbf{R}^3: x_1=5 x_3\right\}$

5. Misalkan $a \in \mathbf{R}$, $\mathbf{v} \in V$, dimana $V$ adalah ruang vektor, yang memenuhi  $av=0$. Buktiakan bahwa $a=0$ atau $\mathbf{v}=0$.


6. buktikan bahwa jika $A=\{v_1, v_2, v_3, v_4\}$ membangun \[atau bebas linear\] ruang vektor $V$, maka vektor berikut: $B=\{v_1-v_2, v_2-v_3, v_3-v_4, v_4\}$
juga membangun \[atau bebas linear\]  $V$.

8. carilah $t$ sehingga vektor berikut:
$$
(3,1,4),(2,-3,5),(5,9, t)
$$
tidak bebas linear di  $\mathbf{R}^3$.

## Jawaban Responsi-1


1. Tinjau bahwa $ $A=\{ (x,0): x\in \mathbb{R}\}\subseteq \mathbb{R}^2$ dan kita tahu bahwa $\mathbb{R}^2$ adalah ruang vektor. Oleh karena itu, yang perlu kita tunjukkan bahwa $A$ adalah subruang dari $\mathbb{R}^2$ sehingga $A$ adalah ruang vektor. Dari teorema subruang, kita buktikan:
    - (tak kosong) Perhatikan bahwa $\mathbf{0}=(0,0)\in A\implies A\neq \emptyset$
    - (tertutup penjumlahan) Kita ambil $\mathbf{x}=(x,0), \mathbf{y}= (y,0)\in A$, dari definisi penjumlahan kita punya $\mathbf{x}+ \mathbf{y}=(x,0)+(y,0)= (x+y,0)\in A$ karena $x+y\in \mathbb{R}$
    - (tertutup perkalian) Kita ambil $k\in\mathbb{R}, \mathbf{x}=(x,0)\in A$. dari definisi perkalian kita punya $k\mathbb{x}= (kx,0)\in A$ karena $kx\in \mathbb{R}$.

    Dengan begitu, $A$ adalah subruang dari $\mathbb{R}$, Jadi $A$ adalah ruang vektor. $\Box$

2. Bukti. Yang akan kita lakukan adalah membuktikan bahwa $U_1 \cap U_2$ subruang dari definisi.
    - (tak kosong) $0 \in U_1$ dan $0 \in U_2$, maka $0 \in U_1 \cap U_2$.
    - (Tertutup terhadap penjumlahan) Ambil $\mathbf{x} \in U_1 \cap U_2$ dan $\mathbf{y} \in U_1 \cap U_2$, maka $\mathbf{x} \in U_1$ dan $y \in U_1$, sehingga $\mathbf{x}+\mathbf{y} \in U_1$ karena $U_1$ tertutup terhadap penjumlahan ($U_1$ ruang vektor). Demikian juga, $\mathbf{x}+\mathbf{y} \in U_2$. Oleh karena itu, $\mathbf{x}+y \in U_1 \cap U_2$.

   - (Tertutup terhadap perkalian skalar): jika $\mathbf{x} \in U_1 \cap U_2$, maka $\mathbf{x} \in U_1$. Kemudian untuk setiap $\lambda \in \mathbb{R}$, kita memiliki $\lambda \mathbf{x} \in U_1$ karena $U_1$ tertutup terhadap perkalian skalar. Demikian juga, $\lambda x \in U_2$. Oleh karena itu, $\lambda x \in U_1 \cap U_2$.

    Dengan begitu, $U_1 \cap U_2$ adalah subruang dari $V$ $\Box$


3. Serupa dengan nomor 1 dan 2 $\dots$ saya tinggalkan sebagai latihan.

4. Akan kita bantah dengan _counterexample_. Kita ambil $V=\mathbb{R}^2$,  $U_1=\{(x,0): x\in \mathbb{R}\}$, dan $U_2=\{(0,x): x\in \mathbb{R}\}$. Dari soal nomor 1, kita tahu $U_1, U_2$(serupa pembuktian dengan $U_1$) adalah subruang dari $V=\mathbb{R}^2$. Selanjutnya, tinjau bahwa $(1,0)\in U_1\implies (1,0)\in U_1 \cup U_2$ dan $(0,1), \in U_2 \implies (0,1)\in U_1 \cup U_2$. Dengan begitu, kita punya elemen $(1,0), (0,1)\in U_1 \cup U_2$, namun penjumlahannya $(1,0)+(0,1)\not\in U_1 \cup U_2$. Oleh karena itu, $U_1 \cup U_2$ tidaklah tertutup terhadap penjumlahan, jadi $U_1\cup U_2$ bukanlah subrruang $V$ $\Box$

5. Jawaban: himpunan $A,D$ adalah subruang sedangkan $B,C$ bukan.

6. Kita akan membagi kasus ketika $a=0$ dan $a\neq 0$
    - Jika $a=0$, jelas pernyataan terpenuhi.
    - Jika $a \neq 0$, maka $a$ memiliki invers perkalian $a^{-1}=(\frac{1}{a})$ sehingga $a^{-1} a=1$. Oleh karena itu, kita punya
$v=1 \cdot v=\left(a^{-1} a\right) v=a^{-1}(a v)=a^{-1} \cdot 0=0. \quad\quad (a)$

    \[Latihan, untuk setiap step (kesamaan) pada persamaan $(a)$ tuliskan alasan kenapa hal tersebut valid dilakukan]

7. - \[Kasus Bebas Linear\]

    Kita dapat membuktikan hal ini berdasarkan kriteria kebebaslinearan, yaitu: bentuk kombinasi linear dari vektor nol bersifat unik (koefisiennya nol semua).

    Anggap ada bilangan $x, y, z, w$ di $\mathbb{R}$ sedemikian sehingga
    $$
    x\left(v_1-v_2\right)+y\left(v_2-v_3\right)+z\left(v_3-v_4\right)+w v_4=0,
    $$
    maka
    $$
    x v_1+(y-x) v_2+(z-y) v_3+(w-z) v_4=0 .
    $$
    Karena $v_1, v_2, v_3, v_4$ linear independen di $V$, maka
    $$
    x=0, \quad y-x=0, \quad z-y=0, \quad w-z=0 .
    $$
    Jadi, kita mendapatkan $x=y=z=w=0$. Ini berarti daftar
    $$
    v_1-v_2, v_2-v_3, v_3-v_4, v_4
    $$
juga linear independen di $V$ berdasarkan kriteria kebebaslinearan.

- \[kasus merentang\]
  Andaikan span($B$)= $W$, yang ingin kita buktikan adalah $W=V=\text{span(A)}$. Kita membuktikannya dengan saling subset.

    TODO  [Selesaikan solusi nomor 7 :D]

8. Dari Definisi ketidakbebas-linearan, salah satu vektor di himpunan tersebut dapat ditulis sebagai kombinasi linear vektor-vektor lainnya. Katakanlah kita bisa tulis:


    $$(5,9,t)= \alpha(3,1,4)+\beta(2,-3,5)$$

    Dari kesamaan posisi kita punya sistem persamaan berikut

    $$
    \begin{align*}
    5&=3\alpha+2\beta\\
      9&= \alpha- 3\beta
    \end{align*}
    $$

    Persamaan diatas mudah kita selesaikan \[ditinggalkan sebagai latihan\], dan kita akan punya $t= 4\alpha + 5\beta=2 \quad\Box$