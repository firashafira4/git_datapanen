# Program Data Panen

Proyek ini berisi program Python untuk:
1. Menampilkan semua data hasil panen dari beberapa lokasi kebun.
2. Menampilkan jumlah hasil panen jagung dari lokasi2
3. Menampilkan nama lokasi dari lokasi 3
4. Memisahkan jumlah hasil panen **padi** dan **kedelai** dari setiap lokasi ke dalam variabel terpisah.
5. Membuat variabel terpisah untuk menyimpan jumlah hasil panen padi dan kedelai dari setiap lokasi
6. Membuat percabangan
7. push hasil pengerjaan kedalam git

## Struktur Data
Data disimpan dalam struktur `dictionary` yang mencakup:
- **Lokasi kebun**: Nama lokasi kebun.
- **Hasil panen**: Data hasil panen untuk tiga komoditas utama (padi, jagung, kedelai).

### Contoh Data
```python
data_panen = {
    'lokasi1': {
        'nama_lokasi': 'Kebun A',
        'hasil_panen': {
            'padi': 1200,
            'jagung': 800,
            'kedelai': 500
        }
    },
    ...
}
