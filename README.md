# CARA PENGGUNAAN GIT
## Intalasi GIT 
#### - Donload GIT, buka wesite resminya Git ( git-scm-com).
#### - Kemudian untuk git seusai dengan arsitektur komputer kita.kalau menggunakan 32bit.
#### - selamat,Git sudah terinstal di windows, untuk mencobanya, silahkan buka CDM atau power powerShell kemudian ketik perintah

## git --Version

#### - pada saaat pertama kali menggunakan Git,per;perlu menggunakan konfigurasi user.email
#### - konfigurasi ini bisa dilakukan untuk global repository atau induvidual revository
#### - apabila belum di lakukan konfigurasi,akan mengakibatkan terjadi kegagalan saat menjalankan perintah global GIT commit 
#### - config global Repository 
$ git config -- global user.name"nama _user"
$ git config -- global user.email "nama _user"

## perintah dasar 
#### - git init, perintah untuk membuat repository lokal.
#### - git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
#### - git commit, perintah untuk meyimpan perubahan kedalam database git.
#### - git push -u origin master, perintah untuk mengirim perubahan pada repository lokal menuju server repository.
#### - git clone [url], perintah untuk membuat working directory yang diambil dari repository server.
#### - git remote add origin[url], perintah untuk menambahkan remote server/repository server pada lokal repository (working directory)
#### - git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke lokal repository.

## Membuat Repository Lokal

#### - Buka directory aktif misal : C:\Users\User\Desktop\dlabs_pemograman1 (buka menggunakan Windows Explorer)
