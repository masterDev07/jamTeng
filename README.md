# JamTeng - Aplikasi Jam Suara dalam Bahasa Indonesia di Linux 🎶

## Perkenalan JamTeng
Selamat datang di JamTeng! 🌟 Aplikasi inovatif yang memungkinkan Anda untuk menyuarakan waktu dalam bahasa Indonesia di sistem operasi Linux! Dengan fitur penjadwalan yang fleksibel, Anda dapat mengatur pengingat setiap seperempat, setengah, atau satu jam. Apakah Anda ingin mendengar suara pria atau wanita? JamTeng memiliki semua yang Anda butuhkan untuk pengalaman yang menyenangkan dan informatif.

Salah satu fitur unggulan dari JamTeng adalah kemampuan untuk membisukan suara pada rentang waktu tertentu. 🕒 Dengan fitur ini, Anda tidak perlu khawatir terganggu oleh pengumuman waktu saat jam istirahat atau saat Anda sedang fokus bekerja. JamTeng memberikan Anda kontrol penuh atas kapan dan bagaimana Anda ingin mendengar pengumuman waktu, sehingga Anda dapat menikmati momen tenang tanpa gangguan.

## Fitur Utama
- **Penjadwalan Fleksibel**: Atur pengingat suara setiap 15 menit, 30 menit, atau 1 jam. ⏳
- **Koreksi Volume**: Sesuaikan volume suara sesuai keinginan Anda. 🔊
- **Pilihan Suara**: Pilih antara suara pria atau wanita untuk pengumuman waktu. 👨‍🦰👩‍🦰
- **Mode Bisukan**: Matikan suara pada rentang waktu tertentu agar tidak mengganggu. 🤫
- **Pengaturan Jeda**: Percepat jeda pengucapan suara untuk pengalaman yang lebih dinamis. ⚡
- **Integrasi Aplikasi Audio**: Pilih aplikasi pemutar audio favorit Anda untuk pengalaman yang lebih personal. 🎧

## Cara Instalasi
Untuk menginstal JamTeng, cukup jalankan perintah berikut di terminal Anda:

```bash
sudo dpkg -i jamTeng.deb
```

Setelah instalasi selesai, buat alias untuk memudahkan akses:

```bash
alias jamteng='/opt/jamTeng/jamTeng'
```

## Cara Menjalankan
Setelah alias dibuat, Anda dapat menjalankan JamTeng dengan perintah berikut:

- Untuk menyuarakan suara pria:
  ```bash
  jamteng p bp
  ```
  [File suara pria](jamTeng/opt/jamTeng/mp3/buatanSendiri/id/pria) 🎤

- Untuk menyuarakan suara wanita:
  ```bash
  jamteng p ww
  jamteng p bw
  ```

  [File suara wanita 1](jamTeng/opt/jamTeng/mp3/wide8/id/wanita) 🎶
  [File suara wanita 2](jamTeng/opt/jamTeng/mp3/buatanSendiri/id/wanita) 🎶

## Penjadwalan
Buat jadwal sesuai pilihan Anda
  ```bash
jamteng bj bp  # Jadwalkan suara pria
jamteng bj bw  # Jadwalkan suara wanita (1)
jamteng bj ww  # Jadwalkan suara wanita (2)
  ```

Hapus jadwal
  ```bash
  jamteng hj
  ```

## Konfigurasi
File untuk koreksi JamTeng [configuration_jamTeng.conf](jamTeng/opt/jamTeng/configuration_jamTeng.conf)

## Kadaluwarsa
Masa aktif JamTeng [kadaluwarsa](jamTeng/kadaluwarsa.txt) 

## Kontak
Kami sangat menghargai masukan dari Anda! 💌 Jika Anda memiliki saran, kritik, atau ingin memperpanjang masa kadaluwarsa  silakan kirim email ke [duitmoro@yahoo.com](mailto:duitmoro@yahoo.com).

---

Yakinkan Anda untuk mencoba **JamTeng** dan nikmati pengalaman baru dalam menyuarakan waktu! Terima kasih telah menggunakan aplikasi kami! 🙌✨
