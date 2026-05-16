# Panduan Penggunaan

Tags: **Markdown**, **Cheatsheet**, **Basic Syntax**, **Extended Syntaxs**<br />
Folder: [**data**](../README.md)

## Daftar Isi

- [**Pengantar**](#pengantar)
- [**Sintaks Dasar**](#sintaks-dasar)
  - [A. Heading](#a-heading)
  - [B. Bold](#b-bold)
  - [C. Italic](#c-italic)
  - [D. Blockquote](#d-blockquote)
  - [E. Ordered List](#e-ordered-list)
  - [F. Unordered List](#f-unordered-list)
  - [G. Code](#g-code)
  - [H. Horizontal Rule](#h-horizontal-rule)
  - [I. Link](#i-link)
  - [J. Image](#j-image)
- [**Sintaks Lanjutan**](#sintaks-lanjutan)
  - [K. Table](#k-table)
  - [L. Fenced Code Block](#l-fenced-code-block)
  - [M. Footnote](#m-footnote)
  - [N. Heading ID](#n-heading-id)
  - [O. Definition List](#o-definition-list)
  - [P. Strikethrough](#p-strikethrough)
  - [Q. Task List](#q-task-list)
  - [R. Emoji](#r-emoji)
  - [S. Highlight](#s-highlight)
  - [T. Subscript](#t-subscript)
  - [U. Superscript](#u-superscript)
- [**Penutup**](#penutup)

## Pengantar

Halaman Docs (**orbits-1317.github.io/docs**) menggunakan Markdown untuk menulis konten. Markdown merupakan format penulisan ringan yang menggunakan sintaks sederhana untuk memformat teks, seperti heading, daftar, tautan, dan lainnya. 

Markdown mempermudah pembuatan konten yang bersih dan terstruktur. Halaman **Docs** dirancang agar mudah diakses dan dipahami.

Artikel ini hanya menjelaskan sintaks yang lebih sering digunakan. Penjelasan lebih lengkap dapat ditemukan di Ebook [The Markdown Guide by Matt Cone](./pdf/the-markdown-guide.PDF).

## Sintaks Dasar

Sintaks dasar mencakup elemen-elemen inti yang sering digunakan untuk memformat teks di Markdown.

### A. Heading

```md
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

### B. Bold

```md
**tebal**
```

**tebal**

### C. Italic

```md
*miring*
```

*miring*

### D. Blockquote

```md
> kutipan
```

> kutipan

### E. Ordered List

```md
1. Satu
2. Dua
3. Tiga
```

1. Satu
2. Dua
3. Tiga

### F. Unordered List

```md
- Satu
- Dua
- Tiga
```

- Satu
- Dua
- Tiga

### G. Code

```md
`kode`
```

`kode`

### H. Horizontal Rule

```md
---
```

---

### I. Link

```md
[ORBITS - Your Next AU2 Mobile-ID Crew](https://orbits-1317.github.io/)
```

[ORBITS - Your Next AU2 Mobile-ID Crew](https://orbits-1317.github.io/)

### J. Image

```md
![Logo ORBITS](./img/logo-orbits.PNG)
```

![Logo ORBITS](./img/logo-orbits.PNG)

## Sintaks Lanjutan

Sintaks lanjutan menawarkan fitur tambahan untuk meningkatkan fleksibilitas penulisan.

### K. Table

```md
| Nama | Status      | Nominal |
|------|-------------|---------|
| Andi | Belum Bayar | 50,000  |
| Eko  | Sudah Bayar | 420,000 |
| Dina | Sudah Bayar | 275,000 |
```

| Nama | Status      | Nominal |
|------|-------------|---------|
| Andi | Belum Bayar | 50,000  |
| Eko  | Sudah Bayar | 420,000 |
| Dina | Sudah Bayar | 275,000 |

(contoh tabel pembayaran hutang :v)


### L. Fenced Code Block

<pre>
```
{
  "namaDepan": "Ericht",
  "namaBelakang": "Samaya",
  "Umur": 22
}
```
</pre>

```
{
  "namaDepan": "Ericht",
  "namaBelakang": "Samaya",
  "Umur": 22
}
```

### M. Footnote

Ini adalah kalimat disertai catatan kaki. [^1]

[^1]: Ini adalah catatan kaki.

### N. Heading ID

```md
#### Judul Besar {#custom-id}
```

#### Judul Besar {#custom-id}

### O. Definition List

term
: definition

### P. Strikethrough

```md
~~Bumi bentuknya datar~~
```

~~Bumi bentuknya datar~~

### Q. Task List

```md
- [x] Beli deterjen bubuk
- [x] Isi ulang galon
- [ ] Nikahi kamuu
```

- [x] Beli deterjen bubuk
- [x] Isi ulang galon
- [ ] Nikahi kamuu

### R. Emoji

```md
Tetap Semangat! :fire:
```

Tetap Semangat! 🔥

(Lihat juga [Menyalin dan Menempel Emoji](https://gist.github.com/rxaviers/7360908))

### S. Highlight

```md
Saya perlu menyoroti ==kata-kata yang sangat penting== ini.
```

Saya perlu menyoroti ==kata-kata yang sangat penting== ini.

### T. Subscript

```md
CO~2~ + H~2~O → H~2~CO~3~
```

CO₂ + H₂O → H₂CO₃

### U. Superscript

```md
E = mc^2^
```

E = mc²

## Penutup  

Dengan memahami sintaks dasar dan lanjutan yang telah dijelaskan, artikel ini diharapkan dapat menjadi referensi yang bermanfaat bagi siapa pun yang ingin menulis dan menyusun konten menggunakan Markdown.  

Semoga panduan ini membantu mempermudah proses penulisan, menjaga konsistensi format, dan mendukung kolaborasi serta distribusi informasi secara lebih efektif.
