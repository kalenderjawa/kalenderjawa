<h2 align="center">
<p align="center">Pustaka Kalender Jawa</p>
<p align="center"><img src="https://raw.githubusercontent.com/kalenderjawa/pustaka/master/images/kj_v2.png" width="80%" alt="sengkala"></p>
</h2>
<h2>
<p align="center">
<a href="https://kalenderjawa.dev"><img src="https://img.shields.io/badge/kalenderjawa.dev-WEBSITE-blue?style=for-the-badge&color=D90429&labelColor=2B2D42"/>  </a>
</p>
</h2>
<p align="center">
<a href="https://actions-badge.atrox.dev/kalenderjawa/pustaka/goto?ref=master"><img alt="Build Status" src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fkalenderjawa%2Fpustaka%2Fbadge%3Fref%3Dmaster&style=flat" /></a>
<a href="https://github.com/facebook/jest"><img src="https://img.shields.io/badge/tested_with-jest-99424f.svg" alt="Tested with Jest"></a>
<a href="https://bundlephobia.com/result?p=@kalenderjawa/pustaka"><img src="https://badgen.net/bundlephobia/minzip/@kalenderjawa/pustaka" alt="bundlephobia"></a> 
</p>

[**Pustaka**](https://github.com/kalenderjawa/pustaka) adalah perpustakaan JavaScript untuk Kalender Jawa.

> Kalender Jawa adalah sistem kalender berbasis bulan. Masyarakat Jawa telah menggunakannya untuk berbagai keperluan dalam kehidupan sehari-hari sejak abad ke-14 hingga sekarang.

**Rumus Matematika Kalender Jawa**

Kalender Jawa didasarkan pada matematika dan dilestarikan dari generasi ke generasi melalui rumus-rumus matematis. Ironisnya, tidak banyak generasi baru yang memahami atau menyadari ilmu ini.

![Rumus Matematika Kalender Jawa](https://assets.caknun.com/media/2019/01/20190102-menek-kalender-4.jpg)
[(*sumber gambar*)](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat)

## **API**

API ini mudah digunakan. Sebagai contoh, jika Anda ingin mengetahui rumus matematis untuk bulan `romadon` pada tahun Jawa 1952:

```js
KalenderJawa.cariRumusAbadiAwalBulanTahunJawa('romadon', 1952).then(data => {
  console.log(`${data.rumus.wulan.wulan}_${data.rumus.dino}_${data.rumus.pasaran}`)
  // romadon_7_4 (don tu pat)
})
```