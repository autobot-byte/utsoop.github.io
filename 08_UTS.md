#### 1. Variabel di Python

Menciptakan program membutuhkan kemampuan untuk menyimpan data. Untuk melakukannya kita menggunakan **variabel**. Contohnya:

```python
desktop = 5
```
Dengan baris code di atas, sekarang kita punya sebuah variabel yang bernama desktop dan memiliki nilai `5`


➡ **Intruksi:**

- Ciptakan varibel yang bernama `laptop` dan beri nilai `2`
- `Simpan dan periksa` untuk menjalankan code anda.

#### 2. Mengubah Nilai Variabel

Sekarang anda tahu bagaimana caranya untuk menyimpan nilai di variabel.

Misalnya kita sudah punya `angka_saya = 1945`. Kita bisa merubah nilainya seperti ini:

`angka_saya = 1`


➡ **Intruksi:**

Ubah nilai dari angka_saya dari `1945` menjadi `1` pada *script.py* berikut:

```python
# angka_saya telah kita beri nilai 1945

angka_saya = 1945

# setelah didefinisikan dan diberi nilai
# kita bisa mengubah nilainya

angka_saya = 

# Untuk melihat kalau kita telah mengubahnya,
# kita akan mencetaknya dengan print

print angka_saya
```

- `Simpan dan periksa` untuk menjalankan code anda.


#### 3. Pentingnya Spasi di Python

Di Python, spasi sangatlah penting karena itu anda harus berhati-hati dalam menggunakannya. Karena spasi digunakan untuk menstruktur code . .

➡ **Intruksi:**

- Coba jalankan code di bawah ini.

```python
Komputer = 1
    laptop = 2
```
- Anda akan menemukan error: 

```python
IndentationError: expected an
indented block 
(<string>, line 2)
```
- Error tersebut karena ada kesalahan dalam strukturnya, betulkan dengan menghapus spasi sebelum `laptop = 2`. Buat sejajar dengan baris pertama.

#### 4. Variabel yang Valid

Syarat variabel yang valid di python:

- Nama variabel panjangnya minimal 1 huruf,
- Menggunakan huruf (besar atau kecil), underscore `_`, atau angka `0` hingga `9`,
- Case sensitif, artinya variabel `SAYA` dan `saya` itu berbeda,
- Variabel tidak boleh dimulai dari angka.
- Variabel boleh dimulai dari underscore `_`,

➡ **Intruksi:**

Lihat code di dibawah! Ada banyak nama variabel yang salah bukan? Hapus nama variabel yang salah, nama variabel yang betul jangan diubah.

```python
.nama_bahasa = "python"

P3MBU4T = "Guido van Rossum" # nama variabel yang 'alay', tapi apakah valid?

T@hun_dibu@tny@ = 1991

# variabel panjang nih
contoh_perusahaan_yang_menggunakan_bahasa_python = "Youtube, Path, dan lain-lain."

$belajar_python_oop = True

3m4ng_s3ru = "Benar"
```