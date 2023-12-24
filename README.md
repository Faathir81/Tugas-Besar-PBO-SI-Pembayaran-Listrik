# Sistem Pembayaran Listrik

Program ini merupakan implementasi sederhana dari Sistem Pembayaran Listrik berbasis Java. Program memungkinkan pengguna untuk mengelola saldo, membeli pulsa, dan membeli token listrik dengan antarmuka tekstual yang mudah digunakan.

## Fitur Utama
1. Isi Saldo: Pengguna dapat mengisi saldo akun mereka.
2. Beli Pulsa: Pembelian pulsa dengan nilai tertentu.
3. Beli Token Listrik: Pembelian token listrik sesuai harga yang ditentukan.
4. Riwayat Transaksi: Melihat riwayat pembelian pulsa dan token listrik.

## Model Class
1. **Pelanggan (Akun):**
   - Atribut: nama, saldo.
   - Metode: isiSaldo(), beliPulsa(), beliTokenListrik(), tampilkanRiwayatTransaksi().

2. **Transaksi (Interface):**
   - Metode: lakukanTransaksi(), getHarga().

3. **TokenListrik (Transaksi):**
   - Atribut: nilaiToken.
   - Metode: lakukanTransaksi(), getHarga().

4. **Pulsa (Transaksi):**
   - Atribut: nilaiPulsa.
   - Metode: lakukanTransaksi(), getHarga().

## Cara Menggunakan
1. Jalankan program dengan menjalankan file `Main.java`.
2. Ikuti instruksi pada layar untuk melakukan transaksi.

## Kontributor
- **Faathir Akbar Nugroho**
  - NPM: 4522210033
