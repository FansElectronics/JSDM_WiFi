# Panduan Singkat Flash ESP32 & ESP8266

Gunakan **Google Chrome** atau **Microsoft Edge**.

## Langkah Flashing

1. **Colokkan ESP** ke komputer menggunakan kabel USB Data.

2. Buka ESP Flasher:
   **https://app.fanselectronics.com/flasher/JSDM/**

3. **Masuk ke mode flash:**

   * **ESP32:** tekan dan tahan tombol **BOOT**.
   * **ESP8266:** tekan dan tahan tombol **FLASH**. Jika perlu, tekan **RESET/RST** sekali.

4. Klik **Connect** pada ESP Flasher.

5. Pilih **Serial Port** ESP yang terhubung, lalu klik **Connect**.

6. Setelah ESP berhasil terdeteksi, **lepaskan tombol BOOT/FLASH**.

7. Pilih firmware yang sesuai dengan board:

   * ESP32 → firmware ESP32
   * ESP8266 → firmware ESP8266

8. Jika diperlukan, klik **Erase Flash** dan tunggu sampai selesai.

9. Klik **Flash** untuk memulai proses flashing.

10. **Jangan mencabut USB atau menekan tombol RESET selama proses flashing.** Tunggu sampai proses selesai.

11. Setelah selesai, ESP akan restart dan menjalankan firmware yang baru.

### Jika Gagal Terhubung

Coba ulangi proses dari awal:

**Cabut USB → colok kembali → tahan BOOT/FLASH → Connect → pilih Serial Port → tunggu terdeteksi → lepaskan BOOT/FLASH → Flash.**

Pastikan menggunakan kabel USB **Data** dan browser **Chrome/Edge**.
