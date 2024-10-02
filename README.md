# Dhea-andheby-saputri_09011182328104_tugas6
<div align="center">

# SISTEM OPERASI 
# 

Disusun Oleh:

Nama    : Dhea Andheby Saputri

NIM     : 09011182328104

Kelas   : SK3B

<br>
<br>

</div>

<div align="justify">

TUGAS 6

Langkah 1: Siapkan Ubuntu

Hal pertama yang perlu Anda lakukan sebelum mulai menginstal SSH di Ubuntu adalah memperbarui semua paket apt ke versi terbaru. Untuk melakukan ini, gunakan perintah berikut:

![Screenshot 2024-09-27 091851](https://github.com/user-attachments/assets/133934b1-71b6-442b-9a06-41bd41c367f7)

Langkah 2: Instal SSH di Ubuntu

OpenSSH tidak diinstal sebelumnya pada sistem, jadi mari kita instal secara manual. Untuk melakukan ini, ketik di terminal:

![Screenshot 2024-09-27 093306](https://github.com/user-attachments/assets/873e04cf-514a-4a23-b44f-85162129f426)

Langkah 3: Mulai SSH

Sekarang Anda perlu mengaktifkan layanan yang baru saja Anda instal menggunakan perintah di bawah ini:

![Screenshot 2024-09-27 094745](https://github.com/user-attachments/assets/deae7304-bb79-4447-b2be-187b4b4cf2cb)

Saat startup berhasil, akan melihat pesan sistem berikut.

Tombol --now membantu untuk meluncurkan layanan dan secara bersamaan mengaturnya untuk dimulai saat sistem booting.

Untuk memverifikasi bahwa layanan diaktifkan dan berhasil berjalan, ketik:

![Screenshot 2024-09-27 094856](https://github.com/user-attachments/assets/37974661-cc9e-482e-9872-dbc2a49208e3)

lalu jika ingin menonaktifkan layanan,jalanakan :

![Screenshot 2024-09-27 095420](https://github.com/user-attachments/assets/a16a502f-2a5b-4395-a08e-22080203a456)

sudo systemctl nonaktifkan ssh

Langkah 4: Konfigurasikan firewall
Sebelum menyambungkan ke server melalui SSH, periksa firewall untuk memastikannya dikonfigurasi dengan benar.

Dalam kasus kami, kami telah menginstal UFW, jadi kami akan menggunakan perintah berikut:

![Screenshot 2024-10-01 143643](https://github.com/user-attachments/assets/dc9df6ad-b4b1-4af5-9d87-ac7e172c6801)

jika output menunjukkan bahwa lalu lintas SSH diizinkan, berarti konfigurasi sudah benar. Namun, jika belum, perintah berikut bisa digunakan untuk membuka akses SSH:

![Screenshot 2024-10-01 143722](https://github.com/user-attachments/assets/fbd15aaf-02fb-4766-a22c-4306d9e8756a)

Langkah 5: Koneksi ke server
Setelah semua langkah sebelumnya selesai, kini bisa mencoba masuk ke server menggunakan SSH. Diperlukan alamat IP atau nama domain server serta username yang ada di server tersebut. Gunakan perintah ini untuk menghubungkan:


![Screenshot 2024-10-01 145530](https://github.com/user-attachments/assets/0f5de1df-2821-46c2-a465-d6360c652751)















