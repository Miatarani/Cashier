# Cashier Project
## Latar Belakang
Membuat Sistem Cashier yang self-service agar customer yang berada di luar kota tempat supermarket tersebut juga dapat membeli dengan cara memasukkan item, jumlah item, serta dapat mengetahui harga dari item yang ingin dibeli
## Objektif 
1. Customer membuat Id transaksi
2. Customer dapat memasukan item, jumlah item, dan harga item
3. Jika terdapat kesalahan dalam memasukkan item, customer bisa melakukan update item
4. jika dalam hal ini customer ingin membatalkan pembelian suatu item, customer bisa menghapus item
5. customer yang masih memiliki keraguan pada saat selesai belanja, dapat melakukan pengecekan kembali dimana jika tidak ada kesalahan input akan ada kata "Pemesanan Sudah Tepat", jika ada kesalahan input akan ada ada kata "terdapat kesalahan pemesanan serta akan ada tabel seluruh pesananan customer yang ditampilkan
6. Selanjutnya, customer dapat melihat total belanja yang harus dibayar dan jika terdapat diskon
## FlowChart
![Doc1 (1)](https://user-images.githubusercontent.com/100061645/213378375-b064e0d1-61d1-4c29-8ff0-56ad6ffdea53.png)
## Function
1. __init__()
untuk class Transaction

- dict_transaksi (dict) = untuk menyimpan data transaksi (dict)

- trans_valid (boolean) = untuk memeriksa apakah data yang dimasukkan dalam dictonary sudah bena

2. add_item(nama, jumlah, harga)
untuk menambahkan item ke dalam dictionary transaksi

3. update_item_name(nama, nama_baru)
untuk mengubah nama item dalam dictionary yang sudah dimasukkan

4. update_item_qty(nama, jumlah_baru)
untuk mengubah jumlah item dalam dictionary yang sudah dimasukkan

5. update_item_price(nama, harga_baru)
untuk mengubah harga item dalam dictionary yang sudah dimasukkan

6. delete_item(nama)
untuk menghapus data nama item beserta jumlah dan harganya dari dictionary

7. reset_transaction()
untuk menghapus semua data pesanan dalam dictionary

8. print_order()
untuk menampilkan semua pesanan dalam dictionary

9. check_order()
untuk mengecek dan menampilkan semua pesanan dalam dictionary

10. total_price()
untuk menampilkan semua pesanan dan total spending

## Test Case
- Membuat ID dan Menambahkan Item
<img width="941" alt="2023-01-20 (2)" src="https://user-images.githubusercontent.com/100061645/213648660-307bbb24-579e-4f18-9b8e-563b0b3bcf64.png">
- Menghapus Item
<img width="954" alt="2023-01-20 (3)" src="https://user-images.githubusercontent.com/100061645/213649044-a0aa757f-5746-4f16-965a-43bdcd6d1f67.png">
- Melakukan reset transaksi
<img width="299" alt="2023-01-20 (5)" src="https://user-images.githubusercontent.com/100061645/213649497-e1986f29-c879-4769-9014-b0c2c0984b1f.png">
- Menghitung Total spending yang sudah termasuk diskon
<img width="955" alt="2023-01-20 (6)" src="https://user-images.githubusercontent.com/100061645/213649620-69ad7b03-fc37-4a25-a4d3-d31412a7b4d9.png">

## Kesimpulan
Sistem super cashier saat ini sudah dapat digunakan untuk mempermudah customer yang berada diluar kota tempat super market tersebut didirikan sehingga dalam hal ini customer dapat membeli item dengan melihat harga serta diskon yang diperoleh 

## Future Work
jika dalam hal ini terdapat waktu yang lebih serta SDM yang unggul atau lebih maka program ini dapat lebih ditingkatkan dengan menambahkan fitur item/barang yang sudah habis tidak dapat dipilih oleh customer sehingga customer dapat mengetahui informasi tersebut 
