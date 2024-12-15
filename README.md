<h2 align="center">
<p align="center"><img src="https://raw.githubusercontent.com/kalenderjawa/pustaka/master/images/kj_v2.png" width="50%" alt="sengkala"></p>
</h2>

Kalender Jawa adalah sistem kalender berbasis bulan. Masyarakat Jawa telah menggunakannya untuk berbagai keperluan dalam kehidupan sehari-hari sejak abad ke-14 hingga sekarang.

[Pustaka](https://github.com/kalenderjawa/pustaka) adalah perpustakaan JavaScript untuk Kalender Jawa.

## Rumus Matematika Kalender Jawa

Kalender Jawa didasarkan pada matematika dan dilestarikan dari generasi ke generasi melalui rumus-rumus matematis. Ironisnya, tidak banyak generasi baru yang memahami atau menyadari ilmu ini.

![Rumus Matematika Kalender Jawa](https://assets.caknun.com/media/2019/01/20190102-menek-kalender-4.jpg)
[(*sumber gambar*)](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat)

## API

API ini mudah digunakan. Sebagai contoh, jika Anda ingin mengetahui rumus matematis untuk bulan `romadon` pada tahun Jawa 1952:

```js
KalenderJawa.cariRumusAbadiAwalBulanTahunJawa('romadon', 1952).then(data => {
  console.log(`${data.rumus.wulan.wulan}_${data.rumus.dino}_${data.rumus.pasaran}`)
  // romadon_7_4 (don tu pat)
})
```

