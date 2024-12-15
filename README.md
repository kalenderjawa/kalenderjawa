<h2 align="center">
<p align="center"><img src="https://raw.githubusercontent.com/kalenderjawa/pustaka/master/images/kj_v2.png" width="50%" alt="sengkala"></p>
</h2>

## Kalender Jawa

Kalender Jawa adalah sistem kalender berbasis bulan. Masyarakat Jawa telah menggunakannya untuk berbagai keperluan dalam kehidupan sehari-hari sejak abad ke-14 hingga sekarang.

## Pustaka 

[Pustaka](https://github.com/kalenderjawa/pustaka) adalah nama perpustakaan npm JavaScript untuk Kalender Jawa.

## API

API ini mudah digunakan. Sebagai contoh, jika Anda ingin mengetahui rumus matematis untuk bulan `romadon` pada tahun Jawa 1952:

```js
KalenderJawa.cariRumusAbadiAwalBulanTahunJawa('romadon', 1952).then(data => {
  console.log(`${data.rumus.wulan.wulan}_${data.rumus.dino}_${data.rumus.pasaran}`)
  // romadon_7_4 (don tu pat)
})
```

## Sejarah

Kalender atau Penanggalan Jawa merupakan penanggalan yang dibawa oleh para leluhur Jawa dan kemudian diolah lebih lanjut oleh para Wali. Sebelum masa para Wali, para leluhur Jawa telah memakai penanggalan berdasarkan matahari atau Saka dan juga berdasarkan bulan.

Dalam perkembangan selanjutnya, para Wali yang berkolaborasi dengan para leluhur bangsa Jawa menghasilkan Penanggalan Jawa yang baru berdasarkan pergerakan bulan. Penanggalan Jawa baru ini sudah umum dipakai sejak Raden Patah menjadi Sultan Demak yang pertama.

Momen ketika Raden Patah menjadi sultan pertama di Demak ditandai dengan *Sengkalan* atau *Candra Sengkala*:

### *Catur Ilang Sucining Ratu*

Sengkalan tersebut menandakan tahun 1404 Saka (887 H, 1482 M) atau 4 tahun setelah runtuhnya Majapahit.

> *Candra Sengkala* atau *Sengkalan* adalah cara orang Jawa mengingat momen tahun dalam bentuk kalimat. Contoh terkenal adalah runtuhnya Majapahit: "Sirna ilang Kertaning Bumi" (1400 Jawa). *Sengkalan* adalah kalender lunar yang sudah lama dipakai sebelum masa para wali [sumber](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat).

Pada masa Sultan Agung, Kalender Jawa diresmikan sebagai kalender kerajaan pada Jumat Legi, 1 Sura 1555 (1 Muharram 1043 H, 8 Juli 1633 M). Kalender ini berlaku di seluruh Pulau Jawa kecuali Banten, Blambangan, dan Madura.

> Para leluhur bangsa Indonesia sebenarnya lebih cepat dalam merumuskan sistem kalender, yaitu lebih dari 100 tahun sebelum Kalender Gregorian diresmikan (1582 M).

## Sistematis

Kalender Jawa sangat kompleks, tetapi dalam *Pustaka Kalender Jawa*, hanya konsep-konsep dasar yang diimplementasikan. Aturan dasar yang menjadi acuan:

- Menggunakan sistem 7 hari (*saptawara*), sama dengan kalender Masehi.
- Menggunakan sistem 5 hari (*pancawara*), dikenal dengan Pasaran.
- Mempunyai siklus 8 tahunan (*windu*).
- Koreksi keberulangan dilakukan setiap 120 tahun (15 *windu*), dikenal sebagai **Salin Kurup** atau **Ganti Kurup** (penambahan 1 hari tiap 120 tahun).

### Hari (*Dinten*/Dino)

Seperti kalender Masehi, Kalender Jawa membagi hari menjadi 7:

| Urutan | Dinten | Hari (Masehi) |
|--------|--------|---------------|
| 1      | Senen  | Senin         |
| 2      | Selasa | Selasa        |
| 3      | Rebo   | Rabu          |
| 4      | Kemis  | Kamis         |
| 5      | Jemah  | Jumat         |
| 6      | Sebtu  | Sabtu         |
| 7      | Akad   | Minggu        |

### Pasaran

Selain 7 hari, masyarakat Jawa juga membagi hari menjadi 5 (*Pasaran*):

| Pasaran | Neptu |
|---------|-------|
| Legi    | 5     |
| Pahing  | 9     |
| Pon     | 7     |
| Wage    | 4     |
| Kliwon  | 8     |

> **Neptu** adalah bobot angka dari Pasaran. Penggunaannya umum dalam adat dan penetapan acara tradisional.

### Bulan (*Sasi*)

Kalender Jawa terdiri dari 12 bulan (*sasi*):

| Urutan | Sasi          | Alias         | Jumlah Hari |
|--------|---------------|---------------|-------------|
| 1      | Mukarom       | Suro          | 30          |
| 2      | Sapar         | -             | 29          |
| 3      | Robi'ulawal   | Mulud         | 30          |
| 4      | Robi'ulakir   | Bakda Mulud   | 29          |
| 5      | Jumadilawal   | -             | 30          |
| 6      | Jumadilakir   | -             | 29          |
| 7      | Rojab         | Rejeb         | 30          |
| 8      | Sakban        | Ruwah, Arwah  | 29          |
| 9      | Romadon       | Pasa, Ramelan | 30          |
| 10     | Sawal         | -             | 29          |
| 11     | Dulkodah      | Séla          | 30          |
| 12     | Dulkijah      | Besar         | 29/30*      |

> **\*** Lihat tabel Tahun Jawa.

### Tahun Jawa

Dalam Kalender Jawa, satu *windu* (8 tahun) adalah siklus terbesar. Nama tahun dalam satu *windu*:

| Urutan | Tahun Jawa | Hari/Tahun |
|--------|------------|------------|
| 1      | Alip       | 354        |
| 2      | Ehe        | 355        |
| 3      | Jimawal    | 354        |
| 4      | Je         | 354        |
| 5      | Dal        | 355        |
| 6      | Be         | 354        |
| 7      | Wawu       | 354        |
| 8      | Jimakir    | 355        |

> Tahun dengan nama sama (misalnya, *Tahun Be*) memiliki awal tahun yang sama (misalnya, *Rebo Kliwon*).

## Rumus Matematis

Kalender Jawa memiliki keteraturan luar biasa, memungkinkan perhitungan pola-pola untuk awal bulan, tahun dan didasarkan pada rumus matematis. Kalender ini dilestarikan dari generasi ke generasi melalui rumus-rumus matematis. Ironisnya, tidak banyak generasi baru yang memahami atau menyadari ilmu ini.

![Rumus Matematika Kalender Jawa](https://assets.caknun.com/media/2019/01/20190102-menek-kalender-4.jpg)
[(*sumber gambar*)](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat)

### Rumus Hafalan Awal Bulan Kalender Jawa Abadi

Contoh untuk menghitung awal bulan *1 Suro (Mukarom) 1953 J* (1 September 2019 M):

1. Tahun 1953 adalah *Tahun Wawu, Kurup Asapon (Alip Selasa Pon)*.
2. Rumus awal bulan *Mukarom* pada *Tahun Wawu*: **"Rom Nem Ro"** (*Mukarom Enem Loro*).  
   - 6 = hari, 2 = pasaran (dihitung dari awal Kurup: Asapon).
3. Hari ke-6 dihitung dari Selasa: Akad (Minggu).
4. Pasaran ke-2 dihitung dari Pon: Wage.
5. Hasil: **1 Suro (Mukarom) 1953 J** bertepatan dengan **Minggu Wage**.

## Referensi

1. Yudi Rohmat, [*Kalender Jowo Digowo Kalender Arab Diruwat*](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat), caknun.com, 2019.
