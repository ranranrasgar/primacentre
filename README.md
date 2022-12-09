# primacentre
# Update POS
TRANSAKSI PENGIRIMAN 
    > HARGA YANG DI TAMPILKAN ADALAH HARGA BELI
    > TOTAL DI FAKTUR KIRIMAN DC ADALAH TOTAL HARGA BELI
    > JUMLAH HARGA TIDAK KE SUM JIKA DI PILIH SATUAN 2,SATUAN 3 (CTN)

Perubahan Satuan di Pembelian

1.DEFAULT COMBO BOX CABANG : ALL
2. SEMUA JUMLAH YANG TAMPIL LAPORAN PENGRIMAN ADALAH SUM DARI HARGA BELI


PER BARANG PER GRUP PER CABANG  HARUSNA TOTAL BELI
1. Untuk jumlah sudah ke HARGA BELI semua
2. Untuk yang jumlahnya tidak sama, Kadang ada transaksi yang tidak sama, dikarenakan tidak ada rincian barangnya, untuk memperbaikinya silahkan gunakan modul PERIKSA TRX ERROR
	
Aplikasi cabang
- [x] 1.hanya bisa d buka 1 x dan 1 user baik d server atw client
- [x] 2.kolom w wallet belum ada d print e.o.d /closing harian
- [x] 3.stock op name > entry stock > proosed corection > list data..samakan dengan Apk Dc..ada nilai jumlah dalam harga beli. 
- [x] Aplikasi hanya bisa dijalankan 1x di satu komputer
		CreateMutex(nil, True, 'bla bla bla');
		  if GetLastError = ERROR_ALREADY_EXISTS then
		    begin
		      {Tuliskan perintah apa yg akan dilakukan jika program
		       ternyata sudah dijalankan}
		      ShowMessage('Programnya sudah dijalankan !');
		      halt;            // Menutup aplikasi
		    end;

Replikasi Database (Manual by system)
- [ ] Modul Syncron dari Lokal ke server
	- [ ] Pengiriman Barang (Status Pengiriman Baru) : Semua Cabang atau bisa Cabang Pilihan
	- [ ] Update Harga Barang Cabang (All atau Pilihan) : Barang update, Barang Baru
	- [ ] Update Customer (Baru / update)
	- [ ] Update Operator (Baru / Update)
	- [ ] Yg lainya sama dgn Otlet
- [ ] Modul Syncron dar Server ke Lokal
