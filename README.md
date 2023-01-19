# Cashier
## Latar Belakang
Membuat Sistem Cashier yang self-service agar customer yang berada di luar kota tempat supermarket tersebut juga dapat langsung memasukkan item, jumlah item, harga item yang dibeli dan fitur lainnya
## Objektif 
sistem kasir yang dibuat mengikuti alur sebagai berikut:
1. Customer membuat Id transaksi
2. Customer dapat memasukan item, jumlah item, dan harga item
3. Jika terdapat kesalahan dalam memasukkan item, customer bisa melakukan update item
4. jika dalam hal ini customer ingin membatalkan pembelian suatu item, customer bisa menghapus item
5. customer yang masih memiliki keraguan pada saat selesai belanja, dapat melakukan pengecekan kembali dimana jika tidak ada kesalahan input akan ada kata "Pemesanan Sudah Tepat", jika ada kesalahan input akan ada ada kata "terdapat kesalahan pemesanan serta akan ada tabel seluruh pesananan customer yang ditampilkan
6. Selanjutnya, customer dapat melihat total belanja yang harus dibayar dan jika terdapat diskon
## Flow Chart
![Doc1 (1)](https://user-images.githubusercontent.com/100061645/213378375-b064e0d1-61d1-4c29-8ff0-56ad6ffdea53.png)
## Function
1. init()
untuk class Transaction
dict_trans (dict) = untuk menyimpan data transaksi (dict)
trans_valid (boolean) = untuk memeriksa apakah data yang dimasukkan dalam dict_trans sudah benar. Nilai awal berupa True namun dapat berubah menjadi False setelah validitasnya diperiksa oleh suatu fungsi.

2. add_item(nama, jumlah, harga)
untuk menambahkan item ke dalam dictionary transaksi.

3. update_item_name(nama, nama_baru)
untuk mengubah nama item dalam dictionary yang sudah dimasukkan.

4. update_item_qty(nama, jumlah_baru)
untuk mengubah jumlah item dalam dictionary yang sudah dimasukkan.

5. update_item_price(nama, harga_baru)
untuk mengubah harga item dalam dictionary yang sudah dimasukkan.

6. delete_item(nama)
untuk menghapus data nama item beserta jumlah dan harganya dari dictionary.

7. reset_transaction()
untuk menghapus semua data pesanan dalam dictionary.

8. print_order()
untuk menampilkan semua pesanan dalam dictionary.

9. check_order()
untuk mengecek validitas dan menampilkan semua pesanan dalam dictionary.

10. total_price()
untuk menampilkan semua pesanan dan total belanja
