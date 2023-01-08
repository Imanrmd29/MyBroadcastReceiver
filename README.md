# Aplikasi Broadcast
Aplikasi yang menggunakan komponen broadcast receiver. Dimana broadcast receiver untuk menerima event yang di-broadcast oleh sistem Android. Dan menerima broadcast ketika ada SMS yang masuk.
Implementasi broadcast receiver untuk komunikasi antar aplikasi. Aplikasi melakukan pengunduhan berkas menggunakan background service dan asynchronous.
Ketika proses mengunduh selesai, service akan melakukan broadcast sebuah event dan akan ada Activity yang merespon.

- FileModel untuk menampung sementara data pengguna.
- Kelas SmsReceiver untuk mengatur konfigurasi broadcast receiver.
- Mengimplementasikan SmsReceiver ke dalam Activity.
- Menambahkan permission untuk mengakses SMS.
- Menjalankan aplikasi dan memicu munculnya SMS.
