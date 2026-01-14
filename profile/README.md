# Kelompok 3 – Riset Operasi TI22D

Kelompok mahasiswa **Program Studi Teknik Informatika – Kelas TI 22D** yang mengembangkan project berbasis **Riset Operasi** dengan pendekatan **Dynamic Programming**, khususnya **Backward Recursion (Top-Down DP)**, untuk menyelesaikan permasalahan **optimasi last-mile delivery**.

## Fokus Project

* Dynamic Programming
* Backward Recursion (Top-Down dengan Memoization)
* Bellman’s Principle of Optimality
* Stage–State Representation
* Optimasi Last-Mile Delivery
* Pengambilan Keputusan Multitahap

## Repository Utama

### Optimasi Last-Mile Delivery (Backward Dynamic Programming)

Sistem optimasi pengiriman **last-mile delivery** yang meminimalkan **total biaya/waktu tempuh** dari depot ke pelanggan dengan mempertimbangkan **urutan kunjungan optimal** menggunakan pendekatan **Backward Dynamic Programming**.

Repository:
https://github.com/kelompok-3-riset-operasi-ti22d/last-mile-backward

## Deskripsi Singkat Algoritma

Permasalahan last-mile delivery dimodelkan sebagai **masalah keputusan multistage**, di mana:

* **State** merepresentasikan posisi kurir dan himpunan pelanggan yang belum dilayani
* **Decision** adalah pemilihan pelanggan berikutnya yang akan dikunjungi
* **Transition** adalah perpindahan dari satu state ke state berikutnya
* **Cost** adalah jarak atau waktu tempuh antar lokasi

Solusi dicari menggunakan **Backward Recursion** dengan **memoization**, sesuai prinsip optimalitas Bellman:

> solusi optimal global tersusun dari solusi optimal subproblem.

## Team Members

| Nama                    | NIM       | Role                                 |
| ----------------------- | --------- | ------------------------------------ |
| Muhammad Hidayat           | 220511088 | Algorithm Design & DP Implementation |
| Rafi Zaidan Rabbani       | 220511074 | Mathematical Modeling & Analysis     |
| Nova Subhan | 220511170 | Visualization & Documentation        |


## Tujuan Akademik

Project ini dikembangkan untuk:

* Mengimplementasikan konsep **Dynamic Programming deterministik** dalam kasus nyata
* Memahami **stage–state formulation** dan **Bellman Equation**
* Menganalisis efektivitas **Backward DP** dibanding pendekatan brute force
* Mengaplikasikan teori **Riset Operasi** ke dalam optimasi sistem logistik

Project ini merupakan bagian dari tugas mata kuliah **Riset Operasi – Teknik Informatika**.

## Output Program

* Total biaya/jarak minimum pengiriman
* Urutan rute optimal (policy hasil DP)
* Tabel memoization (state → cost)
* Visualisasi rute pengiriman (opsional)

## Kontak

GitHub: https://github.com/kelompok-3-riset-operasi-ti22d/
