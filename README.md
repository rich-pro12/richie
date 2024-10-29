Richie Pranata 

Teknik Informatika

312410451

# Gambar Flowchart Tiket Bioskop
![foto1](https://raw.githubusercontent.com/rich-pro12/foto1/9173cf4e8461fae3991c788dbcd13d22888dade7/richie.png)

# Program untuk menghitung harga tiket bioskop

# Harga tiket
``` Pyhton
harga_reguler = 50000
harga_vip = 100000
```

# Input dari user
``` Pyhton
tipe_tiket = input("Masukkan tipe tiket (reguler/vip): ").lower()
status_member = input("Apakah Anda memiliki kartu member? (ya/tidak): ").lower()
```

# Menentukan harga berdasarkan tipe tiket
``` Pyhton
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    total_harga = 0
```

# Menghitung diskon jika user adalah member
``` Pyhton
if status_member == "ya":
    diskon = total_harga * 0.2
    total_harga -= diskon
```

# Menampilkan total harga yang harus dibayar
``` Pyhton
print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
```

# Gambar Hasil Eksekusi
![foto](https://raw.githubusercontent.com/rich-pro12/foto1/b1a6784c360da5e777d3ba1d69b192d1379f21cc/Screenshot%202024-10-30%20000629.png)

# Flowchart Kalkulator Sederhana
![Foto](

