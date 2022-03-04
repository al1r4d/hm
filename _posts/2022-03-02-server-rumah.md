---
title : Server Rumah
layout : post
tag : [cerita,teknologi]
mermaid : true
---
Membangun server di rumah sangat mengasyikkan. Anda harus mencobanya juga.
![](/media/server-rumah/minipc.jpg)

Terlalu banyak komputer yang tidak digunakan di rumah. Setelah nonton video tentang [*homeserver*](https://www.youtube.com/watch?v=f5jNJDaztqk&t), saya menjadi tertarik.

Dengan MiniPC, saya membangun server di rumah. Masalah listrik tak menjadi masalah karena hanya memakan energi yang rendah.
## Spesifikasi Server Rumah
![](/media/server-rumah/htop-neofetch.jpg)

| Keterangan | Nilai |
| ----------- | --------- |
| **Processor** | [Intel Atom x5-Z8350 (4) @ 1.920GHz](https://ark.intel.com/content/www/id/id/ark/products/93361/intel-atom-x5z8350-processor-2m-cache-up-to-1-92-ghz.html) |
| **Memory** | 4 GB |
| **Storage** | 64 GB SD Card & 1 TB HDD Seagate |
| **OS** | Devuan GNU/Linux |
| **Kernel** | ~~Linux-libre Kernel~~ Xanmod Kernel |

MiniPC saya tidak berspesifikasi, hanya dibekali Intel Atom dan Ram 4 GB. Awalnya cuma datang dengan 64 GB SD Card saja, kemudian saya membeli diska keras eksternal karena membutuhkan banyak ruang.

Tidak lupa memasang [Devuan GNU/Linux](https://devuan.org) sebagai operasi sistem. Dengan Linux, saya bisa melakukan apa yang saya inginkan.

Tentang kernel, saya memilih [Xanmod Kernel](https://xanmod.org) yang katanya meningkatkan performa. Sebelumnya saya memakai [Linux-libre Kernel](https://www.fsfla.org/ikiwiki/selibre/linux-libre/) karena tidak menggunakan [*non-free software*](https://www.gnu.org/proprietary/proprietary.html).

## Yang saya lakukan
![](/media/server-rumah/jellyfin.jpg)
Tidak banyak yang saya lakukan. Mesin ini telah terpasang [Jellyfin](https://jellyfin.org) dan [Samba](https://samba.org).

Jellyfin adalah layanan media server yang memungkinkan anda *streaming media* dari server anda. Program ini termasuk [*free software*](https://www.gnu.org/philosophy/free-sw.id.html) dengan lisensi [GPLv2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html). Gratis dalam kebebasan menggunakan dan berbagi. Tidak ada biaya tambahan dan tersembunyi.

> Kenapa tidak dengan Plex?

[Plex](https://www.plex.tv/) memang gratis, tetapi tidak termasuk *free software*. Juga anda tidak bisa mengakses Plex tanpa internet. Bahkan saat login-pun anda harus terhubung internet. Beda dengan Jellyfin.

> Bagaimana performanya di Intel Atom ?

Untuk streaming dua perangkat dengan 1080p cukup aman. Terkadang ada lag, tetapi itu hanya sekali dan berjalan 3 detik saja.

Harap diingat bahwa Intel Atom milik saya generasi 2016.

Kedua adalah Samba. Samba adalah layanan berbagi berkas dan berbagi alat pencentak. Dapat anda bayangkan layanan ini seperti [Nextcloud](https://nextcloud.com) dan Google Drive.