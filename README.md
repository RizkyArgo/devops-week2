#DevOps Week 2

Dokumentasi latihan devops minggu kedua.

##Daftar Hari

Deskripsi kegiatan:

**Day 1** : buat repo khusus week 2

	inisialisasi repo(git init)

	buat branch day_1

**Day 2** : buat branch fitur-a fitur-b

	commit perubahan masing masing branch

	merge branch fitur-a fitur-b ke master

**Day 3** : fix konflik

	edit file didalam fitur-a fitur-b dengan isi yg sama(sengaja)

	merge fitur-a ke master (aman)

	merge fitur-b ke master (konflik)

	manual resolve hapus text yg ga perlu 

	push final

**Day 4** : hapus branch ga kepake lagi

	hapus branch fitur-a fitur-b di local dan di remote

	cek ulang isi master

	pastiin repoisinya cuma branch aktif

**Day 5** : gitignore

	buat file .gitignore di root repo

	tambah file/folder yang gamau di push ke repo didalam gitignore

	cek file yang di ignore tidak muncul di git status

	commit .gitignore dan push

**Day 6** :  Dokumentasi di Readme

	edit Readme

	tambah judul dan deskripsi tiap hari

## Cara Menjalankan

```bash

git clone

https://github.com/RizkyArgo/devops-week2.git

cd devops-week2
