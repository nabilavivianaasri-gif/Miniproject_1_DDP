mini_project_1_ddp

NABILA VIVIANA ASRI |2509116098 |SITEM INFORMASI C 2025

TEMA : SISTEM PEMESANAN TIKET BUS

# FLOWCHART


<img width="370" height="1091" alt="FLOWCHART SISTEM PEMESANAN TIKET BUS" src="https://github.com/user-attachments/assets/66d36108-d1e3-4305-acfc-5ee443fc8e1f" />

# Mulai
Proses dimulai ketika pengguna membuka aplikasi atau sistem pemesanan tiket bus.

# Pilih Menu
Pengguna diberikan dua pilihan utama:

Lihat rute = menampilkan daftar rute bus yang tersedia.

Pesan tiket = langsung menuju ke proses pemesanan tiket.

# Jika Pilih "Lihat Rute"
Sistem akan menampilkan daftar rute bus yang tersedia.

Setelah melihat rute, pengguna diberikan pertanyaan: “Lanjut pesan tiket?”

Jika Ya = masuk ke menu pemesanan tiket.

Jika Tidak = proses langsung selesai.

# Jika Pilih "Pesan Tiket"
Pengguna diminta memilih tujuan perjalanan, misalnya:

- Jakarta
- Surabaya
- Bandung
- Jogja

Sistem meminta nama pengguna untuk dicatat pada tiket.

Sistem meminta jumlah tiket yang ingin dibeli.

Sistem menghitung total biaya pembelian tiket

Total Pembayaran = Harga Tiket × Jumlah Tiket

Apakah Ingin Melihat Detail Tiket?

Sistem memberikan opsi:

Ya = menampilkan detail tiket: 

- Nama pemesan

- Tujuan perjalanan

- Jumlah tiket

- Harga per tiket

- Total pembayaran

Tidak = langsung menuju tahap selesai.

Selesai



# CODINGAN


<img width="1920" height="1080" alt="CODINGAN 1 (2)" src="https://github.com/user-attachments/assets/f7559842-c121-4979-b0bc-f031806c5321" />



<img width="1920" height="1080" alt="CODINGAN 2 (2)" src="https://github.com/user-attachments/assets/563ccbad-39d2-4ca0-a523-22008be07c40" />



<img width="1920" height="1080" alt="CODINGAN 3" src="https://github.com/user-attachments/assets/ec6a1580-dec3-41a5-ac7c-ed83664468b5" />


# rute = berisi daftar kota tujuan bus

# harga_tiket = berisi harga tiket sesuai urutan kota di [list] rute

"masukkan" = input yang berarti masukkan. (user diminta untuk memilih "lihat rute" atau "pesan tiket")

# jika user memilih "lihat rute" maka akan ditampilkan list rute bus

lanjut = "input"yang berarti masukkan. user akan ditanya apakah ingin melanjutkan ke menu pesan tiket? user diminta untuk memilih ya atau tidak

jika ya = maka user akan langsung masuk ke menu pesan tiket

jika tidak = maka selesai dan otomatis keluar karna exit(yang berarti keluar )

# jika user memilih "pesan tiket" maka user akan diminta untuk memilih tujuan yang ingin di datangi :jakarta/surabaya/bandung/jogja

program akan mencocokkan input dengan rute yang ada 

program akan menanyakan nama pemesan tiket

program akan menampilkan harga tiket untuk tujuan yang anda pilih

lalu program menanyakan berapa tiket yang anda ingin beli

program menghitung harga tiket yang di pilih dikali jumlah tiket yang dibeli

lalu program akan menampilkan total tiket yang di pesan

input untuk menanyakan apakah user ingin memlihat detail tiket? ya/ tidak

jika ya maka program akan menampilkan :

- NAMA
- TUJUAN
- JUMLAH TIKET YANG USER BELI
- HARGA TIKET UNTUK TUJUAN YANG DIPILIH USER
- TOTAL PEMBAYARAN USER

jika user memilih tidak maka program akan menampilkan tulisan "transaksi selesai hati hati dijalan"

jika user tidak memilih ya atau tidak maka program akan menulis "TERIMAKASIH SELAMAT MENIKMATI PERJALANAN"
maka pemesanan tiket selesai
