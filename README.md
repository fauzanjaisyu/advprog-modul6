# **Modul 6**

## **Commit 1 Reflection notes**
Method `handle_connection` adalah bagian dari program yang bertugas untuk membaca dan memproses pesan yang diterima dari pengguna melalui saluran TCP. Pertama, saluran dibaca satu baris pesan per baris pesan. Kemudian, baris-baris tersebut diambil dan disusun sedemikian rupa hingga membentuk satu pesan lengkap. Setelah itu, pesan tersebut dapat diproses lebih lanjut atau ditampilkan di layar komputer.

Dengan cara ini, TcpListener dan TcpStream memungkinkan server untuk berkomunikasi dengan pengguna melalui protokol TCP

## **Commit 2 Reflection notes**
Pada commit ke-2 ini method `handle_connection` dilakukan beberapa perubahan di dalamnya, perubahan ini dilakukan agar method ini tidak hanya menerima HTTP saja, melainkan juga mengembalikan konten HTML yang diambil dari file `hello.html`

Berikut saya sertakan hasilnya:
![Commit 2 screen capture](/images/commit2.png)

## **Commit 3 Reflection notes**
Pada commit ke-3 ini saya merubah lagi method `handle_connection` untuk menyeleksi permintaan dan mengembalikan respons yang sesuai, apabila request yang diajukan itu valid alias halaman untuk request tadi tersedia maka halaman tersebut dapat ditampilkan, namun apabila tidak maka saya akan mengarahkannya dalam bentuk konten HTML `404.html`

Berikut saya sertakan hasilnya:
![Commit 2 screen capture](/images/commit3.png)
