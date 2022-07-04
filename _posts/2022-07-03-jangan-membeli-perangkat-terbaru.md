---
title: Jangan Membeli Perangkat Terbaru
layout: post-catatan
tags: [catatan, tekno]
mermaid: true
---
Perangkat sekarang mulai canggih dengan fitur - fiturnya. Sebagian orang tergiur, sehingga membelinya. Bagian buruknya, orang menjadi boros, sehingga menumpuk banyak perangkat.

Sebagai orang yang suka dengan teknologi, saya pernah merasakan. Itu sangat tidak efisien dan membuang banyak uang. Padahal ada yang bisa dibeli, selama perangkat sebelumnya tidak masalah.

Hari ini saya berpesan untuk **jangan membeli perangkat terbaru selagi yang lama masih normal**.

## Laptopku bernama Thinkpad
Sudah 4 tahun saya menggunakan [Thinkpad T440P](https://support.lenovo.com/my/id/solutions/pd100280). Laptop yang diluncurkan pada November 2013, berarti sekarang berumur 9 tahun ini masih saya andalkan untuk menyelesaikan tugas - tugas.

Meskipun berumur 9 tahun, performanya tetap keadaan prima dan mampu bersaing dengan laptop modern. Saya sudah *oprek* laptop ini agar meningkatkan performanya.

| Bagian         | Nilai                                                                          |
|----------------|--------------------------------------------------------------------------------|
| Model          | 20AWS3DD0M ThinkPad T440p                                                      |
| Operasi Sistem | Devuan GNU/Linux                                                               |
| Kernel         | Linux dengan beberapa patch tambahan                                           |
| CPU            | Intel i5-4300M (4) @ 3.300GHz                                                  |
| GPU            | Intel HD 4600                                                                  |
| Memori         | 12 GB                                                                          |
| Diska          | 120 GB Midasforce M2 SSD 500 GB Western Digital Hardisk 500 GB Seagate Hardisk |

Kedepan saya ingin memaksimalkan oprek untuk laptop ini. Saya ada rencana untuk memasang [Coreboot](https://coreboot.org) dan mengganti Intel Wifi Card menjadi Atheros yang *free software*.

## Komputer modern semakin sampah.
Saya benci komputer modern. Kenapa?

### Perangkat susah dimodifikasi dan mudah rusak.

Laptop modern telah dibatasi untuk dimodifikasi. Kebanyakan hanya bisa ditingkatkan RAM dan SSD saja. Lenovo Thinkpad pun berevolusi seperti ini. Padahal sebelum 2014, laptop Thinkpad dapat diupgrade CPU, RAM, SSD, LCD, dan keyboard.

Saya membenci produk Apple karena sejauh ini merupakan perusahaan komputasi paling menyebalkan karena hal ini. Setiap produk Apple dirancang dengan brilian untuk membuatnya sulit untuk memperbaiki masalah dan dapat diperbaiki. Apple bahkan menggunakan [sekrup pentalobe agar orang normal tidak dapat membuka komputer mereka dengan obeng biasa](https://arstechnica.com/gadgets/2011/01/apple-screwing-new-iphones-out-of-simple-diy-repair/).

![](/media/lama/hak.jpg)
Keadaan ini adalah buruk. Pengguna harus punya hak untuk memperbaiki. Semakin modern laptop, semakin dibatasi kustomisasi. Para perusahaan ingin mengambil untung sebanyak - banyaknya.
### Intel Management Engine (Intel ME)
Anda mungkin pernah mendengar bahwa semua prosesor Intel i3/i5/i7 (setelah Intel Core 2 Duo) memiliki program berfungsi sebagai [spyware](https://www.fsf.org/blogs/sysadmin/the-management-engine-an-attack-on-computer-users-freedom). Namanya [Intel Management Engine](https://www.intel.com/content/www/us/en/support/articles/000008927/software/chipset-software.html). Intel ME dapat melihat memori Anda dan terhubung ke internet: pada dasarnya semua komputer modern memiliki *backdoor* permanen ini. 

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/ThinkPad_X60_Series_with_Libreboot.jpg/1920px-ThinkPad_X60_Series_with_Libreboot.jpg)

Di komputer lama, misalnya ThinkPad X200, Anda dapat, dengan sedikit oprek dan mengganti BIOS proprietary dengan [Libreboot](https://libreboot.org) atau Coreboot, tetapi itu tidak mungkin dilakukan pada komputer yang lebih modern (Anda dapat menginstal Coreboot pada komputer yang lebih modern, tetapi tidak semua komponen Intel Management Engine dilepas).

Komputer modern adalah spyware yang tidak dapat dilepas karena sudah didesain dan [NSA](https://www.liputan6.com/tekno/read/2185425/10-dosa-besar-nsa-yang-dibocorkan-edward-snowden) dapat memantau mesin apa pun dengan Mesin Manajemen. Bahkan ada desas-desus bahwa salah satu penyadapan yang dilakukan FBI di bawah pemerintahan Obama terhadap Trump selama kampanyenya adalah bug Management Engine.

## Windows adalah penyakit
Berapa kali Anda mendengar seseorang menjelaskan kepada Anda bahwa komputer mereka lambat karena 'sangat tua', padahal mereka membelinya pada tahun di atas 2015? Pernyataan yang tidak masuk akal tentunya. Komputer tidak hanya menjadi lambat secara ajaib, kecuali jika mereka menjalankan Windows.

Pihak Microsoft memasang banyak *bloatware* dan [*spyware/malware*](https://www.gnu.org/proprietary/malware-microsoft.en.html). Tidak sedikit orang yang kesal dengan auto update yang tidak menghasilkan apa - apa, bahkan berujung dalam masalah yang membawa Blue Screen of The Death. Saya sendiri sudah merasakan itu, terlebih ketika menggunakan Windows 10.

![](/media/lama/win.png)
### Mulailah Memasang GNU/Linux!
Pengalaman buruk di atas tidak akan terjadi ketika anda memulai memasang GNU/Linux pada perangkat anda. GNU/Linux cenderung ringan dan cepat, jika dibandingkan oleh Microsoft Windows dan Apple MacOS. Jarang ada bloatware di distribusi Linux. Kalaupun ada, anda bisa menghapus dengan mudah.

Laptop saya sangat cepat dengan GNU/Linux jika dibandingkan laptop bisnis terbaru dengan Windows didalamnya. Saya sudah membuktikan sendiri, anda kapani
## Pola Pikir
<div class="mermaid">
graph TD
    A[Apakah perangkat normal?] -->|Tidak| B(Beli perangkat terbaru)
    A -->|Ya| C(Apakah perangkat lemot?)
    C -->|Tidak| D(Simpan perangkat anda)
    C -->|Ya| E(Apakah Windows berjalan disitu?)
    E -->|Tidak| F(Pasang GNU/Linux)
    E -->|Ya| G(Beli perangkat terbaru)
</div>
Peta pikiran di atas adalah pola pikir yang saya gunakan. Selagi perangkat saya masih normal, saya tidak membeli barang yang baru.  
