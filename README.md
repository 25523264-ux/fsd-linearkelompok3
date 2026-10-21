# fsd_linear_kelompok3
Tugas Kelompok: Linear Regression dan Logistic Regression

Anggota Kelompok: 
- Laksita Ayudia Nurislami (25523182)
- Fathin Nishrina Nurul Aulya (25523256)
- Fina Nailatul 'Izzah (25523264)

# Bagian A: Linear Regression
## A1. Deskripsi Dataset

Sumber dataset: California Housing (`california_housing_train.csv`), tersedia di folder `sample_data` Google Colab. Dataset ini berisi data sensus California tahun 1990, dengan satu baris mewakili satu blok wilayah (*block group*).

Ukuran dataset: terdiri dari 17.000 baris dan 9 kolom (8 fitur + 1 target)

| Kolom | Tipe | Arti |
|---|---|---|
| `longitude` | Fitur | Posisi bujur blok (makin besar, makin ke timur) |
| `latitude` | Fitur | Posisi lintang blok (makin besar, makin ke utara) |
| `housing_median_age` | Fitur | Median usia rumah di blok (tahun) |
| `total_rooms` | Fitur | Total jumlah ruangan di blok |
| `total_bedrooms` | Fitur | Total jumlah kamar tidur di blok |
| `population` | Fitur | Jumlah penduduk di blok |
| `households` | Fitur | Jumlah rumah tangga di blok |
| `median_income` | Fitur | Median pendapatan rumah tangga di blok (satuan puluhan ribu USD) |
| `median_house_value` | **Target** | Median harga rumah di blok (USD) |

Tujuan: memprediksi `median_house_value` berdasarkan 8 fitur di atas.

## A2. Eksplorasi dan Visualisasi Data

Pada tahap ini kita melihat statistik deskriptif dan membuat tiga visualisasi untuk memahami distribusi target, hubungan antarfitur, serta hubungan fitur dengan target.


# Bagian B: Logistic Regression

## B1. Deskripsi Dataset

**Sumber:** Pokemon with stats (abcsds), Kaggle. https://www.kaggle.com/datasets/abcsds/pokemon

**Ukuran:** 800 baris dan 13 kolom.

**Tujuan:** memprediksi apakah sebuah Pokémon termasuk kategori *Legendary* berdasarkan statistik dasarnya.

**Arti kolom:**
| Kolom | Arti |
|---|---|
| `#` | Nomor Pokédex |
| `Name` | Nama Pokémon |
| `Type 1` | Tipe utama (misalnya Grass, Fire) |
| `Type 2` | Tipe kedua (boleh kosong) |
| `Total` | Jumlah seluruh statistik dasar |
| `HP` | Poin kesehatan |
| `Attack` | Kekuatan serangan fisik |
| `Defense` | Pertahanan fisik |
| `Sp. Atk` | Serangan khusus |
| `Sp. Def` | Pertahanan khusus |
| `Speed` | Kecepatan |
| `Generation` | Generasi kemunculan (1 sampai 6) |
| `Legendary` | Status Legendary (True/False) |

**Variabel target:** `Legendary`
- Kelas 0 (False): bukan Pokémon Legendary
- Kelas 1 (True): Pokémon Legendary (kelas positif)


