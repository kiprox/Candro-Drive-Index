---
layout: posting
lang: "id"
title:  "Telegram Bot Mirror"
description: "Bot telegram untuk menyimpan file di google drive pribadi"
author: candro
image: assets/images/candro-bot.png
featured: true
---

Ini adalah bot Telegram yang menggunakan **[aria2](https://github.com/aria2/aria2)** untuk download file melalui BitTorrent / HTTP(s) dan mengunggahnya ke Google Drive Pribadi. 

`sangat berguna untuk download dari server yang lambat`.


Antrian Download dan paralel mirror juga didukung. Ada beberapa fitur yang dapat diterapkan untuk mencegah pembajakan pengguna.

Bot ini dibuat untuk digunakan dalam grup kecil dan tertutup. Jadi, setelah terinstal hanya berfungsi di grup yang sudah masuk daftar putih.

Mencegah pengguna bot ini untuk *mirror* konten bajakan. Pastikan hanya grup terpercaya yang masuk dalam daftar putih.

## Telegram Bot Untuk Mirroring File

> Contoh proses download di Telegram setelah Bot terinstal di server Debian

![candro-bot](https://i.imgur.com/cghrEyw.png)  


### Coba Gratis

> Saya sediakan bot dan grup chat yang sudah jadi / tinggal pakai sebelum Anda praktek untuk melalukan instalasi sendiri atau perlu bantuan team saya.
>
>> Tapi ingat, kode dari kami memang gratis...tapi tidak dengan ***waktu kami***

<p align="center">
  <a href="https://t.me/joinchat/K37gZkrY6V1NEtbNsbUFlw" target="_blank"><img src="https://i.imgur.com/5MW5sdXm.jpg" title="Candro Drive Index" alt="Mirror Google Drive Telegram Bot"/></a>
</p>  


###### Bot Command

{% highlight html %}
/mirror <url>
/mirrorTar <url>
/mirrorStatus
/cancelMirror
/cancelAll
/list <filename>
/getfolder
{% endhighlight %}


Untuk dokumentasi instalasi di server sendiri ikuti link berikut ini

[How to install telegram Bot](/tutorial/cara-instal-telegram-bot-mirror)