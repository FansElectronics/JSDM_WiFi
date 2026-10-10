# Jadwal Sholat Dot Matrix (JSDM) P10 dengan ESP8266 & ESP32

Firmware display Jadwal Waktu Sholat dengan tampilan Panel P10 Dot Matrix Display (DMD) menggunakan mikrokontroler ESP8266 dan ESP32. Project ini dirancang untuk menjalankan sebuah sistem dan perhitungan jadwal sholat di Indonesia. Sudah didukung dengan pengaturan dengan aplikasi Android yang dapat di download di: https://play.google.com/store/apps/details?id=com.fanselectronics.jsdm&hl=id

## Spesifikasi Firmware ⚙️:
- Mendukung Mikrokontroler ESP8266 dan ESP32
- Mendukung RTC DS3231
- Mendukung Panel P10 Single Color
- Menggunakan catu daya 5V (disesuaikan panel)
- Pengaturan melalui aplikasi Android
- 1 baris Panel x Maksimal 6 kolom Panel (disesuaikan lisensi)

## Fitur yang tersedia ✅:
- Animasi Jadwal Waktu Sholat (tersida beberapa model animasi sesuai pilihan jumlah panel)
- Animasi pesan running text (custom melalui aplikasi android)
- Logo Allah & Muhammad (tersida beberapa model logo)
- Sleep Mode saat malam hari tidak terpakai
- Kalendar Masehi, Hijriah, dan Jawa (Pasaran, Wuku, dan Tahun menurut kalendar Agungan)
- Alarm / Alert waktu Adzan
- Waktu hitung mundur Qobliyah setelah Adzan dan tunggu Iqomah
- Pengaturan waktu Iqomah setiap sholat
- Sleep Mode waktu sholat
- Sleep Mode waktu khotbah Jum'at
- Upload **license.json** melalui aplikasi android
- Update firmware On the Air (OTA), update firmware lebih mudah via internet

_**Catatan:** fitur dan animasi akan selalu diupdate, anda bisa update firmware terbaru dengan mudah melalui fitur OTA di aplikasi android._

## Default SSID + Password
```
    SSID: JSDM WiFi Android
    PASS: fanselectronics
```

## Mengapa dimulai dari versi 3?

Sebelumnya project ini bersifat private saja dengan membuka firmware dan mengimplementasikan sistem lisensi, siapapun dapat membuat sendiri dan hanya tinggal membeli lisensi firmwarenya saja dengan mudah dan murah.

## Bagaimana Sistem Lisensinya?

Kami mengimplementasikan sistem lisensi terenkripsi berbasis **Identifikasi Hardware** unik. Setiap ESP8266 dan ESP32 memiliki ID Unik yang tidak dapat ditukarkan, jadi pembeli tinggal mengirimkan **Device ID** yang tersedia pada menu activation aplikasi setelah aplikasi terhubung ke perangkat dan kami akan mengirimkan file **license.json** yang dapat diupload ke perangkat melalui fitur **Activation** di aplikasi Android.

Menengapa lisensi harus berbayar? tentunya kami membutuhkan dana untuk keperluan riset dan biaya hidup, permintaan ini juga memberikan kami semangat untuk terus memelihara dan perbarui fitur-fitur pada firmware dari JSDM WiFi Android ini. Sehingga mohon pengertiannya.

**Adapun Harga Lisensi dibedakan berdasarkan jumlah panel sebagai berikut 🏷️:**
- 1 Panel : Rp. 25.000
- 2 Panel : Rp. 35.000
- 3 Panel : Rp. 45.000
- 4 Panel : Rp. 55.000
- 5 Panel : Rp. 65.000
- 6 Panel : Rp. 75.000

**Syarat dan Ketentuan Lisensi 📜:** 
- Lisensi berlaku untuk 1 chip ESP866 atau ESP32, karena mengikat berdasarkan chip.
- Lisensi berlaku untuk 1 jenis jumlah panel (setelah lisensi dikirim tidak bisa ganti ukuran)
- Apabila terjadi kerusakan chip kami bisa mengganti lisensi dengan syarat mengirim chip yang rusak kepada kami guna mengihindari penipuan chip rusak. Kami akan kirim lisensi baru dengan DEVICE ID chip yang baru. kalau tidak bisa mengirimkan chip yang rusak bisa beli lisensi baru kembali.
- Kami tidak menerima garansi lisensi apabila pembelian tidak melalui kami secara langsung (beli di pihak ke-3).

## Sistem pembayaran 💵

Kami memberikan 2 sistem pembayaran dimana sistem donasi dan pembayaran sesuai harga tertera. Anda dapat menggunakan sistem donasi apabila ingin memberikan support kepada kami melebihi harga lisensi yang ada.
- Pembelian dan Bantuan: https://wa.me/6281803750001
- Donasi: https://saweria.co/fanselectronics

## Bagaimana Upload Firmwarenya❓
Kami telah menyediakan tool untuk upload / flash chip ES8266 dan ESP32 yang memudahkan siapapun untuk membuat project ini secara mandiri. Berikut url tool JSDM WiFi Flasher:
- Flasher Tools: https://app.fanselectronics.com/flasher/JSDM/
- Tutorialnya bisa baca di [FLASHER.md](FLASHER.md)

## Skematik dan PCB 💾
Semua file Skematik dan PCB saya sediakan gratis di dalam repository ini dalam bentuk desain apliksi EAGLE PCB hingga export PDF. Sesuaikan dengan board yang anda gunakan atau anda bisa mengkustomisasi sesuai dengan keinginan anda dengan panduan pin I/O yang sudah disediakan.

![Skematik JSDM ESP8266 Wemos D1 Mini](https://github.com/FansElectronics/JSDM_WiFi/blob/main/PCB/JSDM%20Wemos%20Mini%20DS3231%20HUB12%20%26%2008%20Single/Skematik.png)
## Tutorial & Video 🎥

[![Tutorial JSDM WiFi](https://youtube.com)](https://www.youtube.com/watch?v=nER4bm2BxC0)


## Terima Kasih Kepada 🤲
- Allah Subhanahu Wa Ta'ala
- Arduino.cc
- GitHub
- Kontributor
- Semua orang yang mentraktir saya kopi
