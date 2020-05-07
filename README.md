# FP_SISOP20_C11

Marsha Nabilah Wibowo - 05111840000027 || Muhammmad Daffa' Aflah Syarif - 05111840000030

# 1. pwd
Source Code : []()

Perintah pwd atau (print working direktori) ini digunakan untuk menampilkan direktori anda sekarang.
Contoh:
```
suhu@suhu-pc:~$ pwd
/home/suhu
```

# 2. find
Source Code : []()

Perintah ini digunakan untuk mencari file di directory. Perintah ini bersifat rekursif.
Contoh :
- list file
- Kosong/dir1/dir2/dir3/ini_teks.txt
- Kosong/dir1/dir2/ini_gambar.jpg
- Kosong/dir1/ini_gambar.jpg
- Kosong/ini_teks.txt
```
$ find -n ini_teks.txt -n ini_gambar.jpg
Kosong/dir1/dir2/dir3/ini_teks.txt
Kosong/dir1/dir2/ini_gambar.jpg
Kosong/dir1/ini_gambar.jpg
Kosong/ini_teks.txt
$ find -n ini_teks.txt -n ini_gambar.jpg -d Kosong/dir1
Kosong/dir1/dir2/dir3/ini_teks.txt
Kosong/dir1/dir2/ini_gambar.jpg
Kosong/dir1/ini_gambar.jpg
```

# 3. stat
Source Code : []()

Menampilkan informasi secara detail tentang file
Contoh:
```
stat file.txt -> menampilkan informasi file, size, blocks, IO Blocks, File type, Device, Inode, Links, Access, Uid, Gid, Context, Access, Modify, Change, Birth
```

# 4. split
Source Code : []()

Membagi file menjadi beberapa file dimana secara default beberapa file tersebut tidak melebihi 1000 line
Contoh:
```
split file1.c -> membagi file1.c menjadi file xaa dan xab dimana file xaa dan xab tidak melebihi 1000 line
```

# 5. sort
Source Code : []()

Mengurutkan file()
Contoh : output akan diprint di terminal kecuali -o
```
sort input.txt (mengurutkan file secara asc)
sort -o output.txt input.txt (Memasukkan hasil output kedalam file output.txt)  
sort -r input.txt (mengurutkan file secara desc)
sort -n input.txt (Mengurutkan file numerik)
sort -k2 input.txt (mengurutkan berdasarkan kolom 2)
sort -c (Mengecek apakah file sudah terurut, jika sudah tidak mengeluarkan output)
sort -u (mengurutkan dan menghapus jika ada duplikasi)
sort -M input.txt (mengurutkan berdasarkan bulan)
```
