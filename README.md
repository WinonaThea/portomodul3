# portomodul3

Business Problem

Harga properti dipengaruhi oleh banyak faktor, mulai dari kondisi bangunan hingga fasilitas yang tersedia. Menentukan harga yang akurat sangat penting bagi pembeli, penjual, maupun developer untuk menghindari undervaluation maupun overvaluation. Tujuan dari proyek ini adalah membangun model machine learning yang dapat memprediksi median sale price properti secara lebih akurat berdasarkan fitur bangunan dan lingkungan.

Evaluation Metrics

Model dievaluasi dengan dua metrik utama:

RMSE (Root Mean Squared Error): mengukur deviasi rata-rata prediksi terhadap nilai aktual dalam satuan harga, lebih sensitif terhadap outlier.

MAPE (Mean Absolute Percentage Error): mengukur rata-rata kesalahan relatif dalam bentuk persentase, sehingga lebih mudah dipahami dari perspektif bisnis.

Dataset & Features

Dataset berisi informasi properti dengan kolom-kolom berikut:

BuildingAge: umur bangunan (tahun).

LogSize: ukuran unit dalam bentuk logaritmik.

N_FacilitiesInApt: jumlah fasilitas dalam apartemen (gym, kolam renang, dll).

AmenitiesIndex: indeks fasilitas umum di sekitar apartemen.

TimeToSubway_Min: waktu tempuh ke subway terdekat (menit).

StationMedianPrice: harga median properti di sekitar stasiun terdekat.

HallwayType: tipe koridor (corridor, mixed, terraced), diubah menjadi ordinal encoding karena hubungannya bersifat ordinal dengan level harga.

SalePrice_median: target variabel, median harga jual properti.
