# Praktikum-BD-3
'''
1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen. 

2. Hapus satu record dat pada tabel dosen yang telah dirjuk pada tabel mahasiswa. 

3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT. 

4. Lakukan perubahan data pada tabel dosen (kd_ds). 

5. Lakukan penghapusan data pada tabel dosen, 

6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL 

7. Lakukan penghapusan data pada tabel dosen.

```

1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen. 

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/6144e4ad-30ad-4b59-b854-7fd5a581d7fd)

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/00b90531-7eb0-491f-9b59-cda93516248c)

2. Hapus satu record dat pada tabel dosen yang telah dirjuk pada tabel mahasiswa.

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/97caa92f-9f74-4828-9307-8e208c641458)

3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT.

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/ceacbc91-73bd-44e1-93dd-68361cd4c8b7)

4. Lakukan perubahan data pada tabel dosen (kd_ds). 

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/ac053337-bbf6-48a7-86d8-4a4f515c1456)

5. Lakukan penghapusan data pada tabel dosen.

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/92da43d1-e4c7-4b6c-8b16-f3a43bbc0884)

6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/fef1132e-ddd2-40d6-83d4-9c1365c84457)

7. Lakukan penghapusan data pada tabel dosen.

![image](https://github.com/DimasF3009/Basis-data-praktikum-3/assets/115356128/a19514e7-0f39-4946-a91e-dfe8b630e1b0)

Evaluasi dan pertanyaan.

1. Apa bedanya pengguna RESTRICT dan CASCADE.?

Penggunaan RESTRICT dan CASCADE adalah dua jenis aturan referential integrity (keutuhan

referensial) yang dapat diterapkan pada kunci asing (foreign key) di basis data relasional.

RESTRICT berarti bahwa ketika ada sebuah baris data di tabel induk (parent table) yang ingin dihapus 

atau diubah, maka sistem basis data akan memeriksa apakah ada baris data di tabel anak (child table) 

yang masih merujuk ke baris data tersebut. Jika ada, maka sistem basis data akan mencegah 

penghapusan atau perubahan data pada baris data di tabel induk yang berdampak pada baris data di 

tabel anak yang masih merujuk ke baris data tersebut.

Sementara itu, CASCADE adalah sebuah baris data di tabel induk dihapus atau diubah, maka sistem 

basis data akan secara otomatis menghapus atau mengubah baris data di tabel anak yang merujuk ke 

baris data yang dihapus atau diubah tersebut.

2. Berikan kesimpulan 

RESTRICT dan CASCADE adalah aturan refential intrgrity Yang dapat diterapkan pada kunci asing yang 

basis data relasional. RESTRICT mencegah penghapusan atau perubahan data pada tabel induk yang 

berdampak pada tabel anak yang masih merujuk ke data yang di hapus atau di ubah. Sementara 

CASCADE dengan secara otomatis menghapus atau mengubah data pada tabel anak yang merujuk ke 

data yang di apus atau di ubah pada tabel induk. Kedua aturan tersebut memiliki kelebihan dan 

kekurangan msing-masing dan harus dipilih secara bijak sesuai dengan kebutuhan dan konteks 

penggunaannya agar dapat memastikan keutuhan data didalam system basis data
