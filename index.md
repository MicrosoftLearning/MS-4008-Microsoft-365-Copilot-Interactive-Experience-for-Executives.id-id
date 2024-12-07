---
title: Instruksi yang Tersedia Online
permalink: index.html
layout: home
---

# MS-4008: Pengalaman Interaktif Microsoft 365 Copilot untuk Eksekutif 

## Daftar Isi Direktori

Demo untuk kursus ini didasarkan pada demo dari kit akselerator [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Penting bagi Anda untuk membiasakan diri dengan demo sebelum memberikan pelatihan ini. Untuk beberapa lab, Anda akan menggunakan contoh dokumen dan rapat dan email Teams yang telah dibuat sebelumnya.

- Unduh semua contoh dokumen [di sini](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- Siapkan rapat Teams dan utas email dengan mengikuti instruksi [di sini](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Biasakan diri Anda dengan pengalaman Interaktif:
    - Opsi 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Opsi 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **CATATAN:** Jika peserta tidak memiliki lisensi Microsoft 365 Copilot, mereka dapat menggunakan versi komersial gratis dari pengalaman ini yang dapat ditemukan di [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## Deskripsi Kursus

Temukan bagaimana Microsoft 365 Copilot meningkatkan produktivitas dan inovasi tempat kerja. Pengalaman ini, disesuaikan untuk pemimpin bisnis modern, memberikan wawasan tentang membuat perintah kontekstual untuk Copilot dan mencakup latihan kasus penggunaan yang menarik yang menampilkan integrasi yang mulus ke dalam alur kerja harian.

Tujuan utama untuk pengiriman ini adalah untuk:

- Memperkenalkan peserta ke Microsoft 365 Copilot dan mengajarkan mereka cara membuat perintah yang efektif
- Mendemonstrasikan Microsoft 365 Copilot di aplikasi office (hingga 3 demo)
- Memandu peserta melalui pengalaman interaktif
- Mengundang peserta untuk mengunduh dan mencoba Microsoft Copilot untuk Seluler

## Waktu Kursus (Perkiraan) 

| # | Topik                                 | Total Waktu      |
|---|---------------------------------------|-----------------|
| 1 | Pengantar Microsoft 365 Copilot | 10 menit    |
| 2 | Panduan eksekutif untuk membuat perintah yang efektif | 30 menit
                |
| 3
           | Pengalaman interaktif Microsoft 365 Copilot  | 20 menit      |
|   |                                       | **Total waktu 60 menit** |


Hyperlink ke masing-masing demo tercantum di bawah ini.

## Demo

{% assign demos = site.pages | where_exp:"page", "page.url berisi '/Instructions/Demos'" %}
| Demo |
| --- |
{% untuk aktivitas di Demo %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
