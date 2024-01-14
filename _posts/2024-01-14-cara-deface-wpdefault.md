---
title: Cara Deface POC Register Member
author: Admin
date: 12-01-2024
categories: [Deface]
tags: [Deface]
pin: true
math: true
mermaid: true
image:
  path: /assets/img/thumbs.jpg
---

Hallo,

Oke pada artikel kali ini saya ingin memberikan Tutorial Deface Poc Wp Default u/p Gimana caranya? Silahkan simak tutorial nya dibawah ini.

Seperti biasa, tahap pertama yang harus dilakukan adalah mencari target.

Tapi kamu bisa mencarinya menggunakan dork yang biasanya saya pakai, tentunya perlu dikembangkan lagi ya.

> 
1. intitle:"Hello World " intext:2021
2. inurl:/wp/
3. intitle:"Wordpress" site:.br
4. intitle:"my blog my wordpress blog" site:.
5. intitle:"my blog my wordpress blog" march 2021
6. intitle:"my blog my wordpress blog" net march 2021

Exploit : 
- websitetarget.com/wp-login.php

Username & Password :
- admin : pass
- admin : admin

Pertama kalian dork buat nyari target nya

![Desktop View](/assets/img/post/wpdefault1.jpg){: width="200" height="400" }

Lalu kalian pilih salah satu website.

![Desktop View](/assets/img/post/wpdefault2.jpg){: width="200" height="400" }

Kalo sudah mendapatkan website kalian masukann exploitnya :
- websitetarget.com.com`/wp-login.php`

Kalian langsung masukan `Username dan Password`

![Desktop View](/assets/img/post/wpdefault3.jpg){: width="200" height="400" }

Jika vuln otomatis bakal masuk ke `Dashboard`, Lalu klik aja garis tiga di pojok kiri atas.

![Desktop View](/assets/img/post/wpdefault4.jpg){: width="200" height="400" }

Nah kalian ke bagian `WP File Manager` kalo ga ada instal dulu di `Plugins`

![Desktop View](/assets/img/post/wpdefault5.jpg){: width="200" height="400" }

Nah kalian langsung aja upload shell kalian di tempat yang dikasih tanda seperti gambar dibawah ini.
Disini saya mengupload shell backdoor.

![Desktop View](/assets/img/post/wpdefault6.jpg){: width="200" height="400" }

Pastikan nama shell kalian ada di tempat yang dilingkarin seperti gambar dibawah ini.

![Desktop View](/assets/img/post/wpdefault7.jpg){: width="200" height="400" }

Kalo udah tinggal panggil shell nya, cara panggilnya :
- www.websitetarget.com`/shell.php`
- www.websitetarget.com`/wp-admin/shell.php`

Akhir Kata

Mungkin cukup sampai disini aja artikel tentang "Deface Poc Wp Default u/p". Mohon maaf bila ada kesalahan kata dan sebagainya, Mohon dimaklumi.

Sampai jumpa di artikel selanjutnya, Semoga bermanfaat!








