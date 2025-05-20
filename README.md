# Honda ECU Scanner

Proyek ini memungkinkan Anda untuk membaca data langsung dari ECU sepeda motor Honda menggunakan ESP8266 dan menampilkan informasi tersebut pada LCD I2C serta aplikasi Android.

## Fitur
- Pembacaan data langsung dari ECU
- Deteksi dan tampilan kode DTC (Diagnostic Trouble Codes)
- Penghapusan kode DTC
- Antarmuka pengguna melalui LCD dan aplikasi Android

## Perangkat Keras
- ESP8266 (misalnya NodeMCU)
- LCD I2C 16x2
- 3 tombol input
- Rangkaian K-Line Transceiver

## Instalasi
1. Unggah `HondaECUScanner.ino` ke ESP8266 menggunakan Arduino IDE.
2. Unggah folder `data` menggunakan SPIFFS.
3. Instal aplikasi Android dari `HondaScanner.apk`.

## Penggunaan
1. Nyalakan perangkat ESP8266.
2. Hubungkan ke jaringan Wi-Fi yang disediakan oleh ESP8266.
3. Buka aplikasi Android dan sambungkan ke perangkat.
4. Navigasi melalui menu untuk melihat data ECU, kode DTC, dan opsi penghapusan DTC.

## Lisensi
Proyek ini dilisensikan di bawah MIT License.
