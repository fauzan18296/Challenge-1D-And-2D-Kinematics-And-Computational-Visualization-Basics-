# 🏹 Gerak Parabola — Memahami Posisi, Kecepatan, dan Sumbu X/Y

> [!NOTE]
> **Ide utama:** Gerak parabola sebenarnya adalah gabungan dari **dua gerakan yang terjadi secara bersamaan**:
>
> * **Sumbu X** → gerak horizontal
> * **Sumbu Y** → gerak vertikal
>
> Keduanya menggunakan **waktu \(t\) yang sama**, tetapi memiliki persamaan yang berbeda.

---

## 🧠 1. Gambaran Besar

Ketika sebuah benda ditembakkan dengan kecepatan awal \(v_0\) dan sudut \(\alpha\):

```text
                         ●
                      ↗     ↘
                   ↗           ↘
                ↗                 ↘
             ↗                       ↘
───────────●────────────────────────────→ X
           ↑
           │
           Y
```

Kecepatan awal \(v_0\) kita pecah menjadi dua komponen:

```math
v_{0x}=v_0\cos\alpha
```

```math
v_{0y}=v_0\sin\alpha
```

Sehingga:

```text
             v₀
            ↗
           /|
          / |
         /  | v₀y
        /α  |
       /____|
        v₀x
```

### Artinya

* \(v_{0x}\) → kecepatan awal arah horizontal
* \(v_{0y}\) → kecepatan awal arah vertikal

---

# 📐 2. Sumbu X dan Sumbu Y

## ➡️ Sumbu X — Horizontal

Jika hambatan udara diabaikan, tidak ada percepatan horizontal:

```math
a_x=0
```

Karena tidak ada percepatan, kecepatan horizontal tetap:

```math
v_x=v_{0x}
```

Maka:

```math
v_x=v_0\cos\alpha
```

Untuk mencari posisi horizontal:

```math
x=v_xt
```

sehingga:

```math
x=(v_0\cos\alpha)t
```

> **Kesimpulan:** pada sumbu X, posisi berubah secara konstan terhadap waktu.

---

# ⬆️⬇️ 3. Sumbu Y — Vertikal

Berbeda dengan sumbu X, pada sumbu Y terdapat percepatan gravitasi:

```math
a_y=-g
```

Tanda negatif menunjukkan bahwa gravitasi arahnya **ke bawah** jika kita menetapkan arah atas sebagai positif.

Gravitasi menyebabkan kecepatan vertikal berubah.

Kecepatan vertikal:

```math
v_y=v_{0y}-gt
```

Karena:

```math
v_{0y}=v_0\sin\alpha
```

maka:

```math
v_y=v_0\sin\alpha-gt
```

---

# 📍 4. Mencari Posisi Vertikal \(y\)

Posisi vertikal benda pada waktu \(t\):

```math
y=v_{0y}t-\frac{1}{2}gt^2
```

atau:

```math
y=(v_0\sin\alpha)t-\frac{1}{2}gt^2
```

### Mengapa ada dua bagian?

Perhatikan:

```math
y=(v_0\sin\alpha)t-\frac{1}{2}gt^2
```

Bagian pertama:

```math
(v_0\sin\alpha)t
```

adalah kontribusi dari **kecepatan awal ke atas**.

Sedangkan:

```math
-\frac12gt^2
```

adalah pengaruh **gravitasi**.

Jadi benda awalnya bergerak ke atas, tetapi gravitasi terus menariknya ke bawah.

---

# 🎯 5. Mengapa Benda Naik Lalu Turun?

Pada awal gerakan:

```math
v_y>0
```

Artinya benda bergerak ke atas.

Semakin lama gravitasi mengurangi kecepatan vertikal:

```math
v_y=v_0\sin\alpha-gt
```

Di titik tertinggi:

```math
v_y=0
```

Kemudian setelah melewati titik tertinggi:

```math
v_y<0
```

Artinya benda mulai bergerak ke bawah.

```text
                    ●  ← titik tertinggi
                   / \
                 ↗     ↘
               ↗         ↘
             ↗             ↘
───────────●──────────────────●────→ X
          naik              turun
```

> **Catatan penting:**
> \(v_y=0\) pada titik tertinggi **bukan berarti benda berhenti secara keseluruhan**.
>
> Pada titik tersebut:
>
> ```math
> v_y=0
> ```
>
> tetapi:
>
> ```math
> v_x\neq0
> ```
>
> sehingga benda masih bergerak ke arah horizontal.

---

# 🧮 6. Mengapa Ada Rumus \(v_y^2\)?

Selain rumus:

```math
v_y=v_0\sin\alpha-gt
```

ada juga:

```math
v_y^2=(v_0\sin\alpha)^2-2gy
```

Rumus ini **bukan rumus tambahan yang harus selalu digunakan setelah mencari \(y\)**.

Fungsinya berbeda.

### Rumus dengan \(t\)

Jika diketahui waktu:

```math
v_y=v_0\sin\alpha-gt
```

Gunakan rumus ini ketika ingin mengetahui kecepatan vertikal **pada waktu tertentu**.

### Rumus tanpa \(t\)

Jika diketahui ketinggian:

```math
v_y^2=(v_0\sin\alpha)^2-2gy
```

Gunakan rumus ini ketika ingin mengetahui kecepatan vertikal **pada ketinggian tertentu**, tanpa perlu mengetahui waktu.

Untuk mendapatkan \(v_y\):

```math
v_y=\pm\sqrt{(v_0\sin\alpha)^2-2gy}
```

Tanda:

* \(+\) → benda sedang naik
* \(-\) → benda sedang turun

---

# 🔄 7. Hubungan Rumus-Rumus Vertikal

Semua rumus tersebut menggambarkan **gerakan vertikal yang sama**.

### Posisi

```math
y=(v_0\sin\alpha)t-\frac12gt^2
```

### Kecepatan

```math
v_y=v_0\sin\alpha-gt
```

### Kecepatan tanpa waktu

```math
v_y^2=(v_0\sin\alpha)^2-2gy
```

Jadi jangan berpikir:

> "Saya harus menggunakan rumus \(y\), lalu \(v_y^2\), lalu selesai."

Lebih tepat berpikir:

> **"Apa yang ditanyakan soal?"**

Kemudian pilih persamaan yang sesuai.

---

# 🧭 8. Bagaimana dengan \(x\)?

Untuk sumbu X:

```math
x=(v_0\cos\alpha)t
```

Tidak ada gravitasi dalam persamaan ini karena gravitasi bekerja pada arah vertikal.

```text
                Y
                ↑
                │
                │       ●
                │     ↗
                │   ↗
                │ ↗
────────────────●────────────────→ X
                │
                │
             gravitasi
                ↓
```

### Perbedaan utama

| Sumbu | Percepatan | Kecepatan                | Posisi                             |
| ----- | ---------- | ------------------------ | ---------------------------------- |
| X     | \(a_x=0\)  | \(v_x=v_0\cos\alpha\)    | \(x=(v_0\cos\alpha)t\)             |
| Y     | \(a_y=-g\) | \(v_y=v_0\sin\alpha-gt\) | \(y=(v_0\sin\alpha)t-\frac12gt^2\) |

---

# ⏱️ 9. Waktu \(t\) Adalah Penghubung X dan Y

Ini bagian yang sangat penting.

Sumbu X dan Y **tidak berdiri sendiri**.

Keduanya menggunakan waktu yang sama.

Misalnya:

```math
t=2\text{ s}
```

Maka pada waktu tersebut kita bisa menghitung:

### Posisi X

```math
x=(v_0\cos\alpha)(2)
```

### Posisi Y

```math
y=(v_0\sin\alpha)(2)-\frac12g(2)^2
```

Sehingga posisi benda:

```math
(x,y)
```

---

# 🔍 10. Kalau Tidak Diberikan Waktu?

Tidak masalah.

Kita dapat mencari \(t\) menggunakan **persamaan yang sesuai dengan informasi soal**.

Misalnya soal memberikan ketinggian:

```math
y=(v_0\sin\alpha)t-\frac12gt^2
```

Kita dapat menggunakan persamaan tersebut untuk mencari \(t\).

Atau jika informasi yang tersedia memungkinkan pendekatan lain, kita dapat menggunakan hubungan kinematika lainnya.

> **Intinya:**
> \(t\) bukan sesuatu yang selalu diberikan oleh soal.
>
> Kita bisa **mencari \(t\)** jika diperlukan.

---

# 🧩 11. Pola Penyelesaian Posisi \((x,y)\)

Jika soal meminta:

> **"Tentukan posisi benda setelah \(t\) detik."**

Gunakan:

### Langkah 1 — Pecah kecepatan awal

```math
v_{0x}=v_0\cos\alpha
```

```math
v_{0y}=v_0\sin\alpha
```

### Langkah 2 — Cari posisi horizontal

```math
x=v_{0x}t
```

atau:

```math
x=(v_0\cos\alpha)t
```

### Langkah 3 — Cari posisi vertikal

```math
y=v_{0y}t-\frac12gt^2
```

atau:

```math
y=(v_0\sin\alpha)t-\frac12gt^2
```

### Langkah 4 — Gabungkan

```math
\boxed{(x,y)}
```

Itulah posisi benda pada waktu tersebut.

---

# 🚀 12. Contoh Sederhana

Misalkan:

```text
v₀ = 20 m/s
α  = 30°
t  = 1 s
g  = 9.81 m/s²
```

### Komponen horizontal

```math
v_{0x}=20\cos30^\circ
```

### Komponen vertikal

```math
v_{0y}=20\sin30^\circ
```

Kemudian:

### Posisi horizontal

```math
x=(20\cos30^\circ)(1)
```

### Posisi vertikal

```math
y=(20\sin30^\circ)(1)-\frac12(9.81)(1)^2
```

Maka kita memperoleh:

```math
(x,y)
```

> Perhatikan bahwa kita **tidak perlu menghitung \(v_y^2\)** karena pertanyaannya hanya meminta posisi.

---

# 🧠 13. Cheat Sheet

```text
                 GERAK PARABOLA
                       │
             ┌─────────┴─────────┐
             ↓                   ↓
          SUMBU X              SUMBU Y
        Horizontal             Vertikal
             │                   │
          ax = 0                ay = -g
             │                   │
             ↓                   ↓
     vx = v₀ cos α       vy = v₀ sin α - gt
             │                   │
             ↓                   ↓
     x = v₀ cos α · t   y = v₀ sin α · t - ½gt²
```

### Rumus utama

| Besaran             | Rumus                              |
| ------------------- | ---------------------------------- |
| Kecepatan awal X    | \(v_{0x}=v_0\cos\alpha\)           |
| Kecepatan awal Y    | \(v_{0y}=v_0\sin\alpha\)           |
| Kecepatan X         | \(v_x=v_0\cos\alpha\)              |
| Kecepatan Y         | \(v_y=v_0\sin\alpha-gt\)           |
| Posisi X            | \(x=(v_0\cos\alpha)t\)             |
| Posisi Y            | \(y=(v_0\sin\alpha)t-\frac12gt^2\) |
| \(v_y\) tanpa \(t\) | \(v_y^2=(v_0\sin\alpha)^2-2gy\)    |

---

# 🎯 14. Cara Memilih Rumus

Jangan menghafal:

> ❌ "Rumus ini harus digunakan setelah rumus itu."

Lebih baik tanyakan:

> **Apa yang diketahui?**
>
> **Apa yang ingin dicari?**

### Jika ingin mencari \(x\)

```math
x=(v_0\cos\alpha)t
```

### Jika ingin mencari \(y\)

```math
y=(v_0\sin\alpha)t-\frac12gt^2
```

### Jika ingin mencari \(v_y\) dan diketahui \(t\)

```math
v_y=v_0\sin\alpha-gt
```

### Jika ingin mencari \(v_y\) tetapi tidak diketahui \(t\), sementara \(y\) diketahui

```math
v_y^2=(v_0\sin\alpha)^2-2gy
```

---

# 🌎 15. Tentang Gravitasi \(g\)

Dalam model gerak parabola sederhana, gravitasi dianggap **konstan**:

```math
g\approx9.81\text{ m/s}^2
```

Artinya selama perhitungan:

```math
g=9.81
```

dianggap tetap.

Jika kondisi fisik berubah secara signifikan sehingga gravitasi tidak dapat dianggap konstan, maka model sederhana ini tidak lagi cukup dan persamaan geraknya perlu disesuaikan.

Untuk soal gerak parabola dasar di dekat permukaan Bumi, asumsi:

```math
g=\text{konstan}
```

biasanya digunakan.

---

# 🔑 Kesimpulan Utama

> **Gerak parabola = gerakan X + gerakan Y yang berlangsung pada waktu yang sama.**

```math
\boxed{x=(v_0\cos\alpha)t}
```

```math
\boxed{y=(v_0\sin\alpha)t-\frac12gt^2}
```

Sedangkan:

```math
\boxed{v_y=v_0\sin\alpha-gt}
```

digunakan ketika ingin mengetahui **kecepatan vertikal**.

Dan:

```math
\boxed{v_y^2=(v_0\sin\alpha)^2-2gy}
```

adalah alternatif ketika ingin mencari **kecepatan vertikal berdasarkan ketinggian tanpa harus mengetahui waktu**.

### 🧠 Prinsip yang perlu diingat

**Jangan mulai dari rumus. Mulai dari pertanyaan:**

> **"Apa yang sedang saya cari?"**

Dari sana baru pilih rumus yang menghubungkan **besaran yang diketahui** dengan **besaran yang ingin dicari**.
