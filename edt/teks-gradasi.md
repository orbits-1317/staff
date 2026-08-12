# Membuat Teks Gradasi Warna Pelangi (RGB)

Date: **2026-08-12**  
Tags: **Colortag**, **Gradient**, **Rainbow**, **Stylish**, **Customization**<br />
Folder: [**Editorial**](../README.md)

Bagi para *gamer*, memiliki tampilan profil atau kolom *chat* yang unik adalah kepuasan tersendiri. Salah satu tren estetika yang paling diminati adalah teks berwarna-warni dengan efek gradasi layaknya pelangi. 

Namun, banyak pemain menghadapi kendala di mana kode warna yang mereka masukkan justru hilang atau terhapus oleh sistem keamanan gim. Artikel ini akan mengupas tuntas rumus rahasia manipulasi kurung siku (*bracket*) berlapis untuk menciptakan teks gradasi RGB yang tebal, mencolok, dan lolos dari filter sistem gim.

---

### **Fungsi Kode Format Dasaran**

Penting untuk memahami kode format dasar di awal teks:

* **`[b]` (Bold):** efek cetak **tebal** pada huruf.
* **`[i]` (Italic):** efek cetak *miring* pada huruf.
* **`[c]` (Color-tag):** Di beberapa gim, kode ini berfungsi sebagai tag penetral warna untuk mengakhiri efek kode sebelumnya agar tidak bocor ke baris teks lain. Jika kode warna yang dipilih tidak memunculkan warna maka tambahkan color-tag sebelum kode warna.

---

### **Rumus Struktur Kode Menurut Penempatan**

Sistem keamanan teks di dalam gim Sweet Dance berbeda-beda tergantung di mana teks itu dipublikasikan. Untuk mengakalinya, kita menggunakan metode *enkapsulasi* (kurung siku berlapis) sebagai berikut:

#### **1. Triple Bracket `Chat`**

Digunakan untuk jendela obrolan publik (now/general), akademi, grup dansa, trainee, dan pesan pribadi.

* **Rumus:** `[KODE[KODE[KODE]]]Teks`

* Contoh 1: **Satu Jiwa, Satu Orbits**  
```text
[b[b[b]]]Satu Jiwa, Satu Orbits
```

* Contoh 2: *Satu Jiwa, Satu Orbits*
```text
[i[i[i]]]Satu Jiwa, Satu Orbits
```

* Contoh 3: <span style="color:#4C1D95;"><strong>Satu Jiwa, Satu Orbits</strong></span>
```text
[4C1D95[4C1D95[4C1D95]]]Satu Jiwa, Satu Orbits
```

* Contoh 4: <span style="font-style:italic; color:#6D28D9;"><strong>Satu Jiwa, Satu Orbits</strong></span>
```text
[b[b[b]]][i[i[i]]][c[c[c]]][6D28D9[6D28D9[6D28D9]]]Satu Jiwa, Satu Orbits
```
```text
[b[b[b]]][i[i[i]]][6D28D9[6D28D9[6D28D9]]]Satu Jiwa, Satu Orbits
```

*terkadang color-tag [c] tidak diperlukan, hanya untuk berjaga-jaga saja, biasanya saya sengaja tidak memakai color-tag biar tidak kepanjangan.*

---

#### **2. Double Bracket `Speaker`**

Khusus penggunaan speaker saja, tidak bisa digunakan dalam kolom chat. Tidak percaya? coba saja sendiri :D

* **Rumus:** `[KODE[KODE]]Teks`

* Contoh 1: **Satu Jiwa, Satu Orbits**  
```text
[b[b]]Satu Jiwa, Satu Orbits
```

* Contoh 2: *Satu Jiwa, Satu Orbits*
```text
[i[i]]Satu Jiwa, Satu Orbits
```

* Contoh 3: <span style="color:#8B5CF6;"><strong>Satu Jiwa, Satu Orbits</strong></span>
```text
[8B5CF6[8B5CF6]]Satu Jiwa, Satu Orbits
```

* Contoh 4: <span style="font-style:italic; color:#C084FC;"><strong>Satu Jiwa, Satu Orbits</strong></span>
```text
[b[b]][i[i]][c[c]][C084FC[C084FC]]Satu Jiwa, Satu Orbits
```
```text
[b[b]][i[i]][C084FC[C084FC]]Satu Jiwa, Satu Orbits
```

---

#### **3. Single Bracket `Caption&Diary Couple`**

Digunakan pada kolom informasi Pasangan dan Diary yang keamanannya cenderung lebih longgar, sehingga tidak memerlukan manipulasi berlapis.

* **Rumus:** `[KODE]Teks`

* Contoh 1: **Satu Jiwa, Satu Orbits**  
```text
[b]Satu Jiwa, Satu Orbits
```

* Contoh 2: *Satu Jiwa, Satu Orbits*
```text
[i]Satu Jiwa, Satu Orbits
```

* Contoh 3: <span style="color:#F0ABFC;"><strong>Satu Jiwa, Satu Orbits</strong></span>
```text
[F0ABFC]Satu Jiwa, Satu Orbits
```

* Contoh 4: <span style="font-style:italic; color:#C084FC;"><strong>Satu Jiwa, Satu Orbits</strong></span>
```text
[b][i][c][C084FC]Satu Jiwa, Satu Orbits
```
```text
[b][i][C084FC]Satu Jiwa, Satu Orbits
```

---

### **Teks Gradasi Warna Pelangi (RGB)**

Rangkaian kode di atas menggunakan kombinasi warna RGB Monokromatik Violet, *Deep Purple* to *Magenta Glow*.

Jika digabung menjadi satu, maka akan menjadi: <br/>
<span style="font-style:italic;"><strong>
<span style="color: #4C1D95;">Sa</span><span style="color: #6D28D9;">tu</span> <span style="color: #8B5CF6;">Jiwa</span> <span style="color: #C084FC;">Satu</span> <span style="color: #F0ABFC;">Orb</span><span style="color: #C084FC;">its</span>
</strong></span>

```text
[b][i][c][4C1D95]Sa[6D28D9]tu[000000] [8B5CF6]Jiwa[000000] [C084FC]Satu[000000] [F0ABFC]Orb[C084FC]its
```

*Coba perhatikan, mengapa ada warna hitam `[000000]` di tengah-tengah kode?*

Sebenarnya untuk memberi spasi diperlukan 1 kode warna mati untuk mengapit spasi. Warna mati ini bebas memilih, saya menyarankan warna netral hitam `#000` dan putih `#fff` agar lebih mudah membedakan warna yang satu dengan yang lain. Apalagi jika menyusun warna *triple bracket* sudah dipastikan akan bingung sekali karna ada banyak kode warna.

Hindari memberi spasi dengan cara seperti ini:

```text
[b][i][c][4C1D95]Sa[6D28D9]tu [8B5CF6]Jiwa [C084FC]Satu [F0ABFC]Orb[C084FC]its
```
Karena nantinya kode tidak berjalan dengan sempurna akan ada kesalahan yang muncul, yaitu kode warna tidak sepenuhnya berfungsi dan akan menempel dengan teks. Lihat ini:

<span style="font-style:italic;"><strong>
<span style="color: #4C1D95;">Sa</span><span style="color: #6D28D9;">tu</span> <span style="color: #c084dc;">8B5CF6]Jiwa</span> <span style="color: #f0abfc;">C084FC]Satu</span> <span style="color: #c084fc;">F0ABF]COrb</span><span style="color: #C084FC;">its</span>
</strong></span>

*Kamu bisa mencobanya sendiri di caption informasi pasangan untuk membuktikan trial & error.*

Berikut adalah warna-warna pilihan yang dapat kamu gunakan.

#### 1. Soft Pastel (Sky to Lilac)

<span style="font-style:italic;"><strong>
<span style="color: #B8E1FF;">Sa</span><span style="color: #B8C0FF;">tu</span> <span style="color: #D6BBFF;">Ji</span><span style="color: #E8AEFF;">wa,</span> <span style="color: #FFC6FF;">Sa</span><span style="color: #E8AEFF;">tu</span> <span style="color: #D6BBFF;">Orb</span><span style="color: #B8C0FF;">it</span><span style="color: #B8E1FF;">s</span>
</strong></span>

```text
[b[b[b]]][c[c[c]]][B8E1FF[B8E1FF[B8E1FF]]]Sa[B8C0FF[B8C0FF[B8C0FF]]]tu[FFFFFF[FFFFFF[FFFFFF]]] [D6BBFF[D6BBFF[D6BBFF]]]Ji[E8AEFF[E8AEFF[E8AEFF]]]wa,[FFFFFF[FFFFFF[FFFFFF]]] [FFC6FF[FFC6FF[FFC6FF]]]Sa[E8AEFF[E8AEFF[E8AEFF]]]tu[FFFFFF[FFFFFF[FFFFFF]]] [D6BBFF[D6BBFF[D6BBFF]]]Orb[B8C0FF[B8C0FF[B8C0FF]]]it[B8E1FF[B8E1FF[B8E1FF]]]s
```

#### 2. Pastel Rainbow Classic

<span style="font-style:italic;"><strong>
<span style="color: #A8E6CF;">Sa</span><span style="color: #DCEDC8;">tu</span> <span style="color: #FFD3B6;">Ji</span><span style="color: #FFAAA5;">wa,</span> <span style="color: #FF8B94;">Sa</span><span style="color: #FFAAA5;">tu</span> <span style="color: #FFD3B6;">Orb</span><span style="color: #DCEDC8;">it</span><span style="color: #A8E6CF;">s</span>
</strong></span>

```text
[b[b[b]]][c[c[c]]][A8E6CF[A8E6CF[A8E6CF]]]Sa[DCEDC8[DCEDC8[DCEDC8]]]tu[FFFFFF[FFFFFF[FFFFFF]]] [FFD3B6[FFD3B6[FFD3B6]]]Ji[FFAAA5[FFAAA5[FFAAA5]]]wa,[FFFFFF[FFFFFF[FFFFFF]]] [FF8B94[FF8B94[FF8B94]]]Sa[FFAAA5[FFAAA5[FFAAA5]]]tu[FFFFFF[FFFFFF[FFFFFF]]] [FFD3B6[FFD3B6[FFD3B6]]]Orb[DCEDC8[DCEDC8[DCEDC8]]]it[A8E6CF[A8E6CF[A8E6CF]]]s
```

#### 3. **Neon Cyberpunk (Cyan to Pink)**

<span style="font-style:italic;"><strong>
<span style="color: #00F0FF;">Sa</span><span style="color: #FF007F;">tu</span> <span style="color: #FFE600;">Ji</span><span style="color: #00FF66;">wa,</span> <span style="color: #9D00FF;">Sa</span><span style="color: #00F0FF;">tu</span> <span style="color: #FF007F;">Orb</span><span style="color: #FFE600;">it</span><span style="color: #00FF66;">s</span>
</strong></span>

```text
[b][c][00F0FF]Sa[FF007F]tu[FFFFFF[FFFFFF[FFFFFF]]] [FFE600]Ji[00FF66]wa,[FFFFFF[FFFFFF[FFFFFF]]] [9D00FF[9D00FF[9D00FF]]]Sa[00F0FF[00F0FF[00F0FF]]]tu[FFFFFF[FFFFFF[FFFFFF]]] [FF007F[FF007F[FF007F]]]Orb[FFE600[FFE600[FFE600]]]it[00FF66[00FF66[00FF66]]]s
```

Ingin lebih banyak rekomendasi warna lain? Kunjungi halaman [**16 Gradasi Warna** (Triple Bracket)](./16-gradasi-warna.html)

---

### **Kesimpulan**

Menciptakan teks pelangi yang menyatu seperti gradasi halus menuntut ketelitian dalam memilih transisi warna Hex dan kejelian memanipulasi kode kurung siku.

Dengan menerapkan rumus *Single, Double,* hingga *Triple bracket* sesuai tempatnya, tampilan akun gim Anda akan terlihat jauh lebih menonjol dibanding pemain lain.
