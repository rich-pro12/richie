Richie Pranata 

Teknik Informatika

312410451

# Gambar Flowchart Tiket Bioskop
![foto1](

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
