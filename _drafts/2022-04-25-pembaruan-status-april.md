---
title : Pembaruan Status April 2022
layout : post
tag : pembaruan
---

## S2LC
Okey, bulan ini saya ikut program kerja S2LC sebagai IT-nya. Terkadang saya benci dengan istilah IT.

Anda bisa membaca lebih lanjut tentangnya di catatan "[S2LC Smala 2022](/s2lc-smala)".

## Ubah Tampilan
Demi mencari tampilan blog yang enak, saya banyak menggonta ganti susunan akhir - akhir ini. Pada halaman pertama saya beri avatar untuk lebih mudah dikenali. Bagian buruknya, saya menghapus daftar kontak untuk menghubungi saya.

## Ganti Domain
Tak terasa domain ini sudah mau 1 tahun. Ada keinginan hendak mengganti ke **my.id** saja. 

Karena lebih murah dan bersifat personal daripada domain **.com** ini. Ada beberapa nama yang sudah saya siapkan, yaitu :
- radhitya
- alrad
- alirad
- alifradhitya

Jujur saja, lebih asik yang pertama.

## Dynamic Window Manager
Saya kembali ke DWM setelah migrasi sementara ke KDE. Karena DWM lama saya sangat ancur - ancuran, saya memulai dari awal dengan versi terbaru, versi 6.3.

Karena pecinta minimalis, saya berusaha menggunakan sedikit patch, yaitu :
- [Always Center](https://dwm.suckless.org/patches/alwayscenter/)
- [Winicon](https://dwm.suckless.org/patches/winicon/)
- [Tab](https://dwm.suckless.org/patches/tab/)
- [Tag Previews](https://dwm.suckless.org/patches/tag-previews/)
- [Useless Gap](https://dwm.suckless.org/patches/uselessgap/)

Saya juga mengganti kode `dwm.c` untuk menjadikan `incnmaster` seperti i3wm.
```c
void
incnmaster(const Arg *arg)
{
	selmon->nmaster = !selmon->nmaster;
	arrange(selmon);
}
```
