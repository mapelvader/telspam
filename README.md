
Program yang saya buat di khususkan untuk melakukan SPAM pada penipu yang mencoba memberikan web palsu seperti pada gambar di bawah ini :

## API Telegram Penipu

Saya tahu web di atas palsu maka saya mencoba melakukan inspect element apakah ada script atau kode yang melakukan pengiriman data ke API telegram bot nya si penipu atau tidak : 

Program yang saya buat terdapat dua versi yaitu versi command line (CLI) dan web (GUI) menggunakan JavaScript. Pada CLI menggunakan Python, jadi sistem komputer Anda perlu mengunduh dan menginstall dulu bahasa pemrograman Python. Anda perlu mengunduh Library tambahan pada Python yaitu :

```
pip install requests
```
Copy dan paste pada terminal Anda. Untuk penggunaan nya seperti ini :

```
python main.py -t <token telegram si penipu> -c <chat id si penipu>
```
hasil
```
python main.py -t 6885075668:AAHo5FR5xWffNA7oXu_TS7jHnk41AsNyXcc -c 7136411148
```

Jika Anda tidak familiar dengan CLI, Anda bisa menggunakan versi GUI. Anda bisa masuk folder **web** dan klik file **index.html** nya lalu Anda bisa mencoba nya langsung. Pastikan koneksi internet menyala sebelum menggunakan program ini.

## Cara Kerja Program

Program yang saya buat akan melakukan request menggunakan method POST yang artinya ketika saya mengirimkan pesan nanti akan masuk ke telegram nya si penipu dengan status response 200 yang artinya pengiriman berhasil.  Hal ini saya sudah tahu token dan chat ID nya si penipu yang nanti akan melakukan hit API telegram bot nya. Jika status nya bukan 200 berarti ada kesalahan dan mungkin akan melemparkan 429 yang artinya terlalu menerima permintaan dari saya, sehingga bot susah menanggapi.


Jika Anda ingin mencoba nya silakan gunakan token dan chat id milik penipu pada file **penipu.txt**. 



## Penutup

Tetap jaga keamanan internet terkadang kita bisa lengah dari serangan penipuan seperti ini. Program ini mungkin akan menerima pembaruan dari saya jika saya ada waktu melakukan nya. Terima kasih.
