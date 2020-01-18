                                   Penjelasan jalannya Program 5

1.Deklarasi dictionary data
2.Input untuk pilih perintah
. Tambah[T] Ubah[U] Hapus[H] Cari[C] lihat[L] Hapus[H]

3.Jika Input [A]

. Input nama,nim,tugas,uts,uas
. Nilai akhir perpaduan nilai tugas,uts,uas
. Jika nilai nim,tugas,uts,uas, kosong/tidak di isi dengan angka maka ValueError dan meminta input ulang
. semua data akan di tambahkan menjadi value dan key menggunakan nama

4.Jika Input[U] 

. Input nama/key yg di cari
. Jika nama ada di data.keys
. Input pembaruan data
. Jika nilai nim,tugas,uts,uas, kosong/tidak di isi dengan angka maka ValueError dan meminta input ulang
. Input akan menimpa data yang lama
. Jika tidak
. Data tidak di temukan

5.Jika Input [H]

. Input nama/key yg di cari
. Jika nama ada di data.keys
. Maka datanya akan di hapus
. Jika tidak
. Data tidak di temukan

6.Jika Input [C]

. Input nama/key yg di cari
. Jika nama ada di data.keys
. Print nama,nim,uts,tugas,akhir

7.Jika Input [L]

. Print data.values / memanggil semua values

8.Jika Input Q

.Program Berhenti/berakhir