# Panduan dalam Berkontribusi
Terdapat 3 cara bagi kamu jika ingin berkontribusi melalui Github :
1. Beri bintang ️️⭐️ ke repository ini.
2. Mengirim [issue](https://github.com/santrenkoding/daftar-group-programmer-developer-semarang/issues)
3. Mengirimkan Pull Request (PR) ke branch `master`. Jika kamu ingin melakukan PR pastikan perubahan yang ingin kamu push tidak dilakukan pada branch `master`. Buat `branch` dengan nama kamu sendiri. Contoh nama branch `branch-farah`.

## Panduan dalam Pull Request
Jika kamu butuh panduan dalam melakukan Pull Request, silahkan mengikuti petunjuk dari dokumentasi berikut ini :
- Fork Repository. [Baca ini](https://help.github.com/articles/fork-a-repo/)
- Pastikan fork repository telah up to date. [Baca ini](https://gist.github.com/CristinaSolana/1885435)
- Setelah selesai lakukan git push ke branch kamu. [Baca ini](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)
- Terakhir Buat Pull Request. [Baca ini](https://help.github.com/articles/creating-a-pull-request/)

##Step Git
1. git clone -> link fork bukan link git origin (git origin punya master)
2. git remote -v -> untuk mengecek repo yang kita remote
3. git remote add upstream -> supaya tidak crach dengan origin 
4. git remote -v -> 2 jenis remote yaitu origin dan upstream 
5. git checkout -b nama_branch -> supaya tidak menganggu branch utama master
6. git status -> memastikan yang kita edit berada di branch baru 
7. melakukan perubahan (edit, delete, menambakan)
8. git add . -> untuk menambahkan seluruh perubahan yang kita lakukan
9. git commit -m "pesan yang akan di push" 
10 . git push upstream nama_branch_baru -> kita upload perubahan ke branch baru
dengan tujuan agar dapat di review oleh owner supaya dapat di merge ke master.

Status hacktoberfest :
hacktoberfest.digitalocean.com/stats/farahoktarina
referensi repo dan panduan kontribusi : https://github.com/santrenkoding

bit.ly/absen-hacktoberfest
