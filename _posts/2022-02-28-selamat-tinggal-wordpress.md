---
title : Selamat Tinggal, Wordpress!
layout : post
tag : [teknologi]
mermaid: true
---
*In 2020, I'm not using Wordpress again for my website. I switched to Jekyll, a static and simple blog platform*. Jadi saya ucapkan : **Selamat tinggal, Wordpress!**

## Kenapa saya pindah dari Wordpress?
Sebagai orang yang menyukai kesederhanaan dan [minimalis](https://theminimalists.com), platform [Wordpress](https://wordpress.org) tidak masuk kategori itu. Sangatlah kompleks untuk menulis di Wordpress. Anda harus menekan tombol - tombol. Belum pula kebutuhan penyimpanan untuk database.


Karena pandemi juga, uang saya sedikit berkurang karena tidak sekolah. Agak tidak rela bayar untuk server. Toh rasanya mubzair membeli server untuk sebuah web yang nihil pengunjungnya.

## Selamat datang, Jekyll.
Perjumpaan saya dengan Jekyll berawal dari mengunjungi blog - blog Linux dan Open Source. Mereka menyematkan *created by [Jekyll](https://jekyllrb.com)*. 

Setelah saya baca - baca, Jekyll adalah platform *blog-aware* yang menggunakan [Markdown](https://www.markdownguide.org/). Bersifat sederhana karena tidak menggunakan database dan setup - setup rumit, statis yang hanya memakai Markdown, Liquid, HTML, dan CSS, dan *blog-aware* yang memiliki fitur *permalink*, *categories*, *pages*, *posts*, dan *custom layout*.

Saya mencoba memasang `Jekyll` di Gentoo GNU/Linux.
```bash
$ sudo emerge jekyll
```

Cara nulis postingan terbaru itu sederhana banget, tidak seperti Wordpress. Saya membuat diagramnya.
<div class="mermaid">
    graph LR
    A[Jalankan Jekyll] --- B[Tulis artikel terbaru di _posts]
    B --- C[Selesai];
</div>

### Jekyll di Github Pages
Tahukah kamu jika [Github](https://github.com) menawarkan hosting gratis untuk Jekyll? Jika anda berminat membuat blog, ini bisa menjadi opsi terbaik. Blog ini menggunakan Jekyll di Github Pages.

Cara kerjanya mirip seperti di atas, namun ditambah beberapa langkah. Saya telah membuat diagramnya.
<div class="mermaid">
    graph TD
    A[Jalankan Jekyll] --- B[Tulis artikel terbaru di _posts]
    B --- C[git add *file*]
    C --- D[git commit *message*]
    D --- E[git push];
    </div>

## Kesimpulan
Saya tidak lagi menggunakan Wordpress karena tidak sesederhana yang saya inginkan. Tempat tinggal terbaru adalah Jekyll yang bersifat statis.
