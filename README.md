# Algoritma Best Route: Dijkstra & Greedy

Proyek ini membahas implementasi dua algoritma pencarian jalur terbaik — **Dijkstra** dan **Greedy** — untuk menemukan jalur terpendek dalam jaringan jalan menggunakan data geospasial dari OpenStreetMap (OSM). Data jaringan jalan diambil dari wilayah **Kabupaten Purbalingga, Indonesia** menggunakan library **OSMNX**.

## **Fitur Proyek**
- **Dijkstra Algorithm**: Menemukan jalur terpendek dengan akurasi tinggi.
- **Greedy Algorithm**: Menemukan jalur cepat dengan pendekatan heuristik.
- **Visualisasi Jalur**: Menampilkan jalur yang ditemukan pada peta Kabupaten Purbalingga.

## **Prasyarat**
Untuk menjalankan proyek ini, pastikan Anda telah menginstal beberapa dependensi berikut:
- Python 3.x
- Library:
  - `osmnx`
  - `geopandas`
  - `matplotlib`
  - `networkx`

Instalasi dependensi menggunakan `pip`:
```bash
pip install osmnx geopandas matplotlib networkx
