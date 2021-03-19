# UTS-Rekayasa-Aplikasi-Terdistribusi

Nama: Setiawan Junior
NIM: 03082180037
Kelas: 18TI3

Chatroom Application

Didalam folder terdapat dua buah file python. File pertama merupakan file "server" dan file kedua merupakan file "client".
Chatroom application ini akan mencatat setiap percakapan yang terjadi didalam chatroom. aplikasi ini bisa dijalankan dari laptop/komputer
manapun, asalkan memiliki file "client". Sama seperti chat application lainnya, setiap orang dapat bergabung didalam chatroom dan bisa 
mengirim pesan kesesama pengguna chatroom. 

Cara penggunaan chatroom untuk berbagai devices/komputer yang berbeda
1. Sangat diperlukan untuk mengetahui IP Address dan Port dari WIFI atau Network yang bisa diakses oleh perangkat/device lainnya.
2. Dengan menggunakan kode netstat -a, untuk mendapatkan IP Address dan Port
3. Mengganti nilai IP dan nilai PORT dalam file "server.py" dan "client.py" sesuai dengan IP Address dan Port yang didapatkan 
   dalam langkah kedua. 
4. Perangkat lainnya hanya perlu memiliki file "client.py" dan nilai IP dan PORT yang telah sesuai dengan nilai di file "server.py"

Cara penggunaan user(mengirim pesan):
1. Menjalankan server, bisa dengan menjalankan program dengan IDLE Python atau menggunakan cmd. 
2. Menjalankan client, jalankan client dengan IDLE Python atau menggunakan cmd. 
3. Setelah menjalankan file client akan diminta untuk menulis username yang akan digunakan di chatroom.
4. Setelah nama terdaftar, maka bisa langsung mengirimkan pesan.
5. Sama juga untuk pengguna kedua/ketiga, jalankan seperti biasa.
6. Untuk mengetahui pesan yang datang/diterima, harus menekan enter untuk menampilkan pesan yang datang (hampir sama dengan fungsi tombol refresh).

Cara penggunaan sejarah percakapan:
- Ketika server sudah dijalankan. Setiap pesan yang dikirim oleh client lainnya akan langsung tercatat di bagian server. Server akan
  secara real-time menampilkan setiap percakapan/pesan yang dikirim oleh para client. Refresh tidak diperlukan untuk menampilkan pesan 
  yang dikirim oleh para client. 
