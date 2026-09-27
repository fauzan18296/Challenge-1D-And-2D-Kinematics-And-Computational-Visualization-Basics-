# 📝 RANGKUMAN GERAK PARABOLA

Gerak parabola adalah perpaduan dua jenis gerak, yaitu **GLB pada sumbu X** (horizontal) dan **GLBB pada sumbu Y** (vertikal).

---

## 📌 1. Komponen Dasar & Kecepatan Awal
Sebelum masuk ke rumus posisi atau waktu, kecepatan awal ($v_0$) harus dipecah terlebih dahulu ke masing-masing sumbu menggunakan sudut elevasi ($\alpha$):

```math
\(v_{0x} = v_0 \cos \alpha \%\%\)MAGIT_PARSER_PROTECT%%```
```math
\(v_{0y} = v_0 \sin \alpha \%\%\)MAGIT_PARSER_PROTECT%%```

---

## 🧭 2. Rumus Posisi Sumbu X dan Sumbu Y

### ➡️ Sumbu X (Horizontal - GLB)
Kecepatannya selalu tetap karena tidak dipengaruhi oleh gaya gravitasi.
```math
x \(= (v_0 \cos \alpha) \cdot\) t
```

### ⬆️ Sumbu Y (Vertikal - GLBB)
Posisinya selalu berubah (naik lalu turun) karena dipengaruhi oleh perlambatan gaya gravitasi.
```math
y \(= (v_0 \sin \alpha) \cdot t - \frac{1}{2}gt^2 \%\%\)MAGIT_PARSER_PROTECT%%```
```math
\(v_y^2 = (v_0 \sin \alpha)^2 - 2gy \%\%\)MAGIT_PARSER_PROTECT%%```

---

## ⏱️ 3. Fleksibilitas Mencari Waktu ($t$)
> ⚠️ **Poin Penting:** Untuk mencari waktu ($t$), **kita bisa menggunakan cara atau rumus apa pun** tergantung data yang disediakan oleh soal. Anda tidak terkunci pada satu rumus saja!

| Kondisi yang Diketahui di Soal | Rumus yang Digunakan |
| :--- | :--- |
| **Diketahui Jarak Horizontal ($x$)** | ```math t \(= \frac{x}{v_0 \cos \alpha}\) ``` |
| **Saat Mencapai Titik Tertinggi / Puncak** | ```math t_{max} \(= \frac{v_0 \sin \alpha}{g}\) ``` |
| **Saat Mencapai Jangkauan Terjauh (Kembali ke Tanah)** | ```math t_{total} \(= \frac{2v_0 \sin \alpha}{g}\) ``` |
| **Diketahui Ketinggian Tertentu ($y$)** | Gunakan persamaan kuadrat: <br> ```math y \(= (v_0 \sin \alpha)t - \frac{1}{2}gt^2\) ``` <br> *(Selesaikan dengan rumus ABC)* |

---

## 🌍 4. Pengetahuan Penting: Nilai Gravitasi ($g$)

### 🟢 Kondisi Standar (Bilangan Konstan)
Pada kasus pelemparan benda di **Bumi**, gravitasi merupakan **bilangan konstan/tetap** yang tidak perlu dicari rumusnya. Anda bisa langsung memasukkan angka baku:
* **$g = 10 \text{ m/s}^2$** (Paling sering digunakan di sekolah agar hitungan mudah)
* **$g = 9,8 \text{ m/s}^2$** (Untuk tingkat akurasi yang lebih presisi)

### 🔴 Kondisi Khusus (Saat Gravitasi Berubah / Harus Dicari)
Jika benda berada di planet lain atau Anda sedang melakukan eksperimen mandiri, nilai $g$ bisa dicari asalkan **ada satu data hasil akhir lintasan**. 

Khusus untuk kasus Anda dengan **sudut elevasi $45^\circ$** ($\sin 45^\circ = \frac{1}{2}\sqrt{2}$), rumusnya menjadi sangat sederhana:

* **Jika diketahui Jarak Terjauh ($x_{max}$):**
```mathga
g \(= \frac{v_0^2}{x_{max}} \%\%\)MAGIT_PARSER_PROTECT%%```
* **Jika diketahui Ketinggian Maksimum ($y_{max}$):**
```math
g \(= \frac{v_0^2}{4 \cdot y_{max}} \%\%\)MAGIT_PARSER_PROTECT%%```
