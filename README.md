# Template LaTeX Proposal Tugas Akhir ITS

[![latest version](https://img.shields.io/github/v/release/b201lab/template-proposal-ta-its)](https://github.com/b201lab/template-proposal-ta-its/releases/)
[![commits since latest version](https://img.shields.io/github/commits-since/b201lab/template-proposal-ta-its/latest)](https://github.com/b201lab/template-proposal-ta-its/commits/master)
[![repo size](https://img.shields.io/github/repo-size/b201lab/template-proposal-ta-its)](https://github.com/b201lab/template-buku-ta-its)
[![license](https://img.shields.io/github/license/b201lab/template-proposal-ta-its)](./LICENSE)
[![build and test status](https://img.shields.io/github/workflow/status/b201lab/template-proposal-ta-its/Build%20LaTeX%20Document)](https://github.com/b201lab/template-proposal-ta-its/actions)

Repositori ini berisi template [LaTeX](https://www.latex-project.org/) dari proposal tugas akhir yang disesuaikan dengan format yang diberlakukan oleh [Institut Teknologi Sepuluh Nopember](https://www.its.ac.id/) (ITS).
Template yang ada saat ini baru mengikuti aturan yang diberlakukan oleh [Departemen Teknik Komputer](https://www.its.ac.id/komputer/) FTEIC - ITS dengan sedikit penyesuaian, sehingga, secara penuh template ini belum mewakili aturan yang berlaku secara umum di setiap departemen yang ada di ITS.

> Perlu diketahui, template ini bukanlah template resmi yang dikeluarkan oleh ITS maupun departemen-departemen yang ada di bawah naungan ITS.

## Fitur

- Format ukuran halaman, margin, dan font yang disesuaikan dengan aturan yang berlaku di ITS.
- Disertai bagian-bagian yang diperlukan seperti pengesahan, latar belakang, tinjauan pustaka, dsb.
- Pembuatan daftar pustaka secara otomatis.
- Penomoran gambar dan referensi secara otomatis.
- Penambahan gambar dengan format JPEG, PNG, maupun format lain pada dokumen.
- Pembuatan daftar, persamaan ilmiah, dan tabel pada dokumen.
- Kompilasi dokumen secara otomatis menggunakan [GitHub Actions](https://github.com/features/actions).

## Cara Menggunakan Template

Bagian utama dokumen terletak pada file [`main.tex`](./main.tex) yang digunakan untuk mengatur package LaTeX yang digunakan serta file lain yang akan diinputkan pada dokumen.
Setelah kompilasi dilakukan, hasilnya akan ada beberapa file `main` dengan format yang berbeda.
Yang terutama adalah file `main.pdf` yang merupakan hasil akhir dari proses kompilasi dokumen.

Selain file `main.tex`, ada juga beberapa bagian lain dari template ini yang bisa diubah, seperti:
- **[`konten`](./konten)**, berisi file `*.tex` dari bagian-bagian yang akan dimasukkan pada proposal tugas akhir.
- **[`pengesahan`](./pengesahan)**, berisi file `*.tex` dari bagian pengesahan untuk proposal tugas akhir.
- **[`gambar`](./gambar)**, berisi file `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada dokumen.
- **[`pustaka/pustaka.bib`](./pustaka/pustaka.bib)**, berisi daftar referensi yang akan dimasukkan pada dokumen.

> Penjelasan lebih lanjut mengenai penggunaan template ini akan dijelaskan dengan comment yang tersedia pada setiap file yang ada.

## Contoh Penggunaan Template

Berikut adalah daftar repositori lain yang menggunakan template yang berasal dari repositori ini:
- [threeal/proposal-ta-simulasi-robot](https://github.com/threeal/proposal-ta-simulasi-robot).

## Lisensi

Kode sumber yang ada pada repositori ini dilisensikan di bawah [lisensi MIT](./LICENSE).
